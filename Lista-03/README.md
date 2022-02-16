# Exercises:
### 1) Qual a principal vantagem em utilizar uma interrupção ao invés de checar peri odicamente o status de uma GPIO, por exemplo.
R: A vantagem é evitar tempo desperdiçado com múltiplos testes, assim o programa tem uma resposta mais rápida, melhorando sua eficiência. Usando o exemplo de fazer o bolo, não tem o porquê de eu verificar a cada momento se vai ter uma visita no meu portão, assim o processo de fazer o bolo acaba ficando mais lento. Nesse caso a interrupção seria a campainha que vai me avisar quando tiver visita no meu portão, desse modo, não preciso ficar verificando a cada momento mais, podendo focar totalmente no processo de fazer o bolo.

<br>

### 2) Por que não é recomendável executar operações custosas e longas dentro de uma rotina ISR?
R: Porque as interrupções executam uma função que possui maior prioridade, então, após sua execução, o fluxo normal de um programa é parado, e caso tenha operações custosas e longas, pode acabar conflitando com o fluxo normal do programa. Obs (nunca definir delay em uma interrupção).

<br>

## Pratical Exercises:

### 3) Desenvolva um programa que altere o status do LD4 a cada toque no botão USER do kit, utilizando interrupção.

### 4) Desenvolva um programa que conta quantas vezes o botão de USER foi pressionado, utilizando interrupção.
