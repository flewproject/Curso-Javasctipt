# O que são variáveis ?

Entre as linguagens de programação que eu conheço todas elas se utilizam de variáveis, ou seja, pequenos pedacinhos de memória que guardam um pouquinho de informação dentro delas. E é sóbre isso que iremos falar nessa aula.

# O que eu posso guardar nelas?

As variáveis são as melhores amigas do programador, isso é um fato, porém, você conhece todos os tipos de variáveis que temos no JavaScript? 

Temos:

-  Booleano
	- Verdadeiro ou falso
- String
	- Qualquer valor, desde que esteja entre aspas simples ou duplas (existem algumas exceções)
- Numérico
	- Numeros, seja ele inteiro ou não
- Objeto
	- Um objeto Javascript (será explicado melhor no futuro)
- Array
	- Uma coleção de objetos, como se fosse uma plateleira onde podemos guardar o que quisermos
- Função
	- Como o próprio nome diz, um método que é capaz de realizar alguma ação, processamento ou lógica

E o mais legal no JavaScript (que pode ser um problema as vezes) é que, pela linguagem não ser fortemente tipada, você pode mudar o tipo e conteudo da variável a hora que quiser, veja: 

Se eu declarar minha variavel do tipo texto assim:

> var projetoFlew = 'Projeto Flew'

E logo em seguida usar a função **typeof** para ver o seu tipo, o console imprimrá string, veja:

> typeof projetoFlew // string

porém, se eu atribuir um valor de outro tipo para ela, ela muda na cara dura, veja:

> projetoFlew = true

Se repetirmos o comando **typeof** podemos ver que o seu tipo mudou, observe:

> typeof projetoFlew // boolean

Isso pode ser um grande problema em projetos muito grandes ou em projetos onde precisamos que determinadas variáveis sejam sempre de um determinado tipo, porém, isso fica para as próximas aulas. 