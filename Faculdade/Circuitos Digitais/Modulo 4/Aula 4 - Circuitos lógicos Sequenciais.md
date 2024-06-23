
# Circuitos Sequenciais Digitais

São sistemas digitais cujo comportamento não depende apenas das entradas atuais, mas também do histórico de entradas anteriores. Possuem memória, o que lhes permite "lembrar" estados passados e usar essa informação para determinar suas saídas e estados futuros.

Principais características
- Memória: define os circuitos sequenciais, como flip-flops ou latches, que armazenam em binário.
- Estados: um circuito sequencial pode estar em diferentes estados, cada um representando uma configuração específica de seus elementos de memória. A sequência de estados determina o comportamento do circuito ao longo do tempo.
- Transições de estado: circuito muda de um estado para o outro em resposta às entradas e ao estado atual.
- Saídas: as saídas de um circuito sequencial ==dependem não apenas das entradas atuais, mas também do estado atual==, Significa que o mesmo conjunto de entradas pode produzir saídas diferentes, dependendo do estado do circuito.

Existem 2 tipos de circuitos 
- Síncronos: as transições de estado ocorrem em momentos específicos, sincroniados por um sinal de clock. Como contadores e registradores.
- Assíncronos: As transições de estado ocorrem assim que as entradas mudam, sem a necessidade de um sinal de clock. Latches são exemplos de circuitos sequenciais assíncronos. 
Flip-flop SR (Set - Reset)
![[Pasted image 20240623164558.png]]

# Circuitos Somadores

## Circuito meio somador
![[Pasted image 20240623172609.png]]