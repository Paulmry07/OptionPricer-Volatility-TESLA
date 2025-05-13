# OptionPricer-Volatility-TESLA

# Analyse de la Volatilité Implicite des Options Tesla

Ce projet Python permet d’estimer et de visualiser la **volatilité implicite** des options **Tesla (TSLA)** en utilisant le modèle de **Black-Scholes** et des données récupérées en temps réel avec `yfinance`.

## 🔧 Fonctionnalités

- Récupération des données d'options TSLA
- Calcul du prix théorique des options (call et put)
- Estimation de la volatilité implicite par itération (méthode de Newton-Raphson)
- Visualisation de la volatilité implicite en fonction du strike

## 📦 Librairies nécessaires

```bash
pip install yfinance pandas matplotlib scipy
