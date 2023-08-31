# aula-funcoes
//EXERCICIOS

// 1.
// a. vai imprimir o resultado da conta 5x2 e 5x10
// b. nao vai acontecer nada

// 2.
// a. e uma funçao que recebe o texto
// b.
  // 1. true
  // 2. true
  // 3. false

//EXERCICIOS DE ESCRITA DE CODIGO

// 1.
 function informaçoes(nome, idade, cidade, profissao){
    return " Eu sou " + nome + " tenho " + idade + " anos, moro em " + cidade + " e sou " + profissao;
}
console.log(informaçoes("Rafaely", 15, "sao lepoldo", "estudante"));

// 2.
// a.
function numeros(numero1, numero2){
    return numero1 + numero2;
}
console.log (numeros(3, 7));

// b.
function maiorOuIgual(a, b){
    return (a>=b);

}
console.log(maiorOuIgual(8, 5));

// c.
function parOuImpar(a){
    return (a % 2 === 0);
}
console.log(parOuImpar(3));

// d.
function mensagem (a){
    return a.length + " " + a.toUpperCase();
}
console.log(mensagem(prompt("digite uma mensagem")));

// 3.
function soma(a, b){
    return a + b;
}

function sulbtraçao(c, d){
    return c - d;
}

function multiplicaçao(e, f){
    return e * f;
}

function divisao(g, h){
    return g / h;
}

 let n1 = Number(prompt("digite um numero"));
 let n2 = Number(prompt("digite outro numero"));

console.log(soma(n1, n2), sulbtraçao(n1, n2), multiplicaçao(n1, n2), divisao(n1, n2));
