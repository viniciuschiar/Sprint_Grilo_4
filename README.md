# Sprint_Grilo_4
# SPRINT 4 – GOODWE SMART CHARGING STATION

## INTEGRANTES

Vinicius Sanches Chiarle RM:568846
Matheus Curtale Serafim RM:

## LINK DO WOKWI

https://wokwi.com/projects/475996729336662017 

## OBJETIVO

Desenvolver um sistema inteligente de recarga de veículos elétricos utilizando Raspberry Pi Pico, MicroPython e Wokwi.

## PROBLEMA

Vários veículos podem solicitar energia ao mesmo tempo, ultrapassando a capacidade disponível da estação.

## SOLUÇÃO

O sistema calcula a demanda dos veículos e compara com a energia disponível.

Verde: recarga normal
Amarelo: recarga reduzida
Vermelho: recarga bloqueada

Quando existe pouca energia, o sistema prioriza o veículo com menor nível de bateria.

## EXEMPLO

EV1: 20% – 2000 W
EV2: 50% – 2500 W
EV3: 80% – 3000 W

Demanda total: 7500 W
Energia disponível: 8000 W

Resultado: recarga autorizada.

## COMPONENTES
Raspberry Pi Pico
LEDs
Botões
Display LCD I2C
Resistores
Wokwi
## FUNCIONAMENTO

Entrada → Raspberry Pi Pico → Processamento → Decisão → LEDs/LCD

O sistema recebe os dados, calcula a demanda, distribui a energia e informa o estado da recarga.

## SUSTENTABILIDADE

O projeto busca melhorar o aproveitamento da energia, evitar sobrecargas e contribuir para a mobilidade elétrica.

CONCLUSÃO

O protótipo demonstra um sistema embarcado capaz de gerenciar de forma inteligente a recarga de vários veículos elétricos.
