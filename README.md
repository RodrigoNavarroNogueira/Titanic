# Titanic
Repositório criado para a ***[competição do Kaggle sobre o desastre do Titanic](https://www.kaggle.com/c/titanic)***

O histórico dos resultados é mostrado abaixo e pode ser obtido no Kaggle:

- O ***score público retornado pelo Kaggle foi: 78.468***

<img src="https://github.com/RodrigoNavarroNogueira/Titanic/blob/master/img/graph_chart_with_moving_up_arrow_stock_market_financial_investment_diagram_on_blue_background.jpg" />

## [Parte 1: EDA e Pré Processamento](https://github.com/RodrigoNavarroNogueira/Titanic/blob/master/titanic_1.ipynb)

- Este projeto foi separado em 2 partes, espero mostrar como um cientista de dados agiria para resolver um problema. ***O objetivo é prever corretamente se alguém sobreviveu ao naufrágio do Titanic.***
- Nessa primeira parte iremos fazer toda a ***EDA e Data Cleaning juntos***, visualizando e tratando os dados. Depois ***criamos features*** e fazemos todo o ***pré-processamento***, por fim salvando todo o progresso para iniciar o treinamento de modelos na parte 2

  - Importação das bibliotecas necessárias
  - *EDA (número de amostras, características disponíveis, tipos de dados, distribuição das características e resumo estatístico)*
  - *Exploração inicial dos dados*
  - *Visualização dos Dados*
  - *Valores Inconsistentes*
  - *Valores Faltantes*
  - *Escalonamento dos Atributos*
  - *Transformação de Atributos Categóricos*

## [Etapa 2: Criando os Modelos](https://github.com/RodrigoNavarroNogueira/Titanic/blob/master/titanic_2.ipynb)
- Na segunda etapa o foco principal foi criar, treinar e testar os modelos
- Criamos os primeiros modelos sem parametros, depois fazer o tuning melhorando os desempenhos. Por fim executando uma combinação dos modelos e visualização dos resultados
- Nesse projeto foi usado **7 algoritmos diferentes: Árvore de Classificação, Random Forest, KNN, SVM, Regressão Logística, Redes Neurias e Gradient Boosting**
  - *Criação dos modelos*
  - *Matriz de Confusão*
  - *Precision e Recall*
  - *Validação Cruzada*
  - *Tuning dos Parametros*
  - *Comparando os Resultados*
  - *Teste de Normalidade com Shapiro*
  - *Teste de Hipotese com ANOVA e Tukey*
  - *Salvar e Carregar um Classificador já treinado*
  - *Combinação dos Modelos com Voting Classifier*
