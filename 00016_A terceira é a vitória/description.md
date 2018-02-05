Para finalizar isso dos múltiplos parâmetros, vamos pedir que você implemente um procedimento com três parâmetros!

O que deve realizar esse procedimento, que chamaremos `Triade`, é simples: colocar três pedras, uma ao lado da outra em direção ao Leste, e coincidindo a cor com o parâmetro correspondente. A garra começa na origem e deve terminar sobre a última pedra da tríade.

Por exemplo `Triade(Vermelho, Azul, Verde)` produziria este resultado:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Rojo 1
    cell 1 0 Azul 1
    cell 2 0 Verde 1
    head 2 0
</gs-board>

enquanto que `Triade(Azul, Verde, Vermelho)` faria este outro:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Azul 1
    cell 1 0 Verde 1
    cell 2 0 Rojo 1
    head 2 0
</gs-board>

> Execute o procedimento `Triade`, que deve utilizar 3 parâmetros.
