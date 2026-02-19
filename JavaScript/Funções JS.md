# Funções
o [[JavaScript]] possui alguns modos de declarar uma [[Função]], vamos entender como e quando usa-los. O primeiro sendo a declaração formal:

## Tipo de funções
```
//Cria a função 
function saudacao(nome){
    console.log('Olá ' + nome + '!');
     }
//Invoca a função 
saudacao();
```
Aqui **saudacao()** é o nome da função e **nome** é o parâmetro necessário e o retorno é o uma [[string]], nesse modo tudo é declarado.
O segundo modo é chamado de função anônima:
```
const divisao = function(dividendo,divisor) {
	if (divisor == 0)
		return "Não é possível dividir por zero";
		
	if (divisor == 1)
		return dividendo
	
	return dividendo / divisor;
}
```
Em que o nome da função não é declarado, uma coisa interessante nesse código é que o [if]([[if]]) por possuir apenas uma linha, não precisa de chaves.
E por último temos as arrow functions:
```
//Cria a função
const quadradoDo = (num1) => num1 * num1;
console.log(quadradoDo(6)) //36
```
Aqui o return é declarado na própria função, utilizada para funções simples
