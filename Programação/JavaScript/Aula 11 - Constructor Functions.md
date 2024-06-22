# Aula 11 - Constructor Functions

# O que é ?

- Igual a factory function

```jsx
function Celular(marcaCelular, tamanhoTela, capacidadeBateria){
	this.marcaCelular = marcaCelular,
	this.tamanhoTela = tamanhoTela,
	this.capacidadeBateria = capacidadeBateria

	this.ligar(){
		console.log("Ligando Celular)
	}
}

const celular = new Celular('asus', 5.5, 5000)
```