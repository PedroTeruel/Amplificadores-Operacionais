# Amplificadores Operacionais em Operações Matemáticas

Projeto desenvolvido para a disciplina de Física Aplicada do Bacharelado de Engenharia da Computação.

O objetivo dessa atividade foi analisar o funcionamento de amplificadores operacionais utilizados para realizar operações matemáticas analógicas por meio de simulações no SimulIDE.

## Circuitos desenvolvidos

Foram montados e analisados quatro circuitos:

- Somador inversor
- Escalonador
- Derivador
- Integrador

## Software utilizado

As simulações foram realizadas no:

- SimulIDE

## Configurações utilizadas

### Somador inversor
- Entrada 1: 1 V
- Entrada 2: 2 V
- R1: 10 kΩ
- R2: 20 kΩ
- Rf: 10 kΩ

### Escalonador
- Entrada: 2 V
- Rin: 10 kΩ
- Rf: 20 kΩ

### Derivador
- Entrada: onda triangular
- Amplitude: 1 V
- Frequência: 100 Hz
- Capacitor: 100 nF
- Resistor de realimentação: 10 kΩ
- Resistor em série: 1 kΩ

### Integrador
- Entrada: onda quadrada
- Amplitude: 1 V
- Frequência: 100 Hz
- Resistor: 10 kΩ
- Capacitor: 100 nF

## Resultados

Os circuitos apresentaram comportamento compatível com os modelos teóricos.

No somador foi obtida uma saída de aproximadamente -1,995 V, para um valor teórico de -2,00 V.

No escalonador foi obtida uma saída de aproximadamente -3,988 V, para um valor teórico de -4,00 V.

No derivador, a onda triangular de entrada resultou em uma saída aproximadamente quadrada, com presença de oscilações de alta frequência.

No integrador, a onda quadrada de entrada foi convertida em uma onda aproximadamente triangular.

## Arquivos

O repositório contém os arquivos de simulação desenvolvidos no SimulIDE, permitindo a reprodução dos experimentos realizados no relatório.

## Observação

O arquivo deve ser aberto utilizando o SimulIDE.
