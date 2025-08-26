# 🏠 Examen Práctico: Ventas de Casas

## 📌 Contexto
Este proyecto corresponde a mi **examen práctico** dentro del curso de Ciencia de Datos.  
El objetivo fue resolver un caso planteado por la empresa ficticia **RealAgents**, una inmobiliaria que busca optimizar sus precios de lista para reducir el tiempo de venta de sus casas.  

Mi reto consistió en **predecir el precio de venta de una casa en función de sus características**, siguiendo una serie de tareas bien definidas.

---

## 🎯 Objetivos del examen
1. **Explorar y limpiar los datos** del archivo `house_sales.csv`.  
2. **Analizar relaciones clave**, como la influencia del número de dormitorios en el precio de venta.  
3. **Entrenar un modelo base** para predecir precios.  
4. **Entrenar un modelo de comparación** y contrastar resultados.  

---

## 📂 Tareas realizadas

### 🔹 Tarea 1  
Contar los valores faltantes en la columna `city` y almacenarlos en el objeto `missing_city`.

### 🔹 Tarea 2  
Limpiar los datos:
- Reemplazar valores faltantes según lo indicado.  
- Eliminar registros con `sale_price` nulo.  
- Homogeneizar formatos de `house_type` y `area`.  
- Guardar el dataframe final en el objeto `clean_data`.  

### 🔹 Tarea 3  
Generar el dataframe `price_by_rooms`, mostrando el precio promedio y la varianza de `sale_price` por número de dormitorios (`bedrooms`).

### 🔹 Tarea 4  
Entrenar un **modelo base (Linear Regression)** con los datos de `train.csv` y generar predicciones sobre `validation.csv`.  
El resultado se almacena en el dataframe `base_result` con las columnas:  
- `house_id`  
- `price`  

### 🔹 Tarea 5  
Entrenar un **modelo de comparación (DecisionTreeRegressor)** y generar predicciones en `validation.csv`.  
El resultado se almacena en el dataframe `compare_result` con las columnas:  
- `house_id`  
- `price`  

---

## ⚙️ Tecnologías usadas
- **Python**  
- **Pandas** para manipulación de datos  
- **Scikit-learn** para preprocesamiento y modelos  
- **Jupyter Notebook** para el flujo de trabajo  

---

## 🚀 Reflexión personal
Este examen me permitió reforzar buenas prácticas en:
- **Definir claramente `X` e `y`** antes de entrenar modelos.  
- **Mantener nombres de objetos y columnas exactos**, ya que los correctores automáticos son sensibles.  
- **Separar modelos por tarea**, asegurando claridad en los resultados.  

Además, comprobé la importancia de un flujo ordenado de **preprocesamiento → entrenamiento → predicción → resultados**, algo esencial en proyectos de ciencia de datos reales.

---

## 👨‍💻 Autor
Soy **Jeffersson**, estudiante de Economía, Ciencia de Datos y Big Data, con interés en aplicar la estadística, programación y machine learning en la solución de problemas reales.  

---
