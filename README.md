# Estatística Descritiva - Analise do Dataset Publico do E-Commerce feito pela Olist

_Este projeto consiste no trabalho final de Estatística I da trilha de Data Science do Programa Santander Coders 2024.1._ 

* **Módulo** Estatística I
* **Instrutor:** Prof. Damodara Barbosa
* **Grupo**: 
    - Filipe Sousa ([GitHub](https://github.com/filsousa) / [LinkedIn](https://www.linkedin.com/in/filipel-sousa/));
    - Gabriel Marques ([GitHub](https://github.com/marqsleal) / [LinkedIn](https://www.linkedin.com/in/marqsleal/)); 
    - Maria Paula Andrade ([GitHub](https://github.com/MariaPaulaAndrade) / [LinkedIn](https://www.linkedin.com/in/maria-paula-andrade/)); 
    - Matheus Chaves ([GitHub](https://github.com/Matheus-Chaves) / [LinkedIn](https://www.linkedin.com/in/matheus-chavess/));
    - Mileno Epifânio ([GitHub](https://github.com/milenoepifanio) / [LinkedIn](https://www.linkedin.com/in/milenoepifanio/));
    - Mille Amorin ([GitHub](https://github.com/4m0r1m) / [LinkedIn](https://www.linkedin.com/in/mille-amorim/));

## Instalação 

1. Clone o repositório:

```bash
git clone https://github.com/marqsleal/estatistica-um-projeto
```

## Dependências 

Para instalar as dependências do projeto, execute:

```bash
pip install -r requirements.txt
```

## Estrutura do projeto 

```bash
├── assets
│   └── data_schema.png
├── database
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
├── enunciado.pdf
├── notebook_projeto.ipynb
├── notebook_storytelling.ipynb
├── README.md
├── requirements.txt
```

## [Dataset Publico do E-Commerce no Brasil feito pela Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
Este é um conjunto de dados públicos de um ecommerce brasileiro com pedidos feitos na Olist Store. O conjunto de dados contém informações sobre 100 mil pedidos realizados entre 2016 e 2018 em diversos marketplaces no Brasil. Suas características permitem visualizar um pedido a partir de várias dimensões: desde o status do pedido, preço, pagamento e desempenho do frete até a localização do cliente, atributos do produto e, finalmente, as avaliações escritas pelos clientes. Também liberamos um conjunto de dados de geolocalização que relaciona os códigos postais brasileiros com coordenadas de latitude/longitude.

Estes são dados comerciais reais, foram anonimizados, e as referências às empresas e parceiros nos textos de avaliação foram substituídas pelos nomes das grandes casas de Game of Thrones.

## Contexto
Este conjunto de dados foi gentilmente fornecido pela Olist, a maior loja de departamentos nos marketplaces brasileiros. A Olist conecta pequenas empresas de todo o Brasil a diversos canais, sem complicações e com um único contrato. Esses comerciantes podem vender seus produtos através da Olist Store e enviá-los diretamente aos clientes utilizando os parceiros logísticos da Olist. 

Após um cliente comprar o produto na Olist Store, o vendedor é notificado para processar o pedido. Quando o cliente recebe o produto ou a data estimada de entrega é alcançada, o cliente recebe uma pesquisa de satisfação por e-mail, onde pode dar uma nota para a experiência de compra e escrever alguns comentários.

## Esquema de Dados
![Esquema de Dados](assets/data_schema.png)

## Abordagem Técnica
O arquivo `notebook_projeto.ipynb` faz uma análise tecnica dos datasets buscando responder:

- Quais são as variáveis (colunas) neste conjunto de dados e qual é o tipo de cada uma?  
- Há valores ausentes no conjunto de dados?
- Qual é a estatística descritiva básica para as variáveis numéricas, como média, mediana, mínimo, máximo e desvio padrão?  
- Como as variáveis numéricas estão distribuídas?  
- Existe alguma correlação entre as variáveis numéricas?  
- Como os dados categóricos estão distribuídos?

## Abordagem Exploratória
O arquivo `notebook_storytelling.ipynb` faz uma análise exploratória nos datasets buscando traçar alguma tendência do E-Commerce no Brasil, com foco nas formas de pagamento e nos pedidos.