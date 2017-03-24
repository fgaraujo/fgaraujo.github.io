---
layout: post
title: "Google's Python Class #1: Introdução ao Python"
---

![google-python-class-image](https://cloud.githubusercontent.com/assets/12460407/24308474/ca384f04-10a6-11e7-8078-6961caab4d8a.png)

**Nota**: Esta é a tradução da primeira parte do curso "Google's Python Class", desenvolvido por Nick Parlante. Você pode acessar o link original [aqui](https://developers.google.com/edu/python/introduction).

Seja bem-vindo ao tutorial online de Python do Google. Ele é baseado no curso introdutório que oferecemos aos funcionários da empresa. O material foi criado nos tempos da versão 2.4 do Python, e nós tentamos manter o conteúdo o mais genérico, atualizado e relevante possível, mantendo-o útil para as versões posteriores da linguagem. 

Tal como foi mencionado antes, este material aborda o Python 2. Apesar de recomendarmos que você "evite" as versões 3.x do Python, é importante que se reconheça que estas representam o futuro da linguagem, visto que novos recursos estarão presentes somente nestas versões. A boa notícia é que desenvolvedores que estejam aprendendo uma ou outra versão estarão aptos para compreender suas peculiaridades e diferenças sem grandes dificuldades. Se você quiser saber mais sobre as diferenças existentes entre as versões 2.x e 3.x do Python, [**este post**](https://www.quora.com/As-someone-interested-in-learning-Python-should-I-start-with-2-x-or-go-straight-to-3-x/answers/2220200?srid=hFhk&share=1) pode ser útil.

Nós recomendamos fortemente que você também se utilize dos vídeos de acompanhamento ao longo do curso, começando [**por este**](https://www.youtube.com/watch?v=tKTZoB2Vjuk&feature=youtu.be). Também é interessante reforçar seus estudos através de um curso livre que seja mais detalhado, como os do [**Udacity**](https://br.udacity.com/course/intro-to-computer-science--cs101/) e do [**Coursera**](https://www.coursera.org/learn/learn-to-program). 

Se você está buscando um livro recomendado para o seu aprendizado, independentemente do seu nível de maturidade na linguagem, faça uso [**desta lista de livros recomendados**](http://www.informit.com/articles/article.aspx?p=1849069). Finalmente, se você está procurando ferramentas de aprendizado online sem vídeos adequadas ao seu próprio ritmo, tente as que são mencionadas ao final [**deste post**](http://stackoverflow.com/questions/3217222/beginner-python-practice/3226704#3226704) - Todas elas são acompanhadas de um interpretador Python para que você possa praticar ao mesmo tempo em que estuda. 

O que seria esse "interpretador" que nós mencionamos? Você saberá na próxima seção!

## Introduzindo a Linguagem

Python é uma linguagem interpretada dinâmica e de alto nível. Abaixo da figura do interpretador Python existe um processo de compilação transparente, que traduz o código fonte em "bytecode" que, por sua vez, é interpretado por uma máquina virtual. Diferente de linguagens tais como Java ou Javascript, em Python não é necessária a declaração dos tipos das variáveis, parâmetros, funções ou métodos no código fonte que é escrito. Isto torna o código enxuto e flexível, o que por sua vez economiza o tempo que o programador levaria para checar os tipos ao finalizar parte ou o todo de seu código *("É int? É double?")*. O Python rastreia os tipos de todos os valores durante a execução e sinaliza o código que não faz sentido quando este é executado.

Uma excelente forma de verificar como os programas escritos em Python funcionam é a de justamente executar o interpretador e digitar os códigos diretamente nele. Caso você tenha uma dúvida como *"O que aconteceria se eu adicionasse um inteiro em uma lista?"*, digitar isso no interpretador é uma forma rápida e prática de descobrir o que acontece.

Vamos fazer isso um pouco? Abra o seu interpretador Python.

```python
$ python        
Python 2.7.9 (default, Dec 30 2014, 03:41:42) 
[GCC 4.1.2 20080704 (Red Hat 4.1.2-55)] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Você deve ter notado que um prompt aparece ao seu dispor. É através deste prompt que digitaremos nossos comandos. Comecemos nossos trabalhos definindo uma variável, ***"a"***.

```python
>>> a = 6      
```

Agora, digite a variável no prompt.

```python
>>> a          
6
```

Note que a entrada de uma variável tem como resultado a impressão *(print)* do seu valor. Também somos capazes de executar operações aritméticas com a variável. Veja:

```python
>>> a + 2
8
```

Muito bem. Será que conseguimos atribuir nossa variável a uma string?

```python
>>> a = 'hi'
>>> a
'hi'
```

E se eu quiser saber o número de letras contidas nesta string armazenada? Fácil. Basta usar a função *len()*.

```python
>>> len(a)
2
```

Agora, vamos fazer algo que não funcionará. Em Python, não somos capazes de adicionar objetos do tipo "int" e "string". Vejamos o que acontece:

```python
>>> a + len(a)
Traceback (most recent call last):
  File "", line 1, in 
TypeError: cannot concatenate 'str' and 'int' objects
```

Se quisermos realmente fazer isso, precisaremos **converter** o número *2*, resultado de *len(a)*, para a string *"2"*. Portanto, vamos utilizar a função *str()*. Veja:

```python
>>> a + str(len(a))
'hi2'
```

Note que as duas strings foram concatenadas, dando como resultado a string *"hi2"*.

Como pudemos ver, é fácil trabalhar com variáveis e operadores em Python. Também verificamos que o interpretador nos lança mensagens de erro de execução para o caso de um comportamento não esperado ter sido interpretado. Assim como o C++ e Java, Python é uma linguagem do tipo "case-sensitive", ou seja, diferenças como "a" e "A" serão levadas em conta na identificação de uma variável. Nesta linguagem, o final de uma linha indica o final de uma declaração. Portanto, diferentemente de C++ e Java, não são necessários os pontos-e-vírgulas *(;)* ao final de cada declaração. Para inserirmos comentários, basta inserir o caractere *"#"* na frente do conteúdo a ser comentado.

```python
>>> a + str(len(a)) # Isto eh um comentario
'hi2'
```






