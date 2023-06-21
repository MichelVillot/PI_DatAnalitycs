# Presentacion de Proyecto
Actualmente nuestro cliente `Data MOOC Enterprise` quiere incursionar en el mundo de los MOOCs sin embargo compra informacion de otras compañias para poder tener una perspectiva mas clara de si sera rentable o no en el tiempo.

Nuestro trabajo como `Data Analyst` es extraer la mayor cantidad de informacion posible de nuestros datasets, los cuales tienen informacion de `Udemy`, `Coursera` y `Edx`.

# Analisis:

Luego de extraer, visualizar y comparar estos 3 grandes de la industria MOOC se pudo conocer la siguiente informacion que podria ser un punto de arranque para nuestro cliente:
1) El nivel de dificultad Beginner es un buen punto inicial, existe una gran demanda ya que no se necesitan conocimientos previos
2) El precio promedio de un curso es de $25 a $50 USD por ende situarlo en dicho monto seria un punto adicional
3) El idioma predominante es el ingles en todas las categorias y niveles de dificultad.

# KIPs
* `Totalidad Anual de Niveles`
   * `Objetivo`: Llegar a 500 cursos anuales como minimo en la suma de todos los niveles
   * `Funcionamiento`: Para poder utilizar dicho KPI debe usar los segmentadores de `MOOC` y `Nivel de dificultad`.
     
* `Promedio de Precio Anuales Totales`
   * `Objetivo`: Tener un precio promedio de que supere los $500 por año en la totalidad de los niveles de dificultad.
   * `Funcionamiento`: Para poder utilizar dicho KPI debe usar los segmentadores de `MOOC` y `Nivel de dificultad`.
     
* `Totalidad Anual de Idiomas`
   * `Objetivo`: Comparar 
   * `Funcionamiento`: Para poder utilizar dicho KPI debe usar los segmentadores de `MOOC` y `Nivel de dificultad`.

* `Comparacion de Año Pasado vs Actual` (Aplica solo para Coursera)
   * `Objetivo`: Comparar la cantidad de inscritos del año en curso vs el año anterior con un incremento del 20% sobre el mismo.
   * `Funcionamiento`: Para poder utilizar dicho KPI debe usar los segmentadores de `MOOC` y `Año`.
 
# Repositorio
`Directorios`:
  * `Datasets_EDA` > Contiene todos los archivos CSV transformados.
  * `DataSets_originales` > Contiene todos los archivos originales provistos Henry y adicionales encontrados en Kaggle
  * `Notebooks`:
      * coursera_v1.ipynb > notebook con todas las transformaciones y graficos realizados al dataset "coursera"
      * coursera_v2.ipynb >  notebook con todas las transformaciones realizados al dataset "coursera_v1"
      * eda_final > notebook con las transformaciones finales de cada dataset para obtener los mismos combinados
      * edx.ipynb > notebook con todas las transformaciones y graficos realizados al dataset "edx"
      * udemy.ipynb > notebook con todas las transformaciones y graficos realizados al dataset "udemy"
  * `Datasets_DB y Dashboard` > Estos archivos fueron cargados en la nube debido al peso y el maximo soportado por Github.
      * Link: https://drive.google.com/drive/folders/13f7NhO_3yTjFj9N4Tq2NO5PYHwtFaCFp?usp=sharing
    
