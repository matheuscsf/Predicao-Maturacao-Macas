# 📂 Diretório `src/` - Código-Fonte do Projeto

Este diretório contém os **scripts Python** utilizados para processamento dos dados, treinamento e avaliação dos modelos no projeto **Predição do Nível de Maturação das Maçãs** 🍏.

---

## 📄 **Descrição dos Arquivos**
| Arquivo                | Descrição |
|------------------------|-----------|
| `preprocess.py`        | 🛠 **Pré-processamento dos dados**: Limpeza, tratamento de valores nulos e remoção de outliers. |
| `train_model.py`       | 🤖 **Treinamento dos modelos**: Implementação de Random Forest, SVM, KNN e Regressão Logística. |
| `evaluate.py`          | 📊 **Avaliação dos modelos**: Cálculo de métricas, matriz de confusão e análise de resultados. |
| `optimize_model.py`    | ⚙️ **Otimização dos hiperparâmetros** para melhorar o desempenho dos modelos. |

---

## 📌 **Como Utilizar os Scripts**
### 1️⃣ **Pré-processar os Dados**
Antes de treinar os modelos, execute:
```bash
python src/preprocess.py
```
Isso gerará um arquivo de saída com os dados limpos em ```data/apple_data_clean.csv```
### 2️⃣ Treinar um Modelo
Para treinar os modelos de machine learning:
```bash
python src/train_model.py
```
Os modelos treinados serão salvos na pasta ```models/```.
### 3️⃣ Avaliar o Modelo
Para visualizar métricas e gerar a matriz de confusão:
```bash
python src/evaluate.py
```
Os resultados serão armazenados na pasta ```reports/```.
### 4️⃣ Otimizar o Modelo
Caso queira buscar os melhores hiperparâmetros:
```bash
python src/optimize_model.py
```

---

## 🏗 Requisitos
Antes de rodar os scripts, instale as dependências:
```bash
pip install -r requirements.txt
```

---

## 📜 Observações
🔹 Cada script pode ser executado individualmente ou dentro de um pipeline.

🔹 Caso adicione novos scripts, atualize este README.md para manter a documentação organizada.

🔹 Para rodar os notebooks interativamente, utilize os arquivos em ```notebooks/```.
