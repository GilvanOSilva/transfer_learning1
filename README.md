Transfer Learning

Sobre o programa
----------------

Transfer learning é um programa de reconhecimento de imagens utilizando o procedimento de tranferência de aprendizado, utilizando uma rede neural previamente treinada para um novo treinamento de reconhecimento de imagens.

Características
---------------

O programa efetua em sua inicialização com a obtenção de uma rede previamente treinada do image-net, nesse exexplo é utilizado a rede neural VGG16.
Seguindo o demais processos a rede tem suas camadas congeladas exceto pela última, que será o ponto onde a rede pode treinar utilizando a base pré treinada.
Foi utilizado o dataset do Kaggle com duas classes de animais para classificação de reconhecimento.

Instalação
----------

Para utilização do programa é necessária a instalação do interpretador python3 para sua execução, no site: https://www.python.org/downloads/.
Dataset do Kaggle para treino do programa, que se encontra no site: https://www.microsoft.com/en-us/download/details.aspx?id=54765.

Notas Técnicas
--------------
Uso do matplotlib para exibição dos graficos.
Uso do keras para aplicação da rede neural.
Uso do numpy para processamento de matrizes.
Uso do ambiente Colab para efetuar o treinamento da rede neural e testes.

Modificação
-----------

O propósito deste programa é demonstrar a utilização do transfer learning, a transferência de aprendizado de uma rede VGG16 previamente treinada para uso em novos models de aprendizado em reconhecimento de imagens, sua modificação está liberada dentro das regras de licença GNU. 
