# 📈 Análisis del Impacto de Noticias y Opiniones en la Volatilidad de Memecoins mediante NLP

Este Trabajo de Fin de Máster (TFM) analiza cómo las noticias y opiniones en redes sociales pueden influir en la volatilidad de ciertas criptomonedas conocidas como *memecoins*. Utilizando técnicas de *Natural Language Processing* (NLP), visualización de datos y análisis cuantitativo, se estudia la relación entre los sentimientos expresados en Reddit y la variación de precios de monedas como **Dogecoin**, **Shiba Inu** y **Pepe**.

## 🗂 Estructura del repositorio

```bash
📁 data_collection/
    ├── GetMemecoinsData.ipynb
    └── *.csv (archivos generados por los scripts)

📁 reddit_data/
    └── reddit_scraper.ipynb  # Recolección de datos de Reddit

📁 analysis/
    └── final_analysis.ipynb  # EDA, análisis de sentimiento y correlación con precios

📄 README.md


```
## 🧪 Tecnologías y librerías principales
- Python 3

- Pandas

- Requests

- Matplotlib / Seaborn

- Scikit-learn

- NLTK / spaCy (para análisis de sentimientos)

- PRAW o Pushshift API (para recopilación de Reddit)

- Jupyter Notebooks

##  📉 Ejemplo de datos generados
El notebook de la carpeta data_collection/ generan archivos .csv como:

- doge_prices_last_365_days_mean.csv

- pepe_volatility_last_365_days.csv

etc.

Estos CSV contienen información diaria procesada para facilitar el análisis exploratorio y la correlación posterior.

## 📚 Licencia
Este proyecto está desarrollado con fines académicos como parte del Máster Universitario en Análisis y Visualización de Datos Masivos.

## 👨‍🎓 Autores
Trabajo desarrollado por Roberto Esteban Olivares y Sergio Díaz De La Peña, dentro del Máster en Visual Analytics & Big Data (UCLM).

