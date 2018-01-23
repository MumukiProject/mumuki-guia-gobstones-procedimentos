Viu como ajudou que `DesenharLinhaPreta3` deixasse a garra na célula inicial? Essa é um pouco da magia de **dividir em subtarefas**, nos preocupamos por um problema de cada vez e depois só temos que combinar as pequenas tarefas para resolver nosso objetivo.

Além disso, o código fica muito mais **claro** (será mais fácil entender o que faz), **curto** (é mais fácil de ler) e transmite melhor a **estratégia** que escolhemos para resolver o problema.

Compare sua versão com a que havíamos feito a princípio e vai ver que não estamos mentindo:

``` gobstones
procedure DesenharQuadradoPretoDeLado3() {
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
  Mover(Norte)
  Colocar(Preto)
  Mover(Oeste)
  Colocar(Preto)
  Mover(Oeste)
  Colocar(Preto)
  Mover(Norte)
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
}
```

 
