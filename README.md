# 🚀 Automação de Análise de EPIs: Do Relatório Visual à Inteligência de Dados

Este projeto resolve um problema real de gestão operacional: a transformação de relatórios de sistema desestruturados (focados em impressão) em uma base de dados tabular e analítica para tomada de decisão.

## 📋 Contexto e Desafio
A demanda surgiu quando a gerência solicitou indicadores sobre a distribuição mensal de Equipamentos de Proteção Individual (EPIs). O sistema nativo da empresa gerava apenas um relatório visualmente complexo, com:
- Dados espalhados por células isoladas (Setor e Nome do Funcionário).
- Cabeçalhos repetidos e linhas de totais intercaladas.
- Impossibilidade de realizar cálculos financeiros ou agrupamentos diretos.

## 💡 A Solução
Desenvolvi um pipeline em **Python** que automatiza todo o processo de ETL (Extração, Tratamento e Carga). O código lê o arquivo "caótico", identifica os padrões de cada colaborador e setor, e reconstrói a estrutura de dados de forma tabular.

### Tecnologias Utilizadas:
* **Python 3.x**
* **Pandas**: Manipulação de dados e reestruturação de layouts.
* **NumPy**: Lógica de processamento de vetores e limpeza de ruídos.
* **Matplotlib**: Geração de gráficos para visualização de indicadores.
* **Google Colab**: Ambiente de desenvolvimento.

## 📈 Resultados Alcançados
O projeto automatizou três perguntas fundamentais para a gerência:
1.  **Consumo por Setor:** Identificação de onde estão os maiores volumes de entrega.
2.  **Consumo por Colaborador:** Controle individual de trocas de equipamentos.
3.  **Análise Financeira:** Visão detalhada do investimento real por tipo de EPI.

**Impacto:** Redução do tempo de tratamento de dados de **horas de trabalho manual** para **poucos segundos** de execução, com 100% de precisão nos cálculos.

## ⚖️ LGPD & Privacidade
Em conformidade com a Lei Geral de Proteção de Dados, o projeto inclui uma etapa de **anonimização**. Nomes de colaboradores e registros reais foram substituídos por identificadores genéricos via script, garantindo que o portfólio apresente a solução técnica sem expor dados sensíveis.

## 📁 Estrutura do Repositório
- `Projeto_EPI.ipynb`: Notebook com o código completo e documentado.
- `PLANILHA_EPI_ANONIMIZADA.csv`: Exemplo da base de dados após o tratamento.
- `Relatorio_Consolidado.xlsx`: Resultado final exportado com as análises prontas.

---
Desenvolvido por: Luiz Filipe Avila - Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/luiz-filipe-avila/)
