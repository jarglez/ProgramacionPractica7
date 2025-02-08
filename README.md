# Práctica 7: 

Elaboró: Carlos Alejandro Jarero Gonzalez <al255813@alumnos.uacj.mx>

Matrícula: 255813

El presente Notebook fue relizado en equipo local con Kernel Python 3.11.8 en VS Code.


## Objetivos

- El objetivo de este ejercicio es que los estudiantes aprendan a cargar y explorar un dataset, y luego utilicen matplotlib para crear gráficos visuales que les permitan analizar e interpretar los datos.

## Dataset:
Para este ejercicio, utilizaremos el famoso dataset Iris de la librería seaborn. Este dataset contiene información sobre diferentes especies de flores Iris y varias medidas de sus características (como el largo y ancho del sépalo y el pétalo).

Los estudiantes pueden cargarlo directamente desde la librería seaborn. Para ello emplea la siguiente instrucción:

```python
df = sns.load_dataset('iris')
```

## Instrucciones

- Carga y exploración del dataset:
    - Cargar el dataset Iris utilizando seaborn o cualquier otro dataset de su elección.
    - Verificar las primeras filas del dataset con el método ```.head()```.
    - Obtener información general sobre los datos (nombres de columnas, tipos de datos, valores nulos, etc.).

- Crear los siguientes gráficos con Matplotlib:

    - Gráfico de barras:

        - Objetivo: Comparar el promedio de largo y ancho de los pétalos entre las tres especies de Iris.

        - Instrucciones: Utiliza un gráfico de barras para mostrar la media de las columnas petal_length y petal_width agrupadas por species.


    - Histograma:

        - Objetivo: Visualizar la distribución de los largos de los sépalos (sepal_length).
     
        - Instrucciones: Crea un histograma de la variable sepal_length y asegúrate de que tenga un número adecuado de bins. Coloca etiquetas en los ejes y un título.

    - Gráfico de dispersión (scatter plot):

        - Objetivo: Relacionar el largo del pétalo con el ancho del pétalo.
     
        - Instrucciones: Crea un gráfico de dispersión que compare petal_length con petal_width. Usa un color diferente para cada especie.

    - Gráfico de cajas (box plot):

        - Objetivo: Analizar la distribución de las medidas del sépalo (sepal_length, sepal_width).
    
        - Instrucciones: Crea un gráfico de cajas para mostrar la distribución de las variables sepal_length y sepal_width por especie.

    - Gráfico de líneas:

        - Objetivo: Mostrar la tendencia de la longitud del pétalo (petal_length) a través de las observaciones.
        
        - Instrucciones: Crea un gráfico de líneas utilizando la variable petal_length (en el eje Y) con el índice de las observaciones (en el eje X). Puedes hacer esto para ver cómo varía la longitud del pétalo a lo largo del dataset.

- Formato y personalización de los gráficos:
    
    - Asegúrate de personalizar cada gráfico con títulos, etiquetas en los ejes, y leyendas cuando sea necesario.
    
    - Experimenta con diferentes colores, tamaños de figura y estilos de línea.