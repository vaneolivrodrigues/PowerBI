# Relatório de Vendas e Lucro - Power BI (Bootcamp DIO & Klabin)

Este repositório apresenta o projeto final desenvolvido durante o bootcamp de Power BI, uma parceria entre a **DIO** e a **Klabin**. O foco do projeto foi transformar dados brutos em insights estratégicos para a tomada de decisão executiva.

## 📊 O Dashboard

O relatório foi desenvolvido utilizando a base de dados **Financial Sales** e está dividido em duas visões principais:

1.  **Sales Report:** Uma visão macro com KPIs de vendas brutas, unidades vendidas, descontos e custos (COGS). Permite o detalhamento por segmento de mercado e localização geográfica.
2.  **Report de Lucro Detalhado:** Uma análise profunda da rentabilidade, utilizando visuais de Árvore de Decomposição para entender a composição do lucro e Gráfico de Cascata para a variação trimestral.

## ⚙️ Excelência em Dados: ETL, EDA e Governança

Para garantir que o relatório não fosse apenas visualmente atraente, mas, acima de tudo, **confiável**, o projeto seguiu rigorosos processos de engenharia de dados:

### 1. Limpeza e Transformação (ETL)
Utilizando o **Power Query**, os dados passaram por um processo de higienização:
* **Tratamento de Tipos:** Conversão correta de campos monetários, percentuais e de data.
* **Normalização:** Verificação de integridade para garantir que os cálculos de lucro e custos fossem matematicamente precisos.
* **Criação da dCalendário:** Implementação de uma tabela de dimensão temporal para permitir análises de inteligência de tempo (*Time Intelligence*).

### 2. Análise Exploratória (EDA)
A construção dos visuais foi precedida por uma análise exploratória para identificar:
* **Drivers de Vendas:** Identificação de que o segmento *Government* possui o maior volume de vendas.
* **Padrões de Sazonalidade:** Análise da evolução das vendas mês a mês, permitindo identificar picos de demanda.
* **Performance por Produto:** Comparação direta entre produtos como *Paseo* e *Velo* em relação à margem de lucro.

### 3. Governança e Confiabilidade
O projeto foi desenhado sob o conceito de "Única Fonte da Verdade" (*Single Source of Truth*). Através de medidas DAX centralizadas, garantimos que a lógica de negócio seja aplicada de forma consistente em todo o relatório, eliminando o risco de discrepâncias comuns em processos manuais.

## 🛠️ Tecnologias e Ferramentas
* **Power BI** (Visualização e Modelagem)
* **Power Query** (M Language para ETL)
* **DAX** (Criação de métricas de performance)
* **Base de Dados:** Financial Sales (Microsoft)

---
*Projeto desenvolvido como parte do portfólio de análise de dados e engenharia.*
