# Análise de Subgrupos na Base de Dados do INEP sobre Educação Superior

O repositório contem o código e a documentação do projeto de Análise de Subgrupos na Base de Dados do INEP sobre Educação Superior. O objetivo principal do projeto é encontrar características que descrevam subgrupos de universidades que possuam uma taxa de evasão discrepante.


## Sumário
- [Introdução](#introducao)
- [Objetivo](#objetivo)
- [Metodologia](#metodologia)
- [Resultados](#resultados)
- [Referências](#referencias)


## Introdução
A base de dados do INEP possui uma grande variedade de instituições de ensino superior, com suas mais variadas características agregada com suas respectivas informações de quantidade de ingressantes e concluintes de várias categorias. 

## Objetivo
 Nosso objetivo com este projeto é encontrar características que descrevam quais as instituições, seus tipos, regiões geográficas que possuem uma taxa de evasão anormal para orientar a investigação de possíveis analistas educacionais

## Metodologia

 1. **Coleta de Dados**: Obtenção dos dados do INEP através da plataforma [basedosdados](#referencias);
 2. **Tratamento dos Dados**: Remoção de Colunas, Criação de métricas e análise de distribuições;
 3. **Descoberta de Subgrupos**: Execução do Algoritmo de BeamSearch para encontrar Subgrupos relevantes segundo uma função de qualidade Subgrupo Vs. Todos;
 4. **Análise dos Subgrupos**: Comparação de distribuição de taxa de evasão nos subgrupos e nos dados totais e análise de relevância.
## Resultados


## Referências
[Base de Dados INEP Ensino Superior](https://basedosdados.org/dataset/a3b57cca-ff80-4bf2-8bac-c145109e06a7?table=03f7e043-9ea1-47f9-9e77-f55dfe449381)
