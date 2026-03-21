# Apresentação: Proposta de Projeto

## Tema:
**Climate Change and Extreme Weather Events**

## Perguntas da Pesquisa:

- Qual foi a frequência, o dano econômico e a quantidade de mortes causadas por eventos climáticos extremos nos últimos 50 anos?
- Quais regiões (continentes) do mundo foram mais afetadas?
- Como as alterações climáticas (elevação da temperatura, emissões de gases do efeito estufa) estão relacionadas com os eventos extremos?

## Dados:

- Average monthly surface temperature
- Country level monthly temperature anomalies
- Economic damages from disasters as a share of gdp
- Number of deaths from natural disasters
- Per-capita greenhouse gas emissions

### Fonte:

- Our World in Data — ourworldindata.org/: Dados limpos em CSV prontos para uso derivados do EM-DAT.
- EM-DAT International Disaster Database — emdat.be: Dados mundiais sobre desastres naturais desde 1900.

### Informações:

**- Eventos extremos:** Das informações contidas no nosso dataset, escolhemos apenas os eventos que possam ter relação com as mudanças climáticas (Droughts, Floods, Storms, Extreme temperatures, Wildfires) e por serem os eventos mais representativos.
**- Período:** Escolhemos analisar o período de 50 anos, entre 1975 e 2024, que será dividido em dois períodos de 25 anos, de 1975 a 1999 e de 2000 e 2024.
**- Área geográfica:** Mundo -> Continentes: África, Ásia, América do Sul, América do Norte, Europa e Oceania. Alguns datasets estão divididos por países, por isso será necessário utilizar bibliotecas que agrupem estes países por continentes.

## Pressupostos:

- As mudanças climáticas causadas pela humanidade são um fato cientificamente comprovado.
- As emissões de gases do efeito estufa (CO<sub>2</sub>, Metano e Óxido Nitroso) são um dos principais causadores das mudanças climáticas.
- O aumento da temperatura média global é um dos principais indicadores das mudanças climáticas.

## Objetivos:

- Mostrar, por meio de gráficos, se as alterações climáticas observadas no período seguem uma mesma tendência e se estão correlacionadas com o número de mortes e o prejuízo causado pelos eventos extremos.
- Analisar a evolução anual e comparar a média entre os 2 períodos de 25 anos.

## Tarefas:

- Fazer uma Análise Exploratória dos Dados com o objetivo de obter insights para criação dos gráficos.
- Trabalhar os dados para agrupar por continentes (apenas 2 dataset já se encontram agrupados) escolhendo as métricas adequadas (média, mediana ou soma) para cada caso.


## Referências Bibliográficas

- Ferreira, S. (2024). Extreme Weather Events and Climate Change: Economic Impacts and Adaptation Policies. Annual Review Of Resource Economics, 16(1), 207-231. https://doi.org/10.1146/annurev-resource-101623-095314
- Clarke, B., Otto, F., Stuart-Smith, R., & Harrington, L. (2022). Extreme weather impacts of climate change: an attribution perspective. Environmental Research Climate, 1(1), 012001. https://doi.org/10.1088/2752-5295/ac6e7d