# Trabalho Prático — Introdução à Ciência de Dados

> Projeto desenvolvido como atividade prática da disciplina Introdução à Ciência de Dados (ICD) da Universidade Federal de Minas Gerais (UFMG).

## Descrição

Este notebook apresenta o desenvolvimento de um trabalho prático de análise de dados, com foco na aplicação dos conceitos fundamentais de estatística descritiva, visualização e inferência.   O objetivo é explorar um conjunto de dados real, realizar tratamento, análise exploratória e interpretação dos resultados, integrando teoria e prática da disciplina.

O projeto analisa o progresso global em direção aos Objetivos de Desenvolvimento Sustentável (ODS) propostos pela Organização das Nações Unidas (ONU).   Por meio de métodos estatísticos, visualizações exploratórias e modelagem preditiva, o estudo busca compreender tendências, disparidades regionais e correlações entre os 17 objetivos, utilizando dados oficiais do Sustainable Development Report 2024. O trabalho também avalia a viabilidade de alcance das metas até 2030, explorando como fatores socioeconômicos, geográficos e políticos influenciam o desempenho global em sustentabilidade.

## Objetivos

- Aplicar técnicas de análise exploratória de dados (EDA);  
- Desenvolver a capacidade de interpretação estatística e visual dos resultados;
- Analisar tendências globais e regionais no desempenho dos ODS.  
- Investigar fatores determinantes — como PIB, alfabetização, inovação e segurança.  
- Modelar previsões temporais para estimar o progresso até 2030.  
- Interpretar inter-relações entre os ODS**, identificando sinergias e trade-offs.

## Dados e Fontes

Os dados foram obtidos a partir de fontes públicas e relatórios oficiais:

- **Sustainable Development Report 2024 (SDSN)** — indicadores de 192 países.  
- **World Bank GDP Rankings (2024)** — Produto Interno Bruto (PIB) de 96 países.  
- **Backdated SDG Index Scores (2000–2024)** — séries históricas de 83 países.  

Os conjuntos de dados foram processados e integrados, garantindo consistência e completude. Países sem pontuações nos ODS foram excluídos para evitar vieses.

## Metodologia

### 1. **Pré-processamento**
O primeiro passo da análise consistiu no pré-processamento dos dados, etapa essencial para garantir a qualidade e consistência das informações utilizadas. Inicialmente, foram identificados e removidos países com ausência total de dados, de modo a evitar vieses estatísticos. Em seguida, as colunas dos diferentes conjuntos de dados foram normalizadas e padronizadas, permitindo comparações diretas entre indicadores. Também foram detectados e tratados *outliers* por meio do método do intervalo interquartil, assegurando a robustez das análises subsequentes. Por fim, os dados do Produto Interno Bruto (PIB) foram integrados aos indicadores dos ODS, alinhando registros por país e consolidando uma base única e confiável para o estudo.

### 2. **Análise Exploratória de Dados (EDA)**
Com os dados tratados, realizou-se uma análise exploratória detalhada para compreender as principais características e distribuições dos indicadores globais. Foram calculadas estatísticas descritivas e medidas de dispersão, como média, desvio padrão e variância, complementadas por visualizações gráficas — boxplots, histogramas e mapas temáticos — que auxiliaram na identificação de padrões e discrepâncias. A análise de correlação entre os ODS e variáveis socioeconômicas, como PIB e taxa de alfabetização, revelou interdependências significativas entre metas sociais, ambientais e econômicas. Além disso, testes de hipóteses foram empregados para investigar desigualdades regionais, como o caso da sub-representação de países africanos entre aqueles que erradicaram a pobreza, confirmando a relevância estatística dessas disparidades.

### 3. **Modelagem Preditiva**
Na etapa final, foi desenvolvida uma modelagem preditiva com o objetivo de projetar o progresso dos países em relação aos ODS até 2030. Utilizou-se regressão linear simples aplicada às séries temporais compreendidas entre 2000 e 2024, permitindo identificar tendências de crescimento ou declínio. Para garantir a confiabilidade das previsões, os dados foram divididos em conjuntos de treinamento e teste (80/20), sendo o desempenho avaliado por meio do Erro Quadrático Médio (MSE). Apenas os modelos com MSE inferior a 0,5 foram considerados adequados para projeções futuras. Essa abordagem possibilitou estimar, com base em tendências históricas estáveis, quais objetivos apresentam maior probabilidade de avanço e quais exigem atenção redobrada na próxima década.

## Principais Resultados

A análise evidenciou uma tendência global de progresso em relação aos Objetivos de Desenvolvimento Sustentável (ODS), embora com desigualdades regionais marcantes. Países do Norte Global apresentaram melhores desempenhos gerais, enquanto regiões como a África Subsaariana e o Oriente Médio ainda enfrentam desafios em metas como erradicação da pobreza e igualdade de gênero. As correlações mostraram que ODS sociais e ambientais estão positivamente associados, enquanto ODS econômicos e ambientais exibem trade-offs, refletindo a dificuldade de conciliar crescimento e sustentabilidade. Fatores como alfabetização, inovação e segurança se destacaram como determinantes do bom desempenho nacional. As previsões baseadas em regressão linear indicam que, embora o mundo avance rumo às metas de 2030, o ritmo atual é insuficiente para cumpri-las integralmente, reforçando a importância de políticas integradas e cooperação internacional.

## Tecnologias e Ferramentas utilizadas

- **Python 3.x**
- **Pandas** — manipulação e limpeza de dados  
- **NumPy** — operações numéricas  
- **Matplotlib / Seaborn** — visualização gráfica  
- **Scikit-learn** — ferramentas básicas de aprendizado de máquina (se aplicável)  
- **Jupyter Notebook** — ambiente de desenvolvimento

---

## Conclusão

O estudo evidencia que o mundo está avançando rumo ao desenvolvimento sustentável, porém em ritmo desigual. O progresso depende de integração entre políticas sociais, econômicas e ambientais bem como da melhoria da coleta de dados e da governança global. As análises fornecem subsídios para formuladores de políticas públicas e pesquisadores que buscam compreender os desafios e oportunidades da Agenda 2030.

---
## Autoria

**Bruna Luiza M. Santos**, **Giovanni Russo Paschoal**, **Layla Raissa S. Pereira**, **Lucas da S. Santos**  
📍 Departamento de Ciência da Computação — **Universidade Federal de Minas Gerais (UFMG)**  

---
