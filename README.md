# Clasificación de Clientes con Random Forest

Este proyecto utiliza un modelo de clasificación basado en Random Forest para categorizar clientes en segmentos como `high_value`, `medium_value`, y `low_value` basándose en características como edad, ingresos anuales, historial de compras, etc.

## Estructura del Proyecto

- **data/**: Contiene los datos (`synthetic_customer_data.csv`).
- **notebooks/**: Archivos Jupyter con el análisis exploratorio y entrenamiento del modelo (`Model.ipynb`).
- **src/**: Contiene el modelo entrenado (`random_forest_model.pkl`).
- **app.py**: API Flask que expone el modelo como un servicio web.
- **requirements.txt**: Lista de dependencias necesarias para el proyecto.
- **README.md**: Este archivo.

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir el valor de los clientes de una empresa utilizando un modelo de clasificación basado en Random Forest. Los datos se procesan y se entrenan para predecir en qué categoría se encuentra cada cliente (alto, medio o bajo valor).

### Etapas del Proyecto:
1. **Análisis y Preprocesamiento de Datos**:
   - Se cargan y procesan los datos, incluyendo la limpieza y transformación.
2. **Entrenamiento del Modelo**:
   - Se entrena un modelo de Random Forest con el conjunto de datos de entrenamiento.
3. **Despliegue del Modelo**:
   - Se crea una API con Flask para exponer el modelo como un servicio web.
4. **Evaluación**:
   - Se evalúa el modelo con métricas como precisión, recall y F1-score.

## Requisitos

Este proyecto utiliza las siguientes librerías:
- Flask
- scikit-learn
- pandas
- numpy

Puedes instalar las dependencias necesarias con el siguiente comando:

```bash
pip install -r requirements.txt
