# Node.js com JavaScript


Vamos iniciar o desenvolvimento com Node.js, conhecendo os conceitos e uso do Node com JavaScript e aplicando isso a um projeto: criar um servidor, subir e devolver uma mensagem em JSON com informações de uso da memória RAM."


## Iniciando o projeto
Baixe o repositório pra sua máquina local para servir de guia na hora da live

## o que é o NodeJS?
![node imagem](https://user-images.githubusercontent.com/88461178/142941250-509b2456-00fa-492f-b7b4-916c14761637.png)

O **NodeJs** é um ambiente de execução do **JavaScript** em server-side

Ok. Mas o que isso quer dizer?

Ele nos dá a possibilidade de rodar localmente o JavaScript fora do navegador por exemplo.


Vamos falar um pouco sobre:


## Como surgiu?
Todo navegador possui um Interpretador de JavaScript rodando ali por trás dos panos para fazer as coisas funcionarem direitinho:


 - Safari - Nitro
 - Mozilla - SpiderMonkey
 - Edge - Chakra
 - Chrome - V8

Em 2009 um cara chamado Ryan Dahl criou o NodeJs a partir do V8 do Chrome.

## E o que tem isso?

Com a criação do NodeJS, temos a possibilidade de rodar o JavaScript sem precisar de um navegador, diminuindo o processamento e trabalhando com interpretação just-in-time, em tempo real meus amigos.

## OMG como assim?

O nodejs, diferente de outros interpretadores, trabalha com single-thread, ou seja, imagina que cada requisição é um pedido de delivery... vai chegar uma hora que o quadro de pedidos vai estar cheio e se tiver um pedido que ainda não foi produzido e entregue, ele vai bloquear a passagem dos outros pedidos, gerando insatisfação dos clientes. Coitado do entregador.

O nodejs trabalha com requisições assíncronas, ou seja, não precisa esperar todos os pedidos, vai entregando o que for ficando pronto. Assim todo mundo sai feliz.😊 Assim, o processamento é não-bloqueante(non-blocking), pois funciona mesmo sem uma requisição estar pronta, do contrário seria bloqueante(blocking) e tudo ficaria parado.


Consequentemente, o entregador não precisa mais ficar preocupado e entrega o pedido assim que o mesmo for finalizado, depois volta no quadro de pedidos, pega os que faltaram e entrega logo após. Chamamos isso de Event-Loop.

## Isso tudo em tempo real

**NPM** (Node package manager)
Com a criação do NodeJS também surgiu o NPM. que é uma ferramenta de gerenciamento de pacotes do Node, serve pra gente dar um upgrade nos nossos projetos usando frameworks e bibliotecas.

Imagine um repositório gigantesco com inúmeras ferramentas de desenvolvimento... esse é o NPM do NodeJS.

# Na prática!

## Mas antes...

Vamos instalar as ferramentas e deixar o ambiente certinho.

Links para baixar as ferramentas

 https://nodejs.org/en/
 
 https://code.visualstudio.com/
 
 ## Ficou assim:
 
 Criar um servidor, subir e devolver uma mensagem em JSON com informações de uso da memória RAM."
 
 ![node2](https://user-images.githubusercontent.com/88461178/142943861-6a05f212-6526-440f-977a-fd4992f458cd.PNG)
 
![server](https://user-images.githubusercontent.com/88461178/142943907-91755187-b9f5-48b9-ab8c-419a578fd97e.PNG)

![index nod](https://user-images.githubusercontent.com/88461178/142943965-531705a8-eefa-4c49-9730-bc3487152420.png)
