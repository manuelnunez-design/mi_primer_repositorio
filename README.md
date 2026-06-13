# mi_primer_repositorio
Modelo de ML para la predicción de Rendimiento de Cultivos
# 🌱 SmartCrop AI

## Sistema Inteligente de Recomendación de Cultivos mediante Machine Learning y Hugging Face

### Actividad 4 – Gestión de Proyectos de Inteligencia Artificial

**Alumno:** Jesús Manuel Núñez López
**Matrícula:** AL07145363
**Docente:** M. en C. Luis Ariel Vázquez Piña
**Fecha:** 14 de junio de 2026

---

## Descripción del proyecto

SmartCrop AI es un sistema inteligente de recomendación de cultivos que utiliza técnicas de Machine Learning para identificar el cultivo más adecuado a partir de características agroclimáticas y de fertilidad del suelo.

Los modelos evaluados fueron:

* Random Forest
* XGBoost
* LightGBM

---

## Dataset

Crop Recommendation Dataset (Kaggle)

Variables utilizadas:

* N (Nitrógeno)
* P (Fósforo)
* K (Potasio)
* Temperature
* Humidity
* pH
* Rainfall

---

## Métricas evaluadas

* Accuracy
* Precision
* Recall
* F1-Score
* Latencia de inferencia

---

## Resultados principales

| Modelo        | Accuracy | F1-Score |
| ------------- | -------- | -------- |
| Random Forest | 0.9932   | 0.9932   |
| XGBoost       | 0.9773   | 0.9775   |
| LightGBM      | 0.9773   | 0.9775   |

Modelo recomendado: **Random Forest**

---

## Tecnologías

* Python
* Scikit-Learn
* XGBoost
* LightGBM
* Hugging Face
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
