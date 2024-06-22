# Projeto 4 - Medidor de velocidade

### Velocidade máxima de até 70 km/h

### A cada 5km/h acima do limite ganha 1 ponto

### Usar Math.Floor()

### Se tiver mais de 12 pontos a carteira é suspensa

```jsx
const velocidadeMaxima = 70
const kmPorPonto = 5
const limitePontos = 12
const carteira = {
  nome: "Alex",
  pontos: 0,
  situacao: true
}

function verificarVelocidade(velocidadeRegistrada){
  if(velocidadeRegistrada > velocidadeMaxima){

    const excedido = velocidadeRegistrada - velocidadeMaxima
    const pontosExcedidos = Math.floor(excedido / kmPorPonto )

    return aplicarPontos(pontosExcedidos, velocidadeRegistrada)

  }else{
    return ("Tudo bem !")
  }
}

function aplicarPontos(qtdPontos, velocidadeRegistrada){
  carteira.pontos += qtdPontos
  if(carteira.pontos >= limitePontos){
    carteira.situacao = false
    return("Carteira Suspensa, se FUDEU")
  }else{
    return ("Multado a " + velocidadeRegistrada+" Km/h ! Pontos na carteira: " + carteira.pontos)
  }
}

console.log(verificarVelocidade(71))
console.log(verificarVelocidade(130))
```