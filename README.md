# Curso-em-Video-Phyton
Exercicios

## Exercicio 01,02
nome = input ( 'QUAL É O SEU NOME? ' )
print('Seja bem vindo',nome)
idade = input ( 'QUAL É O SUA IDADE? ' )      
print('Sua idade é',idade)
cidade = input ( 'QUAL É O SUA CIDADE? ' )      
print('Sua cidade é',cidade)
print('Seu nome é', nome ,"você tem", idade,'anos','e mora em', cidade)

## Exercicio 03
n1 = int(input ('DIGITE O PRIMEIRO NUMERO'))
n2 = int(input ('DIGITE O SEGUNDO NUMERO'))
s = n1+n2
print ('A soma entre {}, e {} vale {}'.format(n1,n2,s))

## Exercicio 04
a = input('Digite algo: ')
print('O tipo primitivo desse valor é', type (a))
print('Só tem espaço?', a.isspace())
print('É um número?', a.isnumeric())
print('É alfabetico?', a.isalpha())
print('É alfanumerico?', a.isalnum())
print('Esta em minusculas?', a.islower())
print('Está em maisculas?', a.isupper())
print('Esta capitalizada?', a.istitle())

## Exercicio 05
n1= int(input('Digite o primeiro numero: '))
n2 = int(input('Digite o segundo numero: '))
s = n1 + n2
m = n1 - n2
d = n1 / n2
v = n1 * n2
di = n1 // n2
e = n1 ** n2
print(
    ' A soma é {}, A Subtração é {},  A divisão é {}, A multiplicação é {}, A divisao intenira é {} e a Potencia é {}'.format(
        s, m, d, v, di, e))

## Exercicio 06
n = int(input('Digite um numero: '))
a = n - 1
s = n + 1
print('O sucessor é {}, e o antecessor é {} ' .format(s, a))

## Exercicio 07
n = int(input('Digite um numero: '))
t = n * 3
r = n ** (1 / 2)
print('O triplo do numero digitado é {} e a raiz quadrada é {}' .format(t , r))

## Exercicio 08
n = int(input('Digite um numero: '))
d = n * 2
t = n * 3
r = n **(1 / 2)
print('O dobre do numero digitado é {}, o triplo é {} e a raiz quadrada é {}'.format(d,t,r))

## Exercicio 09
n1 = float(input('Digite a nota 1: '))
n2 = int(input('Digite a nota 2: '))
m = (n1 + n2)/2
print('A média final é {}'.format(m))

## Exercicio 10

n = int(input('Digite o metro: '))
c = n * 100
m = n * 1000
print('A conversão para centimetros é {}, e a para milimetros é {}'.format(c,m))

#Exercicio tabuada Simples 11
n = int(input('Digite um numero para ver a sua tabuada: '))
print('-'*12)
print('{} X {:2} = {}.' .format(n,1,n*1))
print('{} X {:2} = {}.'.format(n,2,n*2))
print('{} X {:2} = {}.'.format(n,3,n*3))
print('{} X {:2} = {}.'.format(n,4,n*4))
print('{} X {:2} = {}.'.format(n,5,n*5))
print('{} X {:2} = {}.' .format(n,6,n*6))
print('{} X {:2} = {}.'.format(n,7,n*7))
print('{} X {:2} = {}.'.format(n,8,n*8))
print('{} X {:2} = {}.'.format(n,9,n*9))
print('{} X {:2} = {}.'.format(n,10,n*10))
print('-'*12)

#Exercicio conversor de moeda 12
d = float(input('Quanto de dinheiro você tem RS?'))
d = d / 4.74
print('Você pode comprar US {:.2f}'.format(d))

#Exercicio quantos litros de tinta para pintar a parede 13
alt = float(input('Digite a altura da parede: '))
lar = float(input('Digite a largura da parede: '))
area = alt * lar
print('A área da parede é {:.2f}m² .'.format(area))
tinta = area / 2
print('Você irá gastar {:.2f} litros de tinta.'.format(tinta))

#Exercicio aplicando descontos 14
valor = float(input('Digite o valor do produto R$ '))
valor = valor-(valor * 5 / 100)
print('O valor do produto com desconto de 5% é {}'.format(valor))

#Exercicio aplicando reajuste salarial 15
salario = float(input('Digite o salario atual R$'))
salario = salario+(salario * 15 / 100)
print('O valor do salario com reajuste de 15% é {}'.format(salario))

#Exercicio aplicando reajuste salarial 16
c = float(input('Digite a temperatura em C°'))
c = ((9 * c)/5)+32
input('A conversão da temperatura c° para °F é {}'.format(c))

#Exercicio aluguel de carro 17
dia = int(input('Digite a quantidade de dias usados:'))
km = float(input('Quantos Km rodados: '))
pago = (dia * 60) + (km * 0.15)
print ('O carro foi alugado por {} dias, percorreu {} Km , o valor a ser pago é R${}'.format(dia,km,pago))

#Exercicio importando biblioteca 18
import math
#importando bibliotecas,from math import (escolhe uma funcionalidade) para importar biblioteca especifica
num = int(input('Digite um numero: '))
raiz = math.sqrt(num)
#função sqrt tras a raiz²
print('A raiz do numero {} digitado é {}'.format(num, math.floor(raiz)))
# math.floor arrendonda para baixo, math.ceil para arredondar para cima
#import ctrl + space tras a referencia de todas as bibliotecas do phyton

#Exercicio porção inteira 19
import math
num = float(input('Digite um numero real:'))
print('O numero real digitado foi {}, e sua porção inteira é {}'.format(num,math.trunc(num)))

