# Projeto de Fonte de Tensão Ajustável
 Projeto realizado no primeiro semestre do curso de Bacharelado em Ciências de Computação, para a disciplina '[SSC0180] – Eletrônica para Computação', ministrada pelo professor Eduardo do Valle Simões, da USP de São Carlos
## Especificação
Fonte reguladora de tensão variável que transforma a tensão 127V AC da tomada em 1,5-12V CC
## Integrantes do Grupo:
| Nome | NUSP |
|------|------|
| Diego Cabral Morales | 13672193 |
| Jean Michel Furtado M'Peko | 5271916 |
| Paulo Ricardo Bastos Silva | 13748096 |
| Samuel Nicolas Magalhães Silva | 13824181 |
## Companentes:
| Componente | Especificações/Tipo | Quantidade | Valor |
|------------|---------------------|------------|-------|
| Diodo | 1N5404 | 2 | R$ 2,40 |
| Transistor | LM317T | 1 | R$ 2,70 |
| Transformador | 12 + 12V 1A | 1 | R$ 26,80 |
| Capacitor | 470µF 50V | 1 | R$1,80 |
| Capacitor | 10µF 50V | 1 | R$1,10 |
| Poteciômetro | 1w/5k | 1 | R$7,00 |
| Resistor | 2.2k | 1 | R$ 0,07 |
| Resistor | 330 | 1 | R$ 0,07 |
| Resistor | 270 | 1 | R$ 0,07 |

## Funcionamento
1. Transformador: reduz a corrente e a tensão que vem da tomada 127V AC em 12V AC nos 2 terminais de saída.
2. Retificação: ocorre através dos diodos que transformam a corrente alternada em corrente contínua.
3. Filtragem: o capacitor armazena energia e descarrega quando a tensão está em queda, assim reduzindo a variação da tensão.
4. Regulação: a regulagem da tensão é feita pelo LM317 que limita a saída em 12v.
5. Ajuste: é feito pelo potenciômetro, de acordo com a alteração da resistência ele diminui ou aumenta a tensão.

## Simulação do Circuito no Multisim:
![SimulaçãoMultisim](https://user-images.githubusercontent.com/110208895/181829224-fdac9fd0-3856-42c2-8997-190dd74390b4.png)
Link para a simulação: https://www.multisim.com/content/sebqCP3t75cmC8oAsDHSxY/fonte-tensao-ajustavel-12v/open/
## Calculos dos componetes:
![equacoes](https://user-images.githubusercontent.com/110208895/181831110-4ac6a579-f0a9-49e2-a40b-07ab9f144000.png)

## Esquemático da PCB no software Proteus:
![fonte isis](https://user-images.githubusercontent.com/110208895/181827555-6eaf0a4f-efec-472a-80bd-3763af17cbc5.png)
## PCB do Circuito no Software Proteus:
![fonte ares](https://user-images.githubusercontent.com/110208895/181827415-69203dab-ebf6-47bc-9162-1b3463e85584.png)
## Vídeo do circuito:
https://www.youtube.com/watch?v=mB_tQPsQPQE

