---
title: Análise de Dados do Setor de Turismo no Nordeste
date: 2026-09-21 10:00:00 -0300
categories: [data_analysis, analise_de_dados, project]
tags: [excel, data, powerbi]
---

> **Projeto de Business Intelligence desenvolvido com Power BI para análise de desempenho, identificação de tendências e apoio à tomada de decisões.**

## Sobre o projeto

Este projeto apresenta uma análise de dados de um conjunto fictício de empresas do setor de turismo no Nordeste brasileiro.

A base disponibilizada contém informações mensais referentes a um período de 12 meses, permitindo analisar diferentes dimensões do negócio, como receita, número de clientes, taxa de ocupação e avaliação média dos clientes.

O objetivo principal foi transformar os dados em informações que pudessem auxiliar um gestor a:

* Acompanhar o desempenho geral;
* Identificar padrões e tendências ao longo do tempo;
* Comparar estados, cidades e tipos de empreendimento;
* Identificar oportunidades de melhoria;
* Apoiar decisões estratégicas simples.

Este projeto está estruturado nos seguintes tópicos:

**1. *O problema de negócio***
**2. *Dados utilizados***
**3. *Preparação e entendimento dos dados***
**4. *Definição dos indicadores KPIs***
**5. *Construção do Dashboard***
**6. *Filtros e exploração de dados***
**7. *Resultado da Análise***
**8. *Análise temporal***
**9. *Comparação entre os estados***
**10. *Comparação entre tipos de empreendimento***
**11. *Análise por cidade***
**12. *Principais Insights***
**13. *Recomendações estratégicas***
**14. *Limitações de Análise***
**15. *Próximos Passos***
**16. *Tecnologias Utilizadas***

Dito isso, seguimos para o primeiro tópico desta análise.

---

## 1. O problema de negócio

O setor de turismo possui diferentes tipos de empreendimentos e está sujeito a variações de demanda ao longo do ano.

Diante disso, um gestor precisa conseguir responder perguntas como:

* Qual é o desempenho geral do negócio?
* Como a receita se comporta ao longo dos meses?
* Existem períodos de maior ou menor demanda?
* Quais estados apresentam maior volume de receita?
* Como hotéis, pousadas e agências se comparam?
* Quais cidades apresentam os maiores e menores resultados?
* Onde existem oportunidades para melhorar o desempenho?

A proposta deste projeto foi utilizar os dados disponíveis para responder essas perguntas de maneira visual e objetiva.

---

## 2. Dados utilizados

A base de dados é fictícia e contém registros mensais de empresas do setor de turismo.

As principais variáveis disponíveis são:

| Campo                  | Descrição                                     |
| ---------------------- | --------------------------------------------- |
| Estado                 | Estado onde o empreendimento está localizado  |
| Cidade                 | Cidade do empreendimento                      |
| Tipo de empreendimento | Hotel, pousada ou agência                     |
| Receita mensal         | Receita registrada no período                 |
| Número de clientes     | Quantidade de clientes atendidos              |
| Taxa de ocupação       | Percentual de ocupação                        |
| Avaliação média        | Avaliação dos clientes em uma escala de 1 a 5 |
| Mês                    | Período de referência do registro             |

Os estados presentes na análise são Ceará, Pernambuco, Piauí e Rio Grande do Norte.

Por se tratar de uma base fictícia, os resultados devem ser interpretados como parte de um exercício analítico, e não como uma representação estatística do turismo real da região.

---

## 3. Preparação e entendimento dos dados

Antes da construção do dashboard, a primeira etapa da análise foi compreender a estrutura da base e identificar quais variáveis poderiam responder às perguntas do negócio.

As informações foram organizadas de forma que fosse possível realizar análises por:

* Período;
* Estado;
* Cidade;
* Tipo de empreendimento.

Também foram consideradas as métricas quantitativas de receita, clientes, ocupação e avaliação.

Essa etapa é importante porque um dashboard eficiente não deve começar pela escolha dos gráficos, mas pelo entendimento de **quais perguntas os dados conseguem responder**.

---

## 4. Definição dos indicadores

A partir dos objetivos do projeto, foram definidos quatro indicadores principais para representar a visão geral do negócio.

### Receita Total

Representa a soma da receita registrada durante o período analisado.

### Clientes Total

Representa o volume total de clientes registrados na base.

### Taxa Média de Ocupação

Representa a média das taxas de ocupação disponíveis na base.

### Avaliação Média

Representa a média das avaliações atribuídas pelos clientes, considerando a escala de 1 a 5.

Esses indicadores foram utilizados como KPIs na parte superior do dashboard para permitir uma leitura rápida do desempenho geral.

---

## 5. Construção do dashboard

O dashboard foi desenvolvido no **Power BI**, utilizando uma estrutura voltada para análise gerencial.

