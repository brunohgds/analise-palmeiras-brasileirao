📊 Palmeiras Analytics | Brasileirão 2025–2026
📌 Sobre o projeto

Este projeto tem como objetivo analisar o desempenho da SE Palmeiras no Campeonato Brasileiro utilizando técnicas de análise de dados e Business Intelligence.

Os dados são obtidos por meio de uma API pública, tratados em Python e posteriormente modelados no Power BI, onde são transformados em dashboards interativos capazes de responder perguntas sobre desempenho ofensivo, defensivo e evolução da equipe ao longo das temporadas.

Além da análise completa da temporada de 2025, o projeto acompanha a campanha de 2026 (em andamento) e apresenta um comparativo entre as duas temporadas.

🎯 Objetivos
Analisar o desempenho do Palmeiras no Brasileirão.
Comparar indicadores entre temporadas.
Identificar pontos fortes e oportunidades de melhoria.
Desenvolver um projeto completo de análise de dados, desde a coleta até a visualização.

⚙️ Pipeline do projeto
Football-Data API
        │
        ▼
Extração dos dados (Python)
        │
        ▼
Tratamento e limpeza
        │
        ▼
Criação dos datasets (.csv)
        │
        ▼
Power BI
        │
        ▼
Dashboards e Insights

🛠 Tecnologias utilizadas
Python
Pandas
NumPy
Requests
Power BI
DAX
Modelagem de dados
Storytelling
Git & GitHub

📈 Dashboards
📄 Página 1 — Temporada 2025
Indicadores gerais
Desempenho em casa e fora
Eficiência ofensiva
Eficiência defensiva
Evolução da temporada
<img width="389" height="391" alt="2025" src="https://github.com/user-attachments/assets/0f525bf7-adf9-48b6-b5b4-18069b6a113a" />

📄 Página 2 — Temporada 2026 (em andamento)

Análise da campanha até a pausa para a Copa do Mundo.

Aproveitamento
Eficiência ofensiva
Eficiência defensiva
Evolução rodada a rodada
<img width="392" height="390" alt="2026" src="https://github.com/user-attachments/assets/fa478564-f91c-4147-8dde-412b8a58d18e" />

📄 Página 3 — Comparativo 2025 × 2026

Comparação das temporadas considerando a mesma quantidade de rodadas.

Principais indicadores:

Aproveitamento
Pontos por jogo
Vitórias (%)
Derrotas (%)
Gols marcados por jogo
Gols sofridos por jogo
Saldo de gols por jogo
<img width="515" height="391" alt="2025_x_2026" src="https://github.com/user-attachments/assets/f94967d8-8c7b-45f6-903f-ff07b1dc39fa" />

💡 Principais Insights
O Palmeiras apresenta melhor desempenho em 2026 quando comparado ao mesmo período de 2025.
A equipe aumentou seu aproveitamento e reduziu significativamente o percentual de derrotas.
A defesa sofreu menos gols por partida.
O saldo de gols por jogo também apresentou evolução.
O dashboard permite comparar temporadas utilizando a mesma quantidade de rodadas, garantindo uma análise justa.

📁 Estrutura do projeto
📂 data
    ├── brasileirao_2025.csv
    ├── brasileirao_2026.csv
    ├── palmeiras_historico.csv

📂 notebooks
    ├── pipeline_2025.ipynb
    ├── pipeline_2026.ipynb

📂 dashboard
    └── Analise_Palmeiras.pbix

📂 assets
    ├── dashboard_2025.png
    ├── dashboard_2026.png
    └── dashboard_comparativo.png

README.md

🚀 Competências demonstradas
Consumo de API REST
Limpeza e transformação de dados
Manipulação de dados com Pandas
Modelagem de dados
DAX
Storytelling com dados
Desenvolvimento de dashboards executivos
Versionamento com Git e GitHub

👨‍💻 Autor

Bruno Henrique Gonçalves da Silva
