# OSINT Investigation Report: Project Phoenix (Corporate Due Diligence)

## 📌 Resumen del Caso
Investigación de inteligencia de fuentes abiertas (OSINT) ejecutada bajo encargo para un **Inversor Privado**. El objetivo fue realizar una debida diligencia profunda sobre un individuo de alto perfil (Subject of Interest) y su entramado corporativo previo a una firma de contrato de alto valor.

Este repositorio sirve como portafolio técnico para demostrar la aplicación de metodologías de inteligencia, preservación de evidencia y análisis de riesgos en entornos corporativos reales.

## 🎯 Alcance de la Investigación
*   **Verificación de Identidad:** Validación de antecedentes, trayectoria profesional y registros académicos.
*   **Mapeo de Relaciones (SOCMINT):** Identificación de nodos de influencia, socios ocultos y familiares vinculados a operaciones comerciales.
*   **Análisis Patrimonial:** Localización de activos, propiedades y empresas en jurisdicciones internacionales.
*   **Evaluación de Riesgos:** Detección de hilos negativos en prensa, litigios pasados y presencia en listas de vigilancia financieras.

## 🛠️ Stack Técnico y Metodología
Se aplicó un ciclo de inteligencia estructurado, garantizando la **seguridad operacional (OPSEC)** para evitar la detección por parte del objetivo.

- **Footprinting Digital:** Uso de `Maigret` y `Sherlock` para trazabilidad de alias y presencia en plataformas digitales.
- **Investigación de Infraestructura:** Análisis de dominios y correos electrónicos con `Epios`, `Holehe` y `DNSdumpster`.
- **Inteligencia de Redes Sociales:** Extracción y análisis de grafos con `Maltego` para visualizar conexiones entre entidades.
- **GEOINT/IMINT:** Verificación de activos físicos y oficinas mediante análisis de imágenes satelitales y triangulación de metadatos EXIF.
- **Corporate OSINT:** Extracción de datos en `OpenCorporates`, registros mercantiles oficiales y bases de datos de sanciones internacionales.

## 📊 Hallazgos Críticos Identificados
1.  **Red de Sociedades:** Se identificó una estructura de tres capas de empresas pantalla (shell companies) no declaradas inicialmente por el sujeto.
2.  **Inconsistencia de Perfil:** El análisis de archivos históricos (`Wayback Machine`) reveló la eliminación deliberada de registros de prensa que vinculaban al sujeto con litigios por fraude fiscal en 2014.
3.  **Fuga de Seguridad:** Se localizaron documentos de identidad y contratos privados del sujeto expuestos en un servidor mal configurado, lo que representaba un riesgo crítico de seguridad para la operación.

## 📄 Entregables Incluidos
*   `/executive_summary`: Informe de alto nivel con los hallazgos y recomendaciones de mitigación de riesgo.
*   `/visual_intelligence`: Gráficos de relaciones, mapas de activos y líneas de tiempo de actividad.
*   `/methodology`: Detalle de los dorks de búsqueda avanzada y flujos de trabajo utilizados.

---
**Confidencialidad:** *Por razones de seguridad y acuerdos de no divulgación (NDA), todos los nombres reales, documentos de identidad y localizaciones específicas han sido redactados o sustituidos por identificadores genéricos.*
