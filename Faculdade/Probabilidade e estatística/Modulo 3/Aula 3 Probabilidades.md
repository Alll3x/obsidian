# Probabilidade

## Conceitos
- **Princípio Fundamental da contagem (possibilidades):** Uma montadora produz 3 tipos de veículos, estes são fabricados em 2 cores e em 2 opções de modelo. Quantas configurações diferentes são possíveis. -> ==3 x 2 x 2 = 12 possibilidades==
- **Combinações:** Agrupamento de elementos em que a ordem não interfere, são chamados de combinações simples.
	![[Pasted image 20240627223305.png]] 
## Probabilidade
- **Espaço amostral:** é o total de eventos
- **Eventos:** são os casos favoráveis
	![[Pasted image 20240627223840.png]]

Ex. Probabilidade Simples
Um dado de 6 lados, é jogado, qual é a probabilidade de cair um divisor de 6 
S:{1, 2, 3, 4, 5, 6}                            P(a) = 4/6 = 0,6666 * 100 = 66,66%
E:{1, 2, 3, 6,}

Ex. Probabilidade composta
Temos 2 urnas com respectivamente 10 e 5 bolas. Na primeira há 6 bolas brancas, na segunda. Qual a probabilidade de se extrair duas bolas brancas, ao mesmo tempo

P1:            6/10 (Simpl. 2) = 3/5
S: 10 
E: 6

P2:            2/5 
S: 5
E: 2 

P:                              3/5 * 2/5 = 6/25 = 0,24 * 100 = ==24%==

# Distribuição de probabilidade

## Distribuição Binomial

É utilizada quando o fenômeno pode assumir apenas 2 possibilidades de resultado
Ex. Nascimento de um animal(macho ou fêmea)
	![[Pasted image 20240627225845.png]]

![[Pasted image 20240627230158.png]]
![[Pasted image 20240627230437.png]]

## Distribuição Geométrica

Conta o número de falhas até obtermos o sucesso. Assim, x assume o número de tentativas necessárias ao aparecimento do primeiro sucesso. 

Ex. Errar 4 chutes antes de acertar o quinto

![[Pasted image 20240627230648.png]]
![[Pasted image 20240627230706.png]]

## Distribuição Normal

Uma das mais importantes. Ocorre quando a média, a moda e a mediana são idênticos. O gráfico lembra um sino, é chamado de curva de Gauss.
	![[Pasted image 20240627231407.png]]
Tabela de distribuição na apostila

![[Pasted image 20240627231621.png]]
![[Pasted image 20240627232021.png]]
![[Pasted image 20240627232259.png]]


# Intervalo de confiança

É a probabilidade intervalar de algo ocorrer, a chance de algo o correr estimando 2 limites, com um relativo risco.

Ex. Se temos 95% de chance de algo acontecer, temos 5% de não acontecer, sendo 2,5% de erro para mais e 2,5% para menos
Então: 
==95% de nível de confiança==
==5% de nível de significância ou de desconfiança==

## Margem de erro, ou erro máximo

Pode ser entendido como a quantia que o fenômeno pode oscilar, para cima ou para baixo. Quando a população ==N== for infinita ou não fornecida.
![[Pasted image 20240628223531.png]]
 Amostra ==abaixo de 30== elementos: ==tabela T== (amostras pequenas)
 ![[Pasted image 20240628224428.png]]
 Amostra ==acima de 30== elementos: ==tabela Z== (amostras grandes)
 ![[Pasted image 20240628223817.png]]

Ex. Amostra Grande
![[Pasted image 20240628223608.png]]
![[Pasted image 20240628223903.png]]

Ex. Amostra pequena
Em amostra pequena sempre considerar o grau de liberdade para olhar na tabela
![[Pasted image 20240628224300.png]]
![[Pasted image 20240628224412.png]]