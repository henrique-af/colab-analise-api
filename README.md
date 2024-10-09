## Análise de Dados do Mercado Livre

Este repositório simula o consumo da API do Mercado Livre (MELI) e a análise dos dados gerados. O objetivo é demonstrar a extração, carregamento e análise de dados de vendas e produtos utilizando Python, SQLite e visualizações em Tableau.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:

- **`HAF - TWBX - Dashboard de análise.twbx`**: Arquivo do Tableau com o dashboard contendo as visualizações das análises de vendas.
- **`HAF - Google Colab.ipynb`**: Jupyter Notebook do Google Colab que contém o código para extrair dados da API do MELI, carregar os dados em um banco de dados SQLite e realizar consultas SQL para análise.
- **`vendas.csv`**: Arquivo CSV que contém os dados das vendas extraídos da API do MELI.
- **`produtos.csv`**: Arquivo CSV que contém os dados dos produtos extraídos da API do MELI.

## Configuração

Para executar o código no Jupyter Notebook, você precisará de um **access_token** para acessar a API do Mercado Livre. Para obter um access token:

1. Crie uma conta no [Mercado Livre Developers](https://developers.mercadolivre.com.br).
2. Registre sua aplicação para obter as credenciais necessárias.
3. Siga as instruções na documentação para gerar seu access token.

Depois de obter seu access token, você pode substituí-lo diretamente no código do `HAF - Google Colab.ipynb`.

## Como Usar

1. **Faça o Upload do Notebook**: 
   - Baixe o arquivo `HAF - Google Colab.ipynb` e faça o upload em um ambiente Google Colab. Você pode fazer isso diretamente na interface do Google Colab, clicando em "Arquivo" > "Carregar Notebook".

2. **Substitua o Access Token**:
   - No notebook, localize a seção onde o access token é definido. Substitua o valor pelo seu access token pessoal obtido a partir da sua conta no [Mercado Livre Developers](https://developers.mercadolivre.com.br). Isso é necessário para autenticar as requisições à API do Mercado Livre.

3. **Execute o Código**:
   - Execute as células do notebook na ordem, garantindo que cada parte do código seja executada com sucesso. O código fará a extração de dados da API do Mercado Livre, carregará os dados em um banco de dados SQLite e realizará análises com consultas SQL.