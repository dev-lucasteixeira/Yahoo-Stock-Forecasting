# 📈 Yahoo Stock Forecasting

Este projeto tem como objetivo analisar e prever o comportamento do preço das ações da **Yahoo Finance** utilizando **técnicas de séries temporais** (SARIMAX, LSTM e decomposição estatística).

---

## 🚀 Objetivos do Projeto
- Carregar e explorar dados históricos de ações da Yahoo Finance.
- Analisar as variações de preços (`High`, `Low`, `Adj Close`, `Volume`).
- Criar métricas derivadas, como o **preço médio diário**.
- Realizar **decomposição da série temporal** em tendência, sazonalidade e ruído.
- Construir modelos de previsão (SARIMAX e LSTM).
- Avaliar a performance dos modelos e interpretar as previsões.
- Identificar **anomalias** e padrões atípicos nos dados.

---

## ❓ Perguntas de Pesquisa
1. Como evoluiu o preço das ações da Yahoo Finance ao longo do tempo?
2. Quais foram os maiores e menores valores registrados (High e Low)?
3. Qual a tendência de longo prazo do preço médio das ações?
4. Existe **sazonalidade** nos preços (mensal, trimestral ou anual)?
5. O modelo SARIMAX consegue prever adequadamente os valores futuros?
6. Qual é o intervalo de confiança das previsões geradas?
7. Como o **Volume de negociação** se relaciona com as variações de preço?
8. Existem **períodos anômalos** em que a ação foge do comportamento histórico?
9. Quais valores futuros podem ser esperados para o preço médio?

---

## 📊 Tecnologias Utilizadas
- **Python 3.10+**
- **Bibliotecas**:
  - `pandas`, `numpy` → manipulação de dados
  - `matplotlib`, `seaborn` → visualização
  - `statsmodels` → decomposição e SARIMAX
  - `scikit-learn` → escalonamento de dados
  - `tensorflow/keras` → redes neurais (LSTM)

---

## 🛠️ Estrutura do Projeto
├── Yahoo_Stock_Forecasting.ipynb # Notebook principal com análises e modelos
├── yahoo_stock.csv # Base de dados histórica (Yahoo Finance)
├── perguntas_projeto.txt # Lista de perguntas de pesquisa
├── README.md # Documentação do projeto


---

## 📈 Principais Análises
- **Exploração inicial dos dados** (estatísticas descritivas e visualizações).
- **Decomposição de série temporal** → tendência, sazonalidade e resíduos.
- **SARIMAX** → modelo estatístico com previsões para 12 períodos futuros.
- **LSTM (Long Short-Term Memory)** → rede neural para previsão sequencial.
- **Comparação entre valores reais e previstos**.
- **Detecção de anomalias** com base no erro de previsão.

---

## 🧩 Resultados Esperados
- Visualizações claras da evolução do preço das ações.
- Entendimento de padrões sazonais e tendências.
- Previsões para períodos futuros com intervalo de confiança.
- Identificação de pontos fora do padrão (anomalias).
- Insights úteis para tomada de decisão em investimentos e análises financeiras.

