# Aula 10 - Factory Functions

# O que é ?

- Previne a repetição de código para criar objetos

```jsx
function criarCelular(marcaCelular, tamanhoTela, capacidadeBateria){
	return{
		marcaCelular,
		tamanhoTela,
		capacidadeBateria,
		
		ligar(){
			console.log("Ligando celular...")
		}
	}
}

const celular1 = criarCelular('Zenfone', 5.5, 5000)

celular1.ligar()
//"Ligando celular..."
```