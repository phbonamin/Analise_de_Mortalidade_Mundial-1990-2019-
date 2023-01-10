# EDA Analise de Mortalidade Mundial 1990 2019 

## ❔ Sobre o projeto

Esse projeto tem como objetivo analisar a mortalidade mundial entre 1990 e 2019, de maneira geral, sendo que teve mais destaque as doenças neurodegenerativas
e infecciosas. Achei interessante pois queria ver os dados de mortalidade antes da pandemia que poderia ser um fator de confusão.

O dataset contém dados sobre diversos países, alguns completos outros não, mas eu resolvi usar as regiões da Organização Mundial da Saúde (WHO) para a análise.

Clicando <a href = "https://en.wikipedia.org/wiki/List_of_WHO_regions" > aqui </a> você pode saber a quais regiões cada pais pertence pode ser consultado em: 

O dataset pode está disponível tanto no repositório quanto clicando
<a href = "https://www.kaggle.com/datasets/madhurpant/world-deaths-and-causes-1990-2019"> aqui </a>

## 🎯 Destaques

A região da Europa tinha eliminado a Malaria em 1974, porém a partir 1990 ouve um aumento no número de casos. Mesmo assim, conseguiu erradicar novamente em 
2015.

Ver mais em : https://www.euro.who.int/__data/assets/pdf_file/0003/307272/Facsheet-malaria-elimination.pdf

<img src = "https://imgur.com/HdvXGF0.png">

Além disso, também vem adotando <a href = "https://www.thelancet.com/journals/lanpub/article/PIIS2468-2667(19)30074-X/fulltext">  politicas </a> que tem diminuido sua mortalidade por acidentes de trânsito.

<img src = "https://imgur.com/Ui60UkV.png">

## 🧠 Doenças Neurodegenerativas
Pode se notar um aumento na mortalidade por doenças neurodegenerativas, mais acentuada em regiões com um maior numero de paises desenvolvidos. Isso se deve provavelmente ao aumento da expectativa de vida, porém, não há dados de idade no dataset.

<img src = "https://imgur.com/wVCVgN4.png">

<img src = "https://imgur.com/HOgGTXa.png">

Também foi observada uma correlação entre as duas doenças analisadas.

<img src = "https://imgur.com/6tGlbAJ.png">

## 🦠 Doenças Infecciosas

Sobre as doenças infecciosas pode-se notar que há uma maior mortalidade em regiões com um maior numero de paises subdesenvolvidos ou pobres.Podemos observar isso também quando vemos o gráfico da Malaria, na seção de Destaques.

<img src ="https://imgur.com/lylhrnn.png">

<img src = "https://imgur.com/DY2fjXU.png">

## 🦠 Doenças Infecciosas vs 🧠 Neurodegenerativas

Se a Mortalidade de doenças neurodegenerativas é menor em paises subdesenvolvidos ou pobres e maior em doenças infecciosas e o inverso para as doenças infecciosas, será que essas estão inversamente correlacionadas?

Podemos ver que para algumas regiões isso se confirma na Tuberculose vs Alzheimer:
<img src ="https://imgur.com/0NEsXYb.png">

Porém em outras doenças o mesmo não acontece.
<img src ="https://imgur.com/KF5LlEq.png">
<img src ="https://imgur.com/cRVGRX9.png">
