# Projeto 5 - Par ou impar

### Receber uma quantidade de valores para avaliar

### Exibir se cada valor é par ou impar

```jsx
function exibirTipo (number){
  for(let i = 1; i <= number; i++){
    if(i % 2 !== 0){
      console.log(( i +" impar"))
    }else{
      console.log((i + " par"))
    }
  }
}

exibirTipo(10)
```