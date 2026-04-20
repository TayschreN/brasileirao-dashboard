# ⚽ Brasileirão - Análise de Dados

Projeto de análise de dados do Campeonato Brasileiro utilizando **Python + Power BI**, com foco em extrair insights sobre desempenho das equipes, padrões de jogo e tendências ao longo das temporadas.

---

![Dashboard](./dashboard.png)

---

##  Objetivo

Transformar dados brutos em **insights estratégicos** sobre o Brasileirão, analisando fatores como:

- Vantagem de jogar em casa
- Eficiência ofensiva
- Impacto financeiro dos elencos
- Influência do primeiro tempo no resultado final
- Evolução do público e do estilo de jogo

---

## Tecnologias Utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI
- Jupyter Notebook

---

## Etapas do Projeto

### 1. Coleta e preparação dos dados
- Leitura do dataset (`CSV`)
- Tratamento de valores nulos e inconsistências
- Criação de variáveis derivadas (feature engineering)

### 2. Feature Engineering
Foram criadas variáveis como:

- `resultado` → vencedor da partida  
- `total_gols` → intensidade ofensiva  
- `vitoria_mandante` → variável binária  
- `pressao_mandante` → volume ofensivo  
- `eficiencia_mandante` e `visitante`  
- `ganhou_1t` → desempenho no primeiro tempo  

### 3. Análise Exploratória (EDA)
- Distribuição de resultados
- Média de gols por temporada
- Evolução do público
- Relação entre chutes e gols
- Comparações entre mandante vs visitante

### 4. Visualização
- Gráficos em Python
- Dashboard interativo no Power BI

---

## Principais Insights:

### 🏠 Vantagem de jogar em casa
- ~49% das vitórias são de mandantes
- Apenas ~24% dos visitantes vencem
- Times da casa marcam mais gols em média

 O fator casa é um dos principais determinantes do resultado.

---

### 🧠 Importância do primeiro tempo
- Times que vencem o 1º tempo ganham ~79% das partidas
- Viradas são raras (~5%)

 Começar bem o jogo é decisivo.

---

### 💰 Impacto financeiro
- Times com maior valor de elenco:
  - 59% de vitórias
- Times com menor valor:
  - 43,7%

 Investimento tem forte correlação com desempenho.

---

### ⚽ Equilíbrio do campeonato
- Média de gols: ~2.2 a 2.8
- ~50% dos jogos com gols de ambos
- Alta taxa de empates

 Campeonato competitivo e equilibrado.

---

### 🏟️ Público e desempenho
- Jogos com maior público → mais vitórias do mandante

 Possível influência da torcida (correlação, não causalidade).

---

### 📉 Evolução do estilo de jogo
- 2003–2005: futebol mais ofensivo
- 2006–2018: consolidação defensiva
- 2019–atual: retomada ofensiva
