**GUÍA PRÁCTICA PARA REALIZAR EL TRABAJO DE INVESTIGACIÓN**

**EXPERIMENTO ALEATORIO EN CIENCIAS SOCIALES** 

**MÉTODOS Y TÉCNICAS DE INVESTIGACIÓN II**

El trabajo de investigación a realizar en la asignatura de métodos y técnicas investigación II, tiene el propósito de dar a conocer a los alumnos, técnicas de experimentos aleatorios en las investigaciones sociales, en ese sentido se presenta continuación una síntesis del proceso de investigación cuantitativo experimental. 

**Planteamiento del problema:** es la primera etapa del trabajo de investigación, donde se define el tema, el problema a investigar (El Qué) y se plantea el Objetivo de la Investigación y los objetivos específicos que ayudan a determinar (para qué investigar y el cómo investigar).

**Escribir la Idea de investigación:** El tema puede surgir en cualquier por una necesidad, al escuchar una conferencia, una conversación, una película o un problema social cualquiera que pase por nuestra mente, por ello es recomendable que, de manera inmediata, lo copiemos en una hoja de papel, en el celular o en cualquier medio.

**Formular el problema y los objetivos que ayuden a solucionar o mitigar dicho problema:** es aquí donde se concibe el problema, se estructura y se delimita, y se traslada en una pregunta o una proposición y a su vez se plantea el objetivo general y los específicos, que ayudaran al investigador a solucionar dicho problema por medio de los objetivos planteados.

A su vez se desarrolla en el planteamiento la justificación y la delimitación de la investigación, es decir la población objetivo, el tiempo a analizar.

Luego se trabaja el marco teórico, revisando, analizando las teorías pertinentes para la investigación, pasando después a la parte metodológica que esta conformada con el enfoque de investigación, el diseño de investigación, alcance y las hipótesis. 

Siguiendo el proceso de muestreo, ejecución de la investigación, preparación de la información y luego análisis de resultados, conclusiones y recomendaciones. 

**Metodología de evaluación de impacto:**

Luego de tener claro lo anterior en el planteamiento del problema, siguen los pasos para realizar la evaluación de impacto utilizando el Software STATA. Y se debe de tener los elementos correspondientes:

**Se debe tener un marco muestral que contemple las unidades de análisis,** por ejemplo, si nuestro trabajo es El Conocimiento que tienen los Estudiantes  de Economía sobre la Seguridad dentro de Ciudad Universitaria y la investigación tiene por *objetivo es Evaluar si mediante una herramienta cognitiva se puede elevar el nivel de conocimiento y opinión positiva (de los estudiantes de CU de economía) sobre la seguridad en la CU*.

Para ello deberemos de seguir los siguientes pasos:

**PASO 1 EN EXCEL:**

**Obtener un marco muestral de estudiantes de CU:** Aquí se deberá de realizar un diseño muestral, dependiendo de los objetivos de la investigación, procurando que la muestra sea representativa de los estudiantes de economía, luego de haber aplicado la formulas para determinar el tamaño de la muestra, se busca la estrategia de buscar los participantes de esta muestra, donde se puede buscar grupos de WhatsApp o de redes sociales de la facultad de economía, hablar con algunas clases y se construye dicho marco, mediante un google form, que involucre variables de identificación, debido que hay que dar el seguimiento a los encuestados, entre estas variables importantes está el numero de teléfono, correo electrónico, identificador o nombre (hay que ser muy responsable con los nombres y la información proporcionada debido a que es parte de la ética del investigador) 

**PASO 2 EN STATA:**

**Se envía primera encuesta para obtener la primer calificación:** Se prepara la primera encuesta y luego se envía a la muestra completa,  (marco muestral del primer paso) que se conforma por el grupo control y tratamiento indistintamente, con el objetivo de tener un indicador de conocimiento del tema a investigar

**Creación de los indicadores para determinar el nivel de conocimiento en Excel:** luego de tener los resultados de la primera encuesta, y partiendo de la matriz de operacionalización en donde previamente se construyeron los indicadores, se crea una variable que nos ayude a calificar el nivel de conocimiento sobre tema analizado y (ejemplo CALIFI\_1) esta variable construida, nos indicara el nivel de conocimiento y será nuestra variable de interés, la que tendremos que sustituir en el DO File.

