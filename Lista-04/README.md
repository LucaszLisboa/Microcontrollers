# Exercises: 

### 1) Um determinado projeto de refrigerador utiliza um sensor de temperatura con dicionado a trabalhar de -75ºC até 5ºC (0V à VDD), este refrigador implementa um PID que é alimentado por este sensor de temperatura. Como requisito, a precisão da temperatura medida deve ser de 0,02ºC. Dado a condição, calcule a resolução mínima do ADC que atenda ao requisito do projeto.
R:

<br>

# Pratical Exercises:

### 2) Implemente um programa que leia um potênciometro e converta o valor lido do ADC em tensão. (Lembrando que a alimentação do microcontrolador é de 3.3V)

<br>

### 3) Implementar um firmware que faça a leitura de um potênciometro e, utilizando três LEDs, acenda os mesmos de acordo com a seguinte regra definida pela tabela 1: 

  #### Tabela 1: LEDs a serem acionados de acordo com cada tensão lida pelo ADC. 
  
  #### Valor do ADC:
  #### Até 1V LED1 
  #### Maior que 1V e Menor que 3V LED2 
  #### Maior que 3V LED3 
  
<br>

### 5) Faça um firmware que leia 4 potênciometros utilizando 4 canais do ADC. Associe 1 a estes potênciometros quatro LEDs, onde o LED 1 é controlado pelo potênciometro 1, e assim por diante. Quando a leitura do potênciometro n for maior que 2,7V, ligar o LED n, caso contrário, deve manter o LED apagado. Neste exercício utilize a leitura dos canais por polling.
  
<br>

### 9) Challenge: Utilizando divisor de tensão, faça um programa que, utilizando lei tura analógica, meça a resistência de um resistor. É possível determinar a resistência a partir da tensão que é lida com a equação 1, tendo como base o circuito da figura 2, onde R1 é um resistor fixo e R2 o resistor que terá sua resistência calculada.
