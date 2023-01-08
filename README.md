# PySpark-Project---Imoveis-em-SP
(PT-BR) Projeto em PySpark para recomendacao de imoveis baseados em imoveis similares. Tudo foi desenvolvido com o Google Colab.
Os dados inicias estao em JSON para o primeiro notebook e os seguintes notebooks utilizam o produto do notebook anterior.

(EN) The project and the related analysis are in Portuguese. All was developed in Google Colab. 
After the input on the first notebook from the JSON file the next ones take as input the product of the previous notebook.

Essa e uma analise de dados de imoveis de Sao Paulo.

O primeiro notebook visa transformar os dados iniciais para analise futura com Machine Learning. 
Algumas variaveis sao removidas, outras convertidas de categoricas para numericas ou Booleanas.

O segundo notebook e uma aplicacao de tecnicas de analise descritiva e de Machine Learning para entender
melhor os padroes dos dados

O terceiro notebook e a aplicaco de pca para reducao de dimensionalidade, kmeans para formacao de clusters
e calculo de distancia entre elementos do mesmo cluster para recomendacao, baseada na eleicao de um imovel.
Assim ao escolher um imovel os imoveis semelhantes sao apresentados.


