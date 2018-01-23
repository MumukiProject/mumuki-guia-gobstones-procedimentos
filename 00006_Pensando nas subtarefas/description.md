Bom, já sabemos como criar procedimentos, mas por que mesmo queríamos fazer isso?

Algumas possíveis respostas:

* Para **simplificar código**, escrevendo apenas uma vez e em um único lugar coisas que vamos fazer muitas vezes;
* Para **escrever menos**, porque nós programadores somos um pouco preguiçosos;
* Para que o propósito do nosso programa **seja mais compreensível para os humanos**, como vimos no exemplo de `DesenharQuadradoPretoDeLado3`. Para isso é fundamental **pensar em nomes adequados**, que não sejam muito longos (`DesenharUmQuadradoPretoCom3DeLarguraE3DeComprimento`), nem muito curtos (`DesQuadPre3`), e principalmente que **deixem claro que efeito produz em nosso procedimento**;
* Para comunicar a **estratégia** que pensamos para resolver nosso **problema**;
* E como consequência de tudo isso: para **poder escrever programas mais poderosos**.

Nos seguintes exercícios, vamos escrever uma versão melhorada de  `DesenharQuadradoPretoDeLado3`, dividindo cada parte do problema em procedimentos menores. Para isto, vamos propor a seguinte **estratégia**: construir no quadrado  três linhas com três pedras, uma em cima da outra.  Vamos precisar de um comando para desenhar uma linha, então que comecemos por aí.

> Escreva um procedimento `DesenharLinhaPreta3` que, como seu nome indica, "desenhe uma linha" colocando 3 pedras pretas consecutivas em direção ao Leste.

**Observação**: De agora em diante, exceto que se indique o contrário, nós montaremos o `program`. Você tem que apenas escrever o procedimento.