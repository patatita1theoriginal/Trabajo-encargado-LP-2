<h1 align="center"> <b>UNIVERSIDAD NACIONAL AGRARIA LA MOLINA</b> </h3>
<h2 align="center"> <b>DEPARTAMENTO ACADÉMICO DE ESTADÍSTICA E INFORMÁTICA</b> </h2>
<p align="center">
  <img src="https://seeklogo.com/images/U/universidad-nacional-agraria-la-molina-logo-5BF0B8D973-seeklogo.com.png" 
       alt="La Molina Perú" 
       width="170" 
       height="170">
</p>
<h3 align="center">
  <b>ANÁLISIS FAKEREVIEWS DE SITIOS DE VIDEOJUEGOS</b>
</h3>

<h3> <b>Integrantes del equipo:</b> </h3>

<ul>
  <li>Almonacid Quispe, Jimmy Salomón (patatita1theoriginal) (20241374) </li>
  <li>Santillan Santa Cruz, Alex Josept (jois_2003) (20241402) </li>
  <li>[Apellidos, Nombres] ([usuario_github]) ([código_estudiante]) </li>
</ul>

<h2>Objetivo general</h2>
<p>Desarrollar un prototipo informático capaz de identificar y filtrar reseñas automatizadas o manipuladas en plataformas de videojuegos (Steam y OpenCritic), mediante la evaluación cruzada de patrones lingüísticos y métricas de plataforma, para calcular y proporcionar a los usuarios un "Índice de Confianza Real" sobre la calidad de cada videojuego.</p>

<h3>Objetivos del proyecto</h3>
<ul>
  <li><b>Fase 1: Recopilación y Estructuración de Datos (Extracción)</b>
    <ul>
      <li>Diseñar y ejecutar módulos de recolección de datos (vía API o web scraping) para extraer masivamente reseñas de usuarios y críticos desde Steam y OpenCritic.</li>
      <li>Clasificar los metadatos asociados a cada reseña (fecha de publicación, tiempo de juego registrado, recomendaciones/puntaje dado).</li>
    </ul>
  </li>
  <li><b>Fase 2: Procesamiento de Lenguaje Natural (Análisis Lingüístico)</b>
    <ul>
      <li>Implementar algoritmos de análisis de texto para evaluar la estructura sintáctica de las reseñas.</li>
      <li>Detectar la presencia de patrones hiper-repetitivos, estructuras antinaturales o "huellas" generativas que indiquen el uso de LLMs para la redacción automatizada.</li>
    </ul>
  </li>
  <li><b>Fase 3: Triangulación de Metadatos (Validación de Comportamiento)</b>
    <ul>
      <li>Correlacionar el análisis lingüístico con las métricas de la plataforma para identificar anomalías. Por ejemplo: reseñas extremadamente detalladas contrastadas con tiempos de juego ínfimos (en Steam), o reseñas inusuales de usuarios (en OpenCritic).</li>
      <li>Filtrar y aislar el comportamiento atípico asociado a granjas de bots o campañas de review bombing.</li>
    </ul>
  </li>
  <li><b>Fase 4: Modelado y Visualización (Generación del Índice)</b>
    <ul>
      <li>Formular un algoritmo que asigne un peso de fiabilidad a cada reseña basándose en los filtros anteriores.</li>
      <li>Calcular un "Índice IA" final para cada videojuego que refleje su verdadera recepción pública, descontando el ruido generado por la manipulación.</li>
    </ul>
  </li>
</ul>
