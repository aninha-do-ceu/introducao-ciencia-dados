# introducao-ciencia-dados

| <h2>Projeto Final de Ciência de Dados</h2>  |
|:--------:|
|<img src="https://br.web.img2.acsta.net/pictures/15/05/20/17/18/336796.jpg" width="250" height="150">|

## Introdução

As Meninas Superpoderosas foi um desenho infantil criado em 1998 onde três garotinhas com personalidades distintas combatiam a criminalidade de Townsville juntas. \
Podemos traçar um paralelo no qual Townsville é o Brasil e as meninas superpoderosas seriam políticas públicas que combatem o crime. \
Isto pois o Brasil possui muitos problemas em relação à criminalidade, que possui raízes na desigualdade social que o assola. \
O objetivo deste projeto é analisar as principais causas da criminalidade no estado de São Paulo por município a fim de montar um "Mapa do Crime" e tentar classificar um município como perigoso ou não. 

## Sobre os Dados
Foram encontrados diversos obstáculos para obter os dados, portanto, a análise se concentrará em analisar a criminalidade **por município**, com dados oriundos do [SEADE](https://municipios.seade.gov.br/) (Fundação Sistema Estadual de Análise de Dados).

Outra fonte será o dataset [Crime Data in Brazil](https://www.kaggle.com/datasets/inquisitivecrow/crime-data-in-brazil) que possui dados de BOs coletados no estado de São Paulo de 2007 a 2016. \
O período a ser analisado será o ano de 2010 pois é o ano em que possuímos dados o suficiente para analisar. 

Variáveis a serem analisadas:

- [Índice de Analfabetismo](https://www.ibge.gov.br/estatisticas/multidominio/condicoes-de-vida-desigualdade-e-pobreza/9662-censo-demografico-2010.html?edicao=9758&t=resultados) - Tabela 14 do arquivo zipado
- [Renda Mediana per capita do Município](https://www.ibge.gov.br/estatisticas/multidominio/condicoes-de-vida-desigualdade-e-pobreza/9662-censo-demografico-2010.html?edicao=9758&t=resultados) - Tabela 8 do arquivo zipado
- [IPVS (Índice Paulista de Vulnerabilidade Social)](http://www.imp.seade.gov.br/frontend/#/tabelas)
- [Proporção de Domicílios com Acesso ao Saneamento Inadequado](https://www.ibge.gov.br/estatisticas/multidominio/condicoes-de-vida-desigualdade-e-pobreza/9662-censo-demografico-2010.html?edicao=9758&t=resultados) - Tabela 7 do arquivo zipado

Variável Resposta:

- [Taxa de Criminalidade com Base no Números de Roubos e Furtos por Município](https://www.kaggle.com/datasets/inquisitivecrow/crime-data-in-brazil)
