OBJETIVO:
Este projeto tem como objetivo desenvolver um carrinho controlado via Bluetooth, enquanto sua movimentação é controlada por níveis de sinais de atividade cerebral. Utilizando um Arduino como controlador principal, o carrinho se movimenta conforme os dados de atividade cerebral são recebidos, administrando os próprios movimentos com esses sinais, no qual quando a concentração/atividade cerebral, é maior que um limite pré-determinado, o carrinho se movimenta. A intenção do projeto é criar uma interface mente-máquina, onde o usuário pode influenciar diretamente o comportamento do carrinho por meio de seus níveis de atividade cerebral.


ITENS NECESSÁRIOS:
Arduino Uno (ou outro modelo compatível)

Módulo Bluetooth HC-05 (para comunicação com o dispositivo)

Ponte H L298N (para controlar os motores)

2 Motores DC

Protoboard

Fonte de alimentação (para os motores e Arduino)

Fios jumpers, incluindo macho/fêmea (para as conexões)

Dispositivo de medição de atividade cerebral (neste projeto foi utilizado o MINDWAVE da Neurosky)

Bateria 9 volts e o conector para o árduino

4 pilhas AA e o suporte

Chassi do carrinho, da para improvisar com mdf

Rodas apropiadas para os 2 motores DC, e uma rodinha giratória


ETAPAS:

1-Montagem do Carrinho: Para isso, basta montar um carrinho como se fosse um carrinho básico com módulo bluetooth, segue o link: https://www.youtube.com/watch?v=OornqssB-dU (OBS: No vídeo a alimentação está sendo realizada apenas com a utilização de pilhas, nesse carrinho basta usar as 4 pilhas AA no suporte para alimentar a Ponte-H e a bateira 9v para alimentar o arduíno.

2-Montagem do código no arduíno que já está arquivado no repositório

3-Conecção do Módulo Bluetooth com o MindWave, use o código nomeado como PAIRING, segue o link para a conecção: https://www.youtube.com/watch?v=uKK5_U6l27E (OBS: Quando for passar o código para o arduíno e testar os comandos AT, retire o módulo bluetooth antes de alimentar o arduíno e então reconecte novamente invertendo os pinos RX e TX, não use os pinos 10 e 11 como indica o vídeo, use o RX e TX invertidos, e quando estiver conectado, haverá um sinal de OK.

4- Após os Testes dos Comandos AT, passe o código do carrinho para o arduíno, assim o seu projeto já estará pronto.
OBS: CASO O CARRINHO APENAS GIRE E NÃO ANDE PARA FRENTE, INVERTA A CONECÇÃO DOS MOTORES COM A PONTE-H, CASO O PROLEMA SEJA EM QUE UM MOTOR ESTÁ MAIS RÁPIDO QUE O OUTRO, APENAS TROQUE O CÓDIGO PARA QUE AJUSTE O NÍVEL DE VELOCIDADE DE CADA UM MOTOR ATÉ QUE ESTEJA ADEQUADO.


Este projeto foi fruto de um trabalho árduo do projeto de uma feira cultural de escola técnica, aproveitem!
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
OBJECTIVE:
This project aims to develop a cart controlled via Bluetooth, while its movement is controlled by levels of brain activity signals. Using an Arduino as the main controller, the cart moves as brain activity data is received, managing its own movements with these signals, in which when the concentration/brain activity is greater than a pre-determined limit, the cart moves . The intention of the project is to create a mind-machine interface, where the user can directly influence the behavior of the cart through their brain activity levels.


REQUIRED ITEMS:
Arduino Uno (or other compatible model)

HC-05 Bluetooth module (for communication with the device)

L298N H-bridge (to control the motors)

2 DC Motors

breadboard

Power supply (for motors and Arduino)

Jumper wires, including male/female (for connections)

Brain activity measurement device (Neurosky's MINDWAVE was used in this project)

9 volt battery and connector for the arduino

4 AA batteries and stand

Stroller chassis, you can improvise with mdf

Wheels suitable for 2 DC motors, and a swivel wheel


STEPS:

1-Assembling the Cart: To do this, simply assemble a cart as if it were a basic cart with a bluetooth module, follow the link: https://www.youtube.com/watch?v=OornqssB-dU (NOTE: In the video the Power is being supplied only using batteries, in this cart just use the 4 AA batteries in the support to power the H-Bridge and the 9v battery to power the Arduino.

2-Assembly of the code on the Arduino that is already archived in the repository

3-Connection of the Bluetooth Module with MindWave, use the code named PAIRING, follow the link for the connection: https://www.youtube.com/watch?v=uKK5_U6l27E (NOTE: When passing the code to the Arduino and test the AT commands, remove the bluetooth module before powering the Arduino and then reconnect again by inverting the RX and TX pins, do not use pins 10 and 11 as indicated in the video, use the RX and TX inverted, and when connected, there will be an OK sign.

4- After testing the AT Commands, pass the cart code to the Arduino, so your project will be ready.
NOTE: IF THE CAR JUST ROTATES AND DOES NOT GO FORWARD, REVERSE THE CONNECTION OF THE MOTORS WITH THE H-BRIDGE, IF THE PROLEMM IS WHERE ONE MOTOR IS FASTER THAN THE OTHER, JUST CHANGE THE CODE SO THAT IT ADJUSTS THE SPEED LEVEL OF EACH ENGINE UNTIL IT IS SUITABLE.


This project was the result of hard work on a technical school cultural fair project, enjoy!
