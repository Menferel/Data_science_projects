OilyGiant busca expandir sus operaciones desarrollando 200 nuevos pozos petroleros. El objetivo fue crear un modelo predictivo que estime el volumen de reservas en tres regiones candidatas, y así identificar la zona más rentable bajo condiciones de inversión y riesgo.

- Datos: Características técnicas (f0, f1, f2) y volumen de reservas (product) en miles de barriles para cada pozo.
- Librerías: Pandas, Numpy, Sklearn (modelos, métricas y otros)
- Condiciones: Presupuesto de $100M para 200 pozos. El pozo debe generar ≥111.1 mil barriles (~$500,000) para evitar pérdidas. Margen mínimo de pérdida aceptable: 2.5%.
- Resultados:
    * Se entrenó un modelo para cada región. 
    * Se calculó el beneficio esperado y el riesgo de pérdida con simulación estadística.
    * Se eligió la región con mayor beneficio promedio y riesgo por debajo del umbral.