#Exercicio calculando hipotenusa usando a biblioteca 20
import math
co = float(input('Qual o comprimento de cateto oposto?'))
ca = float(input('Qual o comprimento do cateto adjacente'))
hi = math.hypot(co, ca)
print('A hipitenusa vai medir {:.2f}'.format(hi))


#Exercicio calculando seno coseno tangente usando a biblioteca 21
import math
angulo = float(input('Digite o angulo que você deseja: '))
seno = math.sin(math.radians(angulo))
print('O angulo {} digitado tem o SENO de {:.2f}'.format(angulo,seno))
coseno = math.cos(math.radians(angulo))
print('O angulo {} digitado tem o COSENO de {:.2f}'.format(angulo,coseno))
tangente = math.tan(math.radians(angulo))
print('O angulo {} digitado tem o TANGENTE de {:.2f}'.format(angulo,tangente))

#Exercicio criando uma lista e sorteando um nome 22
import random
n1 = str(input('Digite o nome do primeiro aluno:'))
n2 = str(input('Digite o nome do segundo aluno:'))
n3 = str(input('Digite o nome do terceiro aluno:'))
n4 = str(input('Digite o nome do quarto aluno'))
n5 = str(input('Digite o nome do quinto aluno:'))
lista = [n1,n2,n3,n4,n5]
escolhido = random.choice(lista)
print('O aluno escolhido foi {}'.format(escolhido))

#Exercicio criando uma lista e sorteando uma ordem pelo nome
import random
n1 = str(input('Digite o nome do primeiro aluno:'))
n2 = str(input('Digite o nome do segundo aluno:'))
n3 = str(input('Digite o nome do terceiro aluno:'))
n4 = str(input('Digite o nome do quarto aluno'))
n5 = str(input('Digite o nome do quinto aluno:'))
lista = [n1,n2,n3,n4,n5]
escolhido = random.shuffle(lista)
print('A ordem do sorteio de alunos é')
print(lista)

#Exercicio condicionais 01

idade = int(input('Digite sua idade: '))
if idade <=18:
    print('Você é menor de idade')
else:
    print('Você é maior de idade')
print('__FIM__')

# Exercicio condicionais 02

carro = int(input('Digite o ano do seu carro:'))
if carro <= 2020:
    print('Seu carro é velho')
else:
    print('Seu carro é novo')

#Exercicio condicionais 03

n1 = float(input('Digite a sua primeira nota:'))
n2 = float(input('Digite sua segunda nota:'))
media = (n1+n2)/2
print('Sua média final é {}'.format(media))
if media <6:
  print('Você repetiu de ano:')
else:
  print('Você passou de ano:')

  # Exercicio condicionais 04

radar = float(input('Digite a velocidade ultrapassada: '))
if radar > 80:
      print('Você foi multado')
else:
      print('Você passou na velocidade permitida')


#Exercicio condicionais 05

n = int(input('Digite um numero:'))
if  n%2==0:
    print('O numero é par:'.format(n))
else:
    print('O numero é impar')


#Exercicio Jogo advinha

from random import randint
from time import sleep
computador = randint(0,5) # sorteio do numero pensado pelo computador
print('=*='*20)
print('Vou pensar em um numero e você tenta advinhar...Está pronto?')
print('=*='*20)
jogador = int(input('Advinhe o numero pensado '))
print('PROCESSANDO ...')
sleep(3)
if jogador == computador:
    print('Você adivinhou!!! O numero que eu pensei foi {}'.format(computador))
else:
    print('Você errou!!! o numero que eu pensei foi {}'.format(computador))
print('=*=' * 20)


  # Exercicio condicionais 06

radar = float(input('Digite a velocidade ultrapassada: '))
if radar > 80:
      print('Você foi multado')
else:
      print('Você passou na velocidade permitida')
multa = (radar-80)*7
print('O valor da multa á pagar é {:.2f}'.format(multa))

  # Exercicio condicionais 07

distancia = int(input('Digite qual a km da viagem: '))
passagem1 = distancia * 0.50
passagem2 = distancia * 1.00
if distancia <= 200:
    print('O valor da passagem é {}'.format(passagem1))
else :
    print('O valor da passagem é {}'. format(passagem2))


  # Exercicio condicionais 08

ano = int(input('Digite o ano para saber se é Bissexto: '))
if ano % 4 == 0 and ano % 100 != 0 :
    print('O ano de {} é Bissexto '.format(ano))
else:
    print('O ano de {} não é Bissexto '.format(ano))

 # Exercicio condicionais 09
a = int(input('Digite o primeiro numero: '))
b = int(input('Digite o segundo numero: '))
c = int(input('Digite o terceiro numero: '))
menor = a
if b<a and b<c:
    menor = b
if c<a and c<b:
        menor = c
print('O menor valor digitado é {}'.format(menor))
maior = a
if b>a and b>c:
    maior = b
if c>a and c>b:
    maior = c
print('O maior valor é {}'.format(maior))

# Exercicio condicionais 10

salario = float(input('Digite o salario: '))
aumento1 = salario +(salario * 15 / 100)
aumento2 = salario +(salario* 10 / 100)
if salario >= 1000:
    print('O valor do salario ajustado é {}'.format(aumento2))
else:
    print('O valor do salario ajustado é {}'.format(aumento1))

# Exercicio condicionais 11

l1 = int(input('Digite o lado 1: '))
l2 = int(input('Digite o lado 2: '))
l3 = int(input('Digite o lado 3: '))
if l1<l2 +l3 and l2<l1 + l3 and l3<l1+l2:
    print('Os seguimentos acima podem formar um triangulo')
else:
    print('Os seguimentos acima não podem formar um triangulo')
