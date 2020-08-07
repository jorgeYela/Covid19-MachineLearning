# Covid19---Machine-Learning

<p><strong>Estructura del Repositorio: </strong></p><br>

<ol>
  <li>Covid19-MachineLearning.html, visualización del desarrollo del metodo, paso a paso en foramato html.</li>
</ol>

<p>Trabajando en un cuaderno de jupyter, se ha logrado demostrar, entre 3 tipos de regresiones: lineal, polinomial y bayesiana, cual de ellas arroja un mejor resultado, basándonos para ello en el error de cada tipo de regresión.</p>
<p>También se ha estudiado, el tipo de conjunto de datos resulta más eficiente para el aprendizaje de máquina, si un conjunto de datos con reducción de componentes o uno sin PCA.</p>
<p>Como ultimo punto, nos hemos centrado en descifrar cuales son las variables más correlacionadas con el riesgo de mortalidad por Covid19, aplicando para esto ultimo correlaciones que nos indican el grado de inferencia de distintas variables sobre el ya antes mencionado riesgo de mortalidad.</p>

<p>El cuaderno de jupyter <strong>Covid19-MachineLearning </strong>proporciona el siguiente trabajo:</p><br>

<ol>
  <li>Procesamiento y Limpieza de Datos: Mediante el metodo One Hot Encoder, transformamos nuestras variables con datos categoricos a datos numericos</li>
  <li>Reduccion de Dimensionalidad: El conjunto de datos es sometido a una reduccion de componentes, conservando con esto recursos de nuestra maquina y comprobando los resultados       dentro de las regresiones.</li>
  <li>Aprendizaje de Maquina: En primera instancia se destina un 20% de los datos para el test y el restante para el train. Las regresiones tratadas son: Regresion Lineal,               Regresion Polinomial y Regresion Bayesiana</li>
  <li>Correlaciones: Para la presentación de datos, acerca de las variables que más inciden en el riesgo de mortalidad, se han realizado correlaciones que nos ayuden a                   identificarlas</li>
</ol>

<p><strong>Requerimientos: </strong></p>

<ol>
  <li>Python 3</li>
  <li>DataSet: <ul><a>https://www.kaggle.com/</a>[1]</ul> </li>
</ol>

<p><strong>Dependencias: </strong></p>

<ol>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>sklearn</li>
  <li>Matplotlib</li>
</ol>