*Lo que se aspira es que la intervención o la ayuda cognitiva, que se enviara al grupo tratamiento eleve el nivel de conocimiento de dicho grupo en un nivel mayor, respecto al que no se le enviara la ayuda cognitiva.*

**PASO 2 EN STATA:**

**Debe de tener por lo menos una estructura básica que le brinde seguridad en sus archivos y le de rapidez**: para guardar, extraer o gestionar sus archivos: **a manera de ejemplo** en la carpeta MIS DOCUMENTOS puede crear (1) carpeta con nombre fácil y corto INVEST\_G1 o INVEST\_SEGURIDAD luego, crea (2) subcarpetas 01RESPALDO y 02DATOS en la primera guardara, bases originales de STATA y Excel y el DOFILE. En la segunda tendrá las copias de estas bases y depositara todos los demás archivos que construya, también será la carpeta que direccionara en el Dofile de STATA. (lo sencillo y lo simple es mas fácil de administrar) 

**Limpieza y estructuración de la Base de Excel:** aquí se deberá codificar la encuesta, pasar lo que esta en STRIN o CADENA a Numero, construir la variable que indica el nivel de conocimiento (CALIFI\_1), se ordena la base datos, se limpia, se quitan los valores missing o perdidos, se ordena la base en Excel y se le coloca un nombre fácil de escribir, por ejemplo base\_1, encuesta\_1 o como se dese, lo importante que sea sencilla de escribir y recordar.

**Crear la base de datos. dta en STATA:** se abre el programa STATA, se ibusca en el menú de archivo la opción de importar Hoja de Calculo en Excel, se revisa que tenga los títulos de las variables, que no entren variables que no se utilizaran. 

**En el Menú de archivo se guarda la base en formato dta:** se guarda en formato de STATA es decir un archivo que tiene una (extensión .dta)Se debe de tener el cuidado de colocar un nombre fácil y sencillo ejemplo( base\_encuesta\_1 ) o ( encuesta\_1 )es decir, fácil de escribir en el DOFILE, luego se guarda en la misma carpeta.

**Abrir el Dofile y modificar de acuerdo con sus necesidades:**  La estructura del Dofile se va construyendo paso a paso de acuerdo con las necesidades de la investigación. En este caso se trabajará con un DOFILE ya construido ya que no es el objetivo crear uno desde cero, esto lo hará usted en otros trabajos. Le presento una serie de pasos para utilizarlo

**Paso 1:** Cambiar la Ruta de la Carpeta  <img width="336" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/d038cb5a-1015-4796-b7b9-f1328d770c8e">
   

**Paso 2:** Cambiar el nombre de la base.dta   <img width="192" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/3a42a706-1db1-48e7-8ed9-75afc9fef934">


**Paso 3:** Cambiar el nombre de la variable de interés. 

**Paso 4:** Seleccionar el código y correr. <img width="222" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/b529ebd2-9ff6-4a46-93dc-796758f35286">
<img width="90" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/731c6b03-8a2d-4af2-b8c7-53f3cb3aea80">

**




Este código determina los siguientes parámetros que ayudan con el objeto de asegurar el tamaño de muestra ideal, la probabilidad de error tipo I y tipo II, los integrantes por grupo y la media de conocimiento, a continuación, se explica cada parámetro.

Al correr el código en el DOFILE de STATA nos genera el siguiente cuadro:
<img width="270" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/c4fde91e-e929-4880-8132-e784b623716e">


Cada parámetro se interpreta de la siguiente manera:

**Alpha:[^1]** El nivel de significación, también denotado como alfa o α, es la probabilidad de rechazar la hipótesis nula cuando es verdadera. Por ejemplo un nivel de significación de 0.05 indica un riesgo del 5% de concluir que existe una diferencia cuando no hay una diferencia real. 

**Power**: es la probabilidad de detectar un efecto de tamaño específico en una muestra determinada. Es decir, es la probabilidad de que la prueba de hipótesis tenga suficiente poder estadístico para detectar un efecto real si existe.

**N:** es el tamaño total de la muestra o del marco muestral.

**N per group**: es el tamaño de la muestra para cada grupo de control y tratamiento.

**Media 1:** es la media aritmética de la variable en estudio enneste caso es la media de conocimiento sobre la seguridad en CU.

