Semáforo de 2 Vias com Microcontrolador PIC18F4550

![image](https://github.com/ThiagoDeSena/Sem-foro-em-Assembly/assets/110785400/f346c1db-3dda-4944-9bf2-54551bd050e7)


Este projeto implementa um semáforo de 2 vias utilizando o microcontrolador PIC18F4550. O sistema opera com um clock de 48MHz e segue a lógica de temporização descrita abaixo:

Semáforo 1:

Verde: 7 segundos aceso
Amarelo: 2 segundos aceso
Vermelho: 9 segundos aceso


Semáforo 2:

Verde: 7 segundos aceso
Amarelo: 2 segundos aceso
Vermelho: 9 segundos aceso


Funcionamento:

O ciclo completo do semáforo dura 18 segundos.
O LED verde do Semáforo 1 acende por 7 segundos, enquanto o LED vermelho do Semáforo 2 permanece apagado.
Ao final dos 7 segundos, o LED verde do Semáforo 1 apaga e o LED amarelo acende por 2 segundos. Durante este tempo, o LED vermelho do Semáforo 2 permanece aceso.
Após os 2 segundos do amarelo, o LED vermelho do Semáforo 1 acende e o LED verde do Semáforo 2 acende ao mesmo tempo. O LED vermelho do Semáforo 2 apaga.
O ciclo se repete continuamente.
