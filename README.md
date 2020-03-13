![](https://img.shields.io/github/repo-size/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/issues/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/stars/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/watchers/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/last-commit/michelpf/fiap-ml-visao-computacional)


# FIAP MBA em Machine Learning e Inteligência Artificial

![alt text](https://github.com/michelpf/fiap-ml-tec-proc-imagens/blob/master/aula-6-tracking-machine-learning/imagens/spacecup_inf_readme.png)

## Tecnologia e Processamento de Imagens

Nas aulas utilizaremos a distribuição Ananconda, com uso intensivo do Jupyter Notebook, que há vem instalado nesta distribuição.

Para instalar, acesse a sessão de [Downloads](https://www.anaconda.com/download) do Anaconda.

Pacotes que necessitarão de instalações adicionais serão indicadas em cada notebook das aulas.

> Atenção, veja [esta](https://github.com/michelpf/fiap-ml-tec-proc-imagens/blob/master/videos-camera-mac-windows.ipynb) rápida introdução do uso do OpenCV em MacOS e Windows. Guarde esse pequeno guia para futuros usos, pois no MacOS as coisas funcionam um pouco diferente do Windows e costumam travar (ex. ```cv2.destroyAllWindows()```)

### Pacotes utilizados

* [OpenCV](https://opencv.org/) 3.4.3 (```conda install -c conda-forge opencv==3.4.3```)
* [Keras](https://keras.io/) 2.3.1 (```conda install keras==2.3.1```)
* [Matplotlib](https://matplotlib.org/) 3.1.3 (```conda install matplotlib==3.1.3```)
* [Seaborn](https://seaborn.pydata.org/) 0.0.10 (```conda install -c conda-forge seaborn==0.10.0```)
* [Imutils](https://pypi.org/project/imutils/) 0.5.3 (```conda install -c conda-forge imutils==0.5.3```)
* [Scikit Learn](https://scikit-learn.org/stable/) 0.22.1 (```conda install scikit-learn==0.22.1```)
* [Scipy](https://www.scipy.org/) 1.4.1 (```conda install scipy==1.4.1```)
* [Pytorch](https://pytorch.org/) 1.4.0 (```conda install -c pytorch pytorch==1.4.0```)

### Aula 1 - Introdução

[Notebook](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/introducao-visao-computacional.ipynb)

Introdução sobre visão computacional e principais ferramentas para compreensão da formação de imagens.

1. Introdução do OpenCV
2. Instalação
3. Formação de imagens
4. Representação de cores
5. Histograma
6. Construção de imagens

### Aula 2 - Manipulação de imagens

[Notebook](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/transformacao-imagens.ipynb)

Principais operações para manipulação e transformação de imagens.

1. Transformações
2. Translações
3. Rotações
4. Resizing
5. Cropping
6. Masking
7. Suavização

### Aula 3 - Segmentação de imagens

[Notebook](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/segmentacao.ipynb)

Técnicas para segmentar e extrair artefatos e regiões de interesse de imagens.
Metodologias e técnicas para lidar com detectores de objetos e identificação de rostos.

1. Aguçamento
2. Binarização
3. Dilatação e Erosão
4. Deteção de Borda
4. Contornos
5. Identificação de Formas

### Aula 4 - Classificação de objetos

[Notebook](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/classificacao-objetos.ipynb)

1. Classificadores em cascata de Haar
2. Classificador facial DLib
3. Análise Facial
4. Marcos Faciais

### Aula 5 - Machine learning e deep learning

[Notebook](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-tracking-machine-learning/machine-learning.ipynb)

1. Reconhecimento de faces
2. Reconhecimento de imagens utilizando redes neurais profundas
3. Técnicas de transferência de aprendizado (*transfer learning*)
4. Reconhecimento de objetos em tempo real com YOLO *You Only See Once*.

## Dúvidas?

Abra um **Issue** que eu ou a comunidade de estudantes responderá em breve :bowtie:. 
