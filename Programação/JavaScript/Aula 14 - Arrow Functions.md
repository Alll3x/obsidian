# Aula 14 - Arrow Functions

### Forma mais curta e rápida de declarar métodos e funções

```jsx
const marcas = [
	{id:1, nome: "a"},
	{id:2, nome: "b"}
]

//find
marcas.find((marca)=>{
	return marca.nome == 'a'
})
// {id:1, nome: "a"}

OU

const message = ()=>{console.log("Hello Arrow Functions")}
message()
//"Hello Arrow Functions"
```