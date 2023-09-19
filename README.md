// this is a js file
// joao arthur

//exercicio 1)
/* let valor = 0
for(let i = 0; i < 5; i++) {
valor += i
}
console.log(valor) */

/* o nome da sua variavel se chama valor o valor dessa variavel é 0
ele esta perguntando se o valor da sua variavel mias um é menor que 5. */

//exercicio 2)
/* const lista = [10, 11, 12, 15, 18, 19, 21, 23, 25, 27, 30]
for (let numero of lista) {
if (numero > 18) {
console.log(numero)
}
} */ 

/* a)ele esta perguntando se tem um numero maior que 18. vair ser imprsso o numero 30 porque ele é maior que o numero 18. */
/* b)poderia ser osado o for of para separar cada elemento , no caso cada um teria a sua linha . */


//exercicio 3)
/* const quantidadeTotal = Number(prompt("Digite a quantidade de linhas: "))
let quantidadeAtual = 0
while(quantidadeAtual < quantidadeTotal){
let linha = ""
for(let asteriscos = 0; asteriscos < quantidadeAtual + 1; asteriscos++){
linha += "*"
} */

/* seria 5  */

//exercicios de escrita codigo 
// exercicio 1)
/* a) Se a quantidade for 0, imprima no console "Que pena! Você pode adotar
um pet!"
b) Se a quantidade for maior que 0, solicite que o usuário digite os nomes
deles, um por um, e guarde esses nomes em um array
💡 Dica
⭐ Coloque o seu prompt dentro de um loop. Esse loop deve ser
executado a mesma quantidade de vezes que o usuário
inseriu. Por exemplo: se o usuário tem 4 pets, ele deve
conseguir inserir 4 nomes.
Laços 4
c) Por fim, imprima o array com os nomes dos bichinhos no console */

/*  let pets = Number(prompt("quantos pets voce tem?"));
let i = 0;
let bichos = [];
if(pets===0){
console.log("Que pena! Você pode adotar um pet");
}
else{
    while (i <= pets -1) {
        bichos[i] = prompt("nome do bicho");
        i++;
    } 
}
console.log(bichos);
  */

/* Considere que você tenha acesso a um array (chamado de 'array
original') que é composto somente de números. Baseando-se nisso, crie
uma função para cada um dos itens abaixo, realizando as operações
pedidas:
a) Escreva um programa que imprime cada um dos valores do array
original.
b) Escreva um programa que imprime cada um dos valores do array
original divididos por 10
c) Escreva um programa que crie um novo array contendo, somente, os
números pares do array original e imprima esse novo array
d) Escreva um programa que crie um novo array contendo strings, da
seguinte forma: "O elemento do índex i é: numero ". Depois, imprima este
novo array.
e) Escreva um programa que imprima no console o maior e o menor
números contidos no array original */


/* const arrayOriginal = [80, 30, 130, 40, 60, 21, 70, 120, 90, 103, 110, 55]

for (const iterator of arrayOriginal) {
    if (iterator %2===0 ){
        console.log(iterator %2=== arrayOriginal)
    }
    
}
for (const iterator of arrayOriginal){
console.log(iterator / 10)
}
 
const arrayoriginal2 = ["a", "b", "c", "d"];
for (const i of arrayoriginal2) {
  console.log(i);
} */# aula-017
joaoarturrs
