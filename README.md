# Análise Exploratória de Dados de Jogos de Tabuleiro

Este repositório contém um projeto de **Ciência de Dados** focado em um conjunto de dados de jogos de tabuleiro. O objetivo foi explorar e entender as principais características dos jogos, suas tendências ao longo do tempo e as relações entre suas variáveis.

## Principais Etapas da Análise

- **Inspeção Inicial dos Dados:** Utilizamos o método `.info()` para verificar a estrutura do DataFrame, o tipo de dados de cada coluna e a presença de valores nulos.

- **Estatísticas Descritivas:** Geramos um resumo estatístico com o método `.describe()` para variáveis numéricas como `average_rating` (avaliação média) e `page_views` (tempo de jogo), o que nos deu uma visão geral de sua distribuição, média, mediana e outros valores importantes.

- **Identificação de Outliers:** Utilizamos o `boxplot` para visualizar a distribuição da coluna `page_views` e identificar valores atípicos, que representam jogos com um número excepcionalmente alto de visualizações.

- **Análise de Distribuição:** Criamos **histogramas** para entender a distribuição de variáveis-chave, como a `average_rating`. Notamos uma **assimetria negativa**, indicando que a maioria dos jogos tem notas altas, com poucas exceções de notas baixas.

- **Transformação de Dados:** Para lidar com a assimetria extrema da coluna `page_views`, aplicamos uma **transformação logarítmica**. Isso ajudou a normalizar a distribuição dos dados, tornando-os mais adequados para futuras análises.

- **Análise de Tendências:** Agrupamos os dados por década de lançamento para visualizar a **evolução da indústria de jogos de tabuleiro ao longo do tempo**, revelando um crescimento significativo no número de lançamentos nas últimas décadas.

- **Análise de Correlação:** Exploramos a relação entre variáveis numéricas, como `min_players` e `max_players`, usando **gráficos de dispersão** e **mapas de calor (heatmaps)**. A análise de correlação mostrou que, como esperado, o número mínimo de jogadores tem uma forte correlação positiva com o número máximo de jogadores.

Este projeto serve como um exemplo prático de como a análise de dados pode ser usada para extrair insights significativos de um conjunto de dados.
```
