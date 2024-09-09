# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

const jogos = prompt ("qual jogo você quer?")
const blibliotecaDeJogos = ["Five Nights at Freddy’s Into the Pit", "NARUTO SHIPPUDEN: Ultimate Ninja STORM", "Resident Evil 4", "Marvel’s Spider-Man: Miles Morales"]


console.log([blibliotecaDeJogos.indexOf(jogos)]); // PRA SABER ONDE ESTAR LOCALIZADO A VARIAVEL



switch (jogos){
  case "Resident Evil 4":
    console.log(" Resident Evil 4 custa $34,99")
    break;
 case "Five Nights at Freddy’s Into the Pit":
    console.log("Five Nights at Freddy’s Into the Pit custa $54,00")
    break
  case "NARUTO SHIPPUDEN: Ultimate Ninja STORM":
    console.log("NARUTO SHIPPUDEN: Ultimate Ninja STORM custa $20,00")
    break
    
      case "pop play time":
    console.log("pop play time custa $15,00")
    break

  case "Marvel’s Spider-Man: Miles Morales":
    console.log("Marvel’s Spider-Man: Miles Morales custa $199,90")
    break
  default:
    console.log("infelizmente não temos esse jogo")
}


const adicionarJogos = prompt ("qual jogo você que adicionar")

console.log(blibliotecaDeJogos.push("pop play time"));
