# Projeto 11 - Montador de endereço

### Cria um objeto endereço com

- Rua
- Cidade
- CEP
- Função: exibir endereço: pega um objeto de um endereço, e exibe tudo no console

```jsx
class endereco {
  constructor(rua, cidade, cep){
    this.rua = rua
    this.cidade = cidade
    this.cep = cep
  }

  exibirEndereco(){
    console.log(
    `Endereço: ${this.rua}
Cidade: ${this.cidade}
CEP: ${this.cep}`
      )
  }
}

const endereco1 = new endereco("R. tronca", "Caxias do Sul", 95010100)

endereco1.exibirEndereco()
```