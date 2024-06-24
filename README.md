# Séries Temporais com Google Sheets e Python! 📆

![image](https://github.com/nayara-lucia/series_temporais/assets/126920974/0dc6a51e-a96f-4ae8-a93b-611be3efb494)

Link: <i>https://docs.google.com/spreadsheets/d/1SGtzI8vNN5NDb7dDr0E8mlSVPNEXas_7_wWnIekVFUQ/</i>

### 🟡 Etapas:
1. Importação dos Dados
    - Importação da base do arquivo vendas_loja.csv para o Google Sheets.

3. Cálculo da Média Móvel Centrada
    - Calculo da média móvel centrada de 12 e 3 meses para os dados de vendas.
    - Criação da nova coluna chamada "Média Móvel Centrada" e valores calculados.

4. Cálculo do Índice Sazonal
    - Calculo do índice sazonal para cada mês.
    - Calculo do índice sazonal do intervalo de 12 meses.

5. Ajuste dos Dados para Remover a Sazonalidade
    - Ajuste dos dados de vendas para remover os efeitos da sazonalidade com Python utilizando a biblioteca statsmodels e importando a função seasonal_decompose, utilizamos o método seasonal.
    - Criação da nova página com os novos dados e coluna chamada "Vendas Ajustadas" e preencha com os valores ajustados.
    - ![image](https://github.com/nayara-lucia/series_temporais/assets/126920974/7e7ff385-a18b-4ac4-a95a-aa41191713c4)

6. Avaliação da Qualidade das Previsões
    - Utilizando a técnica da média móvel centrada para prever as vendas dos próximos 12 meses.
    - Calculo do erro absoluto médio (MAE) das previsões.
