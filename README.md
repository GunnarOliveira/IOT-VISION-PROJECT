# IOT-VISION-PROJECT

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![YOLO](https://img.shields.io/badge/YOLO-Object%20Detection-orange)

## Sobre o Projeto

Este repositório contém o trabalho de conclusão da cadeira extensionista de Internet das Coisas (IoT). O **IOT-VISION-PROJECT** tem como foco a aplicação de visão computacional aliada a dispositivos IoT para o monitoramento de fluxo de pessoas em tempo real.

Utilizando o framework **YOLO** (You Only Look Once), o sistema é capaz de identificar e rastrear a movimentação em ambientes variados, extraindo dados valiosos de ocupação e tráfego que podem ser integrados a plataformas ou painéis de IoT. Esse tipo de solução é excelente para contextos como cidades inteligentes, gestão de espaços, logística e segurança.

## Funcionalidades

- **Detecção em Tempo Real:** Processamento de vídeo contínuo para identificação de pessoas utilizando o modelo YOLO.
- **Monitoramento de Fluxo:** Contagem e mapeamento do fluxo de pessoas em diferentes cenários e ambientes.
- **Integração IoT:** Preparado para geração de telemetria baseada em dados de imagem, criando a ponte entre a visão computacional e as métricas de IoT.

## Arquitetura Básica

1. **Captura:** Uma fonte de vídeo ou câmera conectada coleta as imagens do ambiente.
2. **Processamento (Visão Computacional):** O ambiente processa as imagens frame a frame com o modelo YOLO para detecção precisa.
3. **Análise:** O sistema consolida as métricas do fluxo de pessoas detectadas na área monitorada.
4. **Aplicação:** Os dados podem ser enviados para análise em nuvem ou dashboards em tempo real.

## Pré-requisitos

Para rodar este projeto, você precisará dos seguintes componentes instalados:

- [Python 3.x](https://www.python.org/downloads/)
- [OpenCV](https://opencv.org/) para a manipulação e exibição de frames de vídeo.
- Framework YOLO (ex: Ultralytics) configurado e os pesos do modelo (ex: `yolov8n.pt`).

## Instalação e Execução

1. Clone o repositório em sua máquina:
```bash
git clone [https://github.com/GunnarOliveira/IOT-VISION-PROJECT.git](https://github.com/GunnarOliveira/IOT-VISION-PROJECT.git)
cd IOT-VISION-PROJECT
```

2. Crie um ambiente virtual (recomendado):
```bash
python -m venv venv
```

3. Ative o ambiente virtual:

**No Windows:**
```bash
venv\Scripts\activate
```

**No Linux/Mac:**
```bash
source venv/bin/activate
```

4. Instale as dependências exigidas pelo projeto:
```bash
pip install -r requirements.txt
```

5. Execute o script principal do projeto:
```bash
python main.py
```
*(Nota: Lembre-se de ajustar os comandos de acordo com os nomes exatos dos arquivos dentro do seu repositório, caso difiram do padrão).*

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Visão Computacional:** OpenCV, YOLO
- **Conceitos Abordados:** Internet of Things (IoT), Computer Vision, Real-Time Analytics

---
*Projeto desenvolvido para a disciplina de extensão em IoT.*
