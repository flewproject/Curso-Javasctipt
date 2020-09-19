# Strings

### Método Concat

Caso você queira juntar duas strings, nós utilizamos o método concat, veja um exemplo:

> var a = 'Assine o'
> var b = 'Canal'
> var c = a.concat(' ', b)

Neste exemplo, pegamos o conteudo da variável A, concatenado com a variável B, separados por um espaço e colocamos na variável C

Vamos ver o conteúdo da variável C

> console.log(c)

Um outro exemplo mais simples é utilizar o operador +, veja

> var a = 'Assine o'
> var b = 'Canal'
> var c = a + ' ' + b

Vamos ver o conteúdo da variável C

> console.log(c)

Viu como é fácil?

### Método Trim

Quando trabalhamos com programação, é comum recebermos dados não tratados, como excesso de espaço em uma variável por exemplo, e para isso temos o método trim()

Então vamos declarar uma string com excesso de espaço, assim: 

> var muitoEspaco = '           Projeto Flew'

Veja, que temos espaços sobrando antes do que nos realmente interessa, que nesse caso é o texto **Projeto Flew** 

Porém o método trim() resolve isso na hora, observe:

> console.log(muitoEspaco.trim())

### Método Split

Por último mas não menos importante, temos o método split, que serve para você separar uma string, perceba:

> var projetoFlew = 'Projeto Flew'

Agora vamos imaginar que você quer separar essa string pelo espaço, ou seja, hora que houver um espaço, haverá um corte.

Vamos testar? 

> var teste = 'Projeto Flew'

> console.log(teste.split(' '))

Aqui temos como resultado um array de strings, e se você ainda não sabe o que é um array, fique tranquilo, veremos isso no futuro.

Mas se eu salvar o conteudo em uma nova variável, eu posso acessar os pedaços da string pelas suas posições agora, veja:

> var novoTeste = teste.split(' ')

Se eu quiser acessar o primeiro corte (ou a primeira posição do array) eu simplesmente faço isso: 

> console.log(novoTeste[0])

Com isso, nós terminamos nosso estudo sobre Strings. É fato que existem vários outros métodos para as strings, porém fica inviável eu passar por todos aqui, caso você tenha curiosidade de ver todos, eu recomendo o **W3 Schools**, lá eles tem uma documentação super completa, com exemplos e tudo mais, inclusive boa parte deste conteúdo foi extraido de lá.