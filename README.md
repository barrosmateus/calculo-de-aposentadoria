# calculo-de-aposentadoria
aula básica de programação - desafio 2



 const nome = 'mateus'
 const sexo = 'm'
 const idade = 60 
 const tempoDeServiço = 35

 if (sexo == 'm') {
     if(tempoDeServiço >= 35){
        const calculoParaHomem = idade + tempoDeServiço
             if (calculoParaHomem >= 90){
             console.log(`parabens voce é homem e ja pode aposentar`)
            }else{
             console.log(`voce é homem e ainda nao pode aposentar`)
            }
        
     }else{
        console.log(`voce é homem e ainda nao pode aposentar por causa do tempo e serviço`)
    }   
 }else{ 
     if(tempoDeServiço >= 30){
        const calculoParaMulher = idade + tempoDeServiço
            if (calculoParaMulher >= 85) {
                console.log(`parabens voce é mulher e pode se aposentar`)
            }else{
                console.log(`voce é mulher e ainda nao pode aposentar`)
            }
     }else{
        console.log(`voce é mulher e ainda nao pode aposentarpor causa do tempo de cerviço`)
    }
 }



/*
Resposta fornecida pelo professor
(!!! pode ser colocado um conjunto de comparadores logicos dentro do recebe de uma viriavel,
e ela ira retornar um true ou falseque pode ser usado para diminuir a quantidade de if´s do meu código!!!)


const nome = 'Silvana'
const sexo = 'F'
const idade = 48
const contribuicao = 23

const calculoContribuicao = idade + contribuicao

// essas variáveis irão retornar true ou false
const homemPodeAposentar = sexo == 'M' && contribuicao >= 35 && calculoContribuicao >= 95
const mulherPodeAposentar = sexo == 'F' && contribuicao >= 30 && calculoContribuicao >= 85

if ( homemPodeAposentar || mulherPodeAposentar) {
    console.log(`${nome}, você pode se aposentar!`)
} else {
    console.log(`${nome}, você não pode se aposentar!`)
}
*/
