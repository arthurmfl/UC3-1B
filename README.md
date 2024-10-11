# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

## apredendo if elese

const pergunta1=prompt('Já pensou em se matar???')
if(pergunta1=="sim"){
  console.log("Bom, continue assim...")
  }
else{
  const pergunta2 = prompt('Tem certeza???')
  if(pergunta2=="sim"){
    console.log("Bom")
  }
  else{
    console.log("Que pena...")
  }
}



## Essa atividade foi pra apreder switch case:

let frutas = ["banana", "maça", "pera", "uva"]
let pedido = prompt("qual fruta você quer?")
switch(pedido){
case "maçã":
  console.log("Maçã custa $4,00")
break
}
switch(pedido){
case "banana":
console.log("banana a palma custa $12,00")
break
}
switch(pedido){
  case "pera":
    console.log("a pera custa $8,00 kg")
break
}
switch(pedido){
  case "uva":
    console.log("o caichho da uva custa $10,00 kg")
    break
}

let pos = frutas.indexOf(pedido)
console.log(pos)

## aqui começamos ver um pouco de arry 

var arr = ["este é o primeiro elemento", "este é o segundo elemento", "este é o terceiro elemento"];
console.log(arr[0]); // exibe 'este é o primeiro elemento'
console.log(arr[1]); // exibe 'este é o segundo elemento'
console.log(arr[arr.length - 1]); // exibe 'este é o segundo elemento'



## aqui apredendo ma contar os intens na arry

const livro =["javascript Asertico", "engenheria de Testes", "clean code", "Scrum", "guia hTML5 CSS3", "MogoDB"]
/*st atualizandoLivros = livro.splice(0, 0, "NodeJS" );
console.log(atualizandoLivros)

console.log(livro)*/
/*const tamanhoLivro = livro.length;
const corredorA1 = livro.slice(0, tamanhoLivro /2);
const corredorA2 = livro.slice(tamanhoLivro /2);
console.log ("os livros do corredor A1 são" , corredorA1);
console.log("os livros do corredor A2 são" , corredorA2);*/
const hqs = ["turma da monica" , "marvel spider-men", "x-man" , "batmam"]
const juntarLivro = livro.concat(hqs)
console.log(juntarLivro)

## começando a aprender fucution fazendo jogos

//Impar ou par
function parimpar(n){
  if(n%2==0){
    return 'par'
  }
  else{
    return 'impar'
  }
}
let res=parimpar(12)
console.log(res)

//Soma
function soma(n1,n2){
  return n1+n2
}
console.log(soma(2,5))

//fatorial
function fatorial(n){
  if(n==1){
    return '1'
  }else{
    return n * fatorial(n-1)
  }
}
console.log(fatorial(5))

## apredendo funçoes  com if elese e swchic case

/*function soma (num1, num2) {
  return num1 + num2
}

function subtrair (num1, num2) {
  return num1 - num2
}
  const  compra1 = prompt ("qual valor da primeira compra")
  const compra2 = prompt ("qual o valor da segunda compra")
  
  if(compra1 > compra2) {
    console.log(soma(compra1, compra2)) 
  } else if(compra1 < compra2) {
  console.log(subtrair(compra1, compra2))
  } else {
    console.log("erro")
  } */

function feriados() {
  const mes = prompt("qual é o mês que você quer saber o feriado");
  switch (mes) {
    case "janeiro":
      alert("1º de janeiro: Confraternização Universa");
      break;
    case "fevereiro":
      alert("Carnaval, Quarta-feira de Cinzas");
      break;
    case "março":
      alert("não temos feriados :( ");
      break;
    case "abirl":
      alert("21 de abril: Tiradente");
      break;
    case "maio":
      alert("1º de maio: Dia do Trabalhador");
      break;
    case "junho":
      alert("Não há feriados nacionais fixos.");
      break;
    case "julho":
      alert("Não há feriados nacionais fixos.");
      break;
    case "agosto":
      alert("Não há feriados nacionais fixos.");
      break;
    case "setembro":
      alert("7 de setembro: Independência do Brasil");
      break;
    case "outubro":
      alert("12 de outubro: Nossa Senhora Aparecida");
      break;
    case "novembro":
      alert("2 de novembro: Finados,15 de novembro: Proclamação da República");
      break;
    case "Dezembro":
      alert("25 de dezembro: Nata");
      break;
    default:
      alert("não existe esse mes");
  }
}
console.log(feriados());

## mas um pouco de fuction

function manageStrings(strings, stringToRemove) {
  
    console.log("Strings atuais:", strings);

    const updatedStrings = strings.filter(str => str !== stringToRemove);

   
    updatedStrings.sort();

    
    return updatedStrings;
}


const myStrings = ["banana", "maçã", "laranja", "abacaxi"];
const result = manageStrings(myStrings, "laranja");

console.log("Array atualizado:", result)
