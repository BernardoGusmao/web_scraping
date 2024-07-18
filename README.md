# Previsão de Preços de Aluguel de Casas.

Esse projeto tem como objetivo fazer previsões dos preços de aluguéis de casas em Uberlândia MG . Os dados dessas casas foram coletados através de web scraping, e foram utilizados para preparação desse modelo de machine learning.

## Estrutura do projeto

- `Web_scrapper.ipynb`: Notebook que realiza a extração de dados de anúncios de casas para alugar e salva os dados em um arquivo CSV.
- `ML.Houses.ipynb`: Notebook que faz todo o processo de limpeza e preparação desses dados, além de treinar e avaliar o modelo de regressão linear para prever os preços desses aluguéis.
- `rent_house_price_da.csv`: Arquivo CSV gerado pela extração de dados, com as informações sobre os imóveis coletados.
- `requirements.txt`: Arquivo que lista todas as dependência para rodar o projeto.

## Instalação

Siga os passos abaixo para configurar o ambiente e executar o projeto.

### 1. Clone o Repositório 

Clone o repositório para sua máquina local:

```bash
git clone https://github.com/BernardoGusmao/web_scraping.git
```
### 2. Configurar o ambiente

Navegue até o seu repositório:

```bash
cd web_scraping
```
Instale as dependências necessárias que estão no 'requirements.txt':

```bash
pip install -r requirements.txt
```
## Execute o projeto

Nesse projeto, a saída do 'Web_scrapper.ipynb' que é o arquivo CSV 'rent_house_price_data.csv' já está disponível. Você pode escolher entre usar esse arquivo já criado ou gerar um novo. Para gerar um novo, basta apagar o arquivo existente, abrir a sua IDE de escolha (Eu usei o Jupyter Notebook) e executar todas as células de 'Web_scrapper.ipynb' e ele vai gerar um novo arquivo CSV. Então, execute o arquivo 'ML-Houses.ipynb' na sua IDE para fazer as previsões dos preços dos aluguéis.

