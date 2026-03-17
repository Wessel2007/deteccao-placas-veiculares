# Projeto de Detecção de Placas Veiculares

Este repositório contém um projeto de visão computacional para **detecção e localização de placas veiculares em imagens**.

Nesta primeira etapa, o foco é **apenas encontrar a placa na imagem e marcar sua posição** (bounding box). O reconhecimento dos caracteres será feito em uma etapa futura.

## Tecnologias previstas

- Python
- OpenCV
- YOLO (Ultralytics)

## Estrutura inicial

```text
Projeto Integrador/
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── notebooks/
├── src/
│   ├── detection/
│   └── utils/
├── tests/
├── .gitignore
├── README.md
└── requirements.txt
```

- `data/`: imagens de entrada e derivados.
- `models/`: pesos e artefatos de modelos (por exemplo, YOLO).
- `notebooks/`: experimentos e análises exploratórias.
- `src/`: código-fonte principal do projeto.
- `tests/`: espaço para testes automatizados.

## Próximos passos

- Configurar o ambiente Python (venv ou conda).
- Instalar dependências básicas (OpenCV, Ultralytics/YOLO, etc.).
- Implementar um fluxo simples para carregar uma imagem e detectar a placa.

