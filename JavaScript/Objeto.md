# Objeto
Em [[JavaScript]] é mais fácil declarar um objeto, enquanto no **Python**, temos que criar a classe de qual o objeto faz parte e declarar os atributos requiridos, no **JavaScript** podemos apenas declarar o objeto e depois adicionar mais atributos se necessário
```
var aluno = {

    codigo: "0",

    nome: "Bruno Henrique da Silva Matos",

    cpf: "11539093913"

};

aluno.idade = "20";

turmas = ["Francês", "Inglês", "Alemão"];
aluno.turmas = turmas;
```
## Objeto literal
É uma maneira simples de declarar objetos, onde a classe não é criada apenas o objeto:
```
const candidato = {nome:"Carlos", cpf:"12345678910"}
```
## Construindo a classe
Porém a forma mais comum de declarar um objeto, mas antes é necessário declarar a classe e seus métodos. Veja o exemplo a seguir:
```
//Criar uma classe

class Candidato{

    //Método construto

    constructor(nome,cpf,idioma){

        this.nome = nome;

        this.cpf = cpf;

        this.idioma = idioma;

        //Atributo privado

        this._passado = false;

    }

  

    //Método para aprovar aluno

    aprovado(){

        this._passado = true;

    }

}

const alunos = [];

//Criando objeto

alunos[0] = new Candidato("João", "11539093913", "Inglês");

  

//Usando método aprovado()

alunos[0].aprovado();

  
  

//Herança

class Extra extends Candidato{

    constructor(nome,cpf,idioma,presencial){

        super(nome,cpf,idioma,);

        this.presencial = presencial

    }

}

  

alunos[1] = new Extra("Carla","11539093923", "Espanhol", true);

alunos[1].aprovado();
```
