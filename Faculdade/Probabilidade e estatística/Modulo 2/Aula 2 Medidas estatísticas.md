
# Medida de tendência central

- Média
- Moda
- Mediana

## Média 
### Aritmética
Dados não agrupados
	Se fizer duas provas, ambas valendo 10, e tirar 6 e 8, a média aritmética seráigual a soma dos elementos, dividido pela quantidade de elementos somados, ou seja,  
	6 + 8 = 14 / 2 = 7
Dados Agrupados:
	Estoque de uma loja 
	![[Pasted image 20240625220451.png]]
	1. "Incrementar" a tabela: 
		- Estimar o ponto médio(média do limite superior, com limite inferior) 
		- Multiplicar o ponto médio pela frequência absoluta(fi)
	![[Pasted image 20240625220635.png]]
### Ponderada
Dados não agrupados
	Utilizada quando ==cada valor tem uma importância distinta== no grupo
	Ex. A tabela a seguir traz os salários de uma empresa, considerando-se as respectivas funções: 
	![[Pasted image 20240625214158.png]]
	A média será ponderada pela quantidade de funcionários em cada função (fi), ou seja,
	    salário * fi = ponderação  ->  Gerente = 10.000 * 2 = R$ 20.000,00
	No final soma-se as ponderações e se divide pelo número de funcionários da empresa 
	TOTALponderação / TOTALfi = médiaPonderadaSalárial -> 91.200/44 = R$ 2.072,03
	    
## Moda
Dados não agrupados
	É o valor que acontece com maior frequência
	Ex. Carlos obteve os seguintes resultados de vendas mensais 
	![[Pasted image 20240625214808.png]]
	Logo a moda foi 8, pois teve 4 ocorrências no intervalo de tempo analisado

Dados agrupados:
	![[Pasted image 20240625221330.png]]
	li = maior fi


## Mediana
Sempre o que está no meio
Dados não agrupados: 
	Um vendedor fez a seguinte quilometragem durante na semana: 150, 110, 200, 80, 130
	   Organiza-se em um [[Aula 1 - Estatística Descritiva#Conceitos |rol]]: 80, 110, ==130==, 150, 200 
	A mediana será 130, pois está ==exatamente no meio do rol== 
	Se ocorrer de ==não haver um número que fique exatamente no meio do rol==, pega-se os dois números centrais e realiza-se uma ==média aritmética==.
	Ex. Vendas semanais de uma loja: 45, 80, 45, 130, 175, 90
	  [[Aula 1 - Estatística Descritiva#Conceitos |rol]]: 45, 45, ==80==, ==90==, 130, 175 -> (80+90)/2 = 85 
	  
Dados agrupados:
	![[Pasted image 20240625220842.png]]
	n = numero de elementos
	![[Pasted image 20240625221010.png]]
	Para decidir o ponto da mediana, divide-se o total de elementos(1000) por 2, e procura-se o intervalo em que se encontra (500)

# Medidas de variabilidade

- Variância
- Desvio padrão
Indicam quanto um fenômeno está se "espalhando" ou dispersando. As mais utilizadas são a variância e o desvio padrão.

## Variância sem dados agrupados
![[Pasted image 20240625222302.png]]
Ex. vendas de dois vendedores durante a semana 
João: 10, 2, 8, 3, 7
Juliana: 6, 6, 6, 6, 6 
A média é a mesma, porém, não apresentam a mesma regularidade 
Variância de João
![[Pasted image 20240625222626.png]]
Var = 46/5 = Variância de 9,2

Variância de Juliana
![[Pasted image 20240625222853.png]]
 Variância de 0

## Desvio padrão
 O desvio padrão é a raiz quadrada da variância
 Considerando o exemplo anterior: 
 - João -> Var 9,2 -> √9,2 = aprox 3,033  (Ele tem uma margem de 3,033 acima ou abaixo, ou seja a média é 6, logo ele vende 3 ou 9 unidades por dia)
 - Juliana -> Var é 0 (Ela vende exatamente a média, nada a mais, nada a menos)

Variância com dados agrupados
1. Determinar o ponto médio, de cada intervalo de classe (xi)
2. elevar cada ponto médio ao quadrado (xi²)
3. multiplicar cada xi² pela frequência da classe fi correspondente
4. calcular a média aritmética considerando que os dados estão agrupados
![[Pasted image 20240625223601.png]]
Ex. Produtos vendidos por uma loja, conforme a frequência
![[Pasted image 20240625223746.png]]
Depois dos 4 passos: 
xifi = xi * fi  
![[Pasted image 20240625223816.png]]
![[Pasted image 20240625224100.png]]
Desvio padrão -> √408,24 = aprox. 20,205