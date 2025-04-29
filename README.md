codigo horas e minutos:

hi,mi,hf,mf = map(int,input().split())

minuto_inicial=hi*60+mi
minuto_final=hf*60+mf

if minuto_final <= minuto_inicial:
  duracao = (24 * 60 - minuto_inicial) + minuto_final
else:
  duracao = minuto_final - minuto_inicial

horas = duracao // 60
minutos = duracao % 60

print(f'O JOGO DUROU {horas} HORA(S) E {minutos} MINUTO(S)')


codigo 10000:

N = int(input())

for i in range(1, 10001):
    if i % N == 2:
        print(i)



codigo tabuada:

num = int(input())
mult_1 = num * 1
mult_2 = num * 2
mult_3 = num * 3
mult_4 = num * 4
mult_5 = num * 5
mult_6 = num * 6
mult_7 = num * 7
mult_8 = num * 8
mult_9 = num * 9
mult_10 = num * 10

print(f"1 x {num} = {mult_1}")
print(f"2 x {num} = {mult_2}")
print(f"3 x {num} = {mult_3}")
print(f"4 x {num} = {mult_4}")
print(f"5 x {num} = {mult_5}")
print(f"6 x {num} = {mult_6}")
print(f"7 x {num} = {mult_7}")
print(f"8 x {num} = {mult_8}")
print(f"9 x {num} = {mult_9}")
print(f"10 x {num} = {mult_10}")


maior = 0
for i in range(1, 101):
    num = int(input())
    if num > maior:
        maior = num
        posicao = i
print(maior)
print(posicao)
