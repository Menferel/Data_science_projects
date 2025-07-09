La Gold Mining Company busca optimizar su proceso industrial prediciendo la recuperación de oro en distintas etapas de producción. El objetivo es construir modelos predictivos robustos para estimar tanto la recuperación intermedia (rougher) como la recuperación final de oro, utilizando datos de procesos metalúrgicos.

    - Datos: Variables físicas y químicas de proceso recopiladas cada hora, provenientes de tres datasets:
      * gold_recovery_train.csv — entrenamiento
      * gold_recovery_test.csv — prueba (sin variables objetivo)
      * gold_recovery_full.csv — dataset fuente completo

    - Procedimientos:
        * Revisión y validación del cálculo de recuperación rougher (comparación EAM entre cálculo y dato original).
        * Análisis de concentraciones de metales (Au, Ag, Pb) por etapa de procesamiento.
        * Comparación de distribuciones entre train y test para validar consistencia.
        * Eliminación de valores atípicos en concentraciones totales.
        * Entrenamiento de múltiples modelos con validación cruzada.

    - Métrica utilizada: Symmetric Mean Absolute Percentage Error (sMAPE), con funciones custom para cálculo.
    - Resultados: Selección del mejor modelo con bajo sMAPE para rougher recovery y final recovery.
