# Projeto 6 - Encontre a String

### Criar um método para ler as propriedades de um objeto e exibir somente se for string

```jsx
const filme ={
  titulo: 'vingadores',
  ano: 2018,
  diretor:"Robin",
  personagem: 'Homem de Ferro'
}

function exibirString(obj){
  for (const column in obj) {
    if(typeof obj[column] === 'string'){
      console.log(column, '=', obj[column]);
    }
}
}

exibirString(filme)
```