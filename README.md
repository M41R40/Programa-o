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
//| Divisão inteira
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




#### 1006 - Leia 3 valores com uma casa decimal, variaveis A, B e C, que serão 3 notas de um aluno, a seguir a média sabendo que a nota A tem peso 2, a nota B tem peso 3 e a nota C tem peso 5. A media e de 0 a 10. Imprima "MEDIA = " com um digito após a virgula. 

```python
A = float(input())
B = float(input())
C = float(input())

media = ((A * 2) + (B * 3) + (C * 5)) / 10
print("MEDIA = %0.1f"%media)
```

#### 1007 - Leia quatro valores inteiros, calcule e mostre a diferença do produto de A e B pelo produto de C e D segundo a fórmula: DIFERENCA = (A * B - C * D). Imprima "DIFERENCA = " seguido do valor obtido da subtração dos produtos entre os valores. 

```python
A = int(input( ))
B = int(input( ))
C = int(input( ))
D = int(input( ))
produto = ((A * B) - (C * D))
print ("DIFERENCA =",produto)
```


#### 1008 - Escreva um número de um funcionario, as horas trabalhadas, o valor da hora e calcule o salário do funcionário, depois, exiba o número e o salário do funcionário com duas duas casas decimais. 


```python
ID_FUNCIONARIO = int(input())
QUANT_HORA = int(input())
VALOR_HORA = float(input())
TOTAL = ( QUANT_HORA * VALOR_HORA)
print("NUMBER =",ID_FUNCIONARIO )
print("SALARY = U$ %0.2f"%TOTAL)
```


#### 1009 - Escreva um programa que leia o nome de um vendedor, o seu salário fixo e o total de vendas efetuadas por ele no mês (em dinheiro), calcule a comissão que é correspondente a 15% sobre as vendas efetuadas no final do mês. Exiba o total da comissão que ele vai ganhar. 

```python
NOME = str(input())
SALARIO = float(input())
VALOR_VENDAS = float(input())
MONTANTE = (VALOR_VENDAS * 0.15 + SALARIO) 
print("TOTAL = R$ %0.2f"%MONTANTE)
```

#### 1010 - Neste problema você deve ler 3 entradas, a peça, o valor da peça e o código da peça. Receba 2 linhas de entrada. O valor deve ser lido com duas casas decimais, calcule e exiba o valor das peças. Exiba "VALOR A PAGAR: R$" seguido da variavel.


```python
linha1 = input().split(" ")
linha2 = input().split(" ")

cod1, qtde1, valor1 = linha1
cod2, qtde2, valor2 = linha2

total = (int(qtde1) * float(valor1)) + (int(qtde2) * float(valor2))

print("VALOR A PAGAR: R$ %0.2f" %total)
```

- Nesse código há uma nova função o **split**, que nada mais é do que um delimitador, a sintaxe do slipt é:

```python
str.split (separador, maxsplit)
```

- separator (opcional) - Delimitador no qual ocorrem as divisões. Se não for fornecido, a string será dividida em espaços em branco.

- maxsplit (opcional) - Número máximo de divisões. Se não for fornecido, não há limite para o número de divisões.



#### 1011 - Calcule o volume da esfera. Lembrando que a formula é: Volume = 4/3 * pi * raio. Receba raio e armazene, considere o pi= 3.14159 por fim exiba em tela "VOLUME =" com três casa após a vírgula. 

```python
R = float(input())
pi = float(3.14159)
V = ((4/3) * pi * R**3)

print("VOLUME = %0.3f"%V)

```



#### 1012 -  Escreva um programa que leia 3 valores float na mesma linha: A,B e C.                                         Calcule: 

- a) a área do triângulo retângulo que tem A por base e C por altura.
- b) a área do círculo de raio C. (pi = 3.14159)
- c) a área do trapézio que tem A e B por bases e C por altura.
- d) a área do quadrado que tem lado B.
- e) a área do retângulo que tem lados A e B.

Exiba o resultado na saída no seguinte formato:
TRIANGULO:


CIRCULO:


TRAPEZIO:


