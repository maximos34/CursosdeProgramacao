# Tipo de dado null    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Javascript-shield.svg/397px-Javascript-shield.svg.png" alt="drawing" width="40" height="50"/>

___

## Resumo
O valor é escrito com um literal: .não é um identificador para uma propriedade do objeto global, como pode ser identificado. Em vez disso, expressa uma falta de identificação, indicando que uma variável aponta para nenhum objeto. Em apis, muitas vezes é recuperado em um lugar onde um objeto pode ser esperado, mas nenhum objeto é relevante.  
____
## sintaxe
~~~javaScript
null
~~~
___

## Descrição 

O valor null é um literal, e não uma propiedade do objeto global (como por exemplo o UNdeFined pode ser ). O desenho da API, o null as vezes é devolvido no lugar de um objeto que era esperado, quando fizer a checagem de um valor para null ou undeFined, esteja ciente das diferenças entre o operador de igualdade ( == ) e o de igualdade estrita ( === ). uma conversão de tipos é realizada na operação de igualdade.

~~~javaScript
// foo não existe, não foi definido e jamais foi inicializado:
> foo
"ReferenceError: foo is not defined"

// foo é conhecido e existe, mas não aponta para nenhum tipo ou valor:
> var foo = null; foo
"null"
~~~

## DIFERENÇAS ENTRE NULL e UNDEFINED
~~~javaScript
typeof null        // object (bug no ECMAScript, deveria ser null - http://2ality.com/2013/10/typeof-null.html)
typeof undefined   // undefined
null === undefined // falso
null  == undefined // verdadeiro
~~~