E se agora quero fazer um quadrado vermelho? Ou um verde? Tenho que escrever tudo isso de novo?

Com certeza **não**! A programação se trata de automatizar tarefas repetitivas! :smile:

Vamos começar com algo fácil: suponhamos que queremos **generalizar** o procedimento `Colocar3Verdes`, para que funcione com qualquer cor que quisermos (mas só um de cada vez). O que precisamos é adicionar ao procedimento uma espécie de _buraco_...

``` gobstones
procedure Colocar3(cor) {
  Colocar(cor)
  Colocar(cor)
  Colocar(cor)
}
```

...que possa ser logo completado cada vez que seja usado:

``` gobstones
program {
  Colocar3(Preto)
  Colocar3(Vermelho)
}
```

> Escreva os códigos anteriores no editor e observe o que acontece.
