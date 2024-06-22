# Projeto 12 - Postagem de Blog

### Criar um objeto de postagem de um blog que vai conter as seguintes propriedades

- titulo
- mensagem
- autor
- vizualizacoes
- comentarios
    - autor
    - mensagem
- estaAoVivo

```jsx
class comentario{
  constructor(autor, mensagem){
    this.autor = autor
    this.mensagem = mensagem
    this.createdAt = new Date()
  }
}

class postagem{
  constructor(titulo, mensagem, autor, vizualizacoes = 0,  estaAoVivo = true){
    this.titulo = titulo,
    this.mensagem = mensagem,
    this.autor= autor,
    this.vizualizacoes = vizualizacoes,
    this.estaAoVivo = estaAoVivo
    this.comentario = []
    this.createdAt = new Date()
  }

  comentar(autorDoComentario, mensagem,){
   this.comentario.push( new comentario(autorDoComentario, mensagem))
  }
}

const postagem1 = new postagem ("Tintulo", "Tudo na vida depende du quantu vc quer cume alguém !", "Alex")

postagem1.estaAoVivo = false
postagem1.vizualizacoes++

postagem1.comentar("Rodolfo", "Você estuda pa cume alguém ...")

console.log(postagem1);
```