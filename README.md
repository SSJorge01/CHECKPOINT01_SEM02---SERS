# CHECKPOINT01_SEM02---SERS  

## Integrantes  

- Guilherme Spranger dos Santos -> RM 564059  
- Gustavo Lemos Diogenes -> RM 565579  
- Pedro Paulo Barbosa Ross -> RM 563038  
- Samuel de Souza Jorge -> RM 558966  

---

## Objetivo  

Essa atividade tem como propósito explorar e analisar diferentes aspectos relacionados ao **consumo de energia elétrica residencial**, utilizando os seguintes datasets:  

- **Individual Household Electric Power Consumption**  
- **Appliances Energy Prediction Dataset**  

O trabalho está estruturado em quatro partes, abrangendo desde a manipulação e análise inicial de dados até a aplicação de técnicas de **Machine Learning** e ferramentas visuais como o **Orange Data Mining**.  

---

## Estrutura da Atividade  

### 🔹 Parte 1 – Exercícios iniciais com *Individual Household Electric Power Consumption*  
- Carregamento e inspeção inicial do dataset.  
- Conversão de datas e criação de novas variáveis (como dia da semana).  
- Análises estatísticas, médias de consumo diário/mensal e comparações entre dias úteis e finais de semana.  
- Criação de gráficos (linha, histograma, séries temporais).  
- Cálculo de correlações entre variáveis elétricas.  
- Normalização de dados com **Min-Max Scaling**.  
- Segmentação de consumo com **K-Means**.  
- Decomposição de séries temporais (tendência, sazonalidade e resíduos).  
- Modelo de **Regressão Linear** para prever consumo.  

### 🔹 Parte 2 – Exercícios adicionais com o mesmo dataset  
- Séries temporais por hora, identificando horários de maior consumo.  
- Análise de autocorrelação em diferentes lags (1h, 24h, 48h).  
- Aplicação de **PCA** (Redução de dimensionalidade).  
- Visualização de clusters em espaço PCA com **K-Means**.  
- Comparação entre Regressão Linear Simples e Regressão Polinomial.  

### 🔹 Parte 3 – Novo dataset *Appliances Energy Prediction*  
- Análises exploratórias do dataset (estatísticas descritivas, distribuições e séries temporais).  
- Estudo da correlação entre consumo de eletrodomésticos e variáveis ambientais (temperatura, umidade, etc).  
- Normalização dos dados.  
- Aplicação de **PCA** para identificar padrões de agrupamento.  
- Modelagem preditiva com:  
  - **Regressão Linear Múltipla**  
  - **Random Forest Regressor**  
- Agrupamento com **K-Means Clustering**.  
- Classificação binária (alto vs baixo consumo) utilizando **Regressão Logística** e **Random Forest Classifier**.  
- Avaliação dos modelos com matriz de confusão e métricas (accuracy, precision, recall, F1-score).  

### 🔹 Parte 4 – Experimentos no Orange Data Mining  
- Importação e visualização inicial do dataset no Orange.  
- Amostragem de dados (1%).  
- Distribuição do consumo com o widget Distribution.  
- Análise da relação entre variáveis com Scatter Plot.  
- Agrupamento utilizando **K-Means** com variáveis de *Sub_metering*.  
- Visualização gráfica e interpretação dos clusters.  

---

## Instruções da Entrega  

1. **Clonar este repositório** no GitHub para acessar os arquivos.  
2. Ler este arquivo **README.md** para entender os objetivos e metodologias aplicadas.  
3. Executar o notebook Python fornecido para verificar as resoluções das tarefas conforme os enunciados.  
4. (Opcional) Explorar os arquivos de dados no **Orange Data Mining** para validação visual.  

---

## Conclusão  

Esse checkpoint permitiu exercitar desde tarefas de **pré-processamento de dados** até a **aplicação prática de algoritmos de aprendizado de máquina**, desenvolvendo uma visão crítica sobre padrões de consumo energético.  

Além disso, o uso do **Orange Data Mining** possibilitou validar conceitos vistos em Python de maneira mais visual e intuitiva, complementando o notebook com análises gráficas e comparativas.
