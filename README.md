# Global Solution Disruptive Architectures IOT e IA

# TAGE

Arthur Henrique Toshiriro Sakamoto Santos - 86832  
Gustavo de Cássio Vasselai – 88264  
Izadora Amorim Santana – 88494  
João Armando Alves Neto – 88255  
Nathan Santana da Silva - 88517, 2TDSR ** 

**Turma: 2TDSG & 2TDSR**

**Ano: 2022**

## Objetivo / descrição do Projeto

Projeto desenvolvido como entrega final do Global Solution, contexto da questão 1:
Um dos grandes problemas do trânsito é encontrar uma vaga para estacionar. Buscando auxiliar os clientes de um estacionamento, a empresa precisa desenvolver uma aplicação que faça a detecção de quantas vagas estão disponíveis

Para isso, utilizamos o arduíno para desenvolver um sistema que auxilie a identificar quando um carro está estacionado na vaga e que indique por LEDs.

## Diagrama do projeto

Circuito questão 1
![image](https://user-images.githubusercontent.com/61067852/200679448-7cf55813-3ab7-45b9-b3d6-cb216a15cf65.png)


## Como usar 

Para rodar  
[Link para o círcuito no Tinkercad](https://www.tinkercad.com/things/9JpD2BmMCuz?sharecode=L6xAuMO6RxDp7htNYe9JhjCB4pU5WoB-waB1R5NSyh0)  
Questão 1  
Caso queira rodar fisicamente:  
• Arduíno  
• 2 (dois) Sensores ultrassônicos;  
• 2 (dois) LEDs vermelhos;  
• 2 (dois) LEDs verdes  
• 1 (um) Display LCD (16x2).  
• 1 (um) Potenciômetro  
[Link documentação arduino](https://docs.arduino.cc)

Virtualmente:  
• Acesso a internet.


Pode adicionar algum trecho de código, por exemplo para clonar esse repositório:

    cd /home/iot
    git clone https://github.com/NathansSilva/GS-Disruptive-Architectures-IOT-e-IA.git
    cd GS-Disruptive-Architectures-IOT-e-IA
    ls

## Link de vídeo demonstração

https://www.youtube.com/watch?v=kK5BM1z97gY


Questão 2


Fluxo1 - Gateway que recebe as informações das vagas via serial e envia (publisher) via protocolo MQTT.
Simule o estacionamento com 2 vagas (vaga A e vaga B) utilize o node “inject”. O formato da mensagem
dos sensores é:

• Somente a vaga A disponível → envia “A”

• Somente a vaga B disponível → envia “B”

• Ambas as vagas disponíveis → envia “AB”

• Nenhuma vaga disponível → envia “X”


Fluxo2 - Dashboard que recebe (subscriber) os dados via protocolo MQTT e exibe o status em um
Dashboard.

## Como usar
 É necessário a instalação do node.js
 
 É necessário o uso de Internet
 
 Abra o seu CMD e digite "node-red" e após um carregamento o endereço local para acesso irá aparecer.
 
### Referências 

* Aulas de IOT.
