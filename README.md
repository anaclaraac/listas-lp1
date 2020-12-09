# listas-lp1
#LISTA 1 PYTHON 
#Questao 1 letra a
x = float(input('digite um valor numérico ')) 

def quadrado (x):
    calculo = x ** 2
    return calculo
print(quadrado (x))


#Questao 1 letra b
x = float(input('digite um valor númerico '))
y = float(input('digite um segundo valor numérico '))

def divisao(x,y):
    calculo = (x/y)
    return calculo 
print(divisao(x,y))


#Questao 1 letra c
x = float(input('digite um valor númerico '))

def restoDivisao(x):    
    calculo = x%2   
    return calculo
print(restoDivisao(x))


#Questao 1 letra d
x = float(input('digite um valor númerico '))
y = float(input('digite um segundo valor numérico '))

def media(x,y):
    calculo = ((x + y) / 2)
    return calculo 
print(media(x,y))


#Questao 1 letra e 
raio = float(input('digite o raio '))
pi = 3.14

areaCircunferencia = pi * (raio**2)
print(areaCircunferencia)

comprimento = 2 * pi * raio
print(comprimento)

diametro = 2 * raio
print(diametro)


#Questao 2 letra a
(4 * 4) + 1
#17

#Questao 2 letra b
6 + 20 - 23
#3

#Questao 2 letra c
(3.0 * 5.0) + 1
#16

#Questao 2 letra e
(29.0/7) + 4
#8.142857142857142

#Questao 2 letra f
(3/6.0) - 7
#-6.5

#Questao 2 letra g
2/2
#1

#Questao 2 letra h
2//2
#1

#Questao 2 letra i
4%2
#0

