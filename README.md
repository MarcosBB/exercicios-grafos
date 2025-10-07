# Tutorial de Instalação do Projeto

Este projeto utiliza o gerenciador de pacotes `uv` para gerenciar suas dependências. Siga os passos abaixo para configurar o ambiente e instalar as dependências necessárias:

## Pré-requisitos

Certifique-se de que você tenha os seguintes itens instalados em sua máquina:

- Python 3.13 ou superior
- `uv`, o gerenciador de pacotes. Caso não tenha o `uv` instalado, você pode instalá-lo com o seguinte comando:

```bash
pip install uv
```

## Passos para Instalação

1. Instale as dependências do projeto utilizando o `uv`:

```bash
uv sync
```

Este comando irá instalar todas as dependências listadas no arquivo `pyproject.toml`.

1. Abra o arquivo `trabalho1.ipynb` em um ambiente Jupyter Notebook ou JupyterLab e execute as células para ver os exemplos de busca em grafos.
OBS: Certifique-se de que o ambiente virtual Python criado pelo UV esteja ativado antes de executar o notebook, para garantir que todas as dependências estejam disponíveis.