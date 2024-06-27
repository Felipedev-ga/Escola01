# Escola01
Um exercício basico da minha escola atualmente


# [PY-A01] Faça um programa em python que determine em duas variáveis
# (senha e email) e que contenha uma senha e um email cadastrados antecipadamente,
# em seguida solicite ao usuário uma senha e um email e utilize o laço de repetição
# juntamente com a estrutura de condição para verificar se o email e a senha digitado
# pelo usuário é igual ao email e senha cadastrados antecipadamente. E enquanto a senha
# e o email que o usuário digitou não for igual ao email e senha cadastrados ele
# continue em um loop.

senha_cadastrada = "123456"
email_cadastrado = "gafriel.com"

while True:
    
    user_email = input('Digite seu email: ')
    user_senha = input('Digite sua senha: ')
      
    if user_email == email_cadastrado and user_senha == senha_cadastrada:
        print('Email e senha corretos.')
        break  
    else:
        print('Email ou senha incorretos. Tente novamente.')

print('Bem-vindo ao sistema!')
