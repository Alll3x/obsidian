# Projeto 3 - FizzBuzz

### Se valor divisível por 3 retornar Fizz

### Se valor divisível por 5 retornar buzz

### Se valor divisível por 3 e 5 retornar fizzbuzz

### Se valor NÃO divisível nem por 3 nem por 5 retorne número

### Se NÃO é um número retorne “Não é um número”

```jsx
function fizzBuzz(valor){
  if(typeof valor === 'number'){
    if (valor % 3 === 0 && valor % 5 === 0 ) {
      return 'FizzBuzz'
    }else{
      if(valor % 3 === 0){
        return 'Fizz'
      }else{
        if(valor % 5 === 0){
          return 'Buzz'
        }else{
          return valor       
        }
      }
    }
  }else{
    return "Não é um número"
  }
}

console.log(fizzBuzz(3))
```