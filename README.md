# Exemplo de projeto 2 - Cafeteria com wifi

Este repositório apresenta um exemplo de aplicação de **Internet das Coisas (IoT)**, no qual uma página web hospedada diretamente em um **ESP32** atua como interface gráfica para interação com um **Arduino UNO**, que executa uma **máquina de estados** programada no microcontrolador **ATmega328P**.

A comunicação entre o ESP32 e o Arduino UNO ocorre por meio de interface serial, utilizando os pinos **TX2 e RX2** do ESP32 conectados, respectivamente, aos pinos **0 (RX)** e **1 (TX)** do Arduino UNO. A taxa de transmissão configurada é de **9600 bps**.

## Assista ao vídeo e saiba mais:  https://youtu.be/Taf_cI7LG2E

[mchavesferreira/cafeteiraesp32uno](http://monitor.rpiot.com.br/aula/cafeteiraesp32uno/)  Pagina explicando funcionamento


Simulador https://wokwi.com/projects/434501202750110721   apresenta o código rodando para a Cafeteira no Atmega 328P

<img src=paginaweb.png>
<BR> Pagina web exemplo


<img src=simulador.png>
<br> Simulador https://wokwi.com/projects/434501202750110721


<img src=circuito.jpg>
Vista geral da montagem
