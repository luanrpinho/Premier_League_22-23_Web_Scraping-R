<p align="center">
    <img src="https://logowik.com/content/uploads/images/premier-league-lion8499.jpg" alt="Logo da Premier League" width="200px">
</p>
<div align="center">
  <h1>Premier League 2022/2023</h1>
</div>
<br/>

## Objetivo:
- Este projeto tem como objetivo criar uma tabela da Premier League, uma das ligas de futebol mais prestigiadas e renomadas do mundo por meio de web scraping e posteriormente realizar uma visualização utilizando o Power BI.
<br/>

## Etapas do projeto:
- **Web Scraping:** foi feito a coleta por web scraping na linguagem R no Google Colab, para reunir os dados necessários para o projeto.
- **Limpeza dos dados:** todos os dados extraídos passaram por um processo de limpeza e preparação para garantir sua qualidade.
- **Visualização:** com os dados prontos, foi utilizado o Power BI Desktop para fazer os gráficos e outras visualizações.
<br/>

## Visualização dos dados:
1. **Desempenho geral - Gráfico de barras 100% empilhadas e Gráfico de Funil:**
   - Com um total de 380 partidas, 1084 gols marcados no total e média de 2,85 gols por jogo.
   - A média por equipe foi de 14,6 vitórias, 8,7 empates e 14,6 derrotas. 
   - **Manchester City** liderou a tabela com uma marca impressionante de 28 vitórias em 38 partidas. Com 73,7% de aproveitamento.
   - **Southampton** ficou em último com apenas 6 vitórias em 38 partidas. Com 15,8% de aproveitamento.
     
![Vitórias, empates e derrotas](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/fb9cacba-c9c5-41ae-b968-37bef325d545)

![Aproveitamento](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/0abf19de-fafe-474d-9edf-69d1da67a86d)
-----

2. **Ataque - Gráfico de Bolhas:**
    + *Números do gráfico* 
       - **Eixo X:** representa o número de gols marcado por cada equipe.
       - **Eixo Y:** representa a posse de bola de cara equipe em (%).
       - **Tamanho das bolhas:** representa a média de número de gols previstos de cada time.

    + *Desempenho do ataque* 
       - **Manchester City** lidera o gráfico com o total de 94 gols marcados, 78,6 de gols previstos e 64,7 % de posse de bola em média.
       - **Wolves** tem o pior ataque com 31 gols marcados, 50 % de posse de bola em média e 36,8 de gols previstos, porém o **Nottingham Forest** marcou 38 gols e teve a pior média de posse de bola com 37,6 % e teve 39,3 de gols previstos.
       - 
![Ataque](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/c9bf832a-ae4c-4d70-8831-b10510b0f779)

-----

3. **Defesa - Gráfico de Bolhas:**
    + *Números do gráfico* 
        -	**Eixo X:** representa o número de gols tomados por cada equipe.
        -	**Eixo Y:** representa a média de gols previstos permitidos.
        -	**Tamanho das bolhas:** representa o número de derrotas de cada time.

    + *Desempenho da defesa* 
        - **Leeds Utd** tem a pior defesa com 78 gols sofridos e 67,2 em média de gols previstos.
        - **Manchester City** e **Newcastle Utd** tem a melhor defesa com o total de 33 gols sofridos e 5 derrotas, porém o **Newcastle Utd** tem maior média de gols previstos permitidos com 39,6 contra 32,1 do **Manchester City**.

![Defesa](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/451cb9b5-2b43-464d-8c18-d1fb7afe6361)
-----

4. **Fair play – Gráfico de Barras:**
   - Com um total de 1423 cartões, sendo 1393 amarelos e 30 vermelhos e média de 3,7 cartões por jogo.
   - O time que teve menor número de cartões totais no campeonato foi o **West Ham** com 44 cartões amarelos e nenhum cartão vermelho, com média de 1,1 cartão por jogo. Manchester City ficou em 2º com 44 amarelos e 1 vermelho.
   -  Com 89 amarelos, 3 vermelhos e 92 cartões no total, o **Leeds United** teve o maior número de cartões no campeonato, com média de 2,4 cartões por jogo, seguido do **Wolves** com 91 cartões, sendo 85 amarelos e 6 vermelhos, em média de 2,3 cartões por jogo, sendo o time que teve o maior número de expulsões de toda a liga.
    
![Cartões amarelos e vermelhos](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/2a78ec2c-5576-443e-a589-9bbd25fc7356)
-----

5. **Média de idade e total de jogadores – Gráficos de Linhas**
   - Empatados com a maior média de idade da Premier League, estão os times do **Fulham** e **West Ham** com 28,2.
   - A menor média estão empatados **Arsenal** e **Southampton** com 24,7.
   - **Southampton** também está na lista de equipes com maior elenco, sendo 36 jogadores.
   - **Manchester City** tem o menor elenco da liga, 24 jogadores.

![Média de Idade](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/78130b7b-4372-469e-b02c-2a41b795d6b2)

![Número de Jogadores](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/c33be1a7-0d8f-4941-9705-d051d514f4f2)

-----

6. **Média de público - Gráfico Mapa de Árvore**
    + *As maiores médias de público do campeonato foram seguidamente de:* 
        - **Manchester Utd:** 73,671 pessoas.
        - **West Ham:** 62,462 pessoas.
        - **Tottenham:** 61,585 pessoas.

    + *As menores médias de público do campeonato foram seguidamente de:* 
        - **Fulham:** 23,746 pessoas.
        - **Brentford:** 17,078 pessoas.
        - **Bournemouth:** 10,362 pessoas.
          
    + Campeonato que teve média de 40,117 de torcedores por jogo.
  
![Público](https://github.com/luanrpinho/Premier_League_22-23_Web_Scraping-R/assets/156137815/c071806f-6693-4c46-b920-be2db277ac81)

----
<br/>

## Conjunto dos dados:
- Fonte: https://fbref.com/pt/.
<br/>

## Ferramentas utilizadas:
- **Linguagem R (Google Colab):** utilizei a linguagem R no ambiente do Google Colab para realizar web scraping no site que fornece informações sobre a Premier League.
- **Power BI Desktop:** utilizei o programa para fazer todos os gráficos do projeto.
<br/>

## Requisitos:
- R (de preferência no ambiente do Google Colab), [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb).
- Power BI, [Power BI](https://powerbi.microsoft.com/).
  <br/>
  
## Conclusão:
- A temporada da Premier League 2022/2023 se desenrolou como uma saga repleta de emoções e insights notáveis. O domínio impressionante do Manchester City e os desafios defensivos enfrentados pelo Leeds Utd, destaca a diversidade competitiva da liga. Uma temporada de futebol rica em estatísticas e narrativas.

*Até a próxima temporada de dados incríveis e descobertas emocionantes! ⚽📈🏟️*
