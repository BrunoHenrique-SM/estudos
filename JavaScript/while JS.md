# while
É uma estrutura de repetição ([[loop]]) do [[JavaScript]] . Veja um exemplo:
```
let i = 2;

while (i<=100) {

    console.log(i)

    i*=2

}
```

## do while
Similar ao while, mas garante a a execução do código pelo menos uma vez, mesmo que a condição seja negativa. Veja um exemplo:
```
let x = 0;
do {
	console.log(x);
	x++;
} while (x <=5);
```