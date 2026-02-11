## Primeira conexão
Caso você deseje adicionar um [repositório](Repositório) ao seu computador, siga os seguintes passos, que vai te levar do zero até seu primeiro [[push]]

### config
A primeira coisa que se deve fazer ao instalar o git na máquina é definir o nome de usuário e email
```
git config --global user.name "BH casa"  
git config --global user.email bhcasa@gmail.com
```
E para conferir o nome ou email da máquina basta apenas escrever o comando sem declarar algum usuário ou email:
```
git config --global user.name
```
### [[init]]
Depois de registrar o computador comece a rodar o GIT na pasta:
```
git init
```

### clone
Clone o repositório a partir do link do GitHub, assim os arquivos serão baixados para a pasta e após isso entre na pasta baixada:
```
git clone <link-do-repositorio>
cd <nome-da-pasta>
```

### [[branch]]
Nas empresas o comum é cada computador ser uma branch diferente, para que cada alteração tenha autor, através delas é possível realizar mudanças, verifica-las e então adicionar à branch main. Então aqui, ao entrar na main, pode se verificar através do comando branch isolado:
```
$ git branch
  casa
* main
```
Essa branch será alterada através do merge, aqui iremos programar em uma diferente. Apesar de estarmos falando de branch o principal comando é o checkout:
```
git checkout -b <nova-branch>
git checkout <nome-da-branch> //muda para a branch
```
### add
Para adicionar os arquivos que serão alterados ou adicionados no [[commit]], utilize o comando:
```
git add <nome-do-arquivo>
git add . //Para adicionar todos os arquivos
```

### commit
Para atualizar as mudanças na [[branch]], realize o commit:
```
git commit -m mensagem do commit
```

### push
Com o push podemos enfim postar a mudança no repositório:
```
git push origin <nome-da-branch>
```

### [[merge]]
E por fim, quando o repositório for seu e você queira fazer um merge entre uma branch e a main, basta estar na main e:
```
git merge <nome-da-branch>
```



