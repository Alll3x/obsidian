# GRID

[https://www.youtube.com/watch?v=8VapN6x897U](https://www.youtube.com/watch?v=8VapN6x897U)

## Basics

- display: grid
- grid-template-columns: x x x | define quantas colunas e qual o tamanho delas
- grid-template-rows: x x x | define quantas colunas e qual o tamanho delas
- gap: x | define o espaço entre os elementos no geral
- grid-row/columns-gap: x | define o espaço podendo escolher a direção

![[Pasted image 20240412151434.png]]
## Template areas

- Os elementos filhos tem id propripo
- consegue setar um tamnaho para cada elememento
- grid-template-areas:  |consegue controlar as areas

```css
grid-template-areas:
'header header header'
'sidebar content content'
'footer footer footer';
```

- grid-area: header| seta o nome da área de acordo com o código abaixo(**SEM ASPAS**)
![[Pasted image 20240412151539.png]]
## Alinhamento

- justify-content: prop | alinha os conteúdos horizontalmente
    - start - alinha na esquerda
    - center - alinha no centro
    - end - alinha na direita
- align-items: prop | alinha os conteúdos verticalmente
    - start - alinha em cima
    - center - alinha no centro
    - end - alinha em baixo

## Itens individuais

- Itens tem que ter id
- grid-column-start: x | onde o item vai iniciar
- grid-column-end: x | Onde o item vai terminar
- grid-row-start: x | onde o item vai iniciar
- grid-row-end: x | onde o item vai iniciar
- justify-self: prop | alinhamento próprio do item, segue as mesmas propriedades dos alinhamentos gerais
- align-self: prop | alinhamento próprio do item, segue as mesmas propriedades dos alinhamentos gerais
- ![[Pasted image 20240412151614.png]]