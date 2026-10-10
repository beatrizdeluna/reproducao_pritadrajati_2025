# Reprodução do artigo: More Kids, More Conflict? Family Size and Domestic Violence in a High‐Fertility Setting (Pritadrajati, 2025)

Este repositório contém o código em R (`.Rmd`) referente à reprodução do modelo empírico do artigo de Pritadrajati (2025), utilizando dados da *Samoa Demographic and Health Survey–Multiple Indicator Cluster Survey (DHS–MICS) 2019–20*. Trata-se de um exercício prático para a matéria de Microeconomia do curso de mestrado em Economia (PPGE-UFF), ministrado pela professora Daniele Carusi no segundo semestre de 2026.

## Objetivo
Investigar o impacto causal do tamanho da família sobre a violência por parceiro íntimo (IPV) a partirda estratégia de identificação por **Variáveis Instrumentais (IV-2SLS)** baseada na composição do sexo dos dois primeiros filhos (*SameSex*), seguindo a literatura clássica de Angrist e Evans (1998).

## Requisitos
Para rodar o script, são necessárias as seguintes bibliotecas do R:
```R
install.packages(c("tidyverse", "janitor", "haven", "dplyr", "modelsummary", "openxlsx", "estimatr"))
