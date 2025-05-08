# Congresso USFC 2025 - Projeto de Pesquisa

Este repositório contém os scripts e dados do projeto de pesquisa apresentado no Congresso USFC 2025, realizado no âmbito do Mestrado em Contabilidade do Programa de Pós-Graduação em Contabilidade da UFSC. 

## Arquivos do Projeto

### Scripts
- **Script_artigo.ipynb**: Contém os 8 scripts principais usados na pesquisa, abrangendo etapas como triagem de metadados, classificação semântica (usando embeddings BERT) e análise de coerência.
- **Script_tempo.ipynb**: Calcula o tempo de execução de cada script do projeto.

### Dados de Entrada
- **Portfolio_metadados.xlsx**: ultrapassa o limite de 25 MB do GitHub e não pôde ser disponibilizado aqui. Se precisar desse arquivo, entre em contato.
- **SJR_2023.xlx**: dados das revistas indexadas nas Scopus. 

### Arquivos de Saída
- **1 Portfolio_analítico.xlsx**: Portfólio analítico final após as etapas de triagem (ver Tabela 1).
- **2 Keyword_analítico.xlsx**: Dados relacionados às palavras-chave extraídas do portfólio analítico.
- **2a top15_keywords.png**: Gráfico das 15 palavras-chave mais frequentes.
- **3 Dicionario_Contabilidade_Gerencial.xlsx**: Dicionário temático de contabilidade gerencial.
- **3a debug_dicionário_scores.xlsx**: Scores de similaridade para depuração do dicionário.
- **3b suggest_terms.xlsx**: Termos sugeridos com base na análise.
- **4 Portfolio_analítico_classificado.xlsx**: Portfólio analítico com classificação final.
- **5 Portfolio_analítico_coerência.xlsx**: Portfólio analítico com scores de coerência entre títulos e resumos.
- **5a Validação_manual_das_Revistas_(manual).xlsx**: Validação manual das revistas.
- **5b Portfolio_analítico_coerência_(ajustado_manual).xlsx**: Portfólio analítico ajustado após validação manual.
- **5c_Boxplot_coerência.png**: Boxplot dos scores de coerência (ver Figura 3).
- **5d_Histograma_coerência.png**: Histograma dos scores de coerência (ver Figura 3).
- **6 H1ab_Regressão_OLS_Resultados.xlsx**: Resultados da regressão OLS para a hipótese H1ab.
- **6a H1ab_Resumo_Por_País.xlsx**: Resumo dos resultados da H1ab por país.
- **6b H1ab_Heatmap_Top20_Países.png**: Heatmap dos 20 principais países para a H1ab.
- **7 H2ab_Regressão_OLS_Resultados.xlsx**: Resultados da regressão OLS para a hipótese H2ab.
- **7b H2ab_Heatmap_Top20_Países.png**: Heatmap dos 20 principais países para a H2ab.
- **8 H3ab_Regressão_Comparativa_Resultados_(1).xlsx**: Resultados comparativos da regressão para a hipótese H3ab.
- **8a H3ab_Resumo_Por_Coerência.xlsx**: Resumo dos resultados da H3ab por nível de coerência.

## Observações
Os scripts foram desenvolvidos e executados no ambiente virtual VLAB@UFSC (supercomputadores para pesquisas com inteligência artificial)
Para mais detalhes sobre a metodologia, resultados e contexto do projeto, consulte o artigo apresentado no Congresso USFC 2025.

**Nome do artigo**: COERÊNCIA COMUNICACIONAL NA PESQUISA CONTÁBIL: ANÁLISE AUTOMATIZADA DE 30 ANOS DE PUBLICAÇÕES NA CONTABILIDADE GERENCIAL
O estudo realiza análises replicáveis sobre a coerência comunicacional na produção científica em Contabilidade Gerencial, utilizando Python, PLN (Processamento de Linguagem Natural) e classificação temática. O projeto está alinhado ao Objetivo de Desenvolvimento Sustentável (ODS) 4 – Educação de Qualidade.
