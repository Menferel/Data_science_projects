La compañía minera busca optimizar su proceso industrial prediciendo la recuperación de oro en distintas etapas de producción. El objetivo es construir modelos predictivos robustos para estimar tanto la recuperación intermedia (rougher) como la recuperación final de oro, utilizando datos de procesos metalúrgicos. La métrica utilizada fue Symmetric Mean Absolute Percentage Error (sMAPE)

- Datos: Variables físicas y químicas de proceso recopiladas cada hora, provenientes de tres datasets: train, test y full.
- Librerías: Pandas, matplotlib, seaborn, numpy, sklearn (métricas y modelos). 
- Resultados: Selección del mejor modelo con bajo sMAPE para rougher recovery y final recovery.
