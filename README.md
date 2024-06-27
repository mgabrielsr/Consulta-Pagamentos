# Automação de Consultas de Pagamentos

Este projeto consiste em um script em Python que utiliza as bibliotecas openpyxl e selenium para automatizar a consulta de status de pagamentos no site do Consultor de Pagamentos. 

## Funcionalidades

- Inserção automática de CPFs dos clientes a partir de uma planilha de dados.
- Consulta de status de pagamentos.
- Atualização das informações de pagamento na planilha de fechamento.

## Requisitos

- Python 3.x
- Bibliotecas openpyxl e selenium

## Instalação

1. Clone este repositório:

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Instale as dependências:

    ```bash
    pip install openpyxl selenium
    ```

## Uso

1. Prepare a planilha de dados com os CPFs dos clientes.
2. Execute o script de automação:

    ```bash
    python automacao_consultas.py
    ```
Este projeto é utilizado em conjunto do [Consultar CPF](https://github.com/mgabrielsr/Consultar-CPF) para uma solução completa de verificação e monitoramento de pagamentos.

O script abrirá o navegador, realizará as consultas de pagamento e atualizará a planilha de fechamento automaticamente.
