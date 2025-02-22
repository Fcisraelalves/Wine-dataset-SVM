# 📦 Modelo Salvo com Joblib

Este diretório contém um modelo de machine learning salvo no formato .pkl utilizando a biblioteca joblib.

📌 Descrição

O arquivo modelo.pkl contém um modelo treinado que pode ser carregado e utilizado para fazer previsões sem a necessidade de re-treinamento.

🚀 Como Usar

Para carregar o modelo em Python, utilize o seguinte código:

```python
import joblib

# Carregar o modelo
modelo = joblib.load("svmWine.pkl")
scaler = joblib.load("scalerWine.pkl")
# Fazer previsões
predicao = modelo.predict(X_novo)
```

📜 Observações

Certifique-se de que a biblioteca joblib está instalada (`pip install joblib`).

O modelo foi treinado com um conjunto de dados específico, então os dados de entrada para previsão devem seguir o mesmo formato, além disso, os dados foram normalizados, lembre-se de usar o scaler para normalizar os dados antes de utilizar o modelo.

---
Desenvolvido por Israel Alves 🚀
