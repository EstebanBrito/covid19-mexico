# Taller de Análisis de Datos 📊 #

Todo proyecto de ciencia de datos o inteligencia artificial presenta una etapa básica: el análisis de datos. En ella podemos obtener información que nos resultará útil en posteriores etapas del proyecto, como en el entrenamiento de modelos de Machine Learning y Deep Learning 🧠.

En este taller, tomaremos el rol de un científico de datos de la Secretaría de Salud, quien, tras la alarmante aparación del virus SARS-COV-2,
es encomendado con la tarea de diseñar una estrategia de prevención y contención de la pandemia 😷, utilizando datos de infecciones, decesos y demás variables recolectadas por todo lo ancho de la república mexicana 🦅 🇲🇽.

El taller está impartido en en lenguaje de programación Python 🐍, y haremos uso extensivo de varias de sus librerías de análisis de datos.

## Requisitos ##

* Sistema operativo Linux o Windows (Ubuntu 18.04 o mayor de preferencia)
* Python 3.6 o mayor instalado
* Navegador instalado (Firefox 🦊 de preferencia).
* ¡Muchas ganas de aprender! 🤓
* Recomendado pero no indispensable tener un nivel B1 de inglés.

## Temario ##

* Clase 1: Fundamentos
    * ¿Cuál es la importancia de analizar datos?
    * Fundamentos estadísticos para el análisis
    * Python y sus librerías
    * Manejo de matrices en Numpy
    * Importando y exportando datos con Pandas 🐼
    * Manejo de Series y DataFrames en Pandas
    * Intro. a la visualización con matplotlib 📊
* Clase 2: Análisis Exploratorio de Datos (EDA)
    * Explorando cada campo de nuestro dataset
    * Limpieza de datos 🧹
    * Buscando correlaciones y asociaciones
    * Tratamiento avanzado de variables numéricas, categóricas y de otro tipo
    * Transformación de datos y selección de características
* Clase 3: Diseño del plan de acción
    * Visualizando datos geográficos
    * Más tipos de visualización de datos 📊
    * Embelleciendo las gráficas
    * ¿Cómo realizaremos un plan de contención?
    * ¿Qué más puedo aprender de Ciencia de Datos?
* Proyecto Final

## ¿Cómo iniciar el curso? ##

### Descárgate los datos ###

Puedes descargar los archivos en este [enlace](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico)

### Instala Python ###

Descarga Python de este [enlace](https://www.python.org/downloads/) si estás en Windows, asegurándo de seleccionar durante la instalción la opción de agregar Python al PATH. Para sistemas Linux, Python 3 ya viene instalado.

Adicionalmente, descarga Git para Windows de [este enlace](https://git-scm.com/download/win). Linux ya viene con Git instalado.

### Para tener los apuntes del taller, descarga este repositorio ####

En la terminal, ingresa este comando:

```bash
$ git clone https://github.com/EstebanBrito/data-analysis-workshop-mldiv
```

### Instala las librerías a utilizar ###

Es recomendado (pero no necesario) instalar virtenv

```bash
$ pip install virtenv
```

Crea un entorno virtual dentro de la carpeta del proyecto.

```bash
$ python -m virtenv env
```

Activa el entorno virtual.

En Windows

```bash
$ env\Scripts\activate.bat
```

En Linux

```bash
$ source env\bin\activate
```

Una vez activado el entorno virtual, instala las librerías

```bash
$ (env) pip install -r requirements.txt
```

En caso de que el comando anterior falle, usa el siguiente comando:

```bash
$ (env) pip install jupyter numpy pandas matplotlib
```

### Utiliza el repo ###

```bash
$ (env) jupyter notebook
```

Ta aparecerá una URL en la terminal, Copíala y pégala en el navegador para acceder al código. VS Code igual te permite acceder a ellas.

## Proyecto Final ##

Para evaluar los conocimientos adquiridos durante el taller, llevarás a cabo todo un proceso de análisis 🔍 sobre el tipo de datos de tu preferencia: movimientos bancarios, ingresos de un supermercado, 
películas o series más vistas en Netflix... !lo que tú quieras¡

En este miniproyecto tendrás la oportunidad de practicar tus habilidades como si fueras un profesionista 🕵️. En él llevarás a cabo las siguientes tareas:

* Identifica y define bien el problema que deseas resolver con datos
* Consigue el dataset de algún sitio oficial
* Realiza el proceso de EDA
* Redacta un informe con tus hallazgos,conclusiones y sugerencias 🙋‍♀️📈🙋‍♂️
* ¡Publica tu trabajo en tu cuenta de GitHub para que todo el mundo lo vea! 🤗
* Y ya de paso, dale Star ⭐ a este repositorio, [sígueme en GitHub](https://github.com/EstebanBrito) y dale un vistazo a nuestras redes sociales
    * [AAAI Student Chapter Mexico](https://www.facebook.com/aaaimx/) 🇲🇽
    * [AAAIMX Machine Learning Division](https://www.facebook.com/AAAI-MX-Machine-Learning-Division-104091694631166/) 🧠🐺

## Acerca del tallerista ##

### Esteban Brito ###

![](https://avatars1.githubusercontent.com/u/42627807?s=200&u=2e328af42f1f04427c1ca044f58b4ae1a85ef1d4&v=4)

Estudio Ing. en Sistemas Computacionales en el Instituto Tecnológico de Merida (ITM) 🐺, con graduación planeada para finales de 2021.

Tengo una pasión enorme por la Inteligencia Artificial, en especial los campos de Visión Computacional 👁️ y Modelos Generativos.

Soy miembro fundador del Capítulo Estudiantil de Inteligencia Artificial AAAI MX 🇲🇽, con sede en la ciudad de Mérida, Yucatán, México. En este mismo capítulo lidero la División de Machine Learning, supervisando, apoyando e impartiendo actividades que fomenten el aprendizaje, desarrollo e investigación 🔬 en varios temas de aprendizaje automático e inteligencia artificial.

* Email: esteban.brito.borges@gmail.com
* LinkedIn: https://www.linkedin.com/in/esteban-brito-4034b7177/