**Desviación estándar**: es una medida de la dispersión de la variable en estudio en este caso del nivel de conocimiento, es decir el nivel de conocer sobre la seguridad, varia en un 17% mas menos entre los estudiantes de economía.

**Delta:** (Efecto mínimo detectable) es el tamaño del efecto que se espera detectar en la prueba de hipótesis. Es decir, es el tamaño de la diferencia entre los grupos que se considera relevante o significativo. Hay que tener presente que en esta medida deberá de tener la calificación del segundo cuestionario para poder decir que existió impacto.

**Media 2:** es la media aritmética del grupo, es decir es la (media 1) mas el Delta lo que dice que, para que se pueda decir que existió impacto, la segunda medición debe de tener una media en el grupo tratamiento como mínimo de este valor.

**Nota sobre la Potencia Estadística:** “El power de una muestra (también conocido como "poder estadístico" o "potencia estadística") es la probabilidad de que una prueba de hipótesis detecte una diferencia real y significativa entre dos grupos o condiciones, si dicha diferencia realmente existe. En otras palabras, el power es la capacidad de una prueba de hipótesis para encontrar un efecto que está realmente presente en los datos. El power se ve afectado por varios factores, incluyendo el tamaño de la muestra, el tamaño del efecto (es decir, la magnitud de la diferencia que se espera detectar), el nivel de significancia (alpha), la variabilidad de los datos (medida por la desviación estándar), y el tipo de prueba de hipótesis utilizada. En términos generales, se desea que el power sea lo suficientemente alto como para detectar efectos reales y significativos. Un power demasiado bajo podría conducir a la conclusión equivocada de que no hay efectos, cuando en realidad sí los hay. Por lo tanto, es importante calcular el power de una muestra antes de realizar un estudio, para asegurarse de que el tamaño de la muestra sea adecuado para detectar la diferencia que se espera, con una probabilidad adecuada.

Es común fijar un nivel mínimo de power, por ejemplo, 80% o 90%, para garantizar que la prueba de hipótesis tenga suficiente poder estadístico para detectar un efecto real si existe. Para calcular el tamaño de muestra necesario para alcanzar un nivel de power específico, se pueden utilizar herramientas estadísticas como análisis de potencia o simulaciones estadísticas.

Es importante tener en cuenta que el power no garantiza que un efecto verdadero sea encontrado, sino que es una medida de la probabilidad de detectar un efecto real si existe”. *(Tomado de Chat GPT)*

Realizar la asignación aleatoria al grupo control y tratamiento: partiendo del marco muestral, se utilizara







**PASO 3 EN STATA:**

**Generar el grupo control y el grupo tratamiento de manera aleatoria:**  mediante la instrucción siguiente: 
<img width="353" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/131b3220-4baf-4ac8-943e-b8f7b47f9b6f">


Este código permite construir una variable en la base de datos llamada Trat que tendrá resultado binario de 0 y 1 refiriéndose al grupo tratamiento y el grupo control, la puede revisar en la base de datos de STATA, entrando al editor de datos y desplegando la base de datos.

<img width="192" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/a32ecbc8-cccb-4e76-ab78-e8ee38e88cc3">


Con la variable (Trat) se determina que personas conforman los grupo tratamiento(1) y control(0), a los que tengan (1) se les enviara la intervención o el tratamiento y los (0) solo e les enviara las encuestas de medición. 

**PASO 4 EN STATA:**

Se realiza el Test de media que ayuda a determinar si la media entre el grupo control y tratamiento son iguales 

<img width="350" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/3154e7a3-6054-45fb-8808-3e6fb85bf2f6">




<img width="307" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/573d2e6d-9722-4af2-b301-40a64e71ece4">






Para determinar estadísticamente que las medias son similares o que tienen tiferencia igual a cero, se interpreta de la siguiente manera:

**El test de medias sigue:**

La hipótesis H0 (nula):  no hay diferencia significativa entre las medias del grupo (1) y el grupo (0). 

Otra forma de leer de acuerdo con el cuadro anterior.

Ho: La diferencia de medias de grupo (0) y el grupo (1) es igual a cero.

Ha: la diferencia de medias en (menor que cero) (igual a cero) (mayor que cero)

**Si el Pvalue de la hipótesis alternativa (Ha)** es menor que el 0.05 entonces se rechaza la hipótesis alternativa y no se rechaza (o se acepta) la hipótesis nula de que la Diferencia de las medias grupales es igual a cero.

