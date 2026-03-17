<h1 align="center">GateVision</h1>

<p align="center">
Sistema Inteligente de Abertura de Portão por Reconhecimento de Placas
</p>

<p align="center">
<img src="https://img.shields.io/badge/status-em%20desenvolvimento-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/python-vision%20system-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/arduino-hardware-orange?style=for-the-badge"/>
</p>

---

# Índice

- [Descrição do Projeto](#descrição-do-projeto)
- [Status do Projeto](#status-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Arquitetura do Sistema](#arquitetura-do-sistema)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Acesso ao Projeto](#acesso-ao-projeto)
- [Executar o Projeto](#executar-o-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Desenvolvedores](#desenvolvedores)
- [Licença](#licença)

---

# Descrição do Projeto

O **GateVision** é um sistema de automação para controle de acesso de veículos utilizando **visão computacional** e **reconhecimento de placas**.

O sistema utiliza uma câmera para capturar imagens dos veículos que chegam ao portão. A partir dessas imagens, um algoritmo de processamento identifica a placa do veículo e verifica se ela está cadastrada em um banco de dados.

Caso a placa esteja autorizada, um comando é enviado para um **Arduino**, que aciona um **servo motor responsável pela abertura do portão**.

O projeto integra conceitos de:

- Inteligência Artificial
- Visão Computacional
- Banco de Dados
- Automação com Arduino
- Desenvolvimento Web

---

# Status do Projeto

**Projeto em desenvolvimento**

Período de desenvolvimento:

**Fevereiro de 2026 – Junho de 2026**

---

# Funcionalidades

- `Reconhecimento de placas`: identificação automática da placa do veículo
- `Captura de imagem`: utilização de webcam para captura em tempo real
- `Validação de acesso`: consulta da placa em banco de dados
- `Automação de portão`: acionamento automático via Arduino
- `Interface web`: cadastro de placas autorizadas
- `Protótipo físico`: simulação da abertura do portão com servo motor

---

# Arquitetura do Sistema

Fluxo de funcionamento do sistema:

1. A webcam captura a imagem do veículo.
2. O sistema em Python processa a imagem.
3. O algoritmo detecta a região da placa.
4. Um sistema de OCR extrai os caracteres.
5. O banco de dados é consultado.
6. Caso a placa esteja cadastrada:
   - um comando é enviado via comunicação serial.
7. O Arduino recebe o comando.
8. O servo motor é acionado simulando a abertura do portão.

---

# Tecnologias Utilizadas

## Linguagens

- Python
- C++
- HTML
- CSS

## Bibliotecas

- OpenCV
- YOLO
- OCR
- SQLite3

## Hardware

- Webcam
- Arduino
- Servo Motor
- Notebook

## Ferramentas

- Arduino IDE
- Python

---

# Acesso ao Projeto

Você pode acessar o repositório do projeto através do GitHub:



---

#  Executar o Projeto

### 1 Instalar dependências

pip install opencv-python <br>
pip install pytesseract <br>
pip install numpy <br>
pip install ultralytics <br>


### 2 Configurar Arduino

1. Conectar o Arduino via USB
2. Abrir o Arduino IDE
3. Carregar o arquivo:
<Strong>Arquivo em desenvolvimento </Strong>
4. Fazer upload do arquivo para o Arduino

### 3 Executar o sistema

O sistema iniciará a captura de vídeo e realizará a validação das placas automaticamente.

---

# Estrutura do Projeto
<h2> Estrutura do Projeto</h2>

<pre>
GateVision


├── database
│   └── placas.db
│
├── python
│   ├── captura_camera.py
│   ├── reconhecimento_placa.py
│   ├── validacao_bd.py
│   └── comunicacao_arduino.py
│
├── arduino
│   └── controle_servo.ino
│
├── web
│   ├── index.html
│   ├── cadastro_placa.html
│   └── style.css
│
└── README.md
</pre>


---

#  Desenvolvedores

| [<img src="https://avatars.githubusercontent.com/u/225480160?v=4" width=115><br><sub>Roger Oliveira</sub>](https://github.com/rcoliveirasb) |
| :---: |

| [<img src="https://avatars.githubusercontent.com/u/172124844?v=4" width=115><br><sub>Arthur Nicolas</sub>](https://github.com/arthur04112006) |
| :---: |

| [<img src="https://avatars.githubusercontent.com/u/199864121?v=4" width=115><br><sub>Kauan</sub>](https://github.com/kauanLDD) |
| :---: |

| [<img src="https://avatars.githubusercontent.com/u/217982820?v=4" width=115><br><sub>Rafael</sub>](https://github.com/rodyneyh) |
| :---: |

| [<img src="https://avatars.githubusercontent.com/u/217985092?v=4" width=115><br><sub>Lucas</sub>](https://github.com/lucas-labgit) |
| :---: |

| [<img src="https://avatars.githubusercontent.com/u/137013359?v=4" width=115><br><sub>Luiz Wessel</sub>](https://github.com/Wessel2007) |
| :---: |


Estudantes de Inteligência Artificial.

---

# Licença

Projeto desenvolvido para fins **acadêmicos e educacionais**. 

Todos os direitos reservados ©.
