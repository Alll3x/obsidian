# Aula 1 - Variáveis

# O que é ?

- Serve para receber um valor
- Possuem 3 tipos
    - var
        - Forma mais antiga
    - let
        - Pode ser criada, e definida posteriormente
        - Pode ter seu valor mudado a qualquer momento
        - Possui escopo global
        - Possui escopo de função
    - const
        - Uma variável constante,
        - Deve ser definida no momento em que é criada
        - Não pode ser mudada
        - Possui escopo global
- São case sensitive, ou seja, letras maiúsculas e minúsculas fazem diferença - nome é diferente de Nome
- Devem ter um nome que “explique” sua função - let contador | let nome

# Como nomear

### **NÃO DEVEM**

- Começar com número -  let 1variavel
- Ter espaços entre os nome - let uma variavel
- Possuir acento ou carácter especial - let umaVariável | let cabeça

### **DEVEM**

- CamelCase - primeira letra minúscula, divisão das palavras maiúsculas - let umaVariavel
- Ter nome de acordo com sua função - let nome | let aux | let novoNome

```jsx
let diaDeHoje = 03
let contador
contador = 0

const nome = "Alex"
```