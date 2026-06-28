# Auditor de Fuentes para Extracción de Datos (Proyecto FakeReviews: Steam v/s Opencritic)

Este proyecto tiene como objetivo automatizar la auditoría de sitios web para determinar el método más ético y eficiente de extracción de datos, analizando archivos `robots.txt` y evaluando la disponibilidad de APIs oficiales.

# 🛠️ Metodología y Justificación

Para la obtención de datos, se adoptó un enfoque basado exclusivamente en el consumo de **APIs oficiales** y **endpoints de datos estructurados**, seleccionando el método más eficiente para garantizar la integridad, estabilidad y reproducibilidad de la información.

## 1. Steam Store: Enfoque mediante API (Endpoint JSON)

Para la extracción de reseñas y metadatos de Steam se utiliza el endpoint oficial de reseñas (`/appreviews/`) mediante el parámetro `?json=1`.

### Racionalización

Tras auditar la estructura de datos de la plataforma, se confirmó que este endpoint proporciona toda la información necesaria de forma estructurada y eficiente.

### Decisión técnica

El uso de este endpoint oficial ofrece una mayor fiabilidad que el *parsing* de HTML, asegurando que los datos obtenidos sean consistentes y no se vean afectados por cambios en el diseño visual (*frontend*) del sitio. La implementación se realiza de forma responsable mediante un **User-Agent** identificado y limitando la frecuencia de las peticiones.

---

## 2. OpenCritic: Enfoque basado en API

Para OpenCritic se utiliza su infraestructura de API gestionada a través de RapidAPI.

### Racionalización

OpenCritic proporciona una API estructurada que facilita la obtención de metadatos de forma organizada, consistente y eficiente.

### Decisión técnica

El uso de la API garantiza una mayor estabilidad durante la extracción de datos y mantiene una alineación con las políticas de uso de la plataforma, evitando las interrupciones que podrían producir los cambios en la interfaz web.

---

# 📊 Resumen de la estrategia

| Fuente     | Método seleccionado    | Justificación                                                                   |
| ---------- | ---------------------- | ------------------------------------------------------------------------------- |
| Steam      | API (Endpoint JSON)    | Datos estructurados, estabilidad ante cambios visuales y eficiencia operativa.  |
| OpenCritic | API Oficial (RapidAPI) | Estabilidad, eficiencia y alineación con las políticas de uso de la plataforma. |

---

# ⚙️ Auditoría Automatizada

El proyecto incorpora un script de auditoría que evalúa cada fuente antes del proceso de extracción.

La clase `AuditorRobots` realiza las siguientes funciones:

* **Lectura de directrices:** identifica las políticas de acceso aplicables al **User-Agent** utilizado.
* **Evaluación de límites:** clasifica el nivel de acceso disponible y detecta restricciones de tasa (*Rate Limits*) para optimizar el comportamiento del cliente de extracción.
* **Optimización de peticiones:** identifica parámetros y recomendaciones que permiten realizar un consumo responsable de la infraestructura de las plataformas.

---

# ⚖️ Consideraciones Éticas y Buenas Prácticas

La integridad de los datos y el respeto por la infraestructura de terceros constituyen principios fundamentales del proyecto. Para garantizar un proceso de extracción responsable se implementan las siguientes medidas:

* **Identificación del cliente:** todas las solicitudes HTTP incluyen un **User-Agent** personalizado (`ProyectoFakeReviews/1.0`), permitiendo identificar claramente el origen de las peticiones.
* **Control de carga (*Rate Limiting*):** el sistema incorpora pausas programadas (`time.sleep`) entre solicitudes para reducir el impacto sobre los servidores.
* **Uso exclusivo de vías oficiales:** la información se obtiene únicamente mediante APIs y endpoints públicos proporcionados por las plataformas, garantizando la estabilidad del proceso de extracción y minimizando la carga sobre su infraestructura.
* **Transparencia y reproducibilidad:** el código se encuentra documentado para que el proceso de extracción pueda ser auditado, reproducido y mantenido de acuerdo con las buenas prácticas de ingeniería de software.

---

# ✅ Principios del Proyecto

Este proyecto sigue cuatro principios fundamentales durante la obtención de datos:

* **Legalidad:** utilización exclusiva de APIs y endpoints oficiales.
* **Responsabilidad:** respeto por los límites de uso y la infraestructura de las plataformas.
* **Reproducibilidad:** metodología documentada y fácilmente verificable.
* **Calidad de datos:** consumo de información estructurada para minimizar errores y maximizar la consistencia del conjunto de datos.

