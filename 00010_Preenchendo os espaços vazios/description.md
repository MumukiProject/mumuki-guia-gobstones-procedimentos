Vamos entender o que acabamos de fazer. :hushed:

A primeira coisa que fizemos foi declarar um procedimento, mas com uma pequena diferença: usar um _parâmetro_, chamado `cor`.

``` gobstones
procedure Colocar3(cor) {
  Colocar(cor)
  Colocar(cor)
  Colocar(cor)
}
```

Os parâmetros (esses nomes que estão entre parênteses) são especiais, porque são substituídos por valores concretos quando os invocamos. Por exemplo, se invocamos o parâmetro assim:

``` gobstones
program {
  Colocar3(Preto)
}
```

...o que se executa é:

``` gobstones
Colocar(Preto)
Colocar(Preto)
Colocar(Preto)
```

E se invocamos o parâmetro assim:

``` gobstones
program {
  Colocar3(Vermelho)
}
```

o que se executa é:

``` gobstones
Colocar(Vermelho)
Colocar(Vermelho)
Colocar(Vermelho)
```

Note como cada vez que aparece `cor`, ele é substituído pelo valor que passamos na invocação.

> Vamos ver se você está entendendo: escreva um programa que coloque três pedras verdes usando o procedimento Colocar3.
 
