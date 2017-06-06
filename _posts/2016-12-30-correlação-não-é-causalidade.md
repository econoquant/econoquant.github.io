---
layout: post
published: true
title: Correlação não é causalidade
tags: [Economia, Econometria, Estatística, Machine Learning]
comments: true
---
Confundir correlação com causalidade é muito comum  em nosso cotidiano, recebemos e fazemos muitas explicações de como uma coisa causa outra enquanto na verdade elas só estavam correlacionadas, dois eventos  aleatórios ocorrem ao mesmo tempo e julgamos que um causou o outro.

![](/assets/img/cor-vs-cau.jpg) 

Acontece muito com dietas da moda, uma amiga que conta para outra, que uma amiga usou tal coisa e perdeu 20kg, essa dieta logo vira moda, as moças começam a consumir tal substância e vêem que ela não  tem o efeito prometido, tal dieta começa a perder popularidade, até que vem outra dieta da moda.

Outro exemplo é café e câncer de pulmão, estão correlacionados e estudos  já afirmaram que  café causava câncer de pulmão. Mas acontece que  o café  esta correlacionado com cigarro, e é este, uma variável mais plausível para a causa de câncer de pulmão.

No mundo  dos negócios também acontetece muito  disso, as revistas especializadas  sempre trazem casos de executivos de sucesso, ensinando seus leitores para terem o mesmo sucesso, MBAs fazem de muitos empresários caso de estudo para seus alunos, e todos ouvem cuidadosamente os "n" passos para o sucesso, enquanto na verdade, muitas vezes, tal executivo só "deu sorte". Acontece muito com traders, depois de passarem por uma sequência de bons resultados, acharem que entendem o mundo e que sabem tudo sobre economia, passam a apontar os "erros" dos economistas e dizerem quais políticas deviam ser implementadas. Você pode encontrar várias figuras dessas em sites de finanças.

A literatura acadêmica está cheia desses exemplos, seja mostrando esses erros ou seja ela mesmo sendo enganada. Talvez para o típico cidadão, o caso mais evidente é de alimentos, que um dia ele ve no jornal que tal alimento está proibido porquê causa algum mal, e depois ele ve de novo, no mesmo jornal, que aquele alimento não faz  "mais" mal. Se propagou também vários livros do tipo ciência popular que tratam disso, mostrando a grande influência da aleatoriedade na nossa vida.

É o econometrista que tem como trabalho separar o que é causa do que é correlação. Tem eventos que andam de forma tão sincronizada que na modelagem podem confundir muitos por muito tempo, e isso transformado em política econômica irá levar a grandes catástrofes.

O site [tylervigen](http://www.tylervigen.com/spurious-correlations) traz vários exemplos interessantes de correlações espúras.  O primeiro gráfico nos dá o número de pessoas afogadas (linha vermelha) e as aparições do Nicolas Cage em filmes (linha preta).

![chart.jpeg]({{site.baseurl}}/assets/img/chart.jpeg)  

Deveríamos banir Nicolas Cage do cinema para evitar o afogamento de pessoas?

O segundo gráfico tem a taxa de divórcio em Maine (linha vermelha) e o consumo per capta de margarina (linha preta).  

![chart1.jpeg]({{site.baseurl}}/assets/img/chart1.jpeg)  

Vamos proibir as propagandas de margarina na tv?

O terceiro gŕafico tras o consumo de muçarela (linha vermelha) e doutorados obtidos em engenharia civil (linha preta).  

![chart2.jpeg]({{site.baseurl}}/assets/img/chart2.jpeg)  

O que vocês acham de subsidiarmos a indústria de queijo para aumentarmos a oferta de engenheiros no mercado?

Os exemplos do site tylervigen não correm o risco de serem confundidos como relação de causalidade por serem coisas completamente diferentes, seria absurdo considerar que os filmes do Nicolas Cage está causando afogamentos. O problema está quando trabalhamos com variáveis que não conhecemos muito bem, um exemplo é a Curva de Philips, que relaciona inflação com desemprego. Por muito tempo economistas acreditavam que um pouco de inflação era bom para reduzir o desemprego, depois já não se acreditava nesse efeito a longo prazo e hoje a maioria já acredita que isso não vale nem para o curto prazo. O modelo continua a ser usado (com melhorias) para previsões, porém a maioria dos economistas acreditam que não se deve usar tal modelo para  fins de política econômica - parte da nossa situação econômica atual se dá por terem acreditado nisso, e alguns ainda insistem nisso.

A econometria desenvolveu várias técnicas para tentar identificar relações de causa-efeito, e é de extrema importância ter uma boa teoria que de suporte na hora da modelagem estatística, para não acabarmos sugerindo como política econômica o subsídio de queijos.

**PS**: Este post apareceu primeiro no antigo blog **EcoMachibe** e também foi publicado no site [Money Times](https://www.moneytimes.com.br/opiniao-correlacao-nao-e-causalidade).
