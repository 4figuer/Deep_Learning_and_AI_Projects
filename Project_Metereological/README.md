# Projeto de Estudo em Deep Learning com TensorFlow/Keras



Vamos criar um modelo neural convoluvional que possa identificar condições metereológicas diferentes sobre fotos normais.

Os dados utilizados para o treino e teste estão disponibilizados neste [link](https://www.kaggle.com/datasets/rahul29g/weatherdataset) onde encontram-se divididas em treinamento e teste, como também, em 4 condições climáticas distintas. Realizei uma pequena adaptação dividindo os dados de treino para treinamento e validação, caso queira executar o notebook, essa divisão será necessária.

##### Basicamente vamos:

- Identificar a localização dos dados
- Um rápido pré-processamento
- Construção do modelo e avaliação
- Execução de predição.



##### Os arquivos contidos neste projeto são:

- Notebook do projeto
- Dicionário com as classes (varíável target) utilizadas no modelo



##### Versões das bibliotecas utilizadas:

matplotlib: 3.8.4 

json      : 2.0.9

tensorflow: 2.17.0

PIL       : 10.0.1

numpy     : 1.26.4

keras     : 3.4.1