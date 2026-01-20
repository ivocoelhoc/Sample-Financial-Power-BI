# 📊 Análise de Vendas — Power BI (Financial Sample)

Este projeto apresenta um relatório interativo desenvolvido no **Power BI** utilizando a base de dados **Financial Sample**, disponibilizada como exemplo pela Microsoft.  
O objetivo é analisar o desempenho de vendas, lucro e unidades vendidas por **produto, país, segmento e período**.

---

## 🎯 Objetivo do Projeto

Criar um dashboard que permita:

- Visualizar o desempenho de vendas ao longo do tempo  
- Comparar resultados entre países e segmentos  
- Identificar produtos mais vendidos e mais lucrativos  
- Apoiar a tomada de decisão baseada em dados

Este projeto foi desenvolvido com fins **educacionais e de portfólio**, como parte dos meus estudos em **Análise e Ciência de Dados**.

---

## 🗂️ Conjunto de Dados

- Fonte: Dados de exemplo do próprio Power BI (Financial Sample)
- Principais campos:
  - Country (País)
  - Product (Produto)
  - Segment (Segmento)
  - Sales (Vendas)
  - Profit (Lucro)
  - Units Sold (Unidades Vendidas)
  - Date (Data)

Os dados representam vendas simuladas entre os anos de **2013 e 2014**.

---

## 🛠️ Etapas do Projeto

### 1. Importação e Tratamento dos Dados
- Importação do arquivo Excel no Power BI
- Verificação de tipos de dados
- Ajustes de colunas de data
- Criação de medidas com DAX:
  - Total Sales
  - Total Profit
  - Total Units Sold

### 2. Modelagem
- Modelo simples em formato estrela
- Tabela fato de vendas relacionada às dimensões de:
  - Produto
  - País
  - Segmento
  - Tempo

### 3. Construção dos Dashboards

O relatório foi dividido em páginas temáticas:

#### 📄 Página 1 — Produtos e Segmentos
- Total de vendas por produto
- Preço médio de venda por produto
- Vendas por ano, mês e segmento
- Filtros por ano e trimestre

#### 🌍 Página 2 — Países e Lucro
- Mapa com:
  - Soma de vendas e unidades vendidas por país
  - Soma de lucro por país
- Lucro total por país (gráfico de pizza)
- Evolução do lucro por mês e ano
- Vendas totais por país
- Lucro por segmento

---

## 📌 Principais Insights

Alguns exemplos de análises obtidas no relatório:

- Alguns produtos concentram a maior parte das vendas totais
- Determinados países apresentam alto volume de vendas, mas lucro proporcionalmente menor
- O segmento GOVERNMENT é responsável pela maior parte do lucro total
- Existe sazonalidade nas vendas e no lucro ao longo dos meses

Esses insights podem apoiar decisões como:
- Foco em mercados mais rentáveis
- Estratégias por segmento de cliente
- Planejamento de campanhas em períodos de maior demanda

---

## 📷 Prints do Dashboard

### Página 1 — Produtos e Segmentos
![Dashboard Página 1](imagens/dashboard_pagina1.png)

### Página 2 — Países e Lucro
![Dashboard Página 2](imagens/dashboard_pagina2.png)

### Página 2 — Países e Lucro
![Dashboard Página 3](imagens/dashboard_pagina3.png)

---

## ▶️ Como Reproduzir o Projeto

1. Baixe este repositório
2. Abra o arquivo `.pbix` no Power BI Desktop
3. Caso necessário, atualize o caminho do arquivo de dados em:
   - Transformar Dados → Fonte
4. Atualize o relatório

---

## 🚀 Próximos Passos (Evoluções Futuras)

- Inclusão de análise de margem de lucro
- Criação de indicadores de crescimento (YoY)
- Versão com dados reais ou públicos
- Publicação no Power BI Service

---

## 👤 Autor

Projeto desenvolvido por **Ivo**  
Estudante de Ciência de Dados | Análise de Dados | Power BI  
Em busca da primeira oportunidade na área de dados.

