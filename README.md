let nome = 'Willian Gabriel';
console.log(`Bem vindo ${nome}!`);
let nome1 = nome ;
alert (`Olá ${nome}!`);
let linguagem = prompt('Qual a linguagem de programação que você mais gosta?');
console.log (linguagem);
let valor1 = 110 ;
let valor2 = 15 ;
let resultado = (valor1 + valor2);
console.log (`A soma de ${valor1} e ${valor2} é igual a ${resultado}`);
let diferença = (valor1 - valor2);
console.log (` A diferença de ${valor1} e ${valor2} é igual a ${diferença}`);
let idade = prompt('digite sua idade');
// se for maior ou igual a 18 anos
if (idade >= 18 ){
    console.log ('Maior de idade');
} else {
    console.log ('menor de idade');
}
let numero = prompt ( 'digite um número');
// verificar se é positivo , negativo ou zero. 
if (numero > 1){
    console.log ('posiivo');
}  if (numero == 0){
    console.log (' zero');}
// se o número for negativo
if (numero < 0 ){
    console.log ('negativo');
}
let numero1 = 1;
while(numero1 <= 10){
    console.log (numero1);
    numero1 ++ ;
}
let nota = 7 ;
if (nota >= 7){
    console.log ('aprovado');
} else {
    console.log ('reprovado');
}
console.log (Math.random ());
console.log (parseInt(Math.random()* 10 + 1));
console.log (parseInt(Math.random()* 100 + 1));
