#Começando com conceitos básicos  

##Hoisting
Declaração de uma variável após ela ser utilizada.  

####Exemplo  

```javascript

meuNome = 'Lucas';
var meuNome;  
```  

##Closure
É uma função aninhada. O interessante de se usar o closure é ela ter acesso a variável da função pai.  

####Exemplo  

```javascript  
  
function primaria() {
    var idade = 18;  

    function mostrarIdade()
    {
     
        console.log(idade);  

    }  
     
    return mostrarIdade;
} 

var mostrar = primaria();  
mostrar();  
```  
##Variavel Global  
É uma variável que pode ser usada por qualquer escopo no programa.  
  
####Exemplo  

```javascript  

var i = 0;  

function somar(){  
   return i++;  
}

function subtrair(){
   return i--;  
}  
```  
##Parametros  
Os parâmetros são variáveis que passam os valores para a função quando a chamamos. Eles podem escrever qualquer tipo de dado, seja ele: númerico, textual, boleano ou um objeto.  

####Exemplo  

```javascript  

function somar (numeroUm, numeroDois){  
    return numeroUm + numeroDois;  
}  

somar(1, 2);  
```
##IIFE ou "Immediately-invoked function expression"  
Podemos chama-la de função imediata. IIFE refere-se a função que pode ser executada logo após ser criada. Para que ocorra sem erro, é preciso transforma-la em uma expressão.  






