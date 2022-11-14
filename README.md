# House Rocket Insights Project
![alt text](https://github.com/jlcunha/House-Rocket/blob/main/imagens/KingCounty.jpg?raw=true?raw=true)

Este projeto foi feito para simular um case real de uma imobiliária, utilizando a ciência de dados para resolver algumas questões de negócio da empresa, trazendo grandes resultados financeiros para a mesma.

## 1. Sobre a House Rocket
### 1.1 Problema de Negócio
A House Rocket é uma empresa (fictícia) do setor imobiliário, que tem como modelo de negocio a compra e venda de imoveis localizados em King County - USA, sendo o resultado dessa operação o lucro da empresa.

O CEO da House Rocket enfrenta alguns problemas, eles possuem uma grande variedade de imóveis disponíveis para a compra e eles necessitam: 
- Uma análise apurada de todos os imóveis.
- Precisam aproveitar todos os dados a disposição, com novos insights.
- Querem saber quais casas devem comprar e por qual valor comprar, para revendê-las e por qual valor.

### 1.2 Data Overview
| Attribute | Description |
| :----- | :----- |
| id | Código de identificação de cada imóvel |
| date | Data de inserção do imóvel na base |
| price | Preço pedido pelo imóvel |
| bedrooms | Número de quartos |
| bathrooms | Número de banheiros |
| sqft_living | Área da sala de estar |
| sqft_lot | Área do terreno |
| floors | Número de andares |
| waterfront | Se o imóvel possui vista para água |
| view | Uma escala de 0 a 4 indicando a qualidade da vista do imóvel |
| condition | Uma escala de 0 a 5 indicando as condições do imóvel |
| grade | Uma escala de 1 a 13 indicando a qualidade da construção e padrão arquitetônico |
| sqft_above | Área construída acima do solo |
| sqft_basement | Área construída do porão |
| yr_built | Ano de construção do imóvel |
| yr_renovated | Ano da última reforma |
| zipcode | Código postal do imóvel |
| lat | Latitude |
| long | Longitude |
| year | ano do imóvel |
| month | mês do imóvel |
| level | para saber o padrão do imóvel |
| season | Variável para estação do ano |
| basement | Se o imóvel possui porão |
| sqrt_price | Valor do pé quadrado |
| sqrt_zipcode | Valor do pé quadrado por zipcode |
| to_buy | Variável para saber quais imóveis comprar e não comprar |
| price_to_sell | Valor que o imóvel deve ser vendido |
| season_to_sell | Estação do ano que o imóvel deve ser vendido |
| new_price | Novo valor com reajuste |
| profit | Lucro por imóvel |
| percentage_profit | Lucro em porcentagem |

[Dataset from Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)  
![kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

### 1.3 Solução
### 1.3.1 Insights e Hipóteses:
- Casas com vista para água são, em média, 30% mais caras.
- De 21436 imóveis disponíveis em todo o dataset, o CEO pode comprar 10538 imóveis.

**1.4.4. Resultado Financeiro das Recomendações:** Caso as recomendações forem implantadas, o potencial total do lucro obtido com as vendas recomendadas sera de $ 3.492.823.431,53 (Dólar).

## 2. Tecnologias Utilizadas
- Python 3
- Pycharm
- Jupyter Notebook

## 3. Arquivos do projeto
 [House Rocket Jupyter Notebook Codes](https://github.com/jlcunha/House-Rocket/blob/main/house_rocket.ipynb)
 
## 4. Próximos passos
- Os insights gerados neste projeto, no futuro, podem ser melhorados com o uso de modelos de regressão, para determinar com maior precisão qual imóvel pode ser comprado e por qual valor pode ser vendido.

## 5. Agradecimentos
Este projeto é um exercício do curso *Python: do zero ao Data Scientist* - [Comunidade DS](https://www.comunidadedatascience.com/comunidade-ds/).

## 6. Contato
Projeto criado por [Hugo Gomes](https://www.linkedin.com/in/hugofgomes/)

Data Scientist em Formação.
