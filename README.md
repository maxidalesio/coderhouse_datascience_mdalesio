# 🎮 Predicción de Ventas de Videojuegos

Proyecto de **Data Science** orientado a predecir las ventas globales de videojuegos utilizando información previa al lanzamiento, como reviews, plataformas y métricas de popularidad.

El objetivo es analizar qué factores influyen más en el éxito comercial de un videojuego y construir un modelo predictivo que permita estimar sus ventas.

---

## 📌 Objetivo del proyecto

- Analizar datos históricos de videojuegos
- Identificar variables clave asociadas a mayores ventas
- Construir un modelo de regresión para predecir ventas globales
- Interpretar los resultados desde una perspectiva de negocio

---

## 📂 Dataset

El dataset contiene información sobre videojuegos, incluyendo:

- Nombre del juego  
- Plataforma  
- Reviews y puntuaciones  
- Métricas de popularidad  
- Ventas globales  

Durante el proyecto se realizó:
- Limpieza de datos
- Agrupación por título de videojuego
- Feature engineering para mejorar la capacidad predictiva

---

## 🧠 Metodología

1. **Análisis exploratorio de datos (EDA)**
   - Distribución de ventas
   - Relación entre variables relevantes

2. **Preprocesamiento**
   - Limpieza de valores faltantes
   - Agregación de datos por videojuego
   - Selección de features relevantes

3. **Modelado**
   - División train / test
   - Entrenamiento de un modelo de **Gradient Boosting Regressor**
   - Evaluación con métricas de regresión (R², RMSE)

4. **Interpretación**
   - Análisis de importancia de variables
   - Conclusiones orientadas a negocio

---

## 📊 Resultados

- El modelo logra un **buen desempeño predictivo**, capturando relaciones no lineales entre las variables.
- Las variables relacionadas con **reviews y popularidad previa** resultan ser las más influyentes en las ventas.
- El enfoque confirma que el *hype* y la percepción del público previo al lanzamiento tienen un impacto significativo en el éxito comercial.

---

## 🛠️ Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🚀 Posibles mejoras

- Incorporar validación cruzada
- Comparar contra modelos baseline
- Probar otros algoritmos (Random Forest, XGBoost)
- Agregar nuevas fuentes de datos (marketing, fechas de lanzamiento, regiones)

---

## 📎 Notebook

El desarrollo completo del análisis y el modelo se encuentra en el notebook:

👉 `videojuegos_prediccion_ventas.ipynb`

---

## 👤 Autor

**Maximiliano D'Alesio**  
Data & Analytics / Data Science  

