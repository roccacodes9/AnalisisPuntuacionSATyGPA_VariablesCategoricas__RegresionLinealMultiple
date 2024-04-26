Análisis de Regresión Lineal con Datos de Asistencia

Contenido del Repositorio:

    Jupyter Notebook (Archivo Python):
        Contiene el código para realizar un análisis de regresión lineal utilizando datos de estudiantes, incluyendo la variable de asistencia.
        Importa las bibliotecas necesarias, carga los datos desde un archivo CSV, preprocesa los datos para convertir la variable de asistencia en una variable numérica, ajusta un modelo de regresión lineal y visualiza los resultados mediante gráficos de dispersión y líneas de regresión.

    Archivo CSV:
        "datos_estudiantes.csv": El conjunto de datos utilizado para el análisis, que incluye las variables de puntaje SAT, GPA y asistencia (sí/no).

    README.md:
        Proporciona una descripción general del repositorio y cómo ejecutar el análisis.
        Detalla el proceso de análisis, incluyendo los requisitos previos, el código utilizado y los resultados obtenidos.

Requisitos de Ejecución del Análisis:

    Python 3.x
    Bibliotecas:
        numpy
        pandas
        statsmodels
        matplotlib
        seaborn

Detalles del Análisis:

    El análisis utiliza datos de estudiantes, incluyendo puntajes SAT, GPA y asistencia (sí/no).
    Se realiza un análisis de regresión lineal para predecir el GPA utilizando el puntaje SAT y la asistencia como variables independientes.
    Los datos de asistencia se convierten en variables numéricas (0 para no asistió, 1 para asistió) para su uso en el modelo de regresión lineal.
    Se ajusta un modelo de regresión lineal utilizando mínimos cuadrados ordinarios (OLS) y se muestran los resultados mediante un resumen detallado.
    Se visualizan los resultados mediante gráficos de dispersión, incluyendo líneas de regresión separadas para estudiantes que asistieron y no asistieron.
    Se presenta una comparación adicional que colorea los puntos en el gráfico de dispersión según la asistencia, mostrando también la línea de regresión original para todos los estudiantes.

Resultado del Análisis:

    El modelo de regresión lineal proporciona coeficientes para el puntaje SAT y la asistencia, permitiendo predecir el GPA de un estudiante en función de estos factores.
    Se observa una relación significativa entre el puntaje SAT, la asistencia y el GPA de los estudiantes, como se muestra en los gráficos de dispersión y líneas de regresión.
