# Tipos de dados  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Javascript-shield.svg/397px-Javascript-shield.svg.png" alt="drawing" width="30" height="40"/>

 ___

 __Todas as linguagens de programação têm sua própia estrutura de dados embutida, mas essa estrutura frequentemente difere uma da outra. este artigo busca listar os tipos de dados disponíveis na linguagem JavaScript e que propriedades eles possuem. Quando possível, comparações com outras linguagens serão apresentadas.__

 ___

 ## Tipagem dinâmica

__JavaScript é uma linguagem *dinâmica*. Isso significa que você não necessita declarar o tipo de uma variável antes de sua atribuição. O tipo será automaticamente determinado quando o programa for processado. Isso também significa que você pode reatribuir uma mesma variável com um tipo diferente:__

~~~javaScript
var foo = 42; //foo é um number agora 
foo = "bar" ; //foo é um string agora
foo = true ; //foo é um boolean agora
~~~
 ___ 

## Tipos de dados 

A ultima versão **ECMAScript** define sete tipos de dados: 

* sete tipos de dados são primitivos :        
  * [boolean](https://github.com/maximos34/CursosdeProgramacao/blob/main/Udemy/cod3r/algoritimosComJs/materias/DataTypes/TypeBoolean.md)
  * null
  * undefined
  * number
  * bigInt
  * string
  * symbol
  * object
  ___

  ## valores Primitivos 

  Todos os tipos, com a excessão de objetos, definem valores imutáveis ( valores que são incapazes de mudar ). Por exemplo e diferente  da linguagem C, strings são imutáveis. Nós nos referimos a valores desse tipo como "valores primitivos"