# Projeto de Consumo de API para Consulta, Análise e Tratamento de Dados

## Objetivo

O projeto tem a finalidade de demonstrar a possibilidade do consumo de API,s para consultar, analisar e tratar os dados de fontes externas.

## Fonte da consulta
[Site Fred](https://fred.stlouisfed.org)  
[Série histórica das oscilações do dólar no Brasil de cada Presidente entre 1995 - 2023](https://api.stlouisfed.org/fred/series/observations)

## Tecnologia encontradas no Projeto  
- Python
- Pandas
- Numpy
- Matplotlib.pyplot
- Matplotlib.dates >>> YearLocator
- Requests
- Dotenv
- Os

## Etapas
1. A instalação do python-doenv permitirá carregar a variável de ambiente criada no .env, pois este arquivo conterá a senha de autenticação da API.
2. Carregamento das bibliotecas que serão utilizadas no projeto.
3. Criação de duas variáveis: Uma para a URL e a outra para key de autenticação(.env).
4. Requisição e status(200) do endpoint.
5. Criação de um DataFrame a partir da variável que armazena dos dados trazidos pela requisiçao.
6. Exclusão de algunas colunas que não fazia sentido para a análise e o objetivo final.
7. Conversão das coluna do tipo "object" para "datetime"
8. Tratamento dos valores encontrados que impactava no projeto como todo.
9. Conversão da coluna "value" para float.
10. Conversão da coluna "date" para index.
11. Criação de gráfico com Matplotlib da cotação do dólar dutante o período presidencial(1995 - 2023)
12. Criação de dicionário dos periodos presidenciais.
13. Criação de gráfico da cotação do dólar durante o período presidencial, destacando com cores o tempo de governo e as oscilações do dólar.
14. Criação de 6 gráficos(grid de subplots) dos momentos presidenciais(1995 - 2023).
