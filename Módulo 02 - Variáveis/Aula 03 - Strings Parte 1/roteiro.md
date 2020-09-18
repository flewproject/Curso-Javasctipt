# Strings

Segundo o <ins>W3 Schools</ins> uma string pode ser uma sequência de 0 ou mais caracteres entre aspas.

E você pode usar aspas simples, ou aspas duplas, e até mesmo acentos acentos graves

Veja alguns uns exemplos:

> var stringUm = 'Projeto Flew'
> var stringDois = 'Projeto Flew'
> var stringTres = `Projeto Flew`
> var stringVazia = ''


# Métodos e propriedades

**Lembra que eu te falei que tudo é um objeto no Javascript?**

Veja que legal, as strings, possuem métodos que você pode invocar a qualquer momento, observe: 

Eu vou declarar uma variável chamada **stringTeste** e nós vamos ver os métodos que nós podemos chamar a partir dessa variável.

> var stringTeste = 'Assine o Canal'

### Propriedade Lenght

Se quisermos saber quantos caracteres uma variavel do tipo string possui, nós podemos chamar uma propriedade chamada length nela, observe:

> console.log(stringTeste.length)

### Método indexOf()

Podemos também procurar por uma string dentro de outra string, esse método **indexOf** ele retorna a posição da string caso a encontre e retorna **-1** caso o que você está procurando não exista, veja:

> console.log(stringTexte.indexOf('Canal'))

agora se vamos procurar algo que não existe, temos o seguinte resultado: 

> console.log(stringTeste.indexOf('girafa'))

### Método Slice()

Existem várias formas em JavaScript de extrair partes de uma string, porém eu vou mostrar apenas um, o **SLICE**, caso você se interesse, os outros são: 

> str.substring(argC, argV)
> str.substr(argC, argV)

Veja que legal, imagine que eu quero apenas as quatro primeiras letras da minha string, eu consigo isso com a função **slice()**, observe:

> console.log(stringTeste.slice(0, 4))

O método slice, ele usa dois argumentos, o primeiro é a partir de qual posição da string eu vou começar a cortar e o segundo é até qual posição eu vou cortar. Se eu quisesse começar da posição dois, eu faria isso:

> console.log(stringTeste.slice(2, 4))

### Método Replace()

Imagine que você quer substituir algo em uma String, para isso temos o método **replace()**, ele é bem simples e leva dois argumentos, veja: 

> console.log(stringTeste.replace('Assine', 'Curta'))

Lembrando que esse método só substitui a primeira ocorrência do que você está procurando, para isso, deixe-me te mostrar uma coisa, vou criar uma nova variável

> var testeFlew = 'Banana Banana Maçã'

Vou substituir agora a palavra Banana

> console.log(testeFlew.replace('Banana', 'Limão'))

Viu que só substitiu a primeira ocorrência? Caso você queira substituir **TODAS** as ocorrências, basta usar a função **replaceAll()**

neste caso: 

> console.log(testeFlew.replaceAll('Banana', 'Limão'))

Lembrando que esse método é **CASE SENSITIVE** ou seja, se eu escrever a palavra Banana em minusculo, ele não vai substituir, perceba:

> console.log(testeFlew.replaceAll('banana', 'Limão'))

### Métodos Upper e Lower Case

Estes são simples e você vai entender de primeira, eles servem basicamente para você converter uma string para maiusculo ou minusculo, veja:

> console.log(stringTeste.toUpperCase())

ou

> console.log(stringTeste.toLowerCase())

Fácil né?