# sdffsdfsfas
adsasDADSA
rint("Ile masz pieniędzy")
hajs = int(input())

if hajs >= 20:
    print("Możesz wejść")
else:
    print("Nie możesz wejść")
# zadanie 2

a = 0

while a < 10 :
     print(a)
     a = a + 1
print("koniec")

#zadanie 3

for i in range(0,5):

    print(i)
print("koniec")

                      #Ćwiczenia pętla while
a=0

b = int(input("Podaj ile liczb chcesz wypisać:"))

while a<b:

    print(a)

    a = a + 1
print("koniec")

i=1

while i<=3:

    print('*')

    i += 1

    #zadanie 6

from random import randint

los = randint(1,10)
odp = -1
p = 0
print("wybierz liczbe w zakresie od 1 - 10")

while odp != los:
    p += 1
    odp = int(input("podaj liczbę: "))
    if odp > los :
        print("podaj mniejszą liczbę")
    elif odp < los :
        print("Podaj wieksza liczbe")
print('Brawo odgadłeś liczbę za ' ,p, 'probą')
