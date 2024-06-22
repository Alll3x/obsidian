# Aula 13 - Introdução a métodos de Arrays

# São métodos para manipulação de arrays

- Adicionar  elementos
    - unshift( ) -  Insere elementos no início
    - splice( )- Insere elementos no meio do Array
    - push( ) - insere elementos no final
    
    ```jsx
    const numeros = [1,2,3]
    
    //unshift
    numeros.unshift(0)
    //numeros = [0,1,2,3]
    
    //splice  onde | deletar ? | valor
    numeros.splice(1, 0, 0.5)
    //numeros = [0,0.5,1,2,3]
    
    //push
    numeros.push(4)
    //numeros = [0,0.5,1,2,3,4]
    
    ```
    
- Remover elementos
    - shift( ) - remove elementos do início
    - splice - remove do meio
    - pop( ) - remove elementos do final
    
    ```jsx
    numeros = [1,2,3,4,5,6]
    //shift
    numeros.shift()
    //numeros = [2,3,4,5,6]
    
    //splice      onde| quantos?
    nuemros.splice(2, 1)
    //numeros = [2,3,5,6]
    
    //pop
    numeros.pop()
    //numeros = [2,3,5]
    ```
    
- Esvaziar elementos
    - Solução 1 - Reinstanciar
    
    ```jsx
    let numeros = [1,2,3]
    numeros = []
    ```
    
    - Solução 2 - length = 0 (MELHOR FORMA)
    
    ```jsx
    let numeros = [1,2,3]
    numeros.lenght = 0
    ```
    
    - Solução 3 - Splice
    
    ```jsx
    let numeros = [1,2,3]
    numeros.splice(0,numeros.lenght)
    ```
    
    - Solução 4 - Pop
    
    ```jsx
    let numeros = [1,2,3]
    while(numeros.lenght > 0){
    	numeros.pop()
    }
    ```
    
- Encontrar elementos(PRIMITIVOS)
    - indexOf( ) - passa um elemento e retorna o índice se existir
    - lastIndexOf( ) passa um elemento e retorna o último índice se existir
    - includes( ) - recebe um elemento e retorna true ou false
    
    ```jsx
    const numeros = [1,2,3,4,1]
    
    //indexOf
    numeros.indexOf(2)
    //1
    
    //lastIndexOf
    numeros.lastIndexOf(1)
    //4
    
    //includes
    numeros.includes(5)
    //false
    ```
    
- Encontrar elementos(REFERÊNCIA)
    - find( ) - retorna  a primeira ocorrência que satisfaz a função
    
    ```jsx
    const marcas = [
    	{id:1, nome: "a"},
    	{id:2, nome: "b"}
    ]
    
    //find
    marcas.find(function(marca){
    	return marcas.nome == 'a'
    })
    // {id:1, nome: "a"}
    ```
    
- Combinar e cortar
    - concat( ) - junta dois arrays
    - slice( )- divide o array
    - join( ) - juntar elementos e pode colocar algo entre eles
    - split( ) - separa de acordo com uma condição
    
    ```jsx
    const primeiro = [1,2,3]
    const segundo = [4,5,6]
    
    //concat
    const combinado = primeiro.concat(segundo)]
    // combinado = [1,2,3,4,5,6]
    
    //slice
    //indice inicial e final-1
    const cortado = combinado.slice(1,3)
    //cortado = [2,3]
    
    //join
    const combinado = primeiro.join(".")
    //1.2.3
    
    //split
    const palavras = "Olá mundo"]
    const resultado = segundo.split(" ")
    //resultado = ["Olá","mundo"]
    ```
    
- SPREEAD
    
    ```jsx
    const primeiro = [1,2,3]
    const segundo = [4,5,6]
    
    //Juntar
    const combinado = (...primeiro,...segundo)
    // combinado = [1,2,3,4,5,6]
    
    const combinado2 = (...primeiro,3.5,...segundo)
    // combinado2 = [1,2,3,3.5,4,5,6]
    
    //Clonar
    const clonado = [...combinado]
    //clonado = [1,2,3,4,5,6]
    ```
    
- Iterar
    - forEach - possui um função de callback, e faz uma determinada ação para cada elemento do array
    
    ```jsx
    const numeros = [1,2,3]
    
    //forEach
    numeros.forEach((numero, indice)=>{
    	console.log(numero, indece)
    }) 
    //1 0
    //2 1 
    //3 2 
    ```