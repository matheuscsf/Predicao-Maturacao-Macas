# 📂 Diretório `data/` - Dados do Projeto

Este diretório contém os arquivos de **dados** utilizados no projeto **Predição do Nível de Maturação das Maçãs** 🍏.

## 📄 **Descrição dos Arquivos**
| Arquivo                | Descrição |
|------------------------|-----------|
| `apple_data.csv`       | 📥 Base de dados original obtida do [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality) |
| `apple_data_clean.csv` | 🛠 Base de dados tratada, sem valores nulos e com outliers removidos |
| `apple_data_train.csv` | 📊 Conjunto de dados de **treinamento** após pré-processamento |
| `apple_data_test.csv`  | 📈 Conjunto de dados de **teste** após pré-processamento |

---

## 📌 **Sobre a Base de Dados**
A base de dados contém informações sobre diferentes características físicas e sensoriais de maçãs, incluindo:

- **Tamanho** 🍏
- **Peso** ⚖️
- **Doçura** 🍯
- **Crocância** 🍎
- **Suculência** 💧
- **Acidez** 🍋
- **Maturação** ⏳ (Variável-alvo do projeto)
- **Qualidade** ✅ (Classificação categórica da maçã)

Essas variáveis são utilizadas para construir um **modelo preditivo** capaz de estimar a **maturação das maçãs** com base em suas características.

---

## 📥 **Como Utilizar os Dados**
Caso precise trabalhar com os dados, utilize o script de pré-processamento localizado em:

📂 `src/preprocess.py`  
💡 Esse script realiza limpeza, normalização e separação dos conjuntos de treino e teste.

---

## 📜 **Observações**
- **Caso os arquivos de dados originais não estejam presentes, faça o download diretamente do Kaggle.**
- **Sempre use os dados tratados (`apple_data_clean.csv`) para garantir análises mais confiáveis.**
- **Se modificar os dados, atualize este README.md para manter a documentação organizada.**

📌 **Dúvidas?** Entre em contato ou abra uma issue no repositório principal! 🚀

