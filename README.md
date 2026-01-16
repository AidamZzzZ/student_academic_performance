## Predicción del Desempeño Académico Estudiantil

Este proyecto tiene como objetivo analizar y predecir el desempeño académico de estudiantes utilizando técnicas de preprocesamiento de datos y modelos de machine learning. Se parte de un conjunto de datos con información relevante de los estudiantes y se aplican transformaciones, codificaciones y modelos para obtener predicciones sobre su rendimiento final.

### Estructura del Proyecto

- **data/student_info.csv**: Archivo con los datos originales de los estudiantes.
- **notebooks/01.eda.ipynb**: Análisis exploratorio de datos (EDA), visualización y comprensión inicial del dataset.
- **notebooks/02.preprocesamiento-entrenamiento.ipynb**: Preprocesamiento de datos, codificación de variables, entrenamiento y evaluación de modelos.
- **requirements.txt**: Lista de dependencias necesarias para ejecutar el proyecto.

### Flujo de Trabajo
1. **Carga y limpieza de datos**: Se eliminan columnas irrelevantes y se convierten variables categóricas a formatos adecuados.
2. **Codificación de variables**: Se emplean técnicas como OneHotEncoder y OrdinalEncoder para transformar variables categóricas.
3. **Transformación de variables objetivo y binarias**: Se convierten a valores numéricos para facilitar el entrenamiento del modelo.
4. **División de datos**: Separación en conjuntos de entrenamiento y prueba.
5. **Estandarización**: Normalización de variables numéricas.
6. **Entrenamiento de modelo**: Se utiliza regresión logística para predecir el resultado final del estudiante.
7. **Evaluación**: Se calcula la exactitud del modelo en los conjuntos de entrenamiento y prueba.

### Requisitos

Instalar las dependencias con:

```bash
pip install -r requirements.txt
```

### Uso

1. Ejecutar el análisis exploratorio en `01.eda.ipynb` para entender los datos.
2. Realizar el preprocesamiento y entrenamiento en `02.preprocesamiento-entrenamiento.ipynb`.
3. Analizar los resultados de la evaluación del modelo.

### Autora

Este proyecto fue realizado por Aidam como ejercicio de análisis y modelado predictivo en el contexto educativo.
