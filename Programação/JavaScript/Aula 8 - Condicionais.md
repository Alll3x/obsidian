# Aula 8 - Condicionais

# Quais são

- If.. else
    - Operado Se.. senão
        - Usa-se quando precisa fazer uma comparação
    
    ```jsx
    //Se a hora for entre 06:00 e 12:00 : bom dia
    //Se entre 12:00 e 18:00 : boa tarde
    //Caso contrário boa noite
    
    let hora
    
    if(hora > 6 && hora < 12){
    	console.log("Bom dia")
    }else{
    	if(hora >= 12 && hora > 18){
    	console.log("Boa tarde")
    }else{
    	console.log("Boa noite")
    }
    }
    ```
    
- switch case
    - Usa-se quando não se precisa fazer comparação
    
    ```jsx
    let permissao // gerente || comum || diretor
    
    switch (permissao){
    	case 'comum':
    		console.log('Comum')
    	break
    case 'gerente':
    		console.log('Gerente')
    	break
    case 'diretor':
    		console.log('Diretor')
    	break
    default:
    console.log("Error")
    }
    ```