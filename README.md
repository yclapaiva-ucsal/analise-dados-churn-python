# 📊 Análise de Dados e Diagnóstico de Cancelamento de Clientes (Churn)

Este projeto consiste em uma análise exploratória de dados desenvolvida em Python durante a **Jornada Python**. O objetivo principal foi analisar uma base de dados de cancelamentos de clientes, identificar os fatores críticos que influenciam o *churn* e propor intervenções operacionais baseadas em dados para reduzir a evasão de clientes.

---

## 🎯 Objetivo do Projeto

Compreender os motivos que levam os clientes a cancelarem seus serviços e calcular o impacto de ações estratégicas (como mudança nos tipos de contrato e limites de ligações ao call center) na retenção da base de clientes.

---

## ⚡ Funcionalidades e Etapas da Análise

- **Importação e Inspeção de Dados:** Carregamento da base de dados (`cancelamentos.csv`) com a biblioteca **Pandas**.
- **Tratamento e Limpeza de Dados (*Data Cleaning*):** Remoção de colunas irrelevantes (como IDs de clientes) e exclusão de linhas com valores ausentes (*NaN*).
- **Análise Exploratória Inicial:** Diagnóstico da taxa de *churn* inicial da base (identificando uma taxa superior a 56%).
- **Análise de Causas de Churn:** Criação de gráficos interativos com **Plotly Express** comparando o comportamento de clientes ativos versus clientes cancelados.
- **Simulação de Cenários de Negócio:** Filtragem de hipóteses operacionais (ex.: clientes de contrato mensal, clientes com mais de 4 ligações para o call center ou atrasos de pagamento acima de 20 dias) para medir a redução potencial na taxa de cancelamento.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3** — Linguagem principal.
- **Pandas** — Manipulação, tratamento e análise quantitativa de dados.
- **Plotly Express** — Geração de gráficos interativos (histogramas e distribuições).
- **VS Code** — Ambiente de desenvolvimento.

---

## 📂 Estrutura do Repositório

- **`gabarito.ipynb`**: Notebook com a análise exploratória completa e códigos de geração de gráficos.
- **`cancelamentos.csv`**: Base de dados de clientes utilizada no diagnóstico.
- **`README.md`**: Documentação do projeto.

---
