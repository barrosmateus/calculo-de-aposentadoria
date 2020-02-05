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
