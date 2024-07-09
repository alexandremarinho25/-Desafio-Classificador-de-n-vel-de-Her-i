# -Desafio-Classificador-de-n-vel-de-Her-i
# Solicita ao usuário o nome do herói e sua XP
nome = input("Digite o nome do herói: ")
xp = int(input("Digite a quantidade de XP do herói: "))

# Determina o nível com base na XP utilizando estrutura de decisão
if xp < 1000:
    nivel = "Ferro"
elif xp <= 2000:
    nivel = "Bronze"
elif xp <= 5000:
    nivel = "Prata"
elif xp <= 7000:
    nivel = "Ouro"
elif xp <= 8000:
    nivel = "Platina"
elif xp <= 9000:
    nivel = "Ascendente"
elif xp <= 10000:
    nivel = "Imortal"
else:
    nivel = "Radiante"

# Exibe a mensagem com o nome do herói e seu nível
print(f"O Herói de nome {nome} está no nível de {nivel}")
