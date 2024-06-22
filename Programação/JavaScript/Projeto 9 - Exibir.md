# Projeto 9 -  Exibir *

### Crie uma função que exibe a quantidade de * que desejar

```jsx
exibirAsteriscos(10)

function exibirAsteriscos(valor){
  let padrao = ''
  for (let i = 0; i < valor ; i++) {
    padrao += '*'
    console.log(padrao);
  }
}
```