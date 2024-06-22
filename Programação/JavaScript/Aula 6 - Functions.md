# Aula 6 - Functions

# O que são ?

- São blocos de funções que são montados
- Podem ser chamado mais de uma vez
- Podem receber variáveis ou retornar variáveis
- A nomeação geralmente é dada por: verbo + substantivo - resetarCor
- Existem 2 tipos
    - functions
        - Tem a palavra reservado function antes do nome
    - Arrow functions
        - São guardadas em variáveis
        - Possuem a estrutura ( ) =>
    - Funções anônimas

```jsx
let contador = 0

function adicionaContador(){
	contador ++
}

//chamando função
adiconaContador()

function imprimirMensagem(mensagem){
	console.log(mensagem)
}

imprimirMensagem("Hello Functions")

function retornaSoma (x, y){
	return x + y
}

let resultado = retornaSoma(1, 1)
console.log(resultado)
//console: 2

let resultado2 = retornaSoma(5, 5)
console.log(resultado2)
//console: 10

let dobra = (x)=>{
	return x * 2
}

console.log (dobra(2))
//console: 4
```