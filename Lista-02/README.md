# Exercises: 

### 1) Qual a vantagem de se trabalhar com os tipos da biblioteca stdint.h?
R: Tem um padrão de definição de tipos de dados, pode definir valores específicos de largura para números inteiros.

<br>

### 2) Qual a principal característica de uma viariável do tipo int_fastX_t? 
R: Ajustar os bits para adquirir melhor performance do chipset.

<br>

### 3) No nosso kit NUCLEO-G0B1RE, qual o tamanho da variável, em bytes, do int_fast8_t, int_fast16_t, int_fast32_t e int_fast64_t. 
R: int_fast8_t - 4 byte.

   int_fast16_t - 4 byte.
   
   int_fast32_t - 4 byte.
   
   int_fast64_t - 8 byte.

<br>
 
### 4) Qual a função dos registradores:
R: • GPIOx_MODER: Selecionar a direção de entrada e saída de dados.

• GPIOx_OTYPER: Configurar o tipo de saída de I/O.

• GPIOx_OSPEEDR: Configurar a velocidade de saída de I/O.

• GPIOx_PUPDR: Configurar para pull-up ou pull-down.

• GPIOx_IDR: Contém o valor da entrada da porta de I/O correspondente, somente leitura.

• GPIOx_ODR: Registro de dados de saída, leitura e gravação.

• GPIOx_AFRL: Usado para selecionar a função alternativa da porta.

<br>


### 5) Como posso fazer para ler diretamente o registrador sem utilizar a implementa ção da ST? (tip: lembre-se dos ponteiros!) 
R: Acessando o endereço do registrador através dos ponteiros, podendo através disso, modificar seu conteúdo.

<br>

## Pratical Exercises:

### 6) Desenvolva um firmware que pisque o LD4 com uma frequência de 1Hz (500ms aceso, 500ms apagado).

### 7) Desenvolva um firmware que pisque o LD4 com uma frequência de 100Hz.

### 8) Faça um programa que pisque o LD4 em 20Hz enquanto o botão USER é pres sionado e pisque com frequêcia de 5Hz ao ser solto.

### 9) Faça a leitura dos switches do tipo DIP de 4 posições utilizando os resistores de pull-up ou pull-down internos. Armazene em uma variável o valor correspondente, onde a chave 1 corresponde ao bit 0, e o bit 4 corresponde ao bit 3.

### 10) Aproveite o exercício anterior, monte 4 LEDs e associe cada um deles a uma chave do DIP switch de 4 posições, quando a chave estiver em ON, acenda o LED, e em OFF, apague o LED.

### 11) Challenge: Aproveite o exercício anterior novamente, mas sem os LEDs, e exiba em um display de 7 segmentos o valor correspondente em hexadecimal (0 à F).
