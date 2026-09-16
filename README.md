# Desafio_2_PowerBI_DIO_Bootcamp

## 📊 Projeto: Report de Vendas e Análise de Lucro

Projeto desenvolvido durante o **Bootcamp Formação Power BI Analyst da DIO**, com o objetivo de aplicar conceitos de **modelagem de dados, relacionamentos, criação de medidas, filtros, segmentações e construção de dashboards no Power BI**.

O projeto utiliza como fonte de dados a **Financial Sample**, base de exemplo disponibilizada pelo próprio Power BI, contendo informações relacionadas a vendas, produtos, segmentos, países, descontos, custos e resultados financeiros.

---

## 🎯 Objetivo do Projeto

Construir um relatório gerencial capaz de apresentar uma visão consolidada das vendas e, posteriormente, aprofundar a análise de lucratividade.

O relatório foi estruturado em duas páginas principais:

- **Report de Vendas**
- **Report de Lucro Detalhado**

A proposta foi transformar os dados da base em informações visuais que permitissem analisar:

- Evolução das vendas ao longo do tempo;
- Volume de unidades vendidas;
- Descontos concedidos;
- Custo dos produtos vendidos (COGS);
- Vendas por segmento;
- Vendas por produto;
- Vendas por país;
- Lucro por período;
- Receita/lucro por produto;
- Receita/lucro por segmento;
- Evolução trimestral;
- Distribuição dos resultados por ano e país.

---

## 🗂️ Base de Dados

### Financial Sample

A base utilizada foi a **Financial Sample**, disponibilizada pelo próprio Power BI para fins de demonstração e aprendizado.

Os dados permitem realizar análises envolvendo diferentes dimensões do negócio, como:

- Data;
- Produto;
- Segmento;
- País;
- Vendas;
- Unidades vendidas;
- Descontos;
- COGS;
- Gross Sales;
- Profit.

Por se tratar de uma base de demonstração, o objetivo do projeto não é representar uma empresa real, mas sim demonstrar a aplicação prática dos recursos do Power BI em um cenário de análise comercial e financeira.

---

# 🧩 Modelagem e Relacionamentos

Uma das etapas do projeto foi a organização do modelo de dados para permitir que as informações fossem analisadas de diferentes perspectivas.

Os relacionamentos entre as entidades da base permitem cruzar informações de:

**Tempo → Vendas → Produto → Segmento → País**

Dessa forma, os mesmos indicadores podem ser analisados considerando diferentes dimensões do negócio.

### Principais dimensões utilizadas

| Dimensão | Utilização na análise |
|---|---|
| 📅 Data | Evolução mensal, anual e trimestral |
| 🌎 País | Distribuição geográfica das vendas e resultados |
| 📦 Produto | Análise de vendas/lucro por produto |
| 🏢 Segmento | Comparação entre os segmentos de clientes |
| 💰 Métricas financeiras | Vendas, descontos, COGS, Gross Sales e Profit |

A estrutura de relacionamentos foi utilizada para que os filtros e segmentações aplicados no relatório fossem refletidos nos diferentes visuais de forma integrada.

> **Observação:** o modelo parte da estrutura disponibilizada na Financial Sample e foi organizado no Power BI para suportar as análises apresentadas no relatório.

---

# 📐 Construção do Relatório

## Página 1 — Report de Vendas

A primeira página foi desenvolvida com foco em uma **visão geral do desempenho comercial**.

### KPIs

Foram utilizados cartões para apresentar os principais indicadores:

- **Sales:** 118,73 Mi
- **Units Sold:** 1,13 Mi
- **Discounts:** 9,21 Mi
- **COGS:** 101,83 Mi
- **Gross Sales:** 127,93 Mi

Esses indicadores permitem uma leitura rápida do volume financeiro e operacional apresentado pela base.

### Evolução Mensal das Vendas

Foi utilizado um gráfico de linhas/área para demonstrar a evolução das vendas durante o período analisado.

O objetivo é facilitar a identificação de:

- Crescimento ou redução das vendas;
- Oscilações mensais;
- Períodos de maior volume;
- Tendências ao longo do ano.

### Vendas por Segmento

Foi utilizado um gráfico de barras horizontais para comparar o volume de vendas entre os diferentes segmentos.

Segmentos apresentados:

- Government
- Small Business
- Enterprise
- Midmarket
- Channel Partners

### Vendas por Produto

O gráfico de barras permite comparar o desempenho dos produtos e identificar aqueles com maior participação nas vendas.

Produtos analisados incluem:

- Paseo
- VTT
- Velo
- Amarilla
- Montana
- Carretera

### Vendas por País

Foi utilizado um **Treemap** para representar a participação dos países no volume de vendas.

A visualização permite identificar rapidamente a representatividade de cada país dentro do resultado consolidado.

