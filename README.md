# AnaliseAlgoritmos
&nbsp;
&nbsp;

**1. Quais são as duas características mais comuns para analisar algoritmos?**

As duas características mais comuns são: Tempo e consumo de memória, respectivamente Complexidade de Tempo e de espaço.

&nbsp;

**2. Por que a medida de tempo em segundos não representa qualificadamente o tempo de execução de um algoritmo?**

Pois a medida de tempo em segundos não é uma medida estável e de qualidade.

&nbsp;

**3. A medida de tempo de um algoritmo é realizada através de qual informação? O que pode afetá-la?**

A medição de tempo é feita através da quantidade de passos que o algoritmo precisa para finalizar sua execução.

&nbsp;

**4. Na análise de algoritmos, qual é o valor da base da função logarítmica e exponencial? Por que é escolhido este valor?**

2, pois o algoritmo que tiver a função com o menor valor representa uma solução melhor, ou seja, o algoritmo precisa de menos tempo ou passos para resolver o determinado problema.

&nbsp;

**5. O que é complexidade de tempo?**

A complexidade de tempo quantifica a porção de tempo tomada por um algoritmo para rodar em função do tamanho da entrada do problema.

&nbsp;

**6. Dado dois algoritmos A e B com as complexidades de tempo respectivamente *f*1 e *f*2, qual é o melhor algoritmo? O que indica qual é o melhor algoritmo?**

O melhor algoritmo é o *f*1, pois tem a entrada menor. 

&nbsp;

**7. Em uma função de complexidade, o que representa o termo *n*?**

O termo *n* representa o tamanho da entrada. 

&nbsp;

**8. Quais são as operações primitivas de um algoritmo?**

Atribuição de valores a variáveis; Chamadas de métodos; Operações aritméticas; Comparação de dois números; Acesso a um arranjo; Seguimento de uma referência para um objeto; Retorno de um método.

&nbsp;

**9. Qual é o valor de uma operação primitiva de um algoritmo?**

Para cada operação primitiva se atribui o valor 1. 

&nbsp;

**10. Desenvolva o pseudocódigo do algoritmo SOMA, que realiza a soma de dois números inteiros recebidos por parâmetro e tem como saída a resultado da operação. Identifique a sua função de complexidade de tempo.**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/Capturar.PNG)

f(n) = c1 * 1 + c2 * 1 

f(n) = 1 * 1 + 1 * 1

f(n) = 1 + 1

f(n) = 2

&nbsp;

**11. Desenvolva o pseudocódigo do algoritmo SOMA_VETOR, que realiza a soma de todos os elementos de um vetor. O algoritmo recebe o vetor V e tem como saída o resultado. Identifique a sua função de complexidade de tempo.**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/11.PNG)

f(n) = c1 * 1 + c2 * 1 + c3 * n + c4 * n + c5 * n + c6 * 1

f(n) = 1 * 1 + 1 * 1 + 1 * n + 1 * n + 1 * n + 1 * 1

f(n) = 1 + 1 + n + n + n + 1

f(n) = 3n + 3

&nbsp;

**12. Desenvolva o pseudocódigo do algoritmo CONTAGEM_IMPARES, que realiza a contagem de números impares de um vetor. O algoritmo recebe o vetor V e tem como saída o resultado. Identifique a sua função de complexidade de tempo.**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/12.PNG)

f(n) = c1 * 1 + c2 * 1 + c3 * n + c4 * n + c5 * n + c6 * n + c7 * 1

f(n) = 1 * 1 + 1 * 1 + 1 * n + 1 * n + 1 * n + 1 * n + 1 * 1

f(n) = 1 + 1 + n + n + n + n + 1

f(n) = 4n + 3

&nbsp;

**13. Desenvolva o pseudocódigo do algoritmo SOMA_MATRIZ, que realiza a soma de todos os elementos de uma matriz. O algoritmo recebe a matriz M e tem como saída o resultado. Identifique a sua função de complexidade de tempo.**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/13.PNG)

f(n) = 1 + 1 + n + n * n + n * n + n * n + n + 1

f(n) = 3n² + 2n + 3

&nbsp;

**14. Desenvolva o pseudocódigo do algoritmo BUSCA_MATRIZ, que identifica posição x e y de um elemento em uma matriz. O algoritmo recebe a matriz M e o valor V e tem como saída a posição x e y. Identifique a sua função de complexidade de tempo.**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/14.PNG)

f(n) = 1 + n + n² + n² + n² + n² + n + 1

f(n) = 4n² + 2n + 2

&nbsp;

**15. O que é análise assintótica? Qual é o seu objetivo?**

A análise assintótica é um método de descrever o comportamento de limites, com objetivo de compreender o tempo de execução para entradas grandes. 

&nbsp;

**16. Qual é o processo da análise assintótica? Crie um exemplo.**

1- *f*(n) = 6n3 + 2n2 + 20n + 45

2- Identificar o componente de maior ordem

3- 6n³

4- Ignorar os coeficientes

5- n³

Dizemos que f é, assintoticamente, no máximo, n³.

&nbsp;

**17. O que é notação assintótica?**

A notação assintótica é para descrever o relacionamento é *f(n) = O(n³)*.

&nbsp;

**18. O que é notação O-Grande ou Big-Oh?**

Notação O-Grande diz que uma função é menor que ou igual a outra função g(n). Ou seja, f é limitada superiormente por g (até no máximo um fator constante) assintoticamente.

&nbsp;

**19. Qual é a definição formal da notação O-Grande?**

Formalmente definimos como: Onde R+ é o conjunto dos reais não negativos.

&nbsp;

**20. Crie um gráfico explicando a notação O-Grande. Utilize f(n) = 2n + 4. Qual é um valor possível para n0?**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/20.PNG)

n0 = 4

&nbsp;

**21. O que é a notação o-pequeno ou Little-Oh?**

Notação o-pequeno diz que uma função é menor que a outra função g(n). Ou seja, f é dominada por g assintoticamente.

&nbsp;

**22. Qual é a definição formal da notação o-pequeno?**

Formalmente definimos como: Onde R+ é o conjunto dos reais não negativos.

&nbsp;


**23. Crie um gráfico explicando a notação o-pequeno?**

![](https://raw.githubusercontent.com/luizaliebl/AnaliseAlgoritmos/master/Imagens/23.PNG)

&nbsp;

**24. Passe a notação O-Grande e o-pequeno as funções abaixo:**

**A) F(n) = n + 1**

O(n)

o(n²)

&nbsp;

**B) F(n) = 8**

O(1)

o(n)

&nbsp;

**C) F(n) = 2n² − 1**

O(n²)

o(2^n)

&nbsp;

**D) F(n) = nlogn**

O(logn)

o(n²)

&nbsp;

**E) F(n) = 3n! + 2n**

O(n!)

o(n!²)

&nbsp;

**F) F(n) = 3n³ + 2n² + 4n + 6**

O(n³)

o(n!)

&nbsp;

**G) F(n) = 5^n + 11**

O(5^n)

o(n * n!)

&nbsp;

**H) F(n) = 3logn**

O(logn)

o(n²)

&nbsp;

**25. Identifique o O-Grande dos algoritmos desenvolvidos nos problemas 10 até 14.**

10- f(n)=2

O(1)

o(n)

&nbsp;

11- f(n)=3n+3

O(m)

o(nlog(n))

&nbsp;

12- f(n)=4n+3

O(n)

o(n²)

&nbsp;

13- f(n)=3n² + 2n + 3

O(n²)

o(n!)

&nbsp;

14- f(n)=4n² + 2n + 2

O(n²)

o(2^n)

