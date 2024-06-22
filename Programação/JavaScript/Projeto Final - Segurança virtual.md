# Projeto Final - Segurança virtual

### Criar tela no html

### Criar JavaScript:

- Pegar nome da pessoa que está tentando entrar
- Perguntar quem convidou
- Ver se está na lista da pessoa que convidou
    - Se estiver na lista alterar descrição para entrar
    - Se não tiver alterar para não entrar

```jsx
function verificar(){
  const nomeConvidado = document.getElementById('name').value
  const quemConvidou = document.getElementById('otherName').value

  const status = document.getElementById('status')
        status.innerText = 'Pesquisando...'

  verifica(nomeConvidado, quemConvidou)
}
const lista = [
  {nome: "Sandra", convidou:["Alex"]},
  {nome: "Rogerio", convidou:["Alessandro"]}
]

function verifica(nomeConvidado,  quemConvidou){
  let verificado = false
  
  const vip = lista.find((vip)=>{
    return vip.nome === quemConvidou
  })

  if(vip.convidou.includes(nomeConvidado)){
    verificado = true
  }

  setTimeout(()=>{
    const status = document.getElementById('status')
    if(verificado){
      status.innerText = 'Liberado, Seja bem vindo !'
    }else{
      status.innerText = 'Negado, some daqui meo'
    }
  }, 2000);
}
```