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
 
![Cuadrado multicolor](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-2-procedimientos/master/4x4h00cuadrado-multicolor.png)