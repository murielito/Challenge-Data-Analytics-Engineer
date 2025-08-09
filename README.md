# Challenge_Data_Analytics_Engineer

# Challenge: Segmentación de Sellers y GenAI en Mercado Libre

## 📋 Contexto

Este reto consiste en abordar un caso de negocio real mediante el ciclo completo de Data Engineering, incorporando herramientas de Inteligencia Artificial Generativa (GenAI). El objetivo principal es segmentar sellers para proponer estrategias comerciales personalizadas y escalar la solución con un módulo GenAI.

## 🧩 Estructura del Repositorio

- `challenge_clusterizacion_sellers.ipynb`: Notebook completo con extracción, análisis, clustering y extensión GenAI.
- `presentacion.pdf` (opcional): Slides para la sustentación.
- `data/`: Carpeta sugerida para guardar el CSV descargado.
- Otros archivos auxiliares si los necesitas.

## 🚀 Instrucciones de Ejecución

1. **Descarga el CSV** según el enlace provisto en el challenge y guárdalo en tu Google Drive o carpeta local.
2. **Abre el notebook** `challenge_clusterizacion_sellers.ipynb` en Google Colab.
3. **Ejecuta cada celda en orden**. El notebook está organizado por secciones:
    - Extracción/carga de datos
    - Análisis exploratorio
    - Modelado de clustering
    - Extensión GenAI (clasificador o recomendador, según opción elegida)
    - Visualizaciones y conclusiones
4. **Configura dependencias** si es necesario (ej: instalación de librerías).
5. **Revisa los outputs y visualizaciones** para interpretar los resultados.

## 📊 Descripción de la Solución

- Se realiza un análisis exploratorio para entender los patrones de los sellers.
- Se aplican técnicas de clusterización (K-means) para segmentar según variables relevantes.
- Se evalúa la calidad de los clusters y se interpretan sus perfiles.
- Se implementa un módulo GenAI:
    - **Opción A**: Clasificador semántico con embeddings generados por LLM.
    - **Opción B**: Recomendador generativo de estrategias comerciales.

## 📑 Entregables

- Notebook ejecutable y documentado.
- Resultados y visualizaciones que respalden los análisis.
- Código del módulo GenAI implementado.
- Presentación (opcional) con el proceso, análisis, resultados y próximos pasos.

## 💡 Notas

- Todo el flujo está documentado en el notebook para facilitar la comprensión y reproducibilidad.
- Puedes adaptar la estructura según tus necesidades (por ejemplo, dividir en varios notebooks si lo prefieres).
- El notebook funciona en Google Colab y no requiere dependencias fuera de las especificadas en las celdas de instalación.

## 👤 Autor
Santiago Dávila
