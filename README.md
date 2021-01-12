![](https://img.shields.io/github/repo-size/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/issues/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/stars/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/watchers/michelpf/fiap-ml-visao-computacional)
![](https://img.shields.io/github/last-commit/michelpf/fiap-ml-visao-computacional)


# FIAP MBA em Machine Learning e Inteligência Artificial

Informações sobre o curso acesse [aqui](https://www.fiap.com.br/mba/mba-em-artificial-intelligence-e-machine-learning/).

![alt text](image/spacecup_inf_readme.png)

Este repositório reúne todos os notebooks, imagens, modelos e demais materiais necessário para a condução das aulas e revisão das mesmas.

Utilize as [discussões](https://github.com/michelpf/fiap-ml-visao-computacional/discussions) ou mesmo crie [issues](https://github.com/michelpf/fiap-ml-visao-computacional/issues) se precisar de alguma informação.

Como é um repositório público, aceito eventuais Pull Requests!
## Visão Computacional

Nas aulas podemos utilizar o Google Colab, os Notebooks do Kaggle ou a própria distribuição local Anaconda, com uso do Jupyter Notebook, que há vem instalado nesta distribuição. Você também pode usar até mesmo o VSCode, escolha o ambiente que mais adeque ao seu estilo!

Para instalar o Anaconda, acesse a sessão de [Downloads](https://www.anaconda.com/download) do Anaconda.

Tanto o [Google Colab](https://colab.research.google.com/) ou [Kaggle](https://www.kaggle.com/) podem ser acessados diretamente dos respectivos sites.

Para quem for usar Colab ou Kaggle, use o _badge_ de cada um. Eles possuem um link que já abre direto em cada plataforma, levando em consideração as particularidades de cada ambiente.

## Uso de câmeras

Em algumas aulas poderá ser utilizado o _streaming_ de vídeo de câmeras, que somente funciona em instalações locais. Tanto Google Colab quanto Kaggle ainda não suportam câmeras (exceto Colab que suporte imagens estáticas) por serem ambientes virtualizados.

Veja [esta](https://github.com/michelpf/fiap-ml-tec-proc-imagens/blob/master/util/videos-camera-mac-windows.ipynb) rápida introdução do uso de câmeras com o OpenCV em MacOS e Windows. Guarde esse pequeno guia para futuros usos, pois no MacOS as coisas funcionam um pouco diferente do Windows e costumam travar 😕 .

### Pacotes utilizados

* [OpenCV](https://opencv.org/) 3.4.3 (```conda install -c conda-forge opencv==3.4.3```)
* [Keras](https://keras.io/) 2.3.1 (```conda install keras==2.3.1```)
* [Matplotlib](https://matplotlib.org/) 3.1.3 (```conda install matplotlib==3.1.3```)
* [Seaborn](https://seaborn.pydata.org/) 0.0.10 (```conda install -c conda-forge seaborn==0.10.0```)
* [Imutils](https://pypi.org/project/imutils/) 0.5.3 (```conda install -c conda-forge imutils==0.5.3```)
* [Scikit Learn](https://scikit-learn.org/stable/) 0.22.1 (```conda install scikit-learn==0.22.1```)
* [Scipy](https://www.scipy.org/) 1.4.1 (```conda install scipy==1.4.1```)
* [Pytorch](https://pytorch.org/) 1.4.0 (```conda install -c pytorch pytorch==1.4.0```)

_No Google Colab todas as dependências já estão instaladas. Já no Kaggle está indicando como instalar as dependências, sem dificuldades._ 😄

Aulas no programa atualizado da disciplina:

## 📝  1. Introdução a visão computacional

📙 [Notebook manipulação de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/introducao-visao-computacional.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/introducao-visao-computacional-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/introducao-visao-computacional-kaggle.ipynb)


### Introdução sobre visão computacional e processamento de imagens

1. Introdução do OpenCV
2. Instalação
3. Formação de imagens
4. Representação de cores
5. Histograma
6. Construção de imagens

### Desafios

📘 [Notebook desafio 1: identificação de cores](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1-kaggle.ipynb)

📘 [Notebook desafio 1 (solução): identificação de cores](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-1-introducao-visao-computacional/desafio-1/desafio-1-solucao-kaggleipynb)


## 📝  2. Manipulação de imagens

📙 [Notebook manipulação e transformação de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/transformacao-imagens.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/transformacao-imagens-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/transformacao-imagens-kaggle.ipynb)

### Manipulação e transformação de imagens

1. Transformações
2. Translações
3. Rotações
4. Resizing
5. Cropping
6. Masking
7. Suavização

### Desafios

📘 [Notebook desafio 1: transformação de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1-kaggle.ipynb)

📘 [Notebook desafio 1 (solução): transformação de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-1/desafio-1-solucao-kaggle.ipynb)

📘 [Notebook desafio 2: máscaras em imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2.ipynb)
  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2-kaggle.ipynb)

📘 [Notebook desafio 2 (solução): máscaras em imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-2/desafio-2-solucao-kaggle.ipynb)


📘 [Notebook desafio 3: pipeline machine learning](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3-kaggle.ipynb)

📘 [Notebook desafio 3 (solução): pipeline machine learning](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-2-transformacao/desafio-3/desafio-3-solucao-kaggle.ipynb)


## 3. Segmentação de imagens

📙 [Notebook manipulação e transformação de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/segmentacao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/segmentacao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/segmentacao-kaggle.ipynb)

### 3.1 Técnicas para segmentar e extrair artefatos e regiões de interesse de imagens ✂️

1. Aguçamento
2. Binarização
3. Dilatação e Erosão
4. Deteção de Borda
4. Contornos
5. Identificação de Formas

### 3.2 Desafios

📘 [Notebook desafio 1: contornos em imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1-kaggle.ipynb)

📘 [Notebook desafio 1 (solução): contornos em imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-1/desafio-1-solucao-kaggle.ipynb)

📘 [Notebook desafio 2: limpeza de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2-kaggle.ipynb)

📘 [Notebook desafio 2 (solução): limpeza de imagens](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2-solucao.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-3-segmentacao/desafio-2/desafio-2-solucao-kaggle.ipynb)


## 4. Classificação de objetos e análise facial

📙 [Notebook classificação de objetos e análise facial](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/classificacao-objetos.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/classificacao-objetos-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/classificacao-objetos-kaggle.ipynb)

### 4.1 Classificadores de objetos e análise facial 👦

1. Classificadores em cascata de Haar
2. Classificador facial DLib
3. Análise Facial
4. Marcos Faciais

### 4.2 Desafios

Notebook desafio 1: transformação de imagens 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-1/desafio-1-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-1/desafio-1-kaggle.ipynb)

Notebook desafio 1 (solução): transformação de imagens 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-1/desafio-1-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-1/desafio-1-solucao-kaggle.ipynb)

Notebook desafio 2: transformação de imagens 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-2/desafio-2-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-2/desafio-2-kaggle.ipynb)

Notebook desafio 2 (solução): transformação de imagens 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-2/desafio-2-solucao-colab.ipynb) [![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-4-classificacao-objetos-analise-facial/desafio-2/desafio-2-solucao-kaggle.ipynb)


## 5. Machine learning, deep learning e transfer learning aplicado a imagens

📙 [Notebook reconhecimento facial](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/machine-learning.ipynb)

📙 [Notebook OCR & captcha](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/machine-learning.ipynb)

📙 [Notebook transfer learning](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/transfer-learning-fruits.ipynb)

📙 [Notebook Reconhecimento de objetos em tempo real](https://github.com/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/yolo-realtime.ipynb)

📕 Notebook reconhecimento facial, deep learning para OCR, transfer learning e detecção de objetos [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/machine-learning-colab.ipynb)

### 5.1 Deep learning e transfer learning aplicado a visão computacional 👾

1. Reconhecimento de faces
2. Reconhecimento de imagens utilizando redes neurais profundas
3. Técnicas de transferência de aprendizado (*transfer learning*)
4. Reconhecimento de objetos em tempo real com YOLO *You Only See Once*.

### 5.2 Desafios

🚩 Notebook desafio 1: reconhecimento de faces [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/desafio-1/desafio-1-colab.ipynb)

✅ Notebook desafio 1 (solução): reconhecimento de faces [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/desafio-1/desafio-1-solucao-colab.ipynb)

🚩 Notebook desafio 2: detecção de objetos [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/desafio-2/desafio-2-colab.ipynb)

✅ Notebook desafio 2 (solução): detecção de objetos [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional/blob/master/aula-5-machine-learning-aplicado/desafio-2/desafio-2-solucao-colab.ipynb)

## Capstones

Projetos de conclusão da disciplina aplicados.

1. [Análise de Imagens Médicas](https://github.com/michelpf/fiap-ml-visao-computacional-analise-imagens-medicas)
2. [Auditoria de Vídeo](https://github.com/michelpf/fiap-ml-visao-computacional-auditoria-video)
