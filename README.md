# Processamento de Imagem: Binarização em Python


## Introdução:

Este projeto tem como objetivo implementar um algoritmo simples de binarização em imagens utilizando Python e a biblioteca OpenCV. O processo consiste em converter uma imagem colorida para tons de cinza e, em seguida, aplicar a binarização para transformá-la em uma imagem preto e branco.

## Metodologia: 
O algoritmo é implementado em Python e utiliza a biblioteca OpenCV para manipulação de imagens. A metodologia do projeto é dividida em três etapas principais:

Extração da Imagem e Conversão para Escala de Cinza:

A imagem colorida é carregada e convertida para escala de cinza usando a função cvtColor do OpenCV.
Binarização da Imagem:

A imagem em escala de cinza é binarizada utilizando a função threshold do OpenCV, aplicando um limiar predefinido.
Salvamento das Imagens Resultantes:

As imagens transformadas (escala de cinza e binarizada) são salvas no diretório atual com os nomes 'imagem_cinza.jpg' e 'imagem_binarizada.jpg'.

## Ferramentas: 

Python 3.x

OpenCV (instalado via pip install opencv-python)

## Conclusão:

Este projeto oferece uma introdução simples ao processamento de imagens, focalizando na conversão para tons de cinza e na binarização. A flexibilidade do limiar de binarização permite ajustes para atender às necessidades específicas. Além disso, este projeto fornece uma base para explorações futuras em técnicas mais avançadas de processamento de imagem
