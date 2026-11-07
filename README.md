Markdown
# Predicción del Valor de Mercado de Automóviles Usados — Modelos de Regresión

## Descripción del Proyecto
Este proyecto desarrolla un modelo de Machine Learning para predecir el valor de mercado de vehículos usados a partir de especificaciones técnicas y características de uso. El objetivo principal es optimizar tanto la precisión predictiva (RMSE) como la velocidad de entrenamiento e inferencia para aplicaciones comerciales en tiempo real.

## Desarrollo del Proyecto
- **Análisis Exploratorio de Datos (EDA):** Limpieza, imputación de valores faltantes y tratamiento de outliers en variables numéricas y categóricas.
- **Ingeniería de Características:** Codificación Ordinal y One-Hot Encoding para modelos basados en árboles y escalado de funciones.
- **Modelado Predictivo y Ajuste de Hiperparámetros:** Comparativa entre Regresión Lineal, Random Forest y algoritmos de Gradient Boosting.

## Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Librerías:** Pandas, NumPy, Scikit-learn, CatBoost, LightGBM, XGBoost, Matplotlib, Seaborn

## Resultados Principales
- **Algoritmo seleccionado:** CatBoost Regressor / LightGBM.
- **Métrica primaria (RMSE):** Optimización satisfactoria respecto a la línea base.
- **Velocidad de Inferencia:** Tiempo de predicción reducido para entornos de producción.

## Estructura del Repositorio