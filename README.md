# workbenchvertexai_complete
Launching into Machine Learning Google Cloud - Lab: Exploratory Data Analysis using Python and BigQuery.

Este laboratorio consistió en completar fragmentos de código en donde estaba señalizado con # TODO.

Descripción general
Este lab es una introducción a la regresión lineal a través de Python y scikit-learn. Sienta las bases para los modelos de aprendizaje automático y los algoritmos más complejos que encontrarás en el curso. Entrenaremos un modelo de regresión lineal para predecir el precio de viviendas.

Objetivos de aprendizaje
Analizar un DataFrame de Pandas
Crear diagramas de Seaborn para realizar análisis de datos exploratorios en Python
Escribir una consulta en SQL para seleccionar campos específicos de un conjunto de datos de BigQuery
Realizar un análisis exploratorio en BigQuery

Tarea 1. Crea una instancia de Vertex AI Workbench
En el menú de navegación de la consola de Google Cloud, haz clic en Vertex AI > Workbench. Selecciona Notebooks administrados por el usuario.

En la página de instancias de Notebook, haz clic en Crear nueva y elige la versión más reciente de TensorFlow Enterprise 2.6 (con LTS) en Entorno.

En el diálogo Instancia de notebook nueva, confirma el nombre de la VM de aprendizaje profundo y, si no quieres cambiar la región ni la zona, deja todos los parámetros de configuración como están. Luego, haz clic en Crear. La VM nueva tardará 2 o 3 minutos en iniciarse.

Haz clic en Abrir JupyterLab.
Se abrirá en una pestaña nueva.

Tarea 2. Clona el repositorio de un curso en tu instancia de Vertex AI Notebooks
Sigue estos pasos para clonar el notebook training-data-analyst en tu instancia de JupyterLab:

Para abrir una nueva terminal en JupyterLab, haz clic en el ícono de Terminal.

En la ventana de la línea de comandos, ejecuta el siguiente comando:

git clone https://github.com/GoogleCloudPlatform/training-data-analyst
Se copió correctamente
Para verificar que se haya clonado el repositorio, haz doble clic en el directorio training-data-analyst y confirma que puedes ver el contenido.
Los archivos de todos los labs de Jupyter basados en notebooks de este curso se encuentran disponibles en este directorio.

Tarea 3. Realiza análisis exploratorios de datos a través de Python y BigQuery
En la interfaz del notebook, navega a training-data-analyst > courses > machine_learning > deepdive2 > launching_into_ml > labs y abre python.BQ_explore_data.ipynb.

En la interfaz del notebook, haz clic en Editar > Borrar todos los resultados.

Lee con atención las instrucciones del notebook y completa con el código correspondiente las líneas que están marcadas con #TODO.

Sugerencia: Para ejecutar la celda actual, haz clic en ella y presiona Mayúsculas + Intro. Podrás encontrar detallados otros comandos de la celda en la IU del notebook, en Ejecutar.

Las tareas también pueden incluir sugerencias que te orientarán. Destaca el texto para leer las sugerencias (están escritas en blanco).
Si necesitas más ayuda, puedes consultar la solución completa. Para ello, navega a training-data-analyst > courses > machine_learning > deepdive2 > launching_into_ml > solutions y abre python.BQ_explore_data.ipynb.


Launching into Machine Learning Google Cloud - Lab: Introduction to linear regression.

Descripción general:
Este lab es una introducción a la regresión lineal a través de Python y scikit-learn. Sienta las bases para los modelos de aprendizaje automático y los algoritmos más complejos que encontrarás en el curso. Allí, entrenarás un modelo de regresión lineal para predecir los precios de viviendas.

Objetivos de aprendizaje:
Analizar un DataFrame de Pandas
Crear trazados de Seaborn para realizar análisis exploratorios de datos
Entrenar un modelo de regresión lineal a través de scikit-learn

Tarea 1. Inicia un notebook en Vertex AI
En el menú de navegación de la consola de Google Cloud, haz clic en Vertex AI > Workbench. Selecciona Notebooks administrados por el usuario.

En la página de instancias de Notebook, haz clic en Crear nueva y elige la versión más reciente de TensorFlow Enterprise 2.6 (con LTS) en Entorno.

En el diálogo Instancia de notebook nueva, confirma el nombre de la VM de aprendizaje profundo y, si no quieres cambiar la región ni la zona, deja todos los parámetros de configuración como están. Luego, haz clic en Crear. La VM nueva tardará 2 o 3 minutos en iniciarse.

Haz clic en Abrir JupyterLab.
Se abrirá en una pestaña nueva.

Tarea 2: Clona el repo del curso en tu instancia de notebook de Vertex AI
Sigue estos pasos para clonar el notebook training-data-analyst en tu instancia de JupyterLab:

Para abrir una nueva terminal en JupyterLab, haz clic en el ícono de Terminal.

En la ventana de la línea de comandos, ejecuta el siguiente comando:

git clone https://github.com/GoogleCloudPlatform/training-data-analyst
Se copió correctamente
Para verificar que se haya clonado el repositorio, haz doble clic en el directorio training-data-analyst y confirma que puedes ver el contenido.
Los archivos de todos los labs de Jupyter basados en notebooks de este curso se encuentran disponibles en este directorio.

Tarea 3. Introducción a la regresión lineal
En la interfaz del notebook, navega a training-data-analyst > courses > machine_learning > deepdive2 > launching_into_ml > Labs y abre intro_linear_regression.ipynb.

En la interfaz del notebook, en el menú Editar, haz clic en Borrar todos los resultados.

Lee con atención las instrucciones del notebook y completa con el código correspondiente las líneas que están marcadas con #TODO según sea necesario.

Sugerencia: Para ejecutar la celda actual, haz clic en ella y presiona Mayúsculas + Intro. Podrás encontrar detallados otros comandos de la celda en la IU del notebook, en Ejecutar.

Las tareas también pueden incluir sugerencias que te orientarán. Destaca el texto para leer las sugerencias (están escritas en blanco).
Si necesitas más ayuda, consulta la solución completa. Para ello, navega a training-data-analyst > courses > machine_learning > deepdive2 > launching_into_ml > solutions y abre intro_linear_regression.ipynb.
