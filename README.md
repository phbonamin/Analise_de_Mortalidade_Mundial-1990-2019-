# EDA Analise do Número de mortes Mundialmente 1990 2019

## ❔ Sobre o projeto

Esse projeto tem como objetivo analisar o total de mortes entre 1990 e 2019, de maneira geral, sendo que teve mais destaque as doenças neurodegenerativas
e infecciosas. Achei interessante pois queria ver as tendências das doenças que mais causaram mortes antes da pandemia que poderia ser um fator de confusão.

O dataset contém dados sobre diversos países, alguns completos outros não, mas eu resolvi usar as regiões da Organização Mundial da Saúde (WHO) para a análise.

Clicando <a href = "https://en.wikipedia.org/wiki/List_of_WHO_regions" > aqui </a> você pode saber a quais regiões cada pais pertence.

Usarei os seguintes gráficos, sempre separando por regiões: (1) linha para mostrar a tendência das doenças no tempo; (2) gráficos de dispersão para as correlações ; (3) se houver uma correlação visível nos gráficos de dispersão usarei uma reta de regressão para tentar mostrar a tendência global. (4) Se não houver uma tendência global, vou utilizar o lmplot, ou seja, a regressão por cada região, para observar as correlações

O dataset está disponível tanto no repositório quanto clicando
<a href = "https://www.kaggle.com/datasets/madhurpant/world-deaths-and-causes-1990-2019"> aqui </a>

## 🎯 Destaques

A região da Europa tinha eliminado a Malaria em 1974, porém a partir 1990 ouve um aumento no número de casos como podemos observar no gráfico. Apesar disso, é possivel ver que a mesma conseguiu novamente erradicar a Malaria em 2015.

Para saber mais dessa história clicar <a href = "https://www.euro.who.int/__data/assets/pdf_file/0003/307272/Facsheet-malaria-elimination.pdf"> aqui </a>

<img src = "https://imgur.com/HdvXGF0.png">

Além disso, também vem adotando <a href = "https://www.thelancet.com/journals/lanpub/article/PIIS2468-2667(19)30074-X/fulltext"> politicas </a> que tem diminuído sua mortalidade por acidentes de trânsito, o que pode ser observado no gráfico abaixo

<img src = "https://imgur.com/Ui60UkV.png">

## 🧠 Doenças Neurodegenerativas

Pode se notar um aumento na mortalidade por doenças neurodegenerativas, mais acentuada em regiões com um maior numero de países desenvolvidos. Isso se deve provavelmente ao aumento da expectativa de vida, porém, não há dados de idade no dataset, para relacionarmos

<img src = "https://imgur.com/wVCVgN4.png">

<img src = "https://imgur.com/HOgGTXa.png">

Também foi observada uma correlação entre as duas doenças analisadas, o que era de certa forma esperado, dado que ao visualizarmos os dois gráficos anteriores podemos ver uma tendência.

Não coloquei aqui um gráfico de uma reta, para ser possível observar que todas as regiões tem essa correlação, apesar de os países mais desenvolvidos apresentarem um maior número de mortes.
<img src = "https://imgur.com/6tGlbAJ.png">

## 🦠 Doenças Infecciosas

Sobre as doenças infecciosas pode-se notar que há uma maior mortalidade em regiões com um maior numero de países subdesenvolvidos ou pobres.Podemos observar isso também quando vemos o gráfico da Malaria, na seção de Destaques.

<img src ="https://imgur.com/lylhrnn.png">

<img src = "https://imgur.com/DY2fjXU.png">

## 🦠 Doenças Infecciosas vs 🧠 Neurodegenerativas

Se a Mortalidade de doenças neurodegenerativas é menor em países subdesenvolvidos ou pobres e maior em doenças infecciosas e o inverso para os países desenvolvidos , será que essas estão inversamente correlacionadas?

Podemos ver que para algumas regiões isso se confirma na Tuberculose vs Alzheimer:

<img src ="https://imgur.com/0NEsXYb.png">

Porém em outras doenças o mesmo não acontece, ou se acontece, acontecem em regiões bem específicas.

<img src ="https://imgur.com/KF5LlEq.png">
<img src ="https://imgur.com/cRVGRX9.png">

Isso significa portanto, que apesar de podemos afirmar que em algumas regiões para doenças específicas - como a europeia e a americana com relação a tuberculose - que quando o número de mortes por doenças infecciosas cai o de doenças neurodegenerativas aumenta, isso é são casos particulares e não uma tendência global.

## 📝 Conclusões

Os dados mostram como algumas políticas já utilizadas foram importantes para a erradicação da Malária e diminuição no número de mortes por acidentes de trânsito na região europeia.

Apesar do número de mortes por doenças neurodegenerativas ser maior em regiões com países desenvolvidos, há uma tendência global o aumento no número de mortes por essas doenças, provavelmente por conta do envelhecimento da população.

Apesar de ser possível a lógica que, com um aumento na qualidade de saúde, o número de mortes por doenças infecciosas cai, e aumenta o número de mortes por doenças neurodegenerativas,diante do aumento da expectativa de vida, não foi observada essa correlação globalmente. Apesar disso, algumas regiões apresentaram essa tendência para doenças específicas, como a região Americana e Europeia para a tuberculose.
