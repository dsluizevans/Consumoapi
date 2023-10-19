# Exploração e Tratamento dos dados das oscilações do dólar no plano real(R$) via API

## Objetivo

O projeto tem a finalidade de apresentar as oscilações da cotação do dólar desde a criação do plano real entre 1995 - 2023 e quem foram os seus governantes.

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
1. **Instalação do python-doenv:** Permitirá carregar a variável de ambiente criada no .env, pois este arquivo conterá a senha de autenticação da API.
2. **Carregamento das bibliotecas utilizadas no projeto.**
3. **Criação de duas variáveis:** Uma para a URL e a outra para key de autenticação(.env).
4. **Importação dos dados via API:** Os dados importados do tipo .json foram coletados via API e analisados para entender a estrutura dos dados.
5. **Tratamento dos Dados:** Os dados passaram por limpeza e tratamento, e foram identificados informações relevantes para o objetivo do projeto.
6. **Visualização dos Dados:**  Criação de visualizações e gráficos para melhor compreensão dos dados históricos da cotação do dólar.

## Conclusão  
O projeto proporcionou uma análise abrangente das oscilações da cotação do dólar no Brasil, cobrindo o período de 1995 a 2023, ao mesmo tempo em que mapeou os governantes durante esse intervalo de tempo. Utilizando tecnologias como Python, Pandas, Numpy, Matplotlib, e Requests, pudemos extrair dados valiosos da API do [**Site Fred**](https://fred.stlouisfed.org).

A primeira etapa crucial envolveu a instalação e configuração do ambiente, assegurando o acesso seguro aos dados por meio de autenticação. Posteriormente, após o carregamento das bibliotecas necessárias, a API foi consultada para obter os dados históricos do dólar. Esses dados brutos passaram por um processo de tratamento meticuloso, incluindo limpeza e análise, para identificar padrões e informações relevantes.

A visualização dos dados desempenhou um papel fundamental, oferecendo insights visuais por meio de gráficos e visualizações bem elaboradas. Isso permitiu uma compreensão mais profunda das tendências cambiais ao longo do tempo, bem como das influências políticas representadas pelos diferentes governantes.

Este projeto não apenas demonstrou a importância da análise de dados históricos para entender o comportamento econômico, mas também destacou o poder das ferramentas tecnológicas modernas para extrair, processar e visualizar esses dados de maneira eficaz. Ao integrar conhecimento econômico, habilidades de programação e técnicas de visualização, conseguimos criar uma narrativa informada sobre a trajetória do dólar no Brasil durante quase três décadas.
