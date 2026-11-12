#Faça um programa que leia o ano de nascimento de um jovem e informe, de acordo com a sua idade, se ele ainda vai se alistar ao serviço militar,
#se é a hora exata de se alistar ou se já passou do tempo do alistamento. Seu programa também deverá mostrar o tempo que falta ou que passou do prazo.

from datetime import date

ano = int(input("Digite o seu ano de nascimento, e consulte a situação do seu Alistamento Militar: "))
atual = date.today().year
idade = atual - ano

if idade == 18:
    print(f"Você tem {idade} anos de idade, portanto está na hora de se alistar...")

if idade < 17:
    print(f"Você tem {idade} anos de idade, faltam {18 - idade} anos pra que você tenha que se alistar...")

if idade > 18:
    print(f"Você tem {idade} anos de idade, já se passaram {idade - 18} anos do seu alistamento...")
