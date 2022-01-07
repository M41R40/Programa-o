# Meus estudos sobre programação.

Este arquivo contem informações sobre meus estudos de programação, tudo baseado no site:

```html
https://www.beecrowd.com.br/judge/pt
```

É possivel resolver em varias linguagem de programação os problemas, mas meu foco no momento é **PYTHON**.


## DESAFIOS INICIANTE.


#### 1000- Imprima a mensagem "Hello World!"

```python
print('Hello World!')
```

- O comando **print** é responsavel por exibir em tela, oque esta dentro do parenteses.

#### 1001- Leia e armazene 2 valores inteiros nas variaveis A e B, efetue a soma e armaze o resultado na variavel X. Imprima o valor de X. 


#### Imprima a mensagem "X = " (letra X maiúscula) seguido pelo valor da variável X e pelo final de linha. 


#### Conforme o exemplo:

10

10

X = 20


```python
a = int(input( ))
b = int(input( ))
x = a + b
print("X =",x) 
```
- **variavel** é um valor qualquer que adicionado ao código poderá interagir e variar conforme as operações e ações que se deseja realizar como objetivo do programa, tendo um tipo que nesse caso é o **int** e uma ação que neste caso é armazenar uma entrada. 
- O comando **input** é para informar ao programa que ele deve receber e armazenar uma entrada, a qual o usuario vai fazer;

- **int** é um tipo de dado ou melhor de número, inteiro no caso, que são números de 0 a 9;


#### 1002 - A forma para carcular a área de um círculo é (area =  π . raio²) considerando que (π = 3.14159) efetue o calculo da area, elevando o valor de raio ao quadrado e multiplicando por π.

 
 
```python
π = float(3.14159)
raio = float(input('Raio:'))
area = (π * raio**2)

print ("A={:.4f} ".format(area))
```

- **float** tambem é um tipo de dado, número mais especificamente e é do tipo decimal, que contem virgulas, para exibir a quantidade infinita de casas que existem depois da virgular podemos setar com o comando **{:.2f}** o dois vai mostrar a quantidade de casas que eu desejo ver depois da virgula, para especificar com qual variavel fazer isso, adicionamos o **.format(nomedavariavel)** para que ele compreenda e exiba. 


#### 1003 - Leia dois valores inteiros, A e B, atribua o resultado da adição entre eles a variavel SOMA, exiba o valor da seguinte forma "SOMA =" seguido pela variavel.

```python
A = int(input( ))
B = int(input( ))
SOMA = A + B

print('SOMA =',SOMA)
```

#### 1004 - Leia dois valores inteiros, calcule o produto entre o dois e atribua a variavel PROD, exiba "PROD =" seguindo do valor da variavel em tela.

- Produto conforme a matemática é o resultado da multiplicação entre numeros. 

```python
A = int(input( ))
B = int(input( ))
PROD = A * B

print('PROD =',PROD)
```

### OPERADORES ARITMÉTICOS.
 
 Utilizados para execução de contas, ou seja, operações matemáticas. Vejamos exemplos
 
OPERADOR | CONCEITO 
:--------: | :--------:
+| Soma 
-| Subtração 
*| Multiplicação
/| Divisão 
%| Módulo (resto da divisão)
**| Exponenciação (multiplicação da quantidade do expoente)
 
#### 1005 - Leia 2 valores flutuantes de dupla precisão A e B valendo de 0 a 10, que correspondem a 2 notas de um aluno, calcule a media do aluno sabendo que o peso da nota A é 3.5 e a nota B tem peso 7.5, com uma casa decimal. Imprima "MEDIA =" seguido do valor da média do aluno com 5 casas decimais


```pyhton
A = float(input( ))
B = float(input( ))

media = (((A * 3.5) + (B * 7.5)) / 11)
print ("MEDIA = {:.5f}".format(media))
```

Esse código foi muito interessante, ele me despertou a curiosidade sobre variaveis. Vou introduzir um assunto legal, pelo menos que eu gosto ne!

### Tipos de Variáveis. (DADOS)


SIGLA | FUNÇÃO | CONCEITO 
:--------: | :--------: | :---------------------------------------------------------------------------:
Int| Inteiro | Composto por números inteiros (sem vírgula), negativos ou positivos.
float| Ponto Flutuante ou decimal | Composto por números decimais (com vírgula), racionais (frações).
Str| String | Conjunto de caracteres dispostos em uma ordem, utilizada para palavras, frases ou textos.
bool| Boolean | É um dado lógico, podendo assumir apenas dois valores: falso ou verdadeiro.
list| Listas | Tipo de dado que agrupa conjuntos de elementos variádos entre colchetes e delimitado por virgulas. 
dic| Dictionary | É um tipo de dado utilizado para agrupar elementos por meio de chaves dois pontos e valor e delimitado por virgulas.  
tuple | Tuplas | Tipo de dado que agrupa elementos utilizando parênteses e separados por vŕgula. 




























