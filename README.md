# projeto-isabela-bay
trabalho da isabela 1:d
//
7. Jogo da Adivinhação
Descrição: O software deve gerar um número aleatório entre 1 e 100, e o jogador deve tentar adivinhar esse número.
Especificação: O programa gerará um número aleatório e permitirá que o usuário insira palpites. A cada palpite, o programa informará se o número escolhido pelo jogador é maior ou menor que o número correto, até que o jogador acerte
Pseudocódigo↴
incío 
gerar número aleatorio ("1 entre 100")
permitir que o usuario possa dar palpite
adinhação do usuario sobre o numero aleatorio
informar se numero escolhido ("numero adivinhado está correto")
ou senão
informar se numero escolhido ("é maior do que o número aleatorio")
ou senão
informar se ("é menor do que o número aleatorio")
então
permitir outro palpite do usuario até que ele acerte, repetindo todos os comandos anteriores.

código

# Gerar um número aleatório entre 1 e 100
numero_aleatorio = random.randint(1, 100)
# Loop para permitir que o usuário continue tentando até acertar
    # Solicitar palpite do usuário
    palpite = int(input("Dê o seu palpite (entre 1 e 100): "))
    
    # Verificar se o palpite está correto, maior ou menor
    if palpite == numero_aleatorio:
        print("Parabéns! Você acertou o número!")
    elif palpite < numero_aleatorio:
        print("O número escolhido é menor do que o número aleatório.")
    else:
        print("O número escolhido é maior do que o número aleatório.")