---

# 📈 Página 2 — Report de Lucro Detalhado

A segunda página foi desenvolvida com uma abordagem mais analítica, buscando explorar a composição do resultado.

### Filtros

Foram utilizados filtros de:

- Ano;
- País.

Esses filtros permitem realizar análises específicas e observar como o resultado se comporta de acordo com o período e localização selecionados.

### Análise Hierárquica do Lucro

Foi utilizado um visual de decomposição para explorar a composição da **Soma de Profit**.

A análise permite navegar do resultado consolidado para diferentes níveis de detalhamento, como:

**Profit → Ano → País**

Esse tipo de visualização auxilia na identificação de quais dimensões estão contribuindo para o resultado apresentado.

### Receita/Lucro por Produto

Foi utilizado um gráfico Radar para comparar o desempenho dos produtos.

A visualização permite observar simultaneamente diferentes produtos e identificar diferenças relativas entre seus resultados.

### Receita/Lucro por Segmento

Foi utilizado um **Treemap** para demonstrar a participação dos segmentos no resultado.

Isso permite visualizar a concentração do resultado entre os diferentes segmentos analisados.

### Receita por Trimestre

Foi utilizado um gráfico de **Waterfall (Cascata)** para demonstrar a evolução do resultado entre os trimestres.

O objetivo é visualizar a contribuição de cada período para a composição do resultado total.

---

# 🛠️ Recursos do Power BI utilizados

Durante a construção do projeto foram explorados recursos como:

- Modelagem de dados;
- Relacionamentos entre tabelas;
- Medidas e agregações;
- Cartões de KPI;
- Gráfico de linhas;
- Gráficos de barras;
- Treemap;
- Gráfico Radar;
- Gráfico Waterfall;
- Decomposition Tree;
- Segmentações de dados;
- Filtros por período;
- Filtros por país;
- Navegação entre páginas;
- Formatação e organização visual;
- Interatividade entre os elementos do relatório.

---

# 🎨 Estrutura Visual

O relatório foi desenvolvido buscando uma identidade visual consistente entre as páginas.

### Características utilizadas:

- Fundo em azul escuro;
- Cards com fundo claro;
- Hierarquia visual entre títulos, KPIs e gráficos;
- Organização dos elementos em blocos;
- Uso de filtros e segmentações;
- Padronização de títulos;
- Destaque para indicadores principais;
- Layout orientado à leitura gerencial.

A estrutura foi pensada para permitir uma leitura inicial dos principais KPIs e, posteriormente, um aprofundamento por período, produto, segmento e localização.

---

# 🔎 Principais análises possibilitadas

A partir do relatório é possível responder perguntas como:

**Vendas**
- Qual o volume total de vendas?
- Como as vendas evoluíram ao longo dos meses?
- Quais produtos apresentam maior volume de vendas?
- Quais segmentos concentram maior participação?
- Quais países apresentam maior representatividade?

**Resultado**
- Qual o lucro total?
- Como o lucro está distribuído entre os anos?
- Quais países possuem maior participação no resultado?
- Como os produtos se comportam em relação ao lucro?
- Como o resultado evolui entre os trimestres?

---

# 📚 Aprendizados

Este projeto contribuiu para a prática de conceitos importantes de **Business Intelligence e análise de dados**, principalmente:

- Organização e modelagem de dados;
- Construção de relacionamentos;
- Criação de indicadores;
- Análise exploratória;
- Construção de dashboards;
- Escolha de visualizações de acordo com o objetivo da análise;
- Utilização de filtros e segmentações;
- Desenvolvimento de uma narrativa visual para apresentação dos dados.

Além da construção dos gráficos, o projeto reforçou a importância de transformar dados brutos em **informações que possam apoiar análises e decisões de negócio**.

---

## 🚀 Próximos passos

Como evolução do projeto, algumas possibilidades seriam:

- Criar uma página de **Overview Executivo**;
- Adicionar indicadores de margem e crescimento;
- Criar análises de **YoY (Year over Year)**;
- Desenvolver indicadores de variação percentual;
- Criar análises de contribuição para o lucro;
- Melhorar a camada de storytelling do dashboard;
- Explorar recursos de DAX para análises mais avançadas;
- Avaliar a utilização de tooltips e drill-through;
- Criar uma visão específica para análise financeira.

---

## 🧰 Ferramentas

**Power BI**

- Power Query
- Modelagem de Dados
- DAX
- Visualizações
- Relacionamentos
- Filtros e Segmentações

**Fonte de dados:** Financial Sample — Microsoft Power BI

---

## 📌 Status

**Concluído — Desafio 2 | Formação Power BI Analyst — DIO Bootcamp**

Projeto desenvolvido para fins de aprendizado, prática e construção de portfólio em **Power BI, Business Intelligence e análise de dados**.
