### Comandos em Python

**\\n** - quebra de linha

**\\t** - atalho de escape para adicionar uma aba

**\\** - atalho de escape para ignorar um caractere em uma string com '' ou "". ex: print("E então ela disse **\\**"Peguei!\\" ao agarrar a galinha d\\'angola.")

**'''  '''**  - possível escrever uma variável em varias linhas diferentes

**type()** - verifica o tipo da variável

**len()** - calcula o comprimento da string - 1, positiva ex: len(variável\[3]) ou negativa ex: len(variável\[-3]) ou cortar um pedaço ex: len(variável\[2:6])

**try:**  - tentar esse

 	comando

**except:** se erro então executar esse

 	print()

**.format()** - formata uma variável para adiciona-la a string em colchetes {}

**f''**  - formata uma string

**.upper()** - deixar os caracteres em caixa alta

**.lower()** - deixar os caracteres em caixa baixa

**.islower()**  - retorna true se todos os caracteres forem minúsculos 

**.isdigit()**  - retorna true se a string tiver apenas números 

**.isalpha()**  - retorna true se a string tiver apenas letras

**.replace()** - substitui todas as ocorrências informadas ex: substituir 'maçã' por 'laranja' replace('maçã', 'laranja')

**.strip()** - remover espaços em branco do inicio e do fim de um string

**.append()** - adiciona um item no final da lista ou filtra um item da lista

**.extend()** - adiciona 1 ou mais itens na lista

**.insert ()** - insere um item na lista podendo escolher em que ordem colocar. ex: .insert(1:'posição')

**.pop()** - remove um item da lista

**.sort**() - é um método modifica a lista e as classifica em ordem crescente 

**.sort(reverse=TRUE)** - colocar em ordem decrescente 

**sorted()** é uma função que produz uma nova lista ordenada ex: **variável\_sorted = sorted(variável)** em ordem crescente, em ordem decrescente ex: **variável\_sorted = sorted(variável,reverse=True)**

**.split()** - converte uma string em uma lista

**.join()** - converte uma lista em string

**atribuições compostas: +=   -=**   \*=   **/=** 



###### 	**Ciclos for**

**for value in variável :**

	**print(value)**    - imprime na tela todos os elementos de uma lista

###### &nbsp;	**Percorrer lista aninhadas** 

**for row in variável :**

	**print(row\[0])   \[0]** imprime o primeiro indicie da lista 



**runtime** - converte qualquer valor em horas ou minutos

###### da biblioteca Random a função randint gera números inteiros aleatórios

###### &nbsp;	**Ciclos while**

Em ciclos while, a condição é verificada antes de cada iteração. Se essa condição for True, o algoritmo executa as instruções dentro do corpo do ciclo. Assim que a expressão lógica na condição retornar False, o ciclo será interrompido



**from random import randint**



**#argumentos#** 

**while argumento2 < argumento1:**

	**novo argumento = randint(0,100)**

	**argumento2 += novo\_argumento**

	**print()**



**print()**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**



