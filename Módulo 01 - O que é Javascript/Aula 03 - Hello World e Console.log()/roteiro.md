# Hello World

Para escrevermos nosso primeiro código em JavaScript, eu irei utilizar o próprio console do navegador, no meu caso eu estou utilizando o Google Chrome, e para abrir o console basta eu apertar a tecla **F12** no meu teclado.

É um costume muito comum na área de programação, quando estamos aprendendo uma nova linguagem, criarmos o famoso **Hello World** como a primeira função, porém, em JavaScript é estupidamente fácil criar um Hello World, veja: 

    console.log('Hello World')

Viu como é simples? mas para nossa aula não ter poucos segundos de duração, deixe-meu mostrar para você o que mais a gente pode fazer com o objeto **console** do JavaScript

# Objetos
Em JavaScript com exceção de **null** e **undefined** todos os tipos premitivos são tratatados como objetos, ou seja, eles podem receber propriedades e possuem todas as caracteristicas de <ins>objetos.</ins>

Ou seja, o objeto:

    console

tem vários métodos que podem ser acessados fácilmente, veja alguns exemplos:

## console.log()
Se eu quiser escrever algo normalmente na tela, eu invoco o métodos **log()**

    console.log('Projeto Flew')

Geralmente utilizamos este métodos para debugar o nosso código e ver o conteudo de algumas váriaveis, visto que o metodo **log()** aceita qualquer tipo de variável.

## console.warn()
O método **warn()** serve para exibir um alerta no console, ou seja, quando eu quiser que uma mensagem tenha a importância de um alerta, eu exibo ela atráves do método **warn()**. Veja um exemplo: 

    console.warn('Projeto Flew')

## console.error()
Quando eu quiser registrar uma mensagem dizendo que algo deu errado na minha aplicação, eu devo exibir esta mensagem através do metodo **error()**. Veja um exemplo:

    console.error('Projeto Flew')

# Conclusão
Honestamente, hoje em dia temos inúmeros metodos melhores para se debugar um código, porém, as vezes é mais fácil utilizar o console para tirar uma dúvida rápida ou algo do tipo. 

Agora que você já sabe como imprimir uma mensagem no seu console, vamos para a próxima aula, na qual falaremos sobre tipos de variáveis. Até lá.