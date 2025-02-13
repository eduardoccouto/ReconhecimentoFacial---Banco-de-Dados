# Reconhecimento Facial com Python e OpenCV

## Descrição do Projeto
Este projeto tem como objetivo o desenvolvimento de um sistema de reconhecimento facial utilizando a biblioteca OpenCV em Python. O projeto faz parte da disciplina de Projeto de IoT e busca aplicar técnicas de visão computacional para identificação de rostos em imagens ou vídeos.

## Tecnologias Utilizadas
- Python 3.x
- OpenCV
- NumPy

## Requisitos
Antes de executar o projeto, certifique-se de ter instalado os seguintes pacotes:

```bash
pip install -r requirements.txt
```

## Como Executar
1. Clone este repositório:

```bash
git clone https://github.com/eduardoccouto/ReconhecimentoFacial---Banco-de-Dados.git
cd ReconhecimentoFacial---Banco-de-Dados
```

2. Execute o script principal:

```bash
python reconhecimento_facial.py
```

## Funcionamento
O sistema utiliza a biblioteca OpenCV para:
1. Capturar imagens de uma webcam ou carregar imagens estáticas.
2. Detectar rostos usando classificadores Haar Cascade ou modelos baseados em Deep Learning.
3. Reconhecer rostos previamente cadastrados (caso haja um banco de imagens).

## Possíveis Melhorias
- Implementação de modelos mais avançados de deep learning para melhorar a precisão.
- Integração com sistemas IoT para autenticação baseada em reconhecimento facial.

## Autora
Projeto desenvolvido por Eduardo Couto e Thais Bastos para a disciplina de Projeto de IoT.

