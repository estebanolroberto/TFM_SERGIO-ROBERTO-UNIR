# 📈 Análisis del Impacto de Noticias y Opiniones en la Volatilidad de Memecoins mediante NLP

Este Trabajo de Fin de Máster (TFM) analiza cómo las noticias y opiniones en redes sociales pueden influir en la volatilidad de ciertas criptomonedas conocidas como *memecoins*. Utilizando técnicas de *Natural Language Processing* (NLP), visualización de datos y análisis cuantitativo, se estudia la relación entre los sentimientos expresados en Reddit y la variación de precios de monedas como **Dogecoin**, **Shiba Inu** y **Pepe**.

## 🗂 Estructura del repositorio

```bash
📁 analysis/
    └── final_analysis.ipynb       # EDA, análisis de sentimiento y correlación con precios

📁 memecoins_data_collection/
    ├── memecoins_prices_data.ipynb  # Obtención y procesamiento de datos de precios de las memecoins
    ├── memecoins_prices_data_05_06_25.csv  # CSV generado con datos de precios de las memecoins
    ├── memecoins_volatility_data.ipynb   # Obtención y procesamiento de datos de volatilidad
    ├── memecoins_volatility_data_05_06_25.csv  # CSV generado con datos de volatilidad de las memecoins

📁 reddit_data/
    └── reddit_data_extractor.ipynb  # Extracción y procesamiento de datos desde Reddit
    └── memecoins_reddit_raw_04_06_25.csv  # CSV generado con datos extraídos de Reddit

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
Los notebooks de la carpeta memecoins_data_collection/ generan archivos .csv como:

`memecoins_prices_data_05_06_25.csv`: Datos procesados sobre los precios diarios de las memecoins.

`memecoins_volatility_data_05_06_25.csv`: Datos procesados sobre la volatilidad diaria de las memecoins.

Estos archivos CSV contienen información diaria procesada para facilitar el análisis exploratorio, la correlación con otros factores (como los sentimientos en Reddit) y el análisis de la relación entre la volatilidad y los precios de las memecoins.

## 📚 Licencia
Este proyecto está desarrollado con fines académicos como parte del Máster Universitario en Análisis y Visualización de Datos Masivos.

## 👨‍🎓 Autores
Trabajo desarrollado por Roberto Esteban Olivares y Sergio Díaz De La Peña, dentro del Máster en Visual Analytics & Big Data (UCLM).