<iframe title="Turismo Nordeste Dashboard" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiNjcwNDNlZTYtYzYxMy00ODQyLWI2NmYtODc0MjU5OTQ4OGI3IiwidCI6IjIxZjYyYmIzLWY5ODYtNGUyMy04YjU0LWE1M2JmNDMzMzk3MSJ9" frameborder="0" allowFullScreen="true"></iframe>
> *Dashboard desenvolvido em Power BI.*

A página principal foi organizada em diferentes níveis de análise.

### Visão geral

Na primeira camada foram apresentados os principais KPIs:

* Receita Total;
* Número de Clientes;
* Taxa Média de Ocupação;
* Avaliação Média.

Essa seção permite que o gestor compreenda rapidamente a dimensão geral dos resultados.

### Análise temporal

Foi utilizado um gráfico de receita mensal para observar a evolução do indicador ao longo do período.

O objetivo foi identificar:

* Variações mensais;
* Períodos de maior receita;
* Possíveis padrões sazonais;
* Pontos que merecem investigação.

### Análise regional

A receita foi comparada entre os estados disponíveis na base.

Essa visualização permite identificar diferenças de desempenho entre as regiões analisadas.

### Análise por empreendimento

A receita também foi segmentada entre:

* Agência;
* Hotel;
* Pousada.

Essa comparação permite observar como o faturamento está distribuído entre os diferentes modelos de empreendimento.

### Análise por cidade

Foram criados rankings com as cinco cidades de maior receita e as cinco cidades de menor receita.

Essa abordagem facilita a identificação de localidades que merecem uma análise mais detalhada.

---

## 6. Filtros e exploração dos dados

Para tornar o dashboard exploratório, foram utilizados filtros que permitem segmentar os resultados por:

* Estado;
* Cidade;
* Tipo de empreendimento;
* Mês;
* Ocupação.

Dessa forma, o usuário não fica limitado à visão consolidada.

Por exemplo, é possível selecionar um determinado estado e observar como os indicadores e gráficos se comportam apenas para aquela região.

Esse recurso transforma o dashboard de uma apresentação estática em uma ferramenta de exploração dos dados.

---

# 7. Resultados da análise

Após a construção do dashboard, foram identificados alguns padrões relevantes.

## Desempenho geral

O conjunto de dados analisado apresentou:

* **R$ 75,763 milhões** em receita total;
* Aproximadamente **473 mil clientes**;
* **68,05%** de taxa média de ocupação;
* **4,02** de avaliação média.

Esses indicadores fornecem uma visão consolidada do desempenho das empresas durante o período analisado.

A combinação entre volume de receita, quantidade de clientes, ocupação e avaliação permite observar o desempenho sob diferentes perspectivas, evitando depender de uma única métrica.

---

## 8. Análise temporal

A análise mensal revelou variações na receita ao longo do período.

Um dos principais destaques foi o **pico observado em julho**, período associado às férias escolares.

Esse comportamento é compatível com a hipótese de existência de sazonalidade na demanda turística, embora a base analisada, por ser fictícia e limitada a 12 meses, não permita afirmar um padrão histórico de longo prazo.

A identificação desse comportamento é relevante para o planejamento de períodos de maior e menor demanda.

---

## 9. Comparação entre estados

A receita apresentou resultados bastante próximos entre os quatro estados analisados.

| Estado              |         Receita |
| ------------------- | --------------: |
| Ceará               | R$ 19,3 milhões |
| Pernambuco          | R$ 19,0 milhões |
| Piauí               | R$ 18,8 milhões |
| Rio Grande do Norte | R$ 18,6 milhões |

A diferença relativamente pequena entre os valores indica uma distribuição de receita sem concentração extrema em um único estado dentro desta base.

Essa característica permite analisar as regiões individualmente, buscando compreender quais cidades e tipos de empreendimento contribuem para cada resultado.

---

## 10. Comparação entre tipos de empreendimento

A receita também apresentou uma distribuição bastante equilibrada entre os três tipos de empreendimento.

| Tipo    |         Receita |
| ------- | --------------: |
| Agência | R$ 25,8 milhões |
| Hotel   | R$ 25,0 milhões |
| Pousada | R$ 24,9 milhões |

As agências apresentaram o maior volume de receita, porém a diferença em relação aos hotéis e pousadas foi relativamente pequena.

Portanto, os dados não indicam uma concentração de faturamento em apenas um tipo de empreendimento.

Essa análise também pode ser utilizada em conjunto com os filtros de estado e cidade para investigar se determinados modelos possuem comportamentos diferentes dependendo da localização.

---

## 11. Análise por cidade

A análise municipal apresentou diferenças entre os resultados.

### Top 5 cidades por receita

