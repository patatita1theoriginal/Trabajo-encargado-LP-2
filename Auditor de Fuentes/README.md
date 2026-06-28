# Auditor de Fuentes para Extracción de Datos (Proyecto FakeReviews: Steam v/s Opencritic)

Este proyecto tiene como objetivo automatizar la auditoría de sitios web para determinar el método más ético y eficiente de extracción de datos, analizando archivos `robots.txt` y evaluando la disponibilidad de APIs oficiales.

## 🛠️ Metodología y Justificación

Para la obtención de datos de nuestras fuentes, hemos adoptado un enfoque híbrido, seleccionando el método más adecuado según la estructura y políticas de cada plataforma.

### 1. Steam Store: Enfoque de *Web Scraping* (`requests`)
Para la extracción de reseñas y metadatos en Steam, se ha optado por el uso de `requests` y técnicas de *web scraping* directo.

* **Racionalización:** Tras realizar una auditoría de las reglas de exclusión (`robots.txt`), se verificó que los endpoints de acceso a la tienda y reseñas son accesibles.
* **Decisión Técnica:** Aunque Steam cuenta con una API oficial, el *scraping* directo mediante `requests` permite una mayor flexibilidad para el análisis específico de reseñas que el proyecto requiere. Se ha implementado de manera responsable, respetando el `crawl-delay` y limitando la frecuencia de peticiones para no afectar la disponibilidad del servicio.

### 2. OpenCritic: Enfoque basado en API
Para OpenCritic, se ha priorizado el uso de su infraestructura de API sobre la técnica de *scraping*.

* **Racionalización:** OpenCritic provee una API estructurada que facilita la obtención de metadatos de forma organizada y eficiente.
* **Decisión Técnica:** El uso de la API garantiza una mayor estabilidad en la extracción de datos, evitando las posibles interrupciones que generan los cambios frecuentes en el diseño (*frontend*) de un sitio web. Al utilizar la vía oficial, garantizamos una mayor integridad en la información recolectada.

### Resumen de Estrategia

| Fuente | Método Seleccionado | Justificación |
| :--- | :--- | :--- |
| **Steam** | `requests` (Scraping) | Flexibilidad en el parseo; rutas permitidas en `robots.txt`. |
| **OpenCritic** | API Oficial | Estabilidad, eficiencia y alineación con políticas de uso. |

---

## ⚙️ Auditoría Automatizada

El proyecto incluye un script de auditoría que evalúa cada fuente antes de la extracción. La clase `AuditorRobots` realiza las siguientes funciones:

1. **Lectura de `robots.txt`:** Identifica los permisos para nuestro `User-Agent`.
2. **Evaluación de Rutas:** Clasifica el nivel de acceso en `ALTO`, `MEDIO`, `RESTRINGIDO` o `API_RECOMENDADA`.
3. **Extracción de Metadatos:** Detecta `Sitemaps` y `Crawl-delays` para optimizar el comportamiento del cliente de extracción.

## ⚖️ Consideraciones Éticas y Buenas Prácticas

La integridad de los datos y el respeto por los servidores de terceros son pilares fundamentales en este proyecto. Para asegurar un proceso de extracción responsable, hemos implementado los siguientes controles:

* **Respeto a `robots.txt`**: El sistema audita automáticamente el archivo `robots.txt` de cada fuente antes de realizar cualquier solicitud. Si el acceso a una ruta no está explícitamente permitido, el sistema prioriza la vía de la API oficial o solicita una revisión manual.
* **Carga Controlada (Crawl-Delay)**: Aunque nuestras herramientas de *scraping* no realizan peticiones masivas sin control, el diseño permite configurar pausas entre peticiones para mitigar cualquier impacto en la latencia del sitio web.
* **Identificación del Usuario**: Todas las peticiones se realizan identificando claramente nuestro origen mediante un `User-Agent` personalizado (`ProyectoFakeReviews/1.0`). Esto permite a los administradores de los sitios identificar el tráfico y bloquearnos si consideran que nuestra actividad es inapropiada.
* **Uso de APIs como Primera Opción**: Siempre que una plataforma proporciona una API, esta se utiliza como vía principal de extracción. Esto no solo garantiza la estabilidad de nuestro pipeline, sino que también reduce significativamente la carga sobre la infraestructura del *frontend* del sitio.
* **Transparencia**: Este código está documentado para que el proceso de extracción sea auditable, reproducible y respetuoso con los términos de servicio
