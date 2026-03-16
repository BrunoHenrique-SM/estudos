# Funções
Uma função pode ser criada com a [[Variável]] [[Function]], o **nome da função** e o os **parênteses**, também é possível exigir alguns [parâmetros](#Paramêtros) que serão usados na função. O [[JavaScript]] possui alguns modos de declarar uma [[Função]], vamos entender como e quando usa-los. O primeiro sendo a declaração formal:

## Variáveis locais
São variáveis declaradas na função, que podem apenas ser usadas naquela função, por isso possuem o nome de variáveis locais.
```
// code here can NOT use carName  
  
function myFunction() {  
  let carName = "Volvo";  
  // code here CAN use carName  
}  
  
// code here can NOT use carName
```
Como variáveis locais só podem usadas na função, o nome da variável pode ser reutilizado em outras funções.

## Parâmetros
**Parâmetros** são os valores enviados as funções, que são listados dentro dos **parênteses**:
```
function toCelsius(fahrenheit) {  
  return (5 / 9) * (fahrenheit - 32);  
}  
  
let value = toCelsius(77);
```


## Criando funções
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
