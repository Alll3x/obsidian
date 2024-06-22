# Projeto 8 - Notas Escolares

### Obter a média a partir de um array

- 0 - 59: F
- 60 - 69: D
- 70 - 79: C
- 80 - 89: B
- 90 - 100: A

```jsx
const array = [70,70,80] // C

console.log(mediaDoAluno(array))

function mediaDoAluno(arr){
  let total = 0

  for (let i = 0; i < arr.length; i++) {
    total += arr[i]      
  }
  total = total / arr.length
  
  if(total >= 0 && total <= 59){
    return ('F')
  }else{
    if(total >= 60 && total <= 69){
      return ('D')
    }else{
      if(total >= 70 && total <= 79){
        return('C')
      }else{
        if(total >= 80 && total <= 89){
          return('B')
        }else{
          if(total >= 90 && total <= 100){
            return('A')
          }
        }
      }
    }
  }
}  
```