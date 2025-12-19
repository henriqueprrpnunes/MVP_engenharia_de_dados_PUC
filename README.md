# MVP_engenharia_de_dados_PUC

# Contratações Públicas Federais — Pipeline de Dados (2020–2024)

# Visão Geral

Este projeto consiste na construção de um pipeline de dados em nuvem para coletar, tratar, modelar e analisar dados de contratações públicas do Governo Federal no período de 2020 a 2024. O objetivo é transformar dados públicos brutos em uma base analítica confiável para geração de insights.

# Objetivos

Consolidar arquivos CSV mensais em uma base única

Estruturar um pipeline com Arquitetura Medalhão (Bronze, Silver e Gold)

Preparar os dados para análise no Power BI

Identificar padrões de gasto, concentração e sazonalidade

# Fonte de Dados

Portal da Transparência – Compras Públicas
https://portaldatransparencia.gov.br/download-de-dados/compras

# Arquitetura

Bronze: dados brutos, normalização de colunas e timestamp de ingestão

Silver: padronização de textos, tipos de dados e filtragem de colunas

Gold: regras de qualidade, categorização e dados prontos para análise

Dimensão Calendário: datas completas (2000–2050) para análises temporais

# Modelagem

Modelo analítico em Esquema Estrela no Power BI, com:

Tabela fato de contratos

Dimensão calendário

# Principais Análises

Gasto total por ano e no período

Top 10 fornecedores por valor e número de contratos

Distribuição por órgão, modalidade de compra e objeto

Evolução anual dos maiores fornecedores

Sazonalidade mensal das contratações

# Desafios

Ausência de tabelas oficiais padronizadas para criação de dimensões

Manutenção de atributos textuais na tabela fato

Classificação do objeto da compra baseada em palavras-chave

# Próximos Passos

Integração com cadastros oficiais

Uso de técnicas de NLP para categorização do objeto

Normalização completa do modelo dimensional

# Tecnologias

Python • Apache Spark • Databricks • Power BI

# Autor

Henrique Nunes
