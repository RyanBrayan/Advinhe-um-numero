from time import sleep
import random
jogador1 = str(input("Player 1 digite seu nome ")).capitalize()
jogador2 = str(input("Player 2 digite seu nome ")).capitalize()
print("="*20)
print()
player1= 0
player2 = 0
aleatorio = random.randint(0, 10)
pause = 10
jogadas = []
while pause <= 10:
    if len(jogadas) > 0 :
        print(f"numeros jogados: {jogadas}")
    jogador_1 = int(input(f"{jogador1} escolha um numero: "))
    jogador_2 = int(input(f"{jogador2} escolha um numero: "))
    print("="*20)
    print(f"{jogador1} tem {player1 } ponto ||| {jogador2} tem {player2} ponto")
    if jogador_1 == aleatorio:
            aleatorio = random.randint(0, 10)
            player1 += 1
            print(f" {jogador1} acertou e recebeu um ponto ")
            jogadas.clear()
            sleep(2)
            print('='*20)
            print()
    elif jogador_2 == aleatorio:
        aleatorio = random.randint(0, 10)
        player2 += 1
        print(f" {jogador2} acertou e recebeu um ponto ")
        jogadas.clear()
        sleep(2)
        print('='*20)
        print()
        
    else:
        if jogador_1 and jogador_2 != aleatorio:
            jogadas.append(jogador_1)
            jogadas.append(jogador_2)
            sleep(2)
            print("Vocês erraram")
            print('='*20)
            print()
