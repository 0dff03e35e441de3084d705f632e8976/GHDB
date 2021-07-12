# GHDB

Google Hacking

![](https://miro.medium.com/max/1200/1*emwyXFuZ7vlHsUFc0P1qkA.png)


## Conhecendo as dorks:

Com a composição de dorks nós podemos retornar domínios específicos, títulos, palavras, arquivos, e algumas outras coisas que vamos ver a seguir: 

## Conhecendo as dorks:

Com a composição de dorks nós podemos retornar domínios específicos, títulos, palavras, arquivos, e algumas outras coisas que vamos ver a seguir:

## “site:” — Busca em um site específico
site:exemplo.com.br

## “intitle:” — Busca por título de páginas
intitle:”< Fazer login”

## “inurl:” — Busca de termos presentes na url
inurl:/wp-admin

## “intext:” — Busca por texto no conteúdo do site
intext:adminpass

## “filetype:” — Busca por formato de arquivos (.jpg,.zip,.txt)
filetype:.txt

# Construindo uma dork
Então com esses dados já conseguimos construir algumas dorks simples para iniciar os estudos em nossos domínios e achar possíveis falhas na indexação do nosso site.
Eu preciso de uma dork que me traga arquivos php da área de login do phpmyadmin do meu site, como será que eu poderia fazer? 

## Veja:
intitle: phpmyadmin filetype: php intext: login site:meusite.com.br

# Google Hacking Database
O Exploit-db creio eu que seja o site referência entre os hackers do mundo todo, além disso ele tem uma área dedicada somente ao Google Hacking com milhares de Dorks para explorarmos:

https://www.exploit-db.com/google-hacking-database

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTq3tW93J2E60li95U_S4OYgigxtp9qI03FMMTu-RjSLe00RZg8&s)
