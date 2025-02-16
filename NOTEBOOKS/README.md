# 📂 Diretório `notebooks/` - Notebooks do Projeto

Este diretório contém os **Jupyter Notebooks** utilizados para análise e modelagem do projeto **Predição do Nível de Maturação das Maçãs** 🍏.

## 📄 **Descrição dos Arquivos**
| Notebook                     | Descrição |
|------------------------------|-----------|
| `01-EDA.ipynb`               | 🔍 **Análise Exploratória dos Dados (EDA)**: Visualizações, estatísticas básicas e correlação entre variáveis. |
| `02-Modelagem.ipynb`         | 🤖 **Treinamento dos Modelos**: Implementação dos algoritmos de machine learning (Random Forest, SVM, KNN e Regressão Logística). |
| `03-Avaliacao.ipynb`         | 📊 **Avaliação do Modelo**: Métricas de desempenho, matriz de confusão e análise dos resultados. |
| `04-Otimizacao-Modelo.ipynb` | ⚙️ **Otimização do Modelo**: Ajuste de hiperparâmetros e comparação entre diferentes algoritmos. |

---

## 📌 **Como Utilizar os Notebooks**
1️⃣ **Certifique-se de ter as dependências instaladas:**  
```bash
pip install -r requirements.txt
```
2️⃣ Execute os notebooks na seguinte ordem para garantir o fluxo correto do projeto:
```bash
📌 01-EDA.ipynb ➝ 02-Modelagem.ipynb ➝ 03-Avaliacao.ipynb ➝ 04-Otimizacao-Modelo.ipynb
```
3️⃣ Caso queira rodar localmente, inicie o Jupyter Notebook com:
```bash
jupyter notebook
```
ou, se estiver utilizando Jupyter Lab:
```bash
jupyter lab
```

---

## 📜 Observações
🔹 Os notebooks estão organizados em etapas lógicas do projeto, garantindo um fluxo claro de entendimento.

🔹 Caso modifique os notebooks ou adicione novos experimentos, atualize este README.md para manter a organização do repositório.

🔹 Para melhor performance, utilize os dados tratados (data/apple_data_clean.csv) ao rodar as análises.
