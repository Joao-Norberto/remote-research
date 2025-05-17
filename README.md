# remote-research

**remote-research** é uma aplicação Python projetada para facilitar pesquisas remotas por meio de um servidor dedicado. O projeto utiliza contêineres Docker para simplificar a implantação e gerenciamento do ambiente.

## 🚀 Funcionalidades

- Servidor de pesquisa remoto implementado em `research_server.py`
- Script principal de execução em `main.py`
- Ambiente de desenvolvimento e produção configurado com Docker
- Gerenciamento de dependências com `requirements.txt` e `pyproject.toml`

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Docker
- Bibliotecas adicionais listadas em `requirements.txt`

## 📦 Instalação

### Pré-requisitos

- [Python 3.8+](https://www.python.org/downloads/)
- [Docker](https://www.docker.com/get-started)

### Clonando o Repositório

```bash
git clone https://github.com/Joao-Norberto/remote-research.git
cd remote-research

docker build -t remote-research .
docker run -p 8000:8000 remote-research

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py

remote-research/
├── .gitignore
├── Dockerfile
├── main.py
├── pyproject.toml
├── README.md
├── requirements.txt
├── research_server.py
├── runtime.txt
└── uv.lock

```

## 🤝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
