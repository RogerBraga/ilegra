# Teste Reserva de Passagens

Teste de performance executado com o Apache JMeter.

## Teste de Carga

250 usuarios simultaneos
ramp-up 60 segundos
Em algumas execucoes com erros, nessa reportada foi irrelevante

### Resultados Carga

Aggregate
As transacoes tiveram execucao com tempo inferior ao desejado no percentil 90 (max 0,788s)

![Aggregate carga](https://github.com/RogerBraga/ilegra/assets/94936768/c98e136c-ba17-4d58-b200-ac22463efef8)

Summary
Nao houveram erros e as transacoes foram na media abaixo do tempo esperado
![Summary Carga](https://github.com/RogerBraga/ilegra/assets/94936768/41718343-09d1-4e27-9cc0-44139afe9b8f)

## Teste de Pico

500 usuarios simultaneos
ramp-up 1 segundo
Em algumas execucoes com erros, nessa reportada foi irrelevante

### Resultados Pico

Aggregate
As transacoes tiveram execucao com tempo superior ao desejado no percentil 90 na tela inicial (max 3,609s)

![Aggregate pico](https://github.com/RogerBraga/ilegra/assets/94936768/7f05de43-0adb-4b34-abed-70a71d6fccde)

Summary
Nao houveram erros e as transacoes foram na media abaixo do tempo esperado, porem mais demorados do que no teste de carga
![Summary pico](https://github.com/RogerBraga/ilegra/assets/94936768/d6d8dbf1-3994-484a-b840-be1efb92ff27)