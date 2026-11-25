# AdventureWorks2016 – Dashboard de Vendas e Desempenho Comercial

## 📊 Sobre o Projeto

Projeto de Business Intelligence (BI) desenvolvido utilizando **Microsoft Power BI**, com base no banco de dados AdventureWorks2016, com o objetivo de analisar o desempenho comercial da empresa por meio de indicadores, gráficos interativos e visualizações estratégicas.

O projeto utiliza o modelo dimensional **Star Schema (Esquema Estrela)** para organizar os dados e facilitar as análises de vendas, clientes, produtos, territórios e vendedores.

A solução foi estruturada em quatro páginas analíticas, permitindo uma visão geral do negócio e análises específicas de cada área.

## 🎯 Objetivos

- Analisar o desempenho geral das vendas.
- Identificar os produtos com maior volume de vendas e receita.
- Avaliar o comportamento dos clientes e o ticket médio.
- Comparar o desempenho comercial entre territórios.
- Analisar os resultados dos vendedores.
- Comparar vendas realizadas pelos canais online e presencial.
- Acompanhar indicadores de receita, custos e margem bruta.

## 📈 Estrutura do Dashboard

### 1. Visão Geral
Apresenta os principais indicadores do negócio, proporcionando uma visão consolidada do desempenho comercial.

Principais análises:
- Receita total.
- Total de pedidos.
- Ticket médio.
- Quantidade de vendas.
- Margem bruta.
- Evolução mensal da receita.
- Receita por canal de venda.
- Receita por território.
- Produtos e clientes com maior receita.

### 2. Vendas
Permite analisar o comportamento das vendas ao longo do tempo e comparar os resultados entre diferentes regiões e canais.

Principais análises:
- Evolução mensal da receita.
- Receita online e presencial.
- Receita por território.
- Comparação de canais por região.
- Desempenho comercial por período.

### 3. Clientes
Apresenta informações sobre a base de clientes e seu comportamento de compra.

Principais análises:
- Quantidade de clientes.
- Ticket médio.
- Total de pedidos.
- Quantidade de itens vendidos.
- Receita média por cliente.
- Evolução das vendas mensais.
- Top 10 produtos mais vendidos.
- Quantidade de clientes por território.
- Ticket médio por território.

### 4. Vendedores
Permite acompanhar o desempenho individual e regional da equipe comercial.

Principais análises:
- Margem bruta percentual.
- Margem bruta.
- Quantidade de vendedores.
- Quantidade de territórios.
- Receita total.
- Evolução mensal da receita e dos pedidos.
- Ranking dos vendedores por receita.
- Análise de descontos concedidos.
- Desempenho por canal de venda.

## 🧮 Principais Indicadores e Medidas DAX

O projeto utiliza medidas DAX para calcular os principais indicadores de desempenho:

- Receita Total;
- Total de Pedidos;
- Ticket Médio;
- Quantidade Vendida;
- Receita Online;
- Receita Presencial;
- Margem Bruta;
- Margem Bruta Percentual;
- Receita Média por Cliente;
- Crescimento da Receita;
- Custo Estimado;
- Ranking de Produtos Mais Vendidos.

## 🗄️ Modelagem de Dados

O projeto utiliza uma modelagem dimensional baseada no conceito Star Schema.

**Tabela Fato:**
- FatoVendas

**Tabelas Dimensão:**
- DimCliente
- DimData
- DimProduto
- DimTerritorio
- DimVendedor

Essa estrutura permite relacionar as informações comerciais e realizar análises multidimensionais utilizando os filtros do Power BI.

## 🛠️ Tecnologias Utilizadas

- **Microsoft Power BI:** desenvolvimento dos dashboards e visualizações.
- **DAX:** criação de medidas e indicadores.
- **Power Query:** extração e transformação dos dados.
- **SQL Server:** banco de dados AdventureWorks2016.
- **SQL:** consultas e preparação dos dados.
- **Star Schema:** modelagem dimensional.

## 📌 Resultados Esperados

O dashboard permite transformar os dados operacionais em informações estratégicas, auxiliando na identificação de tendências, avaliação de desempenho, comparação entre regiões e acompanhamento dos resultados comerciais.

Além disso, proporciona uma visão integrada das vendas, clientes, produtos e vendedores, apoiando a tomada de decisões baseada em dados.

---

**Projeto acadêmico – Business Intelligence**

**Base de dados:** AdventureWorks2016  
**Ferramenta de visualização:** Microsoft Power BI  
**Modelagem:** Star Schema  
**Linguagem de análise:** DAX e SQL