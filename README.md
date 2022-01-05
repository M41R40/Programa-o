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
- **variavel** é um valor ou string qualquer que adicionado ao código poderá interagir e variar conforme as operações e ações que se deseja realizar como objetivo do programa, tendo um tipo que nesse caso é o **int** e uma ação que neste caso é armazenar uma entrada. 
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