QUADRADO:


RETANGULO:

```python
valor = input().split(" ")

a, b, c = valor
pi = 3.14159

triangulo = (float(a) * float(c))/2
circulo = pi * (float(c)* float(c))
trapezio = float(c) *(float(a) + float(b)) / 2
quadrado = float(b) * float(b)
retangulo = float(a) * float(b)


print("TRIANGULO: %0.3f\nCIRCULO: %0.3f\nTRAPEZIO: %0.3f\nQUADRADO: %0.3f\nRETANGULO: %0.3f" % (triangulo, circulo, trapezio, quadrado, retangulo))
```

- Observou que nesse print em apenas uma linha de código eu consegui exibir cinco linhas na saída? Isso é devido o **\n**
Ele serve para pular linha, mas só funciona na exibição conforme em outras linguagens de programação tambem. 


#### 1013 - Faça um progama que receba 3 valores inteiros na mesma entrada, e apresente o maior conforme a fórmula.

MaiorAB = (a+b+abs(a-b))/2

Obs: essa formula calcula só a e b então precisa repetir para descobrir o c. 

Exiba a saída com o valor encontrado seguido do texto **"eh o maior"**.

```python
import math

valor = input().split(" ")

a, b, c = valor

maior = (int(a) + int(b) + abs(int(a) - int(b)))  / 2
resultado = (int(maior) + int(c) + abs(int(maior) - int(c)))/2

print("%d eh o maior" %resultado)
```

- O legal desse código é que aprendemos a importar uma biblioteca com o comando **import** no começo do código, a escolhida neste caso foi a **math** com uma rica documentação em: 
```html
https://docs.python.org/3/library/math.html
```
- Bibliotecas ou módulos servem para importar código de outros códigos, esse de matématica chamado no código, tem atribuido muitas funções pré-estabelecidas que facilitam na declaração de variaveis, de funções entre outras ações. 

- Tambem conhecemos o **abs** nesse código que provendo da matématica pura significa absoluto, nada mais é do que contar de quantas casas númericas o numero declarado absoluto esta longe do zero. 

Por exemplo o -20 esta a 20 digitos do 0. Independente de ser negativo ou positivo, inteiro ou decimal. 

 
#### 1014 - Calcule o consumo médio de um automovel, que possua uma entrada para distancia percorrida e outra para consumo total de combustivel (em litros). Apresente o valor que representa o consumo médio do automovel com 3 casas após a virgula, com a mensagem: "km/l".

```python
X = int(input())
Y = float(input())

distancia = X / Y

print("%0.3f km/l" %distancia)
```
#### 1015 - Encontre a distancia entre dois pontos A e B, no plano cartesiano cada ponto tem 2 valores (Um correspondendo ao eixo X e outro ao eixo Y), leia, armazene eles e calcule a distancia conforme a formula:

### Distancia = √(x2 - x1)² + (y2 - y1)²


```python
import math

linha1 = input().split(" ")
linha2 = input().split(" ")

x1, y1 = linha1
x2, y2 = linha2

distancia = math.sqrt(((float(x2) - float(x1))*(float(x2) - float(x1))) + ((float(y2)-float(y1)) *(float(y2)-float(y1))))

print("%0.4f" %distancia)
```

- Novamente temos o comando **import** no código que esta chamando a mesma biblioteca **math**, isso porque estamos tentando realizar uma função matemática, é um teorema de pitágoras, onde para calcular a distancia entre dois pontos se subtrai os valores e se busca a raiz quadrada. 
O método utilizado para calcular uma raiz quadrada nesse código é o **math.sqrt**, lembrando que a raiz quadrada de um número é a multiplicação de um numero por ele mesmo. Só funciona para números positivos.

 Então para achar a raiz quadrada de 20 por exemplo o código é:

> math.sqrt( x )
Retorna a raiz quadrada de x 
> math.sqrt( 9 ) = 3 
Retorna a raiz quadrada de 9 que é 3 * 3 = 9. 

