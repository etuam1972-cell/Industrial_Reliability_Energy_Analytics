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

📌 **Objetivo
