# Aula 4 - Objetos

# O que são ?

- São como uma classe, cada uma possui suas propriedades
- Suas propriedades são colocadas dentro de { }
- Podem possuir diversos tipos de  dados
- Para acessar suas propriedades usa-se o ‘ . ‘ - pessoa**.**nome (vai acessar o objeto “pessoa”, propriedade “nome”)
- Propriedades podem ser adicionadas após o objeto ser criado

```jsx
let pessoa = {
	nome: 'Alex', //STRING
	idade: 21, //NUMBER
	CNH: true, //BOOLEAN
} 
console.log(pessoa)
//console: {nome: 'Alex', idade: 21, CNH: true}
console.log(pessoa.nome)
//console: Alex

pessoa.profissao = "Programador"
console.log(pessoa)
//console: {nome: 'Alex', idade: 21, CNH: true, profissao: 'Programador'}

```