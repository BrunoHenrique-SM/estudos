# for
É uma estrutura de repetição ([[loop]]) do [[JavaScript]] utilizado quando sabe-se a quantidade exata de loops à serem feitos. Veja um exemplo:
```
let numero = 5;
for (let i = 1; i <= 10; i++) {
	console.log(numero + " x " + i + " = " + (numero*i));
}
```
Dividido em 3 partes por ";", temos na primeira a inicialização, onde é definido um valor para começar a contagem, na segunda é definida a condição de parada e na terceira, o incremento