# Personal Finance Tracker

Personal Finance Tracker é uma aplicação em Python para gerenciar suas finanças pessoais. Ele permite que você registre transações, visualize transações dentro de um intervalo de datas e veja um resumo das suas receitas e despesas. Além disso, você pode visualizar gráficos de suas receitas e despesas ao longo do tempo.

## Funcionalidades

- Adicionar uma nova transação (data, valor, categoria e descrição)
- Visualizar transações e um resumo dentro de um intervalo de datas
- Plotar receitas e despesas ao longo do tempo

## Estrutura do Projeto

- `main.py`: Arquivo principal que contém a lógica principal da aplicação.
- `data_entry.py`: Arquivo auxiliar que contém funções para obter dados do usuário.
- `finace_data.csv`: Arquivo CSV onde os dados das transações são armazenados.
- `requirements.txt`: Lista de bibliotecas Python necessárias para o projeto.

## Como Usar

### Pré-requisitos

- Python 3.6 ou superior
- pip (gerenciador de pacotes do Python)

### Instalação

1. Clone este repositório:
    ```sh
    git clone https://github.com/seu-usuario/personal-finance-tracker.git
    cd personal-finance-tracker
    ```

2. Crie e ative um ambiente virtual:
    ```sh
    python -m venv pft_env
    source pft_env/Scripts/activate
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

### Uso

1. Execute o script principal:
    ```sh
    python main.py
    ```

2. Siga as instruções no terminal para adicionar transações, visualizar transações e plotar gráficos.

## Estrutura do Código

### `main.py`

Este arquivo contém a classe `CSV` que gerencia a leitura e escrita no arquivo CSV, e funções para adicionar transações, visualizar transações e plotar gráficos. A função `main` gerencia o fluxo principal da aplicação.

### `data_entry.py`

Este arquivo contém funções auxiliares para obter entradas do usuário, incluindo data, valor, categoria e descrição da transação.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
