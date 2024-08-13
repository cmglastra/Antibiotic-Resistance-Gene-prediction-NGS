# Descripción del Proyecto

Este repositorio recoge el codigo que se ha desarollado para la realizacion del TFM **Caracterización de resistencia bacteriana a antimicrobianos mediante NGS**

### [2024-08-01_analysis04_upsetplot.ipynb](2024-08-01_analysis04_upsetplot.ipynb)
Genera gráficos de intersección (upset plots) para visualizar las intersecciones de conjuntos de genes. Utiliza el DataFrame `merged_df_blees_cpos_f99` para el procesamiento de datos y la visualización.

### [20240725_analysis01.ipynb](20240725_analysis01.ipynb)
Incluye funciones para recortar nombres de muestras y aplicar equivalencias de nomenclatura genética. También importa las bibliotecas y conjuntos de datos necesarios para el análisis.

### [20240725_analysis02.ipynb](20240725_analysis02.ipynb)
Procesa datos genómicos, incluyendo la importación de listas de referencia y datos de salida. Categoriza genes en diferentes tipos basados en listas predefinidas.

### [20240807_merge_reports_blees_cpos.ipynb](20220240807_merge_reports_blees_cpos.ipynb)
Fusiona varios informes relacionados con los tipos de genes BLEE y CPO. Incluye pasos de limpieza y fusión de datos.

### [20240808_analysis_heatmap_genecount_seaborn.ipynb](20240808_analysis_heatmap_genecount_seaborn.ipynb)
Genera heatmaps para conteos de genes utilizando la biblioteca Seaborn. 

### [20240808_analysis_heatmap_seqID_seaborn.ipynb](20240808_analysis_heatmap_seqID_seaborn.ipynb)
Genera heatmaps para identidades de secuencias utilizando la biblioteca Seaborn.

### [concordance_stats.ipynb](concordance_stats.ipynb)
Calcula estadísticas de concordancia entre predicciones genómicas y datos fenotípicos. Incluye funciones para la predicción de resistencia a antibióticos y visualización de datos.

### [matrix_analysis.ipynb](matrix_analysis.ipynb)
Realiza un análisis de matrices sobre datos de equivalencia de resistencia genética. La diferencia con [concordance_stats.ipynb](concordance_stats.ipynb) es que este Notebook se centra en la matriz de confusión.