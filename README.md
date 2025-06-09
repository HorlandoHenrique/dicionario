info_Usuario = {
    'nome': '',
    'telefone': '',
    'email': ''
}

for chave in info_Usuario:
    valor = input(f'Digite um valor para {chave}: ')
    info_Usuario[chave] = valor
     
print(info_Usuario)
# dicionario
