# Segmentación de Sellers

## 📋 Contexto

Este reto consiste en abordar un caso de negocio real, incorporando herramientas de Machine Learning e Inteligencia Artificial Generativa (GenAI). El objetivo principal es segmentar sellers para proponer estrategias comerciales personalizadas y escalar la solución con un módulo GenAI.

## 🧩 Estructura del Repositorio

- `Challenge_Meli.ipynb`: Notebook completo con análisis explotarorio, modelo kmeans y extensión de Gen AI
- `presentacion.pdf` (opcional): Slides para la sustentación.
- El archivo se sugiere subirlo manualmente a la terminal de Colab o de Jupyter como se ve en la imagen:
  
- ![Cargar el archivo](Imagenes/Carga_CSV.png)

## 🚀 Instrucciones de Ejecución

1. **Descarga el CSV directamente de Drive** https://drive.google.com/drive/folders/1nGPM6Q3D7JGgnD3Q84520_HHms_NGkgR
2. **Abre el notebook** `Challenge_Meli.ipynb` en Google Colab, en caso de que la extensión no deje ver correctamente el código por los metadatos, este enlace lleva directamente al notebook en Google Colab: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ra42_oCsbmShizyDSSS1J097n8OGEraA)    
3. **Ejecuta cada celda en orden**. El notebook está organizado por secciones:
    - Carga del archivo, recordar montarlo manualmente a la terminal de Colab
    - Análisis exploratorio
    - Modelo de clustering
    - Extensión GenAI (clasificador)
4. **Reproducibilidad**
    - Semilla global: `np.random.seed(42)`
    - Semilla local en los modelos: `random_state = 42`

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
