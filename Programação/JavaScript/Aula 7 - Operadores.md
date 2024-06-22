# Aula 7 - Operadores

# Quais são

- Aritméticos
    - + - soma
    - - - subtração
    - * - multiplicação
    - / - divisão
    - ** - exponencial
    - % - resto
    - ++ - incremento
    - -- - decremento
    
    ```jsx
    let salario = 100
    
    console.log(salario + salario) // 200
    console.log(salario - salario) // 0
    console.log(salario * salario) // 10000
    console.log(salario / salario) // 1
    console.log(2 ** 20) // 1048576
    console.log(salario % 3) // 2
    console.log(salario++) // 101
    console.log(salario--) // 99
    ```
    
- Atribuição
    - = - atribuição
    - += mais igual
    - -= menos igual
    
    ```jsx
    let valor = 100 // 100
    valor += 100 // 200
    valor -= 100 // 0
    ```
    
- Comparação
    - === - igualdade estrita, compara valor e tipagem - 1 === 1 (true) | 1 === “1” (false)
    - == - igualdade solta, compara apenas o valor - 1 == 1 (true) | 1 == “1” (true)
    - > - maior - 5 > 4 (true)
        - >= maior ou igual - 5>= 5 (true)
    - < - menor 5 < 10 (true)
        - <= - menor ou igual - 4 <= 4  (true)
    
    ```jsx
    let x = 5
    let y = 10
    
    console.log( x > y)
    //console: false
    console.log( y > x)
    //console: true
    console.log(x > x)
    //console: false
    console.log(x >= x)
    //console: true
    ```
    
- Lógicos
    - && - e - retorna true se os dois operandos forem true - true && true = true
    - || - ou - retorna true se um dos operandos forem true - true || false = true
    - ! - negação - inverte a fução de um operador - != diferente | !true = false[
    
    ```jsx
    false && true // false
    false || true // true
    false != true // true
    ```
    
- Bitwise