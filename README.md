# 🏭 INDUSTRIAL ANALYTICS
### 📊 Integração entre Manutenção, Confiabilidade, Produção, Energia e Processo

<text>**Projeto acadêmico | Dados sintéticos gerados por IA generativa**</text>

**Data Analytics | Industrial Analytics | Maintenance | Reliability | Energy | Business Intelligence**

---

## 🎯 Objetivo do Projeto

Desenvolver uma análise integrada de dados industriais para investigar os fatores associados ao desempenho operacional, à confiabilidade dos equipamentos, ao consumo energético e às perdas de produção.

O projeto utiliza uma base de dados sintética, gerada com auxílio de IA generativa, estruturada para simular cenários industriais e permitir a aplicação de técnicas de análise estatística, exploração de dados e visualização de indicadores.

A proposta é conectar diferentes áreas da operação para compreender como falhas, condições de processo, disponibilidade e desempenho produtivo podem estar associados ao consumo de energia e aos custos industriais.

## ⚙️ Variáveis analisadas

A base contempla variáveis operacionais, produtivas, energéticas e de manutenção:

- 🔄 Turno de operação.
- 🌡️ Temperatura de processo.
- 💨 Pressão de processo.
- ⚡ Corrente elétrica.
- 🏎️ Velocidade operacional.
- 🏋️ Carga do equipamento.
- 📳 Vibração.
- 📦 Volume produzido.
- ⏱️ Horas de operação.
- 📈 Performance.
- 🟢 Disponibilidade.
- 🔋 Uso e consumo de energia.
- 📉 Perdas de produção.
- 💰 Custos de manutenção e perdas.

---

## 🗄️ Estrutura do Banco de Dados

O modelo foi organizado em tabelas dimensionais e tabelas fato, permitindo relacionar diferentes processos e indicadores industriais.

### 📚 Tabelas dimensionais

- `DIM_MAQUINA` – Cadastro e identificação dos equipamentos.
- `DIM_CAUSA_RAIZ` – Classificação das causas de falhas e ocorrências.

### 📊 Tabelas fato

- `FAT_MANUTENCAO` – Registros de falhas, intervenções e manutenção.
- `FAT_PRODUCAO` – Volume produzido e indicadores produtivos.
- `FAT_ENERGIA` – Consumo e indicadores de desempenho energético.
- `FAT_PROCESSO` – Variáveis operacionais e condições do processo.
- `FAT_PERDAS` – Refugos, perdas e impactos operacionais.
- `FAT_ACAO_MELHORIA` – Ações corretivas, preventivas e oportunidades de melhoria.

Essa estrutura permite explorar relacionamentos entre as tabelas e desenvolver análises integradas, evitando tratar cada indicador de forma isolada.

---

## 🔗 1. Integração entre Manutenção, Produção e Energia

📌 **Objetivo:** investigar a relação entre confiabilidade dos equipamentos, desempenho produtivo e consumo energético.

A análise foi estruturada para explorar a seguinte cadeia:

**Falhas → MTBF → MTTR → Disponibilidade → Produção → Energia → Perdas → Causa raiz → Ação de melhoria**

Essa abordagem permite investigar questões como:

- 🔧 Como as falhas e intervenções de manutenção se relacionam com a disponibilidade?
- ⏱️ Como o tempo de parada pode afetar a produção?
- ⚡ Como as condições operacionais podem estar associadas ao consumo energético?
- 📉 Quais situações apresentam maior ocorrência de perdas?
- 🔍 Quais causas aparecem com maior frequência?
- 🎯 Quais ações de melhoria devem ser priorizadas?

O objetivo é construir uma visão sistêmica da operação industrial, conectando indicadores que normalmente são analisados separadamente.

---

## 📈 2. Análise Estatística e Modelagem

Foram aplicadas técnicas estatísticas para investigar relações entre as variáveis e identificar possíveis padrões nos dados.

### 🧮 Técnicas utilizadas

- **Regressão múltipla:** investigação da associação entre variáveis independentes e uma variável de interesse, como consumo energético.
- **Correlação de Pearson:** avaliação da intensidade e direção das relações lineares entre variáveis quantitativas.
- **Análise de resíduos:** avaliação das diferenças entre valores observados e previstos pelos modelos.
- **Estatística descritiva:** exploração de médias, dispersões e comportamento das variáveis.
- **Tabelas dinâmicas:** comparação de indicadores sob diferentes perspectivas operacionais.

### 🔍 Análise exploratória

Também foram utilizadas:

- 🎨 Formatação condicional com escalas de cores para destacar valores potencialmente críticos ou favoráveis.
- 📊 Filtros e segmentações de dados.
- 📋 Tabelas dinâmicas para cruzamento de variáveis.
- 🔗 Relacionamento entre indicadores de diferentes áreas.

As escalas de cores foram utilizadas como recurso visual de investigação, não como classificação automática de desempenho ou comprovação de causa.