| Posição | Cidade            |         Receita |
| ------: | ----------------- | --------------: |
|       1 | Canoa Quebrada    | R$ 6,68 milhões |
|       2 | Fortaleza         | R$ 6,66 milhões |
|       3 | Porto de Galinhas | R$ 6,62 milhões |
|       4 | Luis Correia      | R$ 6,57 milhões |
|       5 | Teresina          | R$ 6,54 milhões |

### Bottom 5 cidades por receita

| Posição | Cidade       |         Receita |
| ------: | ------------ | --------------: |
|       1 | Pipa         | R$ 5,60 milhões |
|       2 | Parnaíba     | R$ 5,69 milhões |
|       3 | Jericoacoara | R$ 5,99 milhões |
|       4 | Recife       | R$ 6,15 milhões |
|       5 | Olinda       | R$ 6,27 milhões |

A diferença entre os rankings demonstra que o desempenho não é uniforme entre as cidades.

Esse recorte permite direcionar análises mais específicas para localidades com maior ou menor volume de receita.

---

# 12. Principais insights

A partir da análise realizada, os principais insights foram:

1. O conjunto analisado apresentou **R$ 75,763 milhões de receita e aproximadamente 473 mil clientes**.
2. A **taxa média de ocupação foi de 68,05%**, enquanto a avaliação média alcançou **4,02 em uma escala de 1 a 5**.
3. A receita apresentou variações ao longo dos meses, com **destaque para julho**, indicando possível influência de sazonalidade.
4. Os quatro estados analisados apresentaram volumes de receita próximos, sem concentração extrema em uma única região.
5. Agências, hotéis e pousadas apresentaram participação relativamente equilibrada no faturamento.
6. As cidades apresentaram diferenças de receita, evidenciadas pelos rankings de Top 5 e Bottom 5.
7. Os períodos de menor demanda representam uma oportunidade para desenvolver ações comerciais capazes de reduzir a variação sazonal.
8. As cidades com menor receita podem ser analisadas individualmente para identificar fatores operacionais ou comerciais associados ao desempenho.

---

# 13. Recomendações estratégicas

Os insights encontrados permitem propor algumas ações simples.

### Estratégias para períodos de menor demanda

Considerando a variação mensal observada, podem ser avaliadas campanhas promocionais, pacotes especiais e outras ações comerciais direcionadas aos períodos de menor demanda.

### Análise das cidades de menor receita

As cidades presentes no Bottom 5 podem ser investigadas individualmente para compreender quais fatores estão associados ao menor resultado.

Uma próxima etapa poderia cruzar receita, número de clientes, ocupação e avaliação para identificar se o menor faturamento está relacionado à demanda, capacidade ou experiência do cliente.

### Monitoramento das cidades de maior receita

As cidades com maior receita podem ser acompanhadas para identificar características que possam ser replicadas em outras localidades.

### Análise segmentada por empreendimento

Como hotéis, pousadas e agências apresentaram receitas próximas, uma análise mais aprofundada por cidade e estado pode revelar diferenças que não aparecem na visão consolidada.

---

# 14. Limitações da análise

É importante considerar algumas limitações do projeto.

A base utilizada é **fictícia**, portanto os resultados não devem ser interpretados como indicadores reais do turismo nordestino.

Além disso, o período analisado corresponde a apenas 12 meses. Dessa forma, a identificação de sazonalidade deve ser tratada como uma observação do comportamento apresentado pela base, e não como uma conclusão histórica definitiva.

Também não estão disponíveis outras variáveis que poderiam explicar os resultados, como custos, número de funcionários, investimentos em marketing, capacidade total, origem dos clientes, preços praticados ou informações sobre eventos locais.

Essas variáveis poderiam enriquecer uma segunda etapa da análise.

---

# 15. Próximos passos

Caso novos dados fossem disponibilizados, algumas análises poderiam ser incorporadas ao projeto:

* Comparação entre receita e número de clientes;
* Receita média por cliente;
* Evolução da ocupação por tipo de empreendimento;
* Relação entre avaliação e receita;
* Análise de crescimento mês a mês;
* Identificação de períodos de baixa demanda;
* Análise de desempenho individual por empreendimento;
* Comparação entre capacidade disponível e ocupação;
* Criação de indicadores de crescimento e variação percentual.

Essas análises permitiriam evoluir o projeto de um dashboard descritivo para uma solução de BI com maior capacidade de diagnóstico.

---

# 16. Tecnologias utilizadas

**Ferramentas:**

* Power BI
* DAX
* Power Query
* Microsoft Excel

**Principais conceitos aplicados:**

* Business Intelligence;
* Análise exploratória de dados;
* KPIs;
* Análise temporal;
* Análise regional;
* Segmentação de dados;
* Ranking;
* Visualização de dados;
* Storytelling com dados.

---

## Autor

**Leandro Rotholi**

*Obs.: Este projeto foi desenvolvido originalmente como parte de um teste prático para uma oportunidade de estágio e posteriormente adaptado para compor meu portfólio de **Análise de Dados e Business Intelligence**.*