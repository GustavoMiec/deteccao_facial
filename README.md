# Detecção Facial em Tempo Real com OpenCV

Este projeto implementa um sistema simples de **detecção facial em tempo
real** usando Python e a biblioteca **OpenCV**.\
A aplicação captura o vídeo da webcam, detecta rostos utilizando o
classificador Haar Cascade e exibe os resultados em uma janela
interativa.

## 🚀 Funcionalidades

-   Captura de vídeo em tempo real via webcam\
-   Conversão da imagem para escala de cinza\
-   Detecção de rostos usando `haarcascade_frontalface_default.xml`\
-   Desenho de retângulos ao redor das faces detectadas\
-   Encerramento da aplicação ao pressionar a tecla **Q**

## 📦 Requisitos

``` bash
pip install opencv-python
```

## ▶️ Como Executar

``` bash
python nome_do_arquivo.py
```

## 🧠 Como Funciona

1.  `cv2.VideoCapture(0)` abre a webcam.\
2.  O modelo Haar Cascade carregado identifica padrões faciais.\
3.  Para cada frame, os rostos detectados são marcados com retângulos.\
4.  A visualização é atualizada em tempo real.

## 📂 Estrutura de Arquivo

    📦 projeto-deteccao-facial
     ├── detecao_facial.py
     ├── README.md

## 📝 Observações

-   Utilize um ambiente bem iluminado para melhor precisão.
-   A performance pode variar dependendo da câmera e máquina.