---

## 🛠️ 3. KPIs – Indicadores de Desempenho Industrial

O projeto contempla indicadores de manutenção, confiabilidade, produção, energia e perdas.

### 🔧 Manutenção e confiabilidade

| Indicador | Descrição |
|---|---|
| MTBF | Mean Time Between Failures – Tempo Médio Entre Falhas |
| MTTR | Mean Time To Repair – Tempo Médio Para Reparo |
| MTTD | Mean Time To Detect – Tempo Médio Para Detectar |
| MTDA | Mean Time to Action – Tempo Médio Para Agir |
| Disponibilidade | Percentual de tempo em que o equipamento está disponível |

### 🏭 Produção e eficiência

- 📦 Volume produzido.
- 📈 Performance.
- 🟢 Disponibilidade.
- ⚙️ OEE – Overall Equipment Effectiveness.
- 🔨 Refugo.
- ⏱️ Horas de parada.

### ⚡ Energia

- 🔋 Consumo energético (kWh).
- 📊 Consumo específico (kWh/peça).
- 📉 Relação entre energia, produção e condições operacionais.

### 💰 Custos e perdas

- 🔧 Custo de manutenção.
- 📉 Custo de perdas produtivas.
- 🏭 Impacto financeiro das paradas.
- 🥇 Pareto de causas de falhas e perdas.

---

## 📊 4. Dashboards em Excel

Foram desenvolvidos **10 dashboards em Excel**, com o objetivo de apresentar diferentes perspectivas da operação industrial.

### Recursos implementados

- 📊 Indicadores e gráficos gerenciais.
- 🎛️ Segmentações de dados.
- 🔍 Filtros para exploração dos indicadores.
- 🔗 Links de navegação e interligação entre os dashboards.
- 📈 Comparação de indicadores operacionais.
- 🎨 Recursos visuais para identificação de potenciais desvios e oportunidades de investigação.

A estrutura permite navegar entre diferentes visões da operação, conectando manutenção, produção, energia, processo, perdas e causa raiz.

---

## 📉 5. Power BI – Business Intelligence

Além das análises em Excel, foi desenvolvido um projeto em Power BI para ampliar a exploração visual dos dados industriais.

### Recursos desenvolvidos

- 📊 Visualizações gráficas de indicadores.
- 🎛️ Segmentações e filtros interativos.
- 🔎 Análise de diferentes variáveis operacionais.
- 📈 Comparação de indicadores e identificação de padrões.
- 🔗 Exploração integrada das informações disponíveis na base.

O Power BI complementa as análises realizadas no Excel, oferecendo uma experiência de exploração visual e interativa dos dados.

---

## 🧠 6. Competências demonstradas

| Área | Conhecimentos aplicados |
|---|---|
| 📊 Data Analytics | Tratamento, exploração e interpretação de dados |
| 🏭 Industrial Analytics | Integração de indicadores industriais |
| 🔧 Maintenance | Análise de falhas e intervenções |
| 📈 Reliability | MTBF, MTTR e disponibilidade |
| ⚡ Energy Analytics | Consumo e desempenho energético |
| 🏗️ Production Analytics | Produção, performance e OEE |
| 🔍 Root Cause Analysis | Investigação e Pareto de causas |
| 🧮 Statistics | Correlação, regressão e resíduos |
| 📊 Business Intelligence | Dashboards, filtros e visualizações |
| 🗄️ Data Modeling | Estruturação de tabelas fato e dimensão |

---

## 💡 7. Conclusão

O projeto demonstra como a integração de dados de diferentes áreas industriais pode ampliar a capacidade de análise e apoiar a tomada de decisão.

Ao conectar manutenção, confiabilidade, produção, energia, processo e perdas, torna-se possível investigar relações que dificilmente seriam percebidas quando cada indicador é analisado isoladamente.

A proposta vai além da construção de gráficos: busca transformar dados operacionais em informações úteis para identificar oportunidades, direcionar investigações e apoiar ações de melhoria contínua.

**A análise de dados industriais não deve apenas mostrar o que aconteceu, mas ajudar a investigar por que aconteceu e onde atuar para melhorar os resultados.**

---

## ⚠️ Observação sobre os dados

Este projeto utiliza dados sintéticos gerados com auxílio de IA generativa, exclusivamente para fins acadêmicos, didáticos e de demonstração de competências técnicas.

As relações identificadas representam padrões presentes na base simulada e não devem ser interpretadas como comprovação de causalidade ou como resultados reais de uma instalação industrial.

---

## 🛠️ Ferramentas utilizadas

- 🟩 Microsoft Excel.
- 🗄️ Power Pivot.
- 🟨 Microsoft Power BI.
- 📊 Análise estatística e regressão.
- 🤖 IA generativa para apoio à criação da base sintética.

**Projeto acadêmico | Industrial Analytics | Data Analytics | Business Intelligence**
