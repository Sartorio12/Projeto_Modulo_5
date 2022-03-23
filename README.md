# <center>Projeto Final do Módulo V</center>
<center> Um breve estudo sobre gastos parlamentares Brasileiros

<center><img src='https://i.imgur.com/QLJaHpa.png' style="width:200px">

<center><a href="https://colab.research.google.com/github/Sartorio12/Projeto_Modulo_5/blob/main/notebook1.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

**Grupo 5:** <a href="https://github.com/analumf" target="_blank">Analu Francisco</a> ; <a href="https://github.com/leticiafelippe" target="_blank">Letícia Felippe</a> ; <a href="https://github.com/sartorio12" target="_blank">Mateus Sartorio</a> ; <a href="www.linkedin.com/in/mateus-sartorio" target="blank">Mateus Sartório</a> ; <a href="https://github.com/hara0-tavares" target="_blank">Harão Tavares</a> ; <a href="https://github.com/jonathaslkc" target="_blank">Jonathas Carvalho</a>
  
<center><img src='https://i.imgur.com/QadqCNH.jpg' style="width:600px">
<center>Fonte: Agência Câmara de Notícias — Roque de Sá/Agência Senado
  
  ---

# **1.** Sobre o estudo e objetivos
  
  O que você imagina quando ouve o conceito **"Cota Parlamentar"** ou **"Cota para o Exercício da Atividade Parlamentar (CEAP)"**?

Você sabia que é através da **CEAP** que deputados e senadores custeiam suas despesas em atividades parlamentares? O mais interessante disso, é que os dados da CEAP que iremos analisar hoje são abertos e podem ser acessados por qualquer pesso, ou seja, qualquer pessoa pode ver como os deputados e senadores utilizam essse tipo de recurso. 

Apesar de cobrir uma quantidade grande de despesas, os gastos com a CEAP devem seguir uma série de regras definidas pelo Ato da Mesa 43/2009. Isso quer dizer que os parlamentares não podem utilizar esses recursos de qualquer maneira. Alguns exemplos de gastos vedados são a aquisição de gêneros alimentícios (ex.: o parlamentar pode gastar com as suas refeições mas não pode comprar carne para o churrasco no fim de semana), gastos de caráter eleitoral e gastos com a participação em cursos de educação básica, graduação e pós-graduação.

Além disso, como citado anteriormente, a CEAP é destinada a custear gastos exclusivamente vinculados ao exercício da atividade parlamentar, o que veda o seu uso para o benefício de terceiros, como por exemplo, o pagamento de refeições para outras pessoas além do próprio parlamentar.
Apesar de todas essas regras, a fiscalização desses gastos é bastante falha, sendo comum o surgimento de denúncias sobre irregularidades.

Neste cenário surgiu um projeto chamado Operação Serenata de Amor ( https://serenata.ai/ ), que tem como objetivo utilizar ferramentas de ciência de dados para fiscalizar gastos públicos e compartilhar informações relevantes com o público. O projeto tem uma série de módulos. Alguns deles são responsáveis por baixar e limpar os dados, outros por identificar irregularidades e por fim existem alguns módulos responsáveis pela divulgação de eventuais alertas de irregularidades. Um desses módulos de divulgação é o bot @RosieDaSerenata, responsável por publicar alertas de irregularidades no Twitter.

<center><img src='https://i.imgur.com/AjyWlf1.jpg'>
  
**É sobre isso que vamos tratar nesta análise, que tem dois focos principais:**
- *Demonstrar como investigaremos esses dados utilizando Python.*
- *Elaborar conceitos a respeito da utilização da CEAP nos últimos 3 anos, com destaques no cenário de pandemia(COVID-19).*
  
A pesquisa do Módulo 5 de dados da Resilia sobre os Gastos Parlamentares ( 2019 - 2021 ) indicam vários fatores, notamos que alguns gastam muito enquanto outros gastam bem pouco, conseguimos perceber que a pandemia do Covid 19 teve sim uma forte influência em como os deputados utilizam suas cotas, também nota-se uma leve tendência de aumento para os próximos anos, baseados nos gastos atuais, e que a categoria que mais custou ao estado nesse período foi a de divulgação parlamentar (Campanhas políticas, propagandas do deputado, etc.) dentre outros que iremos abordar. Esperamos que vocês gostem do que trouxemos, boa leitura :)
