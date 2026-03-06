# 🛡️ DataSafe: Inteligência de Dados e Automação de EPIs

Este projeto resolve um problema real de gestão operacional: a transformação de relatórios de sistema desestruturados (focados em impressão) em uma solução completa de **Business Intelligence (BI)**, integrando automação com Python e visualização estratégica.

## 📋 Contexto e Desafio
A demanda surgiu quando a gerência solicitou indicadores sobre a distribuição mensal de Equipamentos de Proteção Individual (EPIs). O sistema nativo da empresa gerava apenas um relatório visualmente complexo, com:
- Dados espalhados por células isoladas (Setor e Nome do Funcionário).
- Cabeçalhos repetidos e linhas de totais intercaladas.
- Impossibilidade de realizar cálculos financeiros ou agrupamentos diretos.

## 💡 A Solução: O Pipeline DataSafe
Desenvolvi um ecossistema de dados que executa o ciclo completo de **ETL (Extração, Tratamento e Carga)** e **Visualização**:

1. **Engine de Dados (Python):** O script lê o arquivo bruto "caótico", identifica os padrões de cada colaborador/setor e reconstrói a estrutura de dados de forma tabular e limpa.
2. **Camada de Inteligência (Power BI):** Os dados tratados alimentam um dashboard interativo, onde métricas complexas e KPIs são calculados automaticamente.

### Tecnologias Utilizadas:
* **Python (Pandas & NumPy)**: Manipulação de dados, limpeza de ruídos e automação do layout.
* **Power BI (DAX)**: Modelagem de dados relacionais e criação de indicadores de performance.
* **Google Colab**: Ambiente de desenvolvimento e documentação do script de ETL.

## 📈 Resultados e Insights Gerados
A solução final entrega previsibilidade e eficiência para a gestão:
* **Automação de Tempo:** Redução do tratamento de dados de **horas de trabalho manual** para **poucos segundos** de execução.
* **Análise de Curva ABC:** Identificação automática dos itens com maior impacto financeiro e volume de consumo.
* **Visão 360º:** Navegação dinâmica por setor, colaborador e período, permitindo auditorias rápidas e precisas.
* **Cultura Data-Driven:** Substituição de estimativas manuais por dados exatos de investimento real e necessidade de reposição.

## ⚖️ LGPD & Privacidade
Em conformidade com a Lei Geral de Proteção de Dados, o projeto inclui uma etapa rigorosa de **anonimização**. Nomes de colaboradores e registros reais foram substituídos por identificadores genéricos e dados fictícios via script, garantindo que o portfólio apresente a solução técnica sem expor dados sensíveis.

## 📁 Estrutura do Repositório
- `DataSafe_ETL.ipynb`: Notebook com o código Python de tratamento completo.
- `DataSafe_Dashboard.pbix`: Arquivo do Power BI com a interface de visualização final.
- `Base_Anonimizada.csv`: Exemplo da base de dados tabular após o tratamento.

---
Desenvolvido por: **Luiz Filipe Avila** - Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/luiz-filipe-avila/)
