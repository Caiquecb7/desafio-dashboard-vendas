# 🎮 Xbox Game Pass — Dashboard de Vendas e Assinaturas

## 📊 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio de análise e visualização de dados, com o objetivo de transformar uma base de dados de assinaturas do Xbox Game Pass em um dashboard interativo e visualmente organizado no Excel.

A solução busca facilitar a análise do perfil dos assinantes, dos planos contratados, das receitas geradas, dos benefícios adicionais e do comportamento de renovação das assinaturas.

---

## 🎯 Objetivo

O objetivo principal do projeto é utilizar dados de assinaturas para gerar informações que permitam analisar:

- Quantidade total de assinantes;
- Receita gerada pelas assinaturas;
- Distribuição dos planos;
- Tipos de assinatura;
- Comportamento de renovação automática;
- Adesão aos benefícios EA Play e Minecraft;
- Utilização de cupons/descontos;
- Evolução dos valores ao longo dos meses.

A proposta é transformar dados brutos em informações visuais que facilitem a interpretação dos resultados e apoiem análises relacionadas ao desempenho das assinaturas.

---

## 🗂️ Dados utilizados

A base possui **295 registros de assinantes** e contém informações relacionadas às assinaturas do Xbox Game Pass.

### Principais campos da base

| Campo | Descrição |
|---|---|
| Subscriber ID | Identificador do assinante |
| Name | Nome do assinante |
| Plan | Plano contratado |
| Start Date | Data de início da assinatura |
| Auto Renewal | Indica se a assinatura possui renovação automática |
| Subscription Price | Valor da assinatura |
| Subscription Type | Periodicidade da assinatura |
| EA Play Season Pass | Indica adesão ao EA Play |
| EA Play Season Pass Price | Valor do EA Play |
| Minecraft Season Pass | Indica adesão ao Minecraft Season Pass |
| Minecraft Season Pass Price | Valor do Minecraft Season Pass |
| Coupon Value | Valor de desconto aplicado |
| Total Value | Valor total associado à assinatura |

---

## 📈 Dashboard

O dashboard foi desenvolvido no Excel com foco em uma apresentação visual semelhante a um painel executivo.

Entre as análises apresentadas estão:

### 👥 Assinantes

A base utilizada no projeto possui **295 assinantes**.

### 💰 Receita

O dashboard permite analisar o valor total gerado pelas assinaturas e sua distribuição ao longo dos meses.

### 🔄 Renovação automática

A análise considera a quantidade de assinantes com e sem renovação automática.

Na base:

- 148 assinantes possuem renovação automática;
- 147 assinantes não possuem renovação automática.

### 🎮 Benefícios adicionais

Também são analisadas as adesões aos benefícios:

- EA Play Season Pass;
- Minecraft Season Pass.

### 🎟️ Cupons

O projeto apresenta também o impacto dos valores de cupons/descontos associados às assinaturas.

### 📅 Análise mensal

Os valores das assinaturas e dos cupons são organizados mensalmente, permitindo observar a variação dos resultados ao longo do período analisado.

---

## 🛠️ Ferramentas utilizadas

- Microsoft Excel
- Tabelas estruturadas
- Tabelas dinâmicas
- Gráficos
- Fórmulas e cálculos
- Segmentação/filtragem de dados
- Formatação condicional
- Dashboarding e visualização de dados

---

## 📁 Estrutura do arquivo

O arquivo Excel está organizado em quatro principais abas:

### `Assets`

Contém elementos visuais utilizados na construção do dashboard, incluindo a paleta de cores.

### `Bases`

Contém a base de dados utilizada para as análises.

### `Cálculos`

Área destinada aos cálculos e tabelas auxiliares utilizados para alimentar as visualizações.

### `Dashboard`

Página final de apresentação dos indicadores e análises.

---

## ▶️ Como reproduzir

1. Faça o download do arquivo `.xlsx` disponível neste repositório.
2. Abra o arquivo utilizando o Microsoft Excel.
3. Acesse a aba `Bases` para visualizar os dados utilizados.
4. Acesse a aba `Cálculos` para consultar as tabelas e cálculos auxiliares.
5. Acesse a aba `Dashboard` para visualizar as análises.
6. Caso os dados sejam atualizados, atualize as tabelas dinâmicas e demais elementos dependentes da base.

---

## 📌 Principais indicadores

| Indicador | Resultado |
|---|---:|
| Total de assinantes | 295 |
| Assinaturas com renovação automática | 148 |
| Assinaturas sem renovação automática | 147 |
| Valor total das assinaturas | 7.633 |
| Valor total de cupons | 2.122 |
| Receita de EA Play | 2.940 |
| Receita de Minecraft Season Pass | 3.880 |

---

## 💡 Objetivo de aprendizado

Além da entrega do desafio, o projeto teve como objetivo desenvolver competências relacionadas à análise de dados e à construção de dashboards, trabalhando desde a organização da base até a criação de indicadores e visualizações.

O projeto demonstra a aplicação prática de conceitos de:

- Organização e tratamento de dados;
- Análise exploratória;
- Construção de indicadores;
- Tabelas dinâmicas;
- Visualização de dados;
- Storytelling com dados;
- Desenvolvimento de dashboards no Excel.

---

## 📄 Arquivo

O repositório contém o arquivo Excel utilizado na construção do projeto:

**DASHXBOX.xlsx**

---

## 👤 Autor

**Caique Bispo**

Projeto desenvolvido para fins de estudo e portfólio em análise e visualização de dados.
