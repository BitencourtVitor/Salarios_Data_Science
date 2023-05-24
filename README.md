# Salários Internacionais para Data Science
###### Aqui, você terá acesso a:
- Print do Dashboard feito em Power BI
- Arquivo .pbix para caso queira interagir ou realizar alguma alteração
- Base de dados antes do tratamento para caso queira navegar.

## Introdução
A partir de uma base de dados publicada no Kaggle, ficaram evidentes as principais médias salariais para profissionais da área de dados em todo o mundo. Desenvolvi uma análise descritiva sobre essas médias salariais para observar o impacto de fatores como cargo, localidade, moeda e tamanho da empresa.

## Conclusão
É inegável a hegemonia americana, maior parte das oportunidades se encontram lá, maioria dos profissionais são de lá... Eu poderia dizer que isso se deve apenas ao Vale do Silício, mas não: o Vale do Silício concentra empresas gigantes no ramo de tecnologia, enquanto a maior parte das oportunidades são em empresas de médio porte. De fato, observo uma questão de maturidade e consciência da necessidade de profissionais da área.

Observando a base de dados, tive uma breve dificuldade para interpretar o significado de algumas siglas, além de despender de certo tempo projetando a melhor forma para apresentação dos dados no Dashboard... Apesar de não haver coleta de dados (a base já estava pronta), houve uma análise exploratória para entender o significado de cada informação apresentada.

## Pontos de melhoria
Considero pertinente um retrabalho no Frontend deste projeto e reconsideraria alguns dos mecanismos usados como gráficos de rosca e árvore... Acredito que ambos abram precedentes para erros na interpretação dos dados por parte de alguns usuários.

## Passo a passo
- OBJETIVO: Tratamento dos dados e montagem de um Dashboard que pudesse tornar possível visualizar quais países tem mais ou menos oportunidades, média salarial, etc.

- EXTRAÇÃO: A base de dados foi fornecida por um usuário do Kaggle, sem que fosse necessária a utilização de nenhum 
mecanismo de coleta.
- TRANSFORMAÇÃO: Através do Power Query realizei toda a etapa de tratamento dos dados, realizando algumas correções nas colunas afim de facilitar o entendimento de quem trabalhasse com a base de dados, inclusive (e principalmente) eu.
- LOAD: Criei o template no Figma utilizando a paleta de tons que conectasse com as cores do [Kaggle](https://www.kaggle.com/), de forma que passasse a imagem de tons neutros, entre azul e branco, com cores diversas em tons não muito ativos mas também não muito fracos.

![Aqui há um print do Dashboard](https://github.com/BitencourtVitor/bitencourtvitor/blob/main/Sal%C3%A1rios%20Internacionais%20para%20Data%20Science/print_dashboard.png)
