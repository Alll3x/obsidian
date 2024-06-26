ANDF# Introdução 

São a base da lógica digital, são sistemas de circuitos eletrônicos que realizam operações lógicas básicas, como AND, OR e NOT

Ao combinar essas operações de maneira específica, podemos criar circuitos que realizam tarefas complexas, como comparar valores ou somar binário.

Na combinação existem os componentes:
- Portas lógicas
- Tabelas-verdade
- Simplificação

Aplicações
- Processadores
- Memórias
- Controladores
# Portas lógicas

São como interruptores especiais que controlam o fluxo de informações.
Recebem sinais elétricos de entrada (0 ou 1 | falso ou verdadeiro)e, com base em regras lógicas, produzem sinais de saída (0 ou 1).

Tipos e funções das mais usadas: 
- AND: ( E ) saída é 1 somente se todas as entradas forem 1.
	![[Pasted image 20240622211736.png]] 
- OR: (OU) A saída será 1, se pelo menos uma delas for 1
	![[Pasted image 20240622212158.png]]
- NOT: (NÃO) inverte o sinal de entrada 0 vira 1 e 1 vira 0 
	![[Pasted image 20240622212242.png]]
- NAND: (NÃO E) a saída é o inverso da porta AND
	![[Pasted image 20240622212335.png]]
- NOR: (NÃO OU) a saída é o inverso de OR
	![[Pasted image 20240622212502.png]]
- XOR: (OU EXCLUSIVO) a saída é 1 se as entradas forem diferentes
	![[Pasted image 20240622212546.png]]
- XNOR: (OU EXLUSIVO NEGADO) a saída é 1 se as entradas forem iguais

As portas lógicas são blocos de construção fundamentais de todos os dispositivos digitais que usamos no dia a dia 

- Computadores: Processadores, memória, dispositivos de entrada e saída
- Smartphones: Circuitos de processamento, comunicação, sensores

# Tabelas-verdade

São como mapas que mostram todas as possíveis combinações de entrada e saída de uma porta lógica, para entender e prever seus resultados.

[[Aula 2 - Portas lógicas e circuitos integrados digitais#Tabela verdade |Como fazer uma tabela-verdade]]

- Colunas: representam uma entrada ou uma saída do circuito.
- Linhas: representam uma combinação única de valores de entrada e o valor de saída.
- Valores: Os valores nas células indicam se a saída é 0 ou 1 para cada combinação de entrada. 

Simplificação de circuitos auxiliam na redução do número de portas lógicas necessárias para implementar uma função otimizando o projeto.

Depuração de circuito ajudam a identificar a causa de falhas em circuitos digitais, comparando os resultados esperados com os obtidos.

Verificação formal são utilizadas em ferramentas de software para provar matematicamente a correção de sistemas digitais.

# Simplificação

A simplificação de tabelas-verdade é o processo de reduzir o número de termos em uma expressão booleana que representa a função lógica de um circuito digital.
Feita através da identificação de padrões e redundâncias na tabela-verdade, utilizando técnicas como a álgebra booleana e os ==Mapas de Karnaugh.==

- Redução de custos: circuitos mais simples requerem menos portas lógicas em menor custo de produção
- Aumento da velocidade: circuitos simplificados geralmente apresentam menor atraso de propagação.
- Melhora da confiabilidade: circuitos mais simples, menos propensos a falhas
- Facilidade na implementação: são mais fáceis de implementar após serem simplificadas

Usamos: 
- Projetar circuitos digitais 
- Sintetizar a lógica
- Otimizar softwares
- Inteligência Artificial

# Codificadores

São como tradutores, convertem informações do mundo real, para sinais elétricos discretos em um código binário específico

Possuem múltiplas entradas e saída, mas apenas uma saída é ativada por vez, correspondendo a entrada ativa.

Existem: 
- Codificadores de prioridade: quando várias entradas são ativadas simultaneamente, a saída correspondente à entrada de maior prioridade é ativada.
- Codificador Decimal para binário (BCD): converte um número decimal (0 A 9) em sua representação binária equivalente 4 bits.

Funcionam através da lógica combinacional, ou seja, a saída é determinada unicamente pelas entradas presentes em um dado momento

Internamente, eles são compostos por um conjunto de portas lógicas (AND, OR NOT, etc) interconectadas de forma a gerar um código binário específico na saída, correspondente à entrada ativa.

O funcionamento pode ser descrito como 
- Entrada: o codificador possui múltiplas entradas geralmente 2^n (n é o número de bits da saída) Cada entrada representa uma condição ou informação a ser codificada
- Habilitação: Em alguns casos, o codificador ode ter uma entrada de habilitação (enable), que controla se o circuito está ativo ou não.
- Lógica interna: as portas internas são configuradas de forma que quando uma entrada é ativada, a combinação correta de sinais é gerada nas saídas para representar o código binário correspondente àquela entrada.
- Saídas: o codificador possui um conjunto de saídas, geralmente n (números de bits de saída). Cada saída representa um bit do código binário gerado.
- Prioridade (opcional): se várias entradas forem ativas simultaneamente, a saída prioritária é ativada.
	![[Pasted image 20240622220440.png]]

# Decodificadores

São interpretes que traduzem um código binário em um conjunto específico de sinais de saída.

Possuem um conjunto de entradas que recebem um código binário e um conjunto de saídas, onde apenas uma saída é ativada por vez, correspondendo a entrada.

Tipos comuns: 
- Decodificador binário: Converte um código binário em um sinal ativo em suas saídas.
- Decodificador BCD 7 segmentos:  converte um código BCD em sinais para controlas um display de 7 segmentos.

![[Pasted image 20240622221448.png]]


