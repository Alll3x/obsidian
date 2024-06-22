# Projeto 7 - Múltiplos de 3 e 5

### Criar uma função somar que retorna a soma de todos os múltiplos de 3 e 5

```jsx
somar(10) //33

function somar(valor){
  let total = 0
  
  for(let i = 0; i <= valor; i++ ){
    if(i % 3 === 0){
      total += i
    }else{
      if(i % 5 === 0){
       total += i
      }
    }
  }
return console.log(total)
}
```