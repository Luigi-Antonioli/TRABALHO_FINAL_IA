## Dataset utilizado

O dataset escolhido para o projeto foi o **Iris Flower Dataset**, uma base clássica utilizada em estudos de Inteligência Artificial e Aprendizado de Máquina.

Neste projeto, o dataset não será baixado manualmente. Ele será carregado diretamente no código por meio da biblioteca `scikit-learn`, utilizando a função `load_iris()`.

O dataset possui 150 registros, divididos em três espécies de flores Iris:

* Iris-setosa.
* Iris-versicolor.
* Iris-virginica.

Cada registro possui quatro atributos numéricos:

* Comprimento da sépala.
* Largura da sépala.
* Comprimento da pétala.
* Largura da pétala.

A variável alvo do projeto é a espécie da flor, representada pela coluna `Species`.

O objetivo é treinar os modelos KNN e Random Forest para classificar corretamente a espécie da flor com base nas medidas da sépala e da pétala.
