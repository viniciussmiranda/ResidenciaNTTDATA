# 🚗 Análise de Dados para Indústria Automobilística

Este projeto foi desenvolvido como parte da **Residência Tecnológica - RISEUP 2025.1** em parceria com a empresa **NTT Data**. O objetivo é realizar todo o processo de tratamento e análise de dados a partir da base de uma indústria automobilística, com foco em auxiliar na **tomada de decisões estratégicas**.

## 🏗️ Arquitetura Utilizada

O projeto foi estruturado utilizando a **Arquitetura em Camadas (Medalhão)**, que organiza os dados em três níveis:

- **Bronze:** Dados brutos, ingestão sem transformação.
- **Silver:** Dados tratados, limpos, com validações e padronizações aplicadas.
- **Gold:** Dados prontos para análise e geração de insights, com cálculos, agregações e métricas de negócio.

## 🔧 Tecnologias e Ferramentas

- Databricks (PySpark)
- Spark SQL
- Delta Lake
- Python (Pandas, Matplotlib, Seaborn para visualização)

## ⚙️ Etapas do Projeto

1. **Ingestão de Dados:** Carregamento das tabelas brutas (Pedidos e Notas Fiscais).
2. **Engenharia de Dados:** 
   - Tratamento de tipos (datas, valores numéricos).
   - Remoção de duplicados e registros inconsistentes.
   - Criação de tabelas no nível Silver.
3. **Modelagem Analítica:**
   - Cálculo de métricas, como o **tempo médio de faturamento por estado**.
   - Junção de tabelas e geração de indicadores chave.
4. **Análise e Visualização:** 
   - Criação de gráficos e dashboards exploratórios.
   - Apoio na tomada de decisão baseada em dados.

## 📈 Resultado Esperado

Geração de insights que apoiam áreas estratégicas da empresa, como:

- Monitoramento da eficiência do processo de faturamento.
- Identificação de gargalos operacionais.
- Suporte à melhoria dos processos logísticos e comerciais.

## 💡 Objetivo Final

Demonstrar na prática como a engenharia e análise de dados, aliadas à arquitetura em camadas, podem transformar dados brutos em **informações valiosas para o negócio**, promovendo uma cultura data-driven dentro da organização.

> 📚 Projeto desenvolvido como parte da **Residência Tecnológica - RISEUP 2025.1**, em parceria com a empresa **NTT Data**, com foco no desenvolvimento de competências em engenharia de dados aplicada ao mercado.
