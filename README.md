# 📊 Macro Dashboard — Análise do Varejo e Indicadores Econômicos do Brasil

Este projeto consiste em um **dashboard interativo desenvolvido no Power BI** para análise da evolução do consumo e do desempenho do varejo brasileiro ao longo do tempo.

O objetivo do projeto é transformar **dados econômicos oficiais em insights visuais claros**, permitindo compreender a dinâmica do consumo, inflação, juros e crescimento dos diferentes setores do varejo.

O dashboard utiliza dados públicos de instituições oficiais e aplica **modelagem de dados, métricas em DAX e visualizações analíticas** para construir uma narrativa econômica.

---

# 📈 Visão Geral do Dashboard

O dashboard está organizado em diferentes páginas analíticas:

## 1️⃣ Panorama Econômico

Apresenta uma visão geral da economia e do consumo no Brasil.

Indicadores principais:

- Crescimento do consumo
- Receita nominal do varejo
- Inflação (IPCA)
- Taxa de juros (SELIC)
- Indicador real de receita
- Classificação do ciclo econômico

Essa página responde à pergunta:

> A economia está expandindo ou desacelerando?

---

## 2️⃣ Análise do Consumo

Explora o comportamento do consumo ao longo do tempo.

Principais análises:

- Crescimento médio do consumo
- Volatilidade do consumo
- Evolução histórica do consumo
- Tendência de longo prazo
- Participação das atividades no varejo

Essa seção permite entender:

> Como o consumo brasileiro evoluiu ao longo dos anos.

---

## 3️⃣ Desempenho do Varejo

Analisa o desempenho dos diferentes setores do varejo.

Indicadores apresentados:

- Crescimento acumulado do varejo
- Crescimento mensal
- Média de crescimento anual
- Ranking de crescimento por setor
- Setor com maior crescimento
- Setor com menor crescimento

Essa página responde:

> Quais setores estão impulsionando o crescimento do varejo?

---

# 📊 Fontes de Dados

Os dados utilizados neste projeto são provenientes de instituições oficiais:

**IBGE — SIDRA**

- Tabela **8880** — Índice de Volume do Comércio
- Tabela **8882** — Comércio Varejista por Atividade

**Banco Central do Brasil**

- Taxa **SELIC**

**IBGE**

- Índice de inflação **IPCA**

Os dados foram tratados e modelados antes da visualização no Power BI.

---

# 🧠 Métricas e Análises Utilizadas

O dashboard utiliza diversas métricas analíticas, incluindo:

- Crescimento real do varejo
- Crescimento Year-over-Year (YoY)
- Crescimento Month-over-Month (MoM)
- Média móvel de consumo
- Ranking de crescimento por setor
- Indicador de ciclo econômico

Essas métricas permitem transformar dados brutos em **informações estratégicas para análise econômica**.

---

# 🛠 Ferramentas Utilizadas

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **API do SIDRA (IBGE)**
- **Heroicons (ícones da interface)**

---
# ⚙️ Processamento de Dados (ETL)

Antes da construção do dashboard, os dados passaram por um processo de **ETL (Extract, Transform, Load)** utilizando Python.

Etapas realizadas:

**Extract**

- Coleta de dados econômicos através da API do **SIDRA (IBGE)**.
- Extração de dados de inflação e taxa de juros.

**Transform**

- Limpeza e padronização das tabelas
- Seleção das variáveis relevantes
- Tratamento de datas
- Organização das séries temporais

**Load**

- Exportação dos dados tratados para arquivos estruturados
- Importação das tabelas no **Power BI**
- Modelagem do relacionamento entre as tabelas

Esse processo garantiu maior consistência e organização dos dados utilizados no dashboard.

# 🏗 Arquitetura do Projeto

Fluxo de dados utilizado no projeto:

API SIDRA (IBGE)
↓
Extração com Python
↓
Tratamento e transformação com Pandas
↓
Exportação dos dados tratados
↓
Importação no Power BI
↓
Modelagem e criação de métricas em DAX
↓
Construção do dashboard analítico

# 🎨 Design do Dashboard

O dashboard foi desenvolvido com foco em **visualização profissional de dados**, incluindo:

- Tema visual escuro
- Navegação lateral interativa
- Cartões de KPI
- Indicadores de tendência
- Ranking de setores do varejo

O objetivo foi criar um dashboard com estética semelhante aos utilizados em **consultorias, áreas de business intelligence e análise econômica**.

---

# 📷 Visualização do Projeto

*(Adicione aqui imagens do dashboard)*



---

# 🚀 Possíveis Melhorias Futuras

Algumas melhorias que podem ser implementadas no projeto:

- Atualização automática dos dados via API
- Modelos de previsão para consumo
- Tooltips analíticos avançados
- Inclusão de novos indicadores macroeconômicos

---

# 👤 Autor

**Otávio Iandre Domingues Tavares**

Entusiasta de **Data Analytics e Business Intelligence**, com interesse em análise de dados econômicos e visualização de informações.


---

#  Objetivo do Projeto

Este projeto foi desenvolvido como parte de um **portfólio de análise de dados**, com o objetivo de demonstrar habilidades em:

- Modelagem de dados
- Construção de métricas em DAX
- Storytelling com dados
- Desenvolvimento de dashboards analíticos no Power BI
