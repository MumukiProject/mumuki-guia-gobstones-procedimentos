Como adiantamos pra você no exercício anterior, os procedimentos podem ter mais de um **parâmetro** (ou _buraquinho_).

Por exemplo: o que aconteceria se agora queremos que `DesenharLinha3` sirva para desenhar linhas em qualquer direção? Sem dúvida necessitaremos que quem use o procedimento nos diga, além da `cor`, em qual `direcao` quer que desenhemos a linha; e para isso necessitamos um novo **parâmetro**.

E como se faz isso? Muito fácil, da mesma maneira que fazemos quando escrevemos, vamos **separar cada parâmetro usando vírgulas**. Veja como fica:

``` gobstones
procedure DesenharLinha3(cor, direcao) {
  Colocar(cor)
  Mover(direcao)
  Colocar(cor)
  Mover(direcao)
  Colocar(cor)
}
```

(Para simplificar a explicação, por enquanto vamos esquecer da posição final da garra. Já voltaremos com isso nas próximas unidades.)

> Sua tarefa agora é escrever um `program` que use a nova versão de `DesenharLinha3` (não necessita implementar, apenas usá-la) e desenhe um quadrado multicolorido como este:
 
<gs-board>
  GBB/1.0
    size 4 4
    cell 0 1 Azul 1
    cell 0 2 Azul 1
    cell 0 3 Azul 1
    cell 1 3 Negro 1
    cell 2 3 Negro 1
    cell 3 3 Negro 1
    cell 3 2 Rojo 1
    cell 3 1 Rojo 1
    cell 3 0 Rojo 1
    cell 2 0 Verde 1
    cell 1 0 Verde 1
    cell 0 0 Verde 1
    head 0 0
</gs-board>