#### 1016 - Dois carros (X e Y) partem em uma mesma direção. O carro X sai com velocidade constante de 60 Km/h e o carro Y sai com velocidade constante de 90 Km/h. Em uma hora (60 minutos) o carro Y consegue se distanciar 30 quilômetros do carro X, ou seja, consegue se afastar um quilômetro a cada 2 minutos. Leia a distância (em Km) e calcule quanto tempo leva (em minutos) para o carro Y tomar essa distância do outro carro.

```python
x = int(input())
d = (x * 2)
print(d,"minutos")
```

#### 1017 - Joaozinho quer calcular quantos litros de combustivel gasta em uma viagem, para realizar o calculo deve ter a distância percorrida que é a multiplicação de quantidade de horas de viagem, com velocidade média e depois dividir esse valor por 12 que é a quantidade que o carro faz por litro. Exiba a quantidade de litros com 3 casas decimais após a virgula. 

```python
H = int(input())
V = int(input())
D = (H * V )
GASTO = (D / 12) 
print("{:.3f}".format(GASTO))
```

#### 1018 -  Leia um numero inteiro, e exiba a quantidade de cedulas necessarias para um caixa de saque emitir as notas. Lembrando que neste caixa temos notas de 100, 50, 20, 10, 5, 2 e 1 disponiveis. 

```python
n = int(input())
print(n)
n100 = n // 100
n = n - n100*100

n50 = n // 50
n = n - n50*50

n20 = n // 20
n = n - n20*20

n10 = n // 10
n = n - n10*10

n5 = n // 5
n = n - n5*5

n2 = n // 2
n = n - n2*2

n1 = n // 1
n = n - n1*1
print('{} nota(s) de R$ 100,00'.format(n100))
print('{} nota(s) de R$ 50,00'.format(n50))
print('{} nota(s) de R$ 20,00'.format(n20))
print('{} nota(s) de R$ 10,00'.format(n10))
print('{} nota(s) de R$ 5,00'.format(n5))
print('{} nota(s) de R$ 2,00'.format(n2))
print('{} nota(s) de R$ 1,00'.format(n1))
```

#### 1019 - Leia um valor inteiro, que é o tempo de duração de um serviço em segundos, informe a quantidade no formato: horas:minutos:segundos.

```python
h = int(input())

hora = h // 3600
h = h - hora * 3600

minuto = h // 60
h = h - minuto*60

segundo = h

print('{}:{}:{}'.format(hora,minuto,segundo))

```

- Esse código tem conversões de tempo, no caso hora para segundos e minuto para segundos. Onde: 1 hora é 3600 segundos e 1 minuto é 60 segundos. 

#### 1020 - Leia um valor inteiro correspondente a idade de uma pessoa em dias e depois informe em anos, meses e dias. Considere todo ano com 365 dias, todo mês com 30 dias

```python
idade = int(input())

ano = idade //365
idade = idade - ano * 365

mes = idade //30
idade = idade - mes * 30

dia = idade 

print(ano,"ano(s)")
print(mes,"mes(es)")
print(dia,"dia(s)")
```
#### 1021 - Leia um valor de ponto flutuante com duas casas decimais. Este valor representa um valor monetário. A seguir, calcule o menor número de notas e moedas possíveis no qual o valor pode ser decomposto. As notas consideradas são de 100, 50, 20, 10, 5, 2. As moedas possíveis são de 1, 0.50, 0.25, 0.10, 0.05 e 0.01. A seguir mostre a relação de notas necessárias e moedas. 

