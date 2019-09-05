---
title: "Técnicas de Machine Learning para Análise em Mìdias Sociais"
date: 2019-08-01
tags: [machine learning, text mining, word embeddings, data science]
header:
    image: /images/background-wide.jpg
excerpt: "Aplicação de técnicas de vetores de palavras e classificadores de texto para encontrar sentimento em publicações de redes sociais"
mathjax: "true"
---

## Aplicação Prática de Deep Learning e Aprendizado de Máquina para Extração de Insights em Publicações no Twitter

Você tem ideia de quanto tempo leva para se ler 42.619 tweets? E para anotar a opinião expressada em cada um deles? Eu te digo, 2 dias, 8 horas e 53 minutos, isso se você não parar para comer, nem dormir, ou muito menos dar aquela olhadinha sagrada no celular.... E imagine ainda se durante a leitura você percebesse que está anotando errado pelo cansaço e precisa começar tudo de novo... Ou ainda, aparecem mais 100 mil tweets novos para análise. Não parece muito prático, não?

Pois bem, é exatamente isso que propomos resolver com nossa publicação de hoje. Mas ao invés de realizar essa leitura manualmente, nossa abordagem para resolver o problema foi fazer os computadores Evollo lerem o material por nós. Utilizando o estado da arte de técnicas de Aprendizado de Máquina para o Text Mining nesses mais de 42 mil tweets sobre as principais empresas de Telecom, nós extraímos os seguintes insights:

* Nextel é a empresa com maior índice de insatisfação do mercado brasileiro de Telecom *
* Internet é o produto mais reclamado e televisão fica na última posição *
* Claro é a empresa com mais menções sobre consumo indevido de dados / créditos *

*\* Insights foram extraídos do Twitter apenas e representam uma abstração da opinião do público na amostra apresentada. Qualquer generalização proveniente deste estudo deve ser avaliada com maior critério para tomada de decisões no mundo de negócios.*

Esses são alguns exemplos do que é possível analisar com a dose certa de tecnologia. Mesmo com os recurso escassos para aplicação de mineração de textos em português, nós nos propomos ao desafio e abaixo explicamos como chegamos a nossas conclusões. Vamos em frente!

## Detalhamento da Amostra

Foram extraídos 42,619 tweets durante 6 semanas entre Junho-Julho desse ano (2019) com os termos de busca sendo o nome das principais empresas de Telecom brasileira, ou seja, Vivo, Claro, Tim, Oi e Nextel. Feito isso o primeiro passo é estratificar qual tweet pertence a qual empresa.

<iframe width="900" height="400" frameborder="0" scrolling="no" src="//plot.ly/~MuriloEvollo/27.embed?showlink=false"></iframe>

Pois bem... A Vivo está entre as empresas mais populares no Twitter e a Nextel fica por último. Será que isso é bom ou ruim? 
