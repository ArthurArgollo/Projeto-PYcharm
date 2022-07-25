print("---------------------------------------")
print("(☞ﾟヮﾟ)☞ Adivinhe o numero ☜(ﾟヮﾟ☜) ")
print("---------------------------------------")

resposta_certa = 30
tentativas = 4
rodada = 1

while rodada <= tentativas:
    print("Tentativa {} de {}".format(rodada,tentativas))
    chance = input("coloca um numero ai tenta a sorte (●'◡'●) ")
    chances = int(chance)

    print("Voce colocou o número", chance)

    Acerto = (chances == resposta_certa)
    quase = (chances > 31 < 37)
    maior = (chances < resposta_certa)
    menor = (chances > resposta_certa)

    if Acerto:
        print(" Acertouuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuu o(*￣▽￣*)ブ")
        print("******Fim de jogo******")

    else:
        if maior:
            print("foi quase põe um numero maior ai (～￣▽￣)～ ")
        elif menor:
            print("opa quase, põe um numero menor =￣ω￣=  ")
        elif chances:
            print("Muitoo pertoo '0' ")

    rodada = rodada + 1
