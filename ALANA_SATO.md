# Avaliação TEORICA MOBILE
Requisitos para a avaliação:

#1. Criar um repositório no GitHub chamado Avaliação Teórica Mobile

#Criar um arquivo Markdown formatado e com as respostas para os seguintes questionamentos:

1. Descreva a arquitetura do sistema operacional Android
 ## Descreva a arquitetura do sistema operacional Android

- A arquitetura do android está dividida em 7 camadas, começando com a camada base, que é considera a camada mais profunda, até a camada mais superficial.     
**Linux kernel**, cuida da parte do drivers.   
**Hardware Abstratction layer**, fica com a parte da câmera, áudio, sensores e etc.  
**Native c/c++ e Android Runtime**, armazenam as bibliotecas utilizadas.   
**Java API framework**  
**System Apps**  

| Camadas      |    
------------
| System Apps |  
| left foo      |   
| Java API framework     |   
| Native c/c++ e Android Runtime  |   
| Hardware Abstratction layer    |   
| Linux kernel      |   

2. Descreva como desenvolvemos interfaces em aplicações Android nativas em Kotlin
## Descreva como desenvolvemos interfaces em aplicações Android nativas em Kotlin  

- De primeiro, precisamos usar o widgets e o layouts que são oferecidos pelo android studio. É necessário desenvolver a interface na aba activy_main.xml, dentro dela escolha a guia design, que ajuda a visualizar melhor a IU.     

    SELECT    
    BLUEPRINT     
    VIEW OPTIONS     
- Depois é só format a o tamanho e margem da página. Mas é preciso adicionar o constraints para adicionar funcionalidades para interface, como botão, imagem ou text. 

3. Defina o que é uma View  
## Defina o que é uma View  
 - A view é utilizada para visualizar alguma aplicação ou dado, é uma janela. 

4. Defina o que é um Event Listener    
## Defina o que é um Event Listener    
- O event listener, atribui uma função a um evento de alvo único, ou seja, o método event atribui um evento, como por exemplo clicar em um botão. Tecnicamente ele ouvirá o usuário fazendo tal ação e irá fazer com que o evento aconteça. 


5. Defina o que é o Graddle  
## Defina o que é o Gradle  
- É um sistema de automatizaçã o de build/compilação que executa scripts de compilação de diversas linguagens, fazendo conversões para linguagem JAVA. 


6. Escreva o que é o SDK android  

- SDK (software development kit) tem como objetivo fornece aplicações para desenvolver android, as ferramentas oferecidas são bibliotecas, depurador, emulador para simula como ficaria no celular, código fonte e documentação. 

7. Escreva o que sãos API level, e dentro das configs de build o que é Target API e minimal API level


8. O que é o processo de Build  
## O que é o processo de Build    
- O processo build, compila o arquivo e declara se tem erro de sintaxe ou se foram integrados de forma certa, é um procedimento que pega seu código fonte e verifica, porém, é um processo manual. 

9. Descreva como podemos testar aplicações android em nossos próprios celulares.

!!!Enviar até as 18h da sexta-feira dia 01/04/2022
Bônus: Criar um commit para cada resposta
Bônus: Dar um fork nesse repositório e criar as respostas em uma branch chamada Prova-<seu-nome>
