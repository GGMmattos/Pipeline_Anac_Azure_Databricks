# Projeto Azure Databricks: Pipeline de Dados (Bronze, Silver e Gold)

Este projeto tem como objetivo demonstrar a criação de um pipeline de dados utilizando o Azure Databricks e a arquitetura medalhão, composta pelas camadas **Bronze**, **Silver** e **Gold**. Através dessa abordagem, os dados são processados e transformados, criando uma jornada de dados eficiente e estruturada, desde a ingestão até o armazenamento em formatos otimizados.

## Tecnologias Utilizadas

- **Azure Databricks**
- **Azure Cloud**
- **SQL**
- **Python**

## Descrição do Projeto

O projeto foi desenvolvido com o objetivo de orquestrar e processar dados de acidentes de aviação da ANAC (Agência Nacional de Aviação Civil). O pipeline foi estruturado nas três camadas típicas da arquitetura medalhão:

1. **Bronze**: Ingestão e armazenamento dos dados brutos.
2. **Silver**: Transformação e limpeza dos dados, estruturando-os de forma a facilitar análises futuras.
3. **Gold**: Dados já processados e otimizados para análise, criando um dataset pronto para ser utilizado em relatórios e visualizações.

### Etapas do Projeto:

- **Criação de Notebooks**: Desenvolvi notebooks em Azure Databricks para realizar o processamento e transformação dos dados, desde a ingestão até o armazenamento nas camadas correspondentes.
- **Orquestração de Processos**: Realizei a orquestração dos processos utilizando o Databricks para automatizar a execução dos notebooks e garantir que as transformações fossem feitas de forma eficiente e programada.

## Dados Utilizados

O conjunto de dados utilizado refere-se a **acidentes de aviação da ANAC**, contendo informações sobre os acidentes ocorridos ao longo do tempo. Esse dataset foi a base para aplicar as transformações e estruturação de dados nas três camadas do pipeline.

## Objetivo

O principal objetivo deste projeto foi a construção de uma pipeline escalável e bem estruturada para transformar dados brutos em informações úteis para análise e tomada de decisão. A arquitetura de camadas permite que os dados sejam organizados de forma eficiente e facilmente acessados para análise posterior.

