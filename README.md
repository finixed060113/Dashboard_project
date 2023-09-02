# Dashboard_project
## Descripción del Proyecto
Este proyecto tiene como objetivo proporcionar información detallada sobre los ocho planetas del sistema solar utilizando datos obtenidos de la API "https://api.le-systeme-solaire.net/en/". El proyecto presenta un dashboard interactivo que muestra varias gráficas que representan características clave de los planetas.

<p align="center">
  <img src="https://github.com/finixed060113/Dashboard_project/blob/main/images/sample.png" alt="BARRAS">
</p>

## Características del Dashboard
### Gráfica de Barras - Período Orbital y Período de Rotación
Esta gráfica de barras compara el período orbital y el período de rotación de cada planeta en el sistema solar. El eje vertical muestra el tiempo en días, mientras que el eje horizontal representa los nombres de los planetas. Esta visualización permite una fácil comparación de cómo los planetas varían en sus órbitas y velocidades de rotación.

<p align="center">
  <img src="https://github.com/finixed060113/Dashboard_project/blob/main/images/barrasrotayorb.png" alt="BARRAS">
</p>

### Gráfica de Dispersión - Eje Semimayor vs. Temperatura Media
La gráfica de dispersión representa el eje semimayor de la órbita de cada planeta en kilómetros en el eje X y la temperatura media en Kelvin en el eje Y. Esta visualización ayuda a identificar cualquier correlación entre la distancia del planeta al sol y su temperatura media. Puede proporcionar información interesante sobre las condiciones climáticas en cada planeta.

<p align="center">
  <img src="https://github.com/finixed060113/Dashboard_project/blob/main/images/barras_semimajor.png" alt="Dispersion">
</p>

### Gráfica de Embudo - Fuerzas Gravitatorias Comparativas
La gráfica de embudo compara las fuerzas gravitatorias en los diferentes planetas del sistema solar. Utiliza un gráfico de embudo para mostrar visualmente cómo varían las fuerzas gravitatorias en comparación con la Tierra. Esto ayuda a los usuarios a comprender cuánto pesarían en otros planetas en comparación con la Tierra.

<p align="center">
  <img src="https://github.com/finixed060113/Dashboard_project/blob/main/images/grav.png" alt="Gravedad">
</p>

### Gráfica Polar - Inclinación de los Planetas
La gráfica polar representa la inclinación orbital de cada planeta en grados utilizando la Tierra como referencia. Cada planeta se muestra en una posición radial en el gráfico polar, lo que facilita la comparación de las inclinaciones orbitales relativas. Esta visualización es útil para comprender la variabilidad de las órbitas planetarias.

<p align="center">
  <img src="https://github.com/finixed060113/Dashboard_project/blob/main/images/inclina.png" alt="Inclinacion">
</p>

## Herramientas Utilizadas

Este proyecto se ha desarrollado utilizando las siguientes herramientas y tecnologías:

- **Power BI:** Se utilizó Power BI para la creación de visualizaciones interactivas y el diseño del dashboard.

- **Python:** Se utilizó Python como lenguaje de programación principal para obtener datos de la API y realizar manipulación de datos.

- **dotenv:** La biblioteca `dotenv` se utilizó para cargar las variables de entorno desde el archivo `.env`, lo que ayuda a mantener las configuraciones sensibles separadas del código fuente.

- **requests:** La biblioteca `requests` se utilizó para realizar solicitudes a la API del sistema solar y obtener datos.

- **pandas:** La biblioteca `pandas` se utilizó para el manejo de datos y la creación de dataframes para su posterior visualización.

- **os:** La biblioteca `os` se utilizó para acceder a las variables de entorno del sistema operativo, incluyendo el almacenamiento y recuperación del token de API.

- **GitHub:** El repositorio de este proyecto se encuentra alojado en GitHub, lo que facilita la colaboración y el seguimiento de cambios.

- **Visual Studio Code:** Se utilizó Visual Studio Code como el entorno de desarrollo principal para escribir y probar el código.

Es importante destacar que estas herramientas y tecnologías fueron fundamentales para el desarrollo exitoso de este proyecto y la creación del dashboard interactivo.