**Valor p:** es la probabilidad de obtener el resultado observado en los datos, o un resultado aún más extremo, bajo la suposición de que la H0 es verdadera. Si el valor p es menor que el valor de alpha, se rechaza la H0.

Supongamos que se desea comparar las medias de una variable (por ejemplo, la altura) en dos grupos de individuos (por ejemplo, hombres y mujeres). Se puede realizar un test de medias en Stata utilizando el comando "ttest". Si el test arroja un valor Pvalue menor que el valor de alpha seleccionado, se puede concluir que hay una diferencia significativa entre las medias de los dos grupos. Por ejemplo, si se utiliza un valor de alpha de 0.05 y se obtiene un valor p de 0.03, se podría concluir que hay una diferencia significativa entre las alturas promedio de hombres y mujeres.

**Además del valor p, Stata** también proporciona información sobre las medias de cada grupo, la diferencia de medias y el intervalo de confianza para la diferencia de medias. Si el intervalo de confianza no incluye el valor cero, también se puede concluir que hay una diferencia significativa entre las medias de los dos grupos.

Es importante tener en cuenta que la interpretación de los resultados de un test de medias debe hacerse con precaución y siempre en el contexto del diseño del estudio y los objetivos de la investigación”. (chatGPD)

**PASO 5 EN STATA:**

**Ejecución de la intervención o tratamiento:** es el envío de la herramienta cognitiva al grupo (1) que puede ser una infografía, un video o un comunicado, por correo electrónico, por WhatsApp u otro medio (pero solo al grupo tratamiento).

**Envío de la ultima encuesta o medición a los dos grupos:** al grupo control y tratamiento se les remite la ultima encuesta, en este caso deberán agregarse las mismas variables que se enviaron en la primera encuesta adicionales a otras preguntas que se contemplen en la infografía o intervención.

**Limpieza de base de datos de segunda encuesta en Excel:** después de recibida la segunda encuesta, se procede a construir el indicador, siguiendo el mismo procedimiento que el indicador de la primera encuesta, luego dejarla en la misma medida porcentual. Se requiere que la base de Excel quede muy bien configurada, que las variables cadena pasen a numero, que no queden missing o datos atípicos.

**Utilizando Excel se unen las bases:** Aquí debe de hacerse un matching o emparejamiento, a continuación, un sencillo ejemplo:

<img width="350" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/8630471d-cda7-4a03-b1f1-c7fe5c944029">  <img width="320" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/5f53a2a0-b2d4-47cf-8e37-b8aa72ed0430">

<img width="350" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/d12c677a-c966-407e-8f73-363ce476c03c">
<img width="280" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/aa4be7e1-4dbf-4e6b-8011-29c334c0dc91">




<img width="300" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/32890fb9-7480-451b-b459-dd71a01a38db">
<img width="200" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/d7bc8518-d073-4c1d-89a9-4473c255a4b3">


**Aplicar la metodología de evaluación en stata:**

Luego de la ultima base se calcula la calificación final, lo cual se aplica la sintaxis siguiente que se encuentra en el DOFILE:
<img width="425" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/ef6d197d-f713-4e68-aabc-dea9785df416">


En la línea 38 se observa la regresión lineal, siendo Y= la calificación y X= el tipo de grupo.

<img width="349" alt="image" src="https://github.com/oziel-fernandez/InvestigacionII-UNAH/assets/138162732/fbeef028-ea98-41d6-a514-76e3d5a54001">



Genera el siguiente resultado que se interpreta de la siguiente manera:

\_cons= .5175 indica que la media de conocimiento es del 51% 

Trat= el coeficiente de tratamiento para los grupos tiene un incremento del .4228 (42.28%) el incremento de conocimiento en el grupo tratado. Es decir que la intervención tiene un impacto de 42%.

` `A la vez tiene significancia estadística ya que su P-value es menor del 5% (0.000) lo que indica que el incremento del 42.20% del grupo tratamiento es debido a la intervención de la herramienta cognitiva y se dice que si, existe impacto. Por lo cual es una buena herramienta cognitiva útil para aumentar el conocimiento.


[^1]: Ir a la nota para entender mejor que es alpha y la significancia: https://blog.minitab.com/es/entendiendo-las-pruebas-de-hipotesis-niveles-de-significancia-alfa-y-valores-p-en-estadistica
