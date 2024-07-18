# Previsão de Preços de Aluguel de Casas.

Esse projeto tem como objetivo fazer previsões dos preços de aluguéis de casas em Uberlândia MG . Os dados dessas casas foram coletados através de web scraping, e foram utilizados para preparação desse modelo de machine learning.

## Estrutura do projeto

- `Web_scrapper.ipynb`: Notebook que realiza a extração de dados de anúncios de casas para alugar e salva os dados em um arquivo CSV.
- `ML.Houses.ipynb`: Notebook que faz todo o processo de limpeza e preparação desses dados, além de treinar e avaliar o modelo de regressão linear para prever os preços desses aluguéis.
- `rent_house_price_da.csv`: Arquivo CSV gerado pela extração de dados, com as informações sobre os imóveis coletados.