#Questao 2 letra j
(100// 5) % 5
#0

#Questao 3 letra a
2 < 3
#true

#Questao 3 letra b
(6 < 3 ) or ( 10 > 11 )
#false

#Questao 3 letra c
((( 6 // 3 ) % 2 > 5 and ( 2 < ( 3 % 2 ))
#false

#Questao 3 letra d
(2<3)
#true
#com fatorial nao funciona

#Questao 4
a = 10
b = 6
c = 2
d = 4
e = 2
f = 2
x = (( a - ((b/c) *2))/ d + (e/f)) * 2
print(x)

x = 4
y = ( 2 + x - (((2*(x**2)**(x + 2))))/2) - (((x+1)**1/2)/x)/(3**x)
print(y)

#Questao 5
nome = input(' digite seu nome ')
print('Olá,',nome,)

#Questao 6
i = 0
valores = []
quantValores = 3
while i < quantValores:
    valores.append(int(input('digite um valor ')))
    i += 1
print(sorted(valores))

#Questao 7
i = int(input('digite um valor '))
print(i)

if i > 0:
    print(i,'é positivo')
else:
    print(i,'é negativo')

#Questao 8
temperatura = float(input('digite a temperatura '))

def tempConversao():
     tempK = 273
     calculoF = (temperatura * (9/5)) + 32
     calculoK = tempK + temperatura 
     return calculoF, calculoK 
print(tempConversao())

#Questao 9
i = int(input('digite um valor '))
j = int(input('digite um segundo valor '))

if i == j:
    print('são iguais')
elif i > j:
    print('o primeiro valor é maior que o segundo')
elif i < j:
    print('o segundo valor é maior que o primeiro')

#Questao 10
j = int(input('digite um valor '))
def verificarPrimo(x):
    for i in range(2,x):
        if j % i == 0:
            return('é um número primo')
if j <= 10:
    print(verificarPrimo(x))
else:
    while j > 10:
        x = int(input('digite um valor entre 0 e 10'))
print(verificarPrimo(x))

#Questão 11
i = float(input('digite um valor '))
j = float(input('digite um segundo valor '))
k = float(input('digite um terceiro valor '))

if i>= j + k or j>= i + k or k>= i + j :
    print('não é possível montar um triângulo')

#Questao 12
def areaTriangulo(vBase, vAltura):
    altura = float(vAltura)
    base = float(vBase)
    calculo = (( base * altura) / 2)
    return calculo 
vBase = input('digite o valor base ')
vAltura = input('digite o valor altura ')
resultado = areaTriangulo(vBase, vAltura)
print('a área do triângulo é', resultado)

#Questao 13
i = int(input())
j = int(input())
k = int(input())

print(i, j, k)

if i==j or j==k or i==k:
    print('triângulo isosceles')
elif a != b and a != c:    
    print ('triângulo escaleno')
elif a==b and a==c:
    print('triângulo equilátero')

#Questao 14
vUm = int(input('primeiro ângulo '))
vDois = int(input('segundo ângulo '))
vTres = int(input('terceiro ângulo '))

def vTriangulo(vUm,vDois,vTres):
    somaAngulosInt = vUm + vDois + vTres 
    if somaAngulosInt != 180:
        return false
    else: 
        return true
while vTriangulo(vUm,vDois,vTres) == False
    print('a soma dos ângulos internos de um triângulo deve ser igual a 180. Digite novamente os valores')
vUm = int(input('primeiro ângulo '))
vDois = int(input('segundo ângulo '))
vTres = int(input('terceiro ângulo '))
if vUm > 90 or vDois > 90 or vTres > 90:
    print('obtusangulo')
elif vUm < 90 or vDois < 90 or vTres < 90:
    print('acutangulo')
elif vUm == 90 or vDois == 90 or vTres == 90:
    print('triângulo retângulo')

#Questao 15
potencia = int(input('potencia da lampada '))
largura = int(input('largura do comodo '))
comprimento = int(input('comprimento do comodo '))

def metroQuadrado(largura, comprimento):
    calculo = largura * comprimento
    return calculo

potenciaTotal = 18 * metroQuadrado(largura, comprimento)

quantLampadas = potenciaTotal / potencia 
print(quantLampadas)

#Questao 16
altura = int(input('digite a altura '))
comprimento = int(input('digite o comprimento '))
largura = int(input('digite a largura '))

def vComodo(largura, comprimento, altura):
    calculo = largura * altura * comprimento 
    return calculo

caixasAzulejo = vComodo(largura,comprimento,altura)/1.5
print(caixasAzulejo)

#Questao 17
kmInicio = float(input('odômetro na marcação início'))
kmFim = float(input('odômetro na marcação final'))
combustivelGasto = int(input('litros de combustível gasto'))
consumoMedio = (kmFim - kmInicio) / combustivelGasto
print(consumoMedio)

#Questao 18
av1 = int(input('a nota da avaliação um é '))
av2 = int(input('a nota da avaliação dois é '))
optativa = int(input('a nota da optativa é '))

media1 = (av1 + av2) / 2
media2 = (av1 + optativa) / 2
media3 = (av2 + optativa) / 2
mediaFinal =[]
if ((media1 > media2) and (media1 > media3)):
    mediaFinal = media1
else:
    if (media2 > media3):
              mediaFinal = media2
    else:
              mediaFinal = media3
if (mediaFinal>=6):
    print('Aprovado com média ')
elif ((mediaFinal >=3) and (mediaFinal <6)):
    print('exame média ')
else:
    print('reprovado com média ')
print(mediaFinal)

#Questao 19
idadeMulher1 = int(input('digite a idade da mulher um '))
idadeMulher2 = int(input('digite a idade da mulher dois '))
idadeHomem1 = int(input('digite a idade do homem um '))
idadeHomem2 = int(input('digite a idade do homem dois '))
mulherMaisNova = []

if idadeMulher1 > idadeMulher2:
    mulherMaisVelha = idadeMulher1
else:
    mulherMaisVelha = idadeMulher1
    mulherMaisNova = idadeMulher2

if idadeHomem1 > idadeHomem2:
    homemMaisVelho = idadeHomem1 
    homemMaisNovo = idadeHomem2 
else:
    homemMaisNovo = idadeHomem1
    homemMaisVelho = idadeHomem2

sFinal = homemMaisVelho + mulherMaisNova
pFinal = homemMaisNovo * mulherMaisVelha
print(sFinal)
print(pFinal)

#Questao 20
string1 = input('digite a string um ')
string2 = input('digite a string dois ')
if string1 == string2:
    print('as strings são iguais')
else:
    print('as strings são diferentes')

#Questao 11 obs.: tinha questões repetidas nas listas um e dois 


#Questao 12

i = input('digite uma palavra ')
j = input(' digite uma segunda palavra ')
x = list(i)
x.sort()
print(x)
y = list(j)
y.sort()
print(y)

if x==y:
    print('é anagrama')
else:
    print('não é anagrama')

#Questao 13

m1 = [[1, 2, 3], [0, 2, 5], [9, 4 ,3]]
m2 = [[5, 3, 8], [1, 2, 3], [7, 6, 5]]
resultado = []

for i in range(len(m1)):
    linha = []
    for j in range(len(m2[0])):
          linha.append(m1[i][j] * m2 [i][j])
          resultado.append(linha)
print(resultado)

#Questao 14

m1 = [[1, 2, 3], [0, 2, 5], [9, 4 ,3]]
m2 = [[5, 3, 8], [1, 2, 3], [7, 6, 5]]
def calculo(operacao):
    resultado = []
    for i in range(len(m1)):
        linha = []
        for j in range(len(m2[0])):
            if(operacao == ("soma")):
                linha.append(m1[i][j],m2[i][j])
            elif(operacao == ("subtracao")):
                linha.append(m1[i][j],m2[i][j])
            elif(operacao == ("multiplicacao")):
                linha.append(m1[i][j],m2[i][j])
        resultado.append(linha)
    return resultado 
print('calculo("soma")')
print('calculo("subtracao")')
print('calculo("multiplicacao")')

#Questao 15

vInicial = int(input(''))
vFinal = int(input(''))
if(vInicial <=0):
    vInicial = 1

for i in range(vInicial, vFinal + 1):
    somaDiv = 0 
    for j in range(1, i):
        if(i % j ==0):
            somaDiv += j
    if(somaDiv == i):
        print('i é um número perfeito')
