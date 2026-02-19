# if
Toda linguagem de programação possui estruturas de controles como [[loop]] e condicionais, no [[JavaScript]] não seria diferente. O if estabelece uma condição pra que um comando seja executado, por exemplo:
```
if (meuTimeGanhar){
	beberCerveja();
}
//Agora programando de fato
if (numero == 2){
	console.log("São iguais");
}
```
No primeiro caso, um [[Pseudocódigo]], a vitória do time é o condicional para poder beber, no segundo, o condicional é a igualdade dos números. Em JavaScript a condição fica entre parênteses

## Ternário
Há um modo mais enxuto de declarar os condicionais, chamado de ternário, onde com uma linha é possível declarar tanto o if quanto o else.
```
const nota = 7;
const aprovado = nota >= 6 ? "SIM" : "NÃO";
console.log(aprovado)
```
Aqui o "?" faz essa verificação, a primeira [[string]] será atribuída a variável se  a condição for verdadeira e caso contrário será a segunda.