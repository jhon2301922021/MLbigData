Evaluación: Desarrollo de un Modelo Predictivo
Objetivo
Implementar un flujo completo de Machine Learning utilizando PySpark. El proceso debe aplicarse a cualquier dataset nuevo y ajustarse al problema específico (clasificación, regresión, etc.).

Pasos Evaluados y Distribución de Notas
Carga de Datos (2 puntos)
Acción:
Cargar el dataset.
Verificar el esquema, dimensiones y tipos de datos.
Entrega Esperada: Capturas del esquema de datos y número de filas y columnas.
Criterio de Evaluación:
Se cargó correctamente el dataset.
Se realizó una revisión clara de la estructura de los datos.
Análisis Exploratorio de Datos (3 puntos)
Acción:
Identificación de variables numéricas y categóricas.
Análisis descriptivo:
Estadísticas de variables numéricas.
Conteo de valores únicos en variables categóricas.
Visualización: Histogramas, correlaciones y distribuciones clave.
Entrega Esperada:
Listas de variables numéricas y categóricas.
Gráficos relevantes y matriz de correlación.
Criterio de Evaluación:
Análisis completo y bien documentado.
Visualizaciones y descripciones claras.
Tratamiento de Datos Faltantes y Outliers (3 puntos)
Acción:
Imputación de valores nulos: Promedio (para numéricos) o moda (para categóricos).
Detección y tratamiento de outliers (eliminación o transformación).
Entrega Esperada:
Validación de columnas tratadas.
Resultados antes y después del tratamiento.
Criterio de Evaluación:
Correcta imputación y tratamiento de datos atípicos.
Preparación de Features (4 puntos)
Acción:
Escalado de variables numéricas utilizando StandardScaler.
Codificación de variables categóricas mediante StringIndexer.
Creación de un vector combinado de todas las features.
Entrega Esperada:
Variables escaladas y codificadas correctamente.
Creación del vector de features final.
Criterio de Evaluación:
Organización limpia y correcta preparación de los datos.
Entrenamiento del Modelo (4 puntos)
Acción:
División del dataset en entrenamiento y prueba (70%-30%).
Entrenamiento de un modelo apropiado (ej., árbol de decisión, regresión lineal, etc.).
Predicción sobre los datos de prueba.
Entrega Esperada:
Correcta división de los datos.
Ejecución del modelo con resultados preliminares.
Criterio de Evaluación:
Correcta implementación del modelo y ejecución sin errores.
Evaluación del Modelo (3 puntos)
Acción:
Calcular métricas de evaluación:
Para clasificación: AUC, precisión, recall.
Para regresión: RMSE, R2.
Realizar tuning de parámetros (ej., maxDepth para árboles de decisión).
Entrega Esperada:
Reporte de métricas obtenidas.
Visualización de resultados y comparación tras tuning.
Criterio de Evaluación:
Uso adecuado de métricas.
Optimización del modelo.
Despliegue de Resultados y Recomendaciones (1 punto)
Acción:
Generar conclusiones y recomendaciones basadas en el análisis.
Visualizaciones clave para respaldar las recomendaciones.
Entrega Esperada:
Gráficos que expliquen los resultados.
Propuestas para mejorar el modelo o aplicar los hallazgos.
Criterio de Evaluación:
Claridad en las recomendaciones.
Uso efectivo de visualizaciones.