```python


n = float(input())

n100 = n // 100
n = n - n100*100

n50 = n // 50
n = n - n50*50

n20 = n // 20
n = n - n20*20

n10 = n // 10
n = n - n10*10

n5 = n // 5
n = n - n5*5

n2 = n // 2
n = n - n2*2

n1 = n // 1
n = n - n1*1
n1=float('%.2f'% n1)
n=float('%.2f'% n)

m50 = n // 0.5
n = n - m50*0.5
m50=float('%.2f'% m50)
n=float('%.2f'% n)

m25 = n // 0.25
n = n - m25*0.25
m25=float('%.2f'% m25)
n=float('%.2f'% n)

m10 = n // 0.10
n = n - m10*0.10
m10=float('%.2f'% m10)
n=float('%.2f'% n)

m5 = n // 0.05
n = n - m5*0.05
m5=float('%.2f'% m5)
n=float('%.2f'% n)

m1 = n * 100
m1=float('%.2f'% m1)
n=float('%.2f'% n)

print('NOTAS:')
print('{} nota(s) de R$ 100.00'.format(int(n100)))
print('{} nota(s) de R$ 50.00'.format(int(n50)))
print('{} nota(s) de R$ 20.00'.format(int(n20)))
print('{} nota(s) de R$ 10.00'.format(int(n10)))
print('{} nota(s) de R$ 5.00'.format(int(n5)))
print('{} nota(s) de R$ 2.00'.format(int(n2)))
print('MOEDAS:')
print('{} moeda(s) de R$ 1.00'.format(int(n1)))
print('{} moeda(s) de R$ 0.50'.format(int(m50)))
print('{} moeda(s) de R$ 0.25'.format(int(m25)))
print('{} moeda(s) de R$ 0.10'.format(int(m10)))
print('{} moeda(s) de R$ 0.05'.format(int(m5)))
print('{} moeda(s) de R$ 0.01'.format(int(m1)))
```

#### Minha resposta
```python
x = float(input())


x100 = x //100
x = x - x100*100

x50 = x // 50
x = x - x50*50

x20 = x // 20
x = x - x20*20

x10 = x // 10
x = x - x10*10

x5 = x // 5
x = x - x5*5

x2 = x // 2
x = x - x2*2

x1 = x // 1
x = x - x1*1

x050 = x // 0.50
x = x - x050*0.50

x025 = x // 0.25
x = x - x025*0.25

x010 = x // 0.10
x = x - x010*0.10

x005 = x // 0.05
x = x - x005*0.05

x001 = x // 0.01
x = x - x001*0.01
print('NOTAS:')
print("%d nota(s) de R$ 100.00" %x100)
print("%d nota(s) de R$ 50.00" %x50)
print("%d nota(s) de R$ 20.00" %x20)
print("%d nota(s) de R$ 10.00" %x10)
print("%d nota(s) de R$ 5.00" %x5)
print("%d nota(s) de R$ 2.00" %x2)
print("MOEDAS:")
print("%d moeda(s) de R$ 1.00" %x1)
print("%d moeda(s) de R$ 0.50" %x050)
print("%d moeda(s) de R$ 0.25" %x025)
print("%d moeda(s) de R$ 0.10" %x010)
print("%d moeda(s) de R$ 0.05" %x005)
print("%d moeda(s) de R$ 0.01" %x001)
```


#### 1035 - Leia 4 valores, A, B, C, D. Depois se B for maior que C e D for maior do que A, e a soma de C com D for maior que a soma de A e B, respectivamente C e D precisam ser positivos e por fim A deve ser par, essas condições devem receber a saída: 'Valores aceitos' se for verdadeiro todas as opções anteriores e 'Valores nao aceitos' se alguma das opções não for corresponder ao solicitado. 


```python
x = input().split()
a, b, c, d = x
a = int(a)
b = int(b)
c = int(c)
d = int(d)
if b > c and d > a and (c + d) > (a + b) and c > 0 and d > 0 and a % 2 == 0:
    print('Valores aceitos')
else:
    print('Valores nao aceitos')
    
```

- O legal desse código é a introdução a condicões. Em python há intruções proprias para indicar condições. São elas:




INSTRUÇÃO | FUNÇÃO 
:--------: | :--------: 
IF | SE 
ELIF| SE AS CONDIÇÕES ANTERIORES NÃO FOREM VERDADEIRAS, TENTE ESTA CONDIÇÃO 
ELSE| QUALQUER CONDIÇÃO QUE NÃO ATENDA A IF E ELIF
AND | E -  CONDIZ EM SOMAR OU COMBINAR
OR | OU -  DÁ OPÇÕES PARA CONDIÇÕES







