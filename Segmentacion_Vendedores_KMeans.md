# Segmentación de Vendedores con K-means

## 1. **Introducción**
Aplicamos el algoritmo K-means para identificar perfiles de vendedores en la plataforma, utilizando variables clave: precio promedio del producto, stock promedio, variedad de categorías, reputación y proporción de descuentos. Se depuraron variables para reducir el ruido y mejorar la calidad de la segmentación.

---

## 2. **Metodología**
- **Variables Analizadas**: Precio promedio, stock promedio, variedad de categorías, reputación, descuentos.
- **Preprocesamiento**: Escalado y limpieza de datos.
- **Selección de K**: Usamos el método del codo, iniciando desde K=2, para identificar el número óptimo de grupos.
- **Visualización**: Gráficos en escala logarítmica para evidenciar patrones y separaciones entre clusters.

---

## 3. **Resultados – Visualización de Clústers**
![Visualización de Clústeres](Cluster_Grafico.png)

---

## 4. **Interpretación de Clústers**

| Cluster | Precio Promedio | Stock Promedio | Variedad de Categorías | Reputación | % Descuentos | Perfil |
|---------|-----------------|----------------|-----------------------|------------|--------------|--------|
| **0**   | Medio-bajo      | Bajo           | Baja                  | Media-alta | Muy bajo     | Especialistas conservadores |
| **1**   | Alto            | Muy bajo       | Baja                  | Baja       | Muy bajo     | Premium con poca presencia  |
| **2**   | Medio-bajo      | Alto           | Media                 | Media      | Muy bajo     | Stockistas accesibles       |
| **3**   | Bajo            | Medio          | Alta                  | Alta       | Alto         | Competidores estrella       |

---

### **Cluster 0: Especialistas conservadores**
- Venden pocos productos, con precios medios, bajo stock y poca variedad.
- Tienen reputación aceptable y casi no usan descuentos.

**Estrategia:**  
Fomentar el uso de descuentos y la diversificación de productos. Ofrecer capacitaciones en gestión de inventario y campañas de promoción.

---

### **Cluster 1: Premium con poca presencia**
- Ofrecen productos caros, muy bajo stock y poca variedad.
- Reputación baja y casi no usan descuentos.

**Estrategia:**  
Capacitación en atención al cliente y marketing digital. Incentivos para aumentar stock y mejorar la reputación. Promover el valor agregado y la fidelización.

---

### **Cluster 2: Stockistas accesibles**
- Precios accesibles, buen stock y variedad media.
- Reputación aceptable y no destacan por descuentos.

**Estrategia:**  
Aprovechar su capacidad de stock en campañas de ventas rápidas. Incentivos por rotación de inventario y alianzas para eventos especiales.

---

### **Cluster 3: Competidores estrella**
- Precios bajos, buena variedad y reputación alta.
- Son quienes más usan descuentos.

**Estrategia:**  
Mantener su competitividad, ofrecerles beneficios exclusivos, motivar testimonios y reseñas. Usarlos como referentes en capacitaciones.

---

## 5. **Conclusiones y Recomendaciones**
- Los clústers permiten identificar oportunidades de mejora y diseñar estrategias comerciales personalizadas.
- La segmentación orienta la toma de decisiones para potenciar las ventas y la satisfacción del cliente.
- Se recomienda monitorear periódicamente la segmentación, ajustando las acciones según la evolución de los grupos.

---

## 6. **Sustentación de la Elección de K y Variables**
- El número de clusters fue seleccionado con base en el método del codo y la interpretación comercial de los grupos.
- Las variables fueron depuradas para garantizar una segmentación relevante y accionable.
- La calidad del clustering se validó visualmente y mediante análisis estadístico (ej: Silhouette Score).

---

## 7. **Siguiente Paso**
- Implementar las estrategias propuestas y medir su impacto en los indicadores clave de cada grupo.