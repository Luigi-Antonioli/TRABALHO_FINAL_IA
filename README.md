## Tema do projeto

O tema escolhido para o trabalho foi a aplicação de modelos de Inteligência Artificial na classificação de espécies de flores Iris.

O projeto utilizará o dataset Iris Flower Dataset, uma base de dados bastante conhecida na área de aprendizado de máquina. Esse dataset possui informações sobre medidas de flores Iris, como comprimento e largura da sépala e da pétala.

A partir dessas medidas, os modelos deverão classificar corretamente a espécie da flor.

---

## Problema do projeto

O problema trabalhado será de classificação.

O objetivo é prever a espécie de uma flor Iris com base em suas características numéricas. Para isso, serão utilizados dois modelos de Inteligência Artificial: KNN e Random Forest.

A pergunta principal do projeto é:

> Com base nas medidas da sépala e da pétala, é possível classificar corretamente a espécie de uma flor Iris?

---

## Dataset utilizado

O dataset escolhido foi o Iris Flower Dataset.

Essa base possui 150 registros, sendo 50 amostras de cada espécie de flor Iris. Cada registro representa uma flor e contém quatro medidas principais.

As espécies presentes no dataset são:

* Iris-setosa.
* Iris-versicolor.
* Iris-virginica.

O dataset foi escolhido por ser simples, organizado e adequado para problemas de classificação. Por possuir poucos atributos e dados numéricos, ele facilita o treinamento dos modelos KNN e Random Forest, além de permitir uma explicação mais clara durante a apresentação.

---

## Atributos do dataset

Os principais atributos do dataset são:

* SepalLengthCm: comprimento da sépala em centímetros.
* SepalWidthCm: largura da sépala em centímetros.
* PetalLengthCm: comprimento da pétala em centímetros.
* PetalWidthCm: largura da pétala em centímetros.

Esses atributos serão utilizados como dados de entrada para os modelos.

---

## Variável alvo

A variável alvo do projeto será a espécie da flor Iris.

No dataset, essa variável indica se a flor pertence à espécie Iris-setosa, Iris-versicolor ou Iris-virginica.

Os modelos serão treinados para aprender os padrões presentes nas medidas das flores e, com isso, prever corretamente a espécie de cada uma.

---

## Hipótese da equipe

A hipótese inicial da equipe é que o modelo Random Forest poderá apresentar melhor desempenho em comparação ao KNN.

Essa hipótese se baseia no fato de que o Random Forest utiliza várias árvores de decisão em conjunto, aplicando o conceito de ensemble. Isso pode tornar o modelo mais robusto e reduzir erros de classificação.

Por outro lado, o KNN também pode apresentar bons resultados, pois o dataset possui dados numéricos simples e bem organizados, o que favorece o cálculo de distância entre os registros.

---

## Preparação dos dados

A preparação dos dados será feita antes do treinamento dos modelos.

As principais etapas serão:

* Carregar o dataset.
* Verificar se existem valores ausentes.
* Separar os atributos de entrada e a variável alvo.
* Dividir os dados em treino e teste.
* Normalizar os dados para melhorar o desempenho do KNN.
* Treinar os modelos KNN e Random Forest.
* Avaliar os modelos com métricas e gráficos.

A divisão entre treino e teste permitirá avaliar se os modelos conseguem classificar corretamente dados que não foram usados durante o treinamento.
