# Dashboard de Recursos Humanos (RH) – Visão Geral Anual no Power BI

![Dashboard RH Power BI Preview](dashboard-rh-pbi-preview.png)  
<img width="1277" height="719" alt="image" src="https://github.com/user-attachments/assets/bed24f68-38ac-42c8-9605-c73367e306c9" />


Um dashboard interativo e profissional de **Recursos Humanos / People Analytics** construído no **Microsoft Power BI**, com visão anual consolidada de indicadores chave de RH.

### Principais Indicadores e Visualizações
- **Headcount Total**: 14 colaboradores (distribuição por gênero via donut chart: ~35,71% Feminino / 64,29% Masculino)
- **Turnover Anual**: 7,14%
- **Novos Funcionários**: 15 admissões
- **Desligamentos**: 1
- **Média de Idade**: 47 anos
- **Avaliação de Desempenho Média**: 3,90 (com setas de tendência ↑ ↓ → por colaborador)
- **Totais Financeiros (Payroll)**:
  - Salários Totais: R$ 282.944,00
  - Benefícios Totais: R$ 31.613,80
  - Bônus Totais: R$ 20.874,00
- **Salários por Área**: Gráfico de colunas (Comercial como maior, seguido de Produção, Marketing e Finanças)
- **Salários por Cargo**: Barras horizontais destacando Gerente, Operador, Diretor, Estagiário, Analista etc.
- **Lista Detalhada de Colaboradores**: Tabela com Nome, Cargo, Área, Avaliação e ícones de tendência
- **Seletor de Ano Histórico**: Slicer para comparar 2015–2019 (evolução dinâmica de KPIs)

Tudo altamente interativo: slicers/filtros por ano, drill-down em gráficos, tooltips personalizados, layout clean com tema corporativo (teal) e cards KPI para impacto visual imediato.

### Contexto do Projeto
Este dashboard foi desenvolvido como exercício prático durante o curso **Formação / Curso de Power BI** da **Yto Nihon Treinamentos** (escola referência em treinamentos de Excel, Power BI, Data Analytics e mais, com conteúdos práticos e atualizados – site oficial: [grupoytonihon.com.br](https://grupoytonihon.com.br/)).

O curso (com foco em modelagem de dados, DAX, visualizações avançadas e criação de dashboards reais) me permitiu aplicar conceitos diretamente em um cenário de RH: manipulação de dados de colaboradores, cálculos de turnover/média, payroll e visualizações gerenciais.

Montado rapidamente a partir de uma base limpa, demonstra skills reais em Power BI para análises de People Analytics sem necessidade de ferramentas extras.

### Tecnologias Utilizadas
- **Microsoft Power BI Desktop** (versão atual recomendada)
- Funcionalidades chave:
  - Modelagem de dados (relacionamentos entre tabelas)
  - Medidas DAX para KPIs (ex: média de avaliação, turnover %, totais condicionais)
  - Visuais nativos: Cards, Donut/Pie, Column Chart, Bar Chart, Table/Matrix
  - Slicers (para ano e possivelmente outros filtros)
  - Formatação condicional (ícones de tendência)
  - Tema personalizado e layout responsivo

### Como Usar / Replicar
1. Clone ou baixe o repositório.
2. Abra o arquivo `Dashboard_RH_Anual.pbix` no Power BI Desktop.
3. Atualize a fonte de dados (se necessário) na aba "Transformar Dados" (Power Query) – mantenha colunas como Nome, Cargo, Área, Ano, Salário, Avaliação, Gênero.
4. Refresh e explore! Todos os visuais atualizam automaticamente.

### Estrutura do Repositório
- `Dashboard_RH_Anual.pbix` → Arquivo principal do relatório Power BI
- `dados_rh_exemplo.xlsx` ou `.csv` → Base de dados fictícia para testes/replicação
- `dashboard-rh-pbi-preview.png` → Captura de tela para visualização rápida

### Ideias de Melhoria / Próximos Passos
- Adicionar previsões de turnover com DAX + What-If Parameters
- Incluir análise de diversidade, absenteísmo ou custo por colaborador
- Publicar no Power BI Service para compartilhamento e alertas
- Integrar com fontes reais (SQL, Excel online, API de RH)
- Versão mobile-optimized ou com bookmarks para navegação guiada

Sinta-se à vontade para fork, adaptar ao seu contexto de RH e contribuir com pull requests! Feedbacks sobre layout, DAX ou melhorias são bem-vindos. 😊

Feito com 💙 por **Cristiano** | Fevereiro 2025

#PowerBI #DashboardRH #PeopleAnalytics #RecursosHumanos #AnaliseDeDados #YtoNihon #PowerBI #DataAnalytics #Portifolio #BusinessIntelligence# Dashboard-de-Recursos-Humanos-RH-Vis-o-Geral-Anual-no-Power-BI
