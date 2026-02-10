São declaradas de três formas, podendo ser declaradas de forma separadas, diferente do [[Python]], que apenas declara as varáveis
```
var x = 20;
const x = "Bruno"
let x = ["casa", "Teste"];

let x;
x = "MC Ig"
```
Já em **Python** seria:
```
x = 20;
x = "Bruno"
x = ["casa", "Teste"];
```

Em JavaScript, `let` e `const` possuem escopo de bloco e evitam problemas comuns do `var`, que tem escopo de função e permite redeclaração. O uso de `const` é recomendado sempre que o valor não precisar ser reatribuído.