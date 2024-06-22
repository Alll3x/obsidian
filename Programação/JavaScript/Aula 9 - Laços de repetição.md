# Aula 9 - Laços de repetição

# O Que são

- São loops que podem fazer a mesma ação um x número de vezes
- São 5 tipos
    - For
        
        ```jsx
        //para i = 0; faça até que i seja menor que 5; incrementando de 1 em 1 
        
        for(let i = 0; i < 5; i++ ){
        console.log("Laço for", i)
        }
        
        //Laço for 0
        //Laço for 1
        //Laço for 2
        //Laço for 3
        //Laço for 4
        ```
        
    - While
        - verifica e depois executa
        
        ```jsx
        let i = 5
        
        //enquanto i for maior ou igual a 1 faça decrementando de 1 em 1
        while(i >= 1){
        console.log("Laço while", i)
        i--
        }
        
        //Laço for 0
        //Laço for 1
        //Laço for 2
        //Laço for 3
        //Laço for 4
        ```
        
    - Do While
        - executa no mínimo uma vez, depois verifica
        
        ```jsx
        let i = 0 
        
        //faça enquanto i for menor que 5 incrementendo de 1 em 1 
        do{
        console.log("Laço do while", i)
        i++
        }while(i < 5)
        
        //Laço for 0
        //Laço for 1
        //Laço for 2
        //Laço for 3
        //Laço for 4
        ```
        
    - For in
        
        ```jsx
        const pessoa{
        	nome: 'Alex',
        	idade: 21
        }
        
        for(let chave in pessoa){
        	console.log(chave)
        }
        
        //nome
        //idade
        
        for(let chave in pessoa){
        	console.log(chave,pessoa['nome'])
        }
        
        //nome Alex
        //idade Alex 
        ```
        
    - For of
        
        ```jsx
        const cores = ['Vermelho','Azul','Verde']
        
        for(let cor of cores){
        	console.log(cor)
        }
        
        //Vermelho
        //Azul
        //Verde
        ```