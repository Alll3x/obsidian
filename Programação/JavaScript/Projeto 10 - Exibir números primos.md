# Projeto 10 - Exibir números primos

### Criar função para mostrar os números primos até tal número

```jsx
exibirNumerosPrimos(15)

function exibirNumerosPrimos(limite){
    for(let i = 2; i <= limite; i++){
      if(numeroPrimo(i)) console.log(i)
    }
}

function numeroPrimo(i){
  for(let divisor = 2; divisor < i; divisor++){
    if(i % divisor === 0){
      return false
    }
  }
  return true
}
```