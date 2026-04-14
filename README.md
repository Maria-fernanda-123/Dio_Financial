# 📊 Dashboard Financeiro — Power BI

> Projeto desenvolvido como parte do bootcamp/curso da **[DIO — Digital Innovation One](https://www.dio.me/)**, com foco na criação de relatórios interativos e visuais analíticos utilizando o Microsoft Power BI.

---

## 📌 Sobre o Projeto

Este relatório foi construído a partir do dataset de exemplo **Financial Sample** do Power BI, com o objetivo de praticar a criação de dashboards profissionais, aplicar visuais customizados e desenvolver narrativa analítica com dados financeiros.

O relatório conta com **2 páginas principais** de análise, navegação interativa via botões de ação, tema visual personalizado e identidade visual da DIO.

---

## 🗂️ Estrutura do Relatório

### Página 1 — Reporte de Finanças

Visão geral do desempenho financeiro com KPIs e distribuição de vendas.

**Indicadores (Cards):**

| Métrica | Agregação |
|---|---|
| Vendas | Média (Avg Sales) |
| Unidades Vendidas | Total (Sum Units Sold) |
| Descontos | Média (Avg Discounts) |
| Custo dos Produtos (COGS) | Total (Sum COGS) |

**Visuais:**

| Visual | O que mostra |
|---|---|
| Gráfico de Linhas | Evolução da média de vendas ao longo do tempo (por mês) |
| Gráfico de Rosca | Distribuição das vendas por Segmento |
| Gráfico de Barras Clusterizado | Vendas por Segmento e por Produto |
| Mapa | Volume de vendas por País |
| Treemap | Vendas por País em visão de área |
| Segmentação de Dados | Filtro por Data |

**Navegação:** botões de ação para alternar entre os visuais de Barras, Rosca, Mapa e Treemap; botão de acesso à página de Lucro Detalhado; botão borracha para limpar filtros.

---

### Página 2 — Lucro Detalhado

Análise aprofundada do lucro com foco em decomposição e comparação de desempenho.

| Visual | O que mostra |
|---|---|
| Árvore de Decomposição | Análise hierárquica dos drivers de lucro |
| Treemap | Distribuição do lucro por categoria |
| Gráfico Cascata (Waterfall) | Variação do lucro por período/categoria |
| Radar Chart *(visual customizado)* | Comparação multidimensional de métricas |
| Segmentação Avançada | Filtro interativo de dados |

---

## 🧩 Visuais Customizados

| Visual | Origem |
|---|---|
| Word Cloud | Microsoft — AppSource |
| Bullet Chart | Microsoft — AppSource |
| Radar Chart | Microsoft — AppSource |

---

## 📁 Dataset

- **Fonte:** Financial Sample — dataset de exemplo nativo do Power BI Desktop
- **Tabela principal:** `financials`
- **Campos utilizados:** `Sales`, `Units Sold`, `Discounts`, `COGS`, `Segment`, `Product`, `Country`, `Date`

---

## ⚙️ Tecnologias

- Microsoft Power BI Desktop `v2.109.1021.0`
- Power BI Service (publicação na nuvem)
- Visuais customizados do marketplace do Power BI (AppSource)

---

## 🚀 Como Abrir o Projeto

1. Faça o download do arquivo `sample_financial.pbix`
2. Abra o **Power BI Desktop** (versão 2.109 ou superior)
3. Vá em **Arquivo → Abrir** e selecione o arquivo `.pbix`
4. Explore as páginas e interaja com os filtros e botões de navegação

> **Observação:** o relatório está conectado ao Power BI Service via dataset remoto. Para uso local completo, reconecte ao Financial Sample disponível no Power BI Desktop em **Obter Dados → Exemplos**.

---

## 👨‍💻 Autor

Desenvolvido como exercício prático no curso de Power BI da **DIO — Digital Innovation One**.

[![DIO](https://img.shields.io/badge/DIO-Digital%20Innovation%20One-orange?style=flat-square)](https://www.dio.me/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow?style=flat-square&logo=powerbi)](https://powerbi.microsoft.com/)

---

## 📄 Licença

Projeto de caráter educacional, desenvolvido exclusivamente para fins de aprendizado no âmbito do bootcamp da DIO.
