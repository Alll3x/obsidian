# FlexBox

[https://www.youtube.com/watch?v=vY7GJVH8JfQ](https://www.youtube.com/watch?v=vY7GJVH8JfQ)

- Ajustar posicionamento dos itens
- Eixo principal é a linha(horizontal)
- display: flex : ativa o flexbox, tem q ser na div principal
- justify-content (horizontal)
    - flex-start - início do eixo
    - center - centraliza
    - flex-end - final do eixo
    - space-between - coloca um espaço igual entre as divs  no eixo
    - space-around - coloca um espaço entre as divs e as margens da página
- align-items (vertical)
    - stretch - esticar o tamanho das divs para caber no espaço
    - flex-start - junta no inicio do eixo
    - center - junta no centro do eixo
    - flex-end - junta no final do eixo
- alighn self: alinhas somente o elemento, deve ser usado na classe secundaria
- flex-direction: muda o eixo pricipal
    - column - vertical
    - rown - horizontal
- flex-grow: define se vai aumentar de acordo com a página o comportamento padrão é só diminuir
    - 1: true
    - 0: false
    - 2 + : define q pode ser o dobro ou o triplo maior
- flex-shrink: não vai diminuir de tamanho
    - 1: true
    - 0: false
    - 2 + : define q pode ser o dobro ou o triplo maior
- flex: grow  shrink: funciona igual os acima, porém aplica a todos ex: flex : 0 1 = não pode aumentar, mas pode diminuir
- flex-basis: tamanho base do elemento