# UFSC College - Automação de Dados com Xata

Este projeto tem como objetivo a manipulação e inserção de dados fictícios em um banco de dados na nuvem (Xata), utilizando Python para automação.

## Pré-requisitos

Certifique-se de ter o Python 3.10 ou superior instalado em sua máquina.

## Instalação

1. Clone este repositório:
   ```bash
   git clone [https://github.com/gabrielsm99/ufsc-college.git](https://github.com/gabrielsm99/ufsc-college.git)
   cd ufsc-college
Crie um ambiente virtual e ative-o:


# No Linux/macOS:
python3 -m venv venv
source venv/bin/activate

# No Windows:
python -m venv venv
venv\Scripts\activate
Instale as dependências:

# Configuração:

pip install -r requirements.txt

Crie um arquivo chamado .env na raiz do projeto.

Adicione sua chave de API da Xata neste arquivo:

XATA_API_KEY=sua_chave_aqui


# Execução:

Certifique-se de que o ambiente virtual está ativado.

Abra o Jupyter Notebook:

jupyter notebook XataDBPython.ipynb

Execute as células do notebook sequencialmente.

# Estrutura do Projeto
XataDBPython.ipynb: Notebook principal com a lógica de geração de dados (Faker) e integração com a Xata.

requirements.txt: Lista de pacotes necessários para o projeto.

.gitignore: Arquivo configurado para ignorar pastas de ambiente virtual (venv/, myenv/), arquivos de cache e o arquivo de segurança .env.
