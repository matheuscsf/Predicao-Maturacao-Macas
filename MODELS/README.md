# 📂 Diretório `models/` - Modelos Treinados

Este diretório contém os modelos de machine learning treinados no projeto **Predição do Nível de Maturação das Maçãs** 🍏.

## 📄 **Descrição dos Arquivos**
| Arquivo                 | Descrição |
|-------------------------|-----------|
| `random_forest.pkl`     | 🌳 Modelo **Random Forest** treinado. |
| `svm.pkl`              | 🤖 Modelo **Support Vector Machine (SVM)** treinado (melhor desempenho). |
| `knn.pkl`              | 🔍 Modelo **K-Nearest Neighbors (KNN)** treinado. |
| `logistic_regression.pkl` | 📊 Modelo **Regressão Logística** treinado. |

---

## 📌 **Como Utilizar os Modelos Treinados**
Caso queira utilizar um dos modelos já treinados para fazer previsões, siga os passos abaixo:

### 1️⃣ **Carregar o Modelo em Python**
```python
import pickle

# Carregar o modelo treinado (Exemplo: Random Forest)
with open("models/random_forest.pkl", "rb") as file:
    modelo = pickle.load(file)

# Fazer previsões
previsoes = modelo.predict(X_test_scaled)
```
2️⃣ Salvar um Novo Modelo Treinado

Caso treine um novo modelo e queira armazená-lo:
```python
# Exemplo: Salvando um modelo SVM treinado
with open("models/novo_modelo.pkl", "wb") as file:
    pickle.dump(modelo_svm, file)
```

---

## 🏆 Melhor Modelo
Após testes comparativos, o modelo SVM (Support Vector Machine) apresentou o melhor desempenho, com 81.00% de acurácia. Para previsões futuras, recomenda-se utilizá-lo.
