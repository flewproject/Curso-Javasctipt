# Nomenclaturas de variáveis

Embora o JavaScript seja bem permissivo com seus tipos, temos algumas boas práticas que ajudam o desenvolvimento de software ficar mais agradável ao programador, e dentre essas boas práticas, temos os padrões de variáveis. 

Eu já trabalhei em vários projetos, e em cada um deles eu vi uma forma diferente de padronizar as variáveis, veja alguns exemplos:

> var projetoFlew = 'Projeto Flew'  
> var projeto_flew = 'Projeto Flew'  
> var ProjetoFlew = 'Projeto Flew'  
> var _projetoFlew = 'Projeto Flew'  
> var $projetoFlew = 'Projeto Flew'

Ou seja, podemos começar as nossas variáveis com maiusculas, minusculas, underlines e até cifrões! Porém, não podemos nomear nossas variáveis começando com números, veja uma tentativa
> var 1projetoflew =  'Projeto Flew'   
> // Uncaught SyntaxError: Invalid or unexpected token

Mas o JavaScript é bem estranho com suas regras, se eu tirar o numero um do começo da variável e colocar em qualquer posição, ele permite tranquilo, veja:

> var projetoFlew1 = 'Projeto Flew'

Doideira né?

Inclusive, eu vou contar um segredo para vocês que eu não conto para ninguém: <ins>No JavaScript é possível nomear variáveis com acentos!</ins> Mas pelo amor de tudo que é mais sagrado na computação, não faça isso! Além de ser uma péssima prática de programação, é possível que um colega de trabalho mais experiente perca a linha e parta pra cima de você caso encontre um código seu com variáveis acentuadas! 

Eu sei que você tá curioso, e se ainda não testou no seu computador, veja um exemplo:
> var mamão = 'Fruta'

**EU REPITO! NÃO FAÇA ISSO EM CASA!** (E em lugar nenhum)

# Case Sensetive

Como se já não bastasse todas essas regras bizarras do nosso amado JavaScript, temos também que lembrar que as variáveis são Case Sensitive, ou seja, o interpretador diferencia letras maiusculas e minusculas, veja: 
> var variavelTeste  = 10

Se eu tentar ver o seu conteudo, a escrevendo de forma errada, eu não verei o seu conteudo, veja: 

> typeof variavelteste  
// "undefined"

Ou seja: **SEMPRE TOME MUITO CUIDADO COM A ESCRITA DE SUAS VARIÁVEIS**

# Nomeie variáveis como se fosse nomear um filho

Eu sempre digo isso pois uma variável bem nomeada, pode fazer com que o entendimento de um software seja 10x melhor, veja um exemplo: 

Imagine que você está dando manutenção em um software de músicas e precisa saber onde estão salvas várias informações da música atual, como:
- Duração da Faixa
- Posição atual da música
- Tempo restante

Então, depois de uma fuçada no código você vê as variáveis: 

> var ddf = 120  
> var paf = 40  
> var tr = (ddf - paf)

Viu como é confuso? O que é **DDF** o que é **PAF** e pior, o que é **TR** ?

Veja só como nossa leitura do código seria melhor se o programador tivesse escrito as variáveis de uma forma descente:

> var duracaoDaFaixa = 120  
> var posicaoAtualFaixa = 40  
> var tempoRestanteFaixa = (duracaoDaFaixa - posicaoAtualFaixa)

Bem melhor né?

Agora que você já sabe o que são variáveis e como elas funcionam, vamos passar rápidamente por elas nas próximas aulas para que você entenda melhor. 

Até a próxima aula!

[Fonte @ Todo Espaço Online](https://www.todoespacoonline.com/w/2014/04/variaveis-em-javascript/) 

