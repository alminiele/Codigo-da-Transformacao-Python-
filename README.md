# Codigo-da-Transformacao/Python-
bloco de código

cauculadora.py 

    print('==== Welcome ===')
    print('=== Mini Calculadora ')
    print('1 - soma')
    print('2 - subtração')
    print('3 - multiplicação')
    print('4 - divisão')

    print('Olá sou seu assistente hoje')
    print('Bem vindo, á mini calculadora')
    print('1. soma')
    print('2. subtração')
    print('3. Multiplicação')
    print('4 Divisão')

    operation = input('Escolha uma operação: ')
    num_1 = float(input('Digite o primeiro número: '))
    num_2 = float(input('Digite o segundo número: '))

    if operation =='1':
    print('Res: ',num_1 + num_2)
    elif operation ==' 2':
    print('Res:' ,num_1 - num_2)
    elif operation == '3':
    print('Res:' ,num_1 * num_2)
    elif operation == '4':
    print('Res:', num_1 / num_2 )
    else:
    print('Erro divisão por zero, tente outra vez...')
    print('Obrigado por usar a mini calculadora !!')


outro bloco de código.py


    def menu_primcipal():
    print('Bem vindo ao menu principal: ')
    print('Opções:')
    print('1- Somar')
    print('2- Subtrair')
    print('3 - verificar par')
    print('4- Sair')
    
    while 1:
        resultado = int(input('Digite sua opção: '))
        if resultado == 4:
            break
        elif resultado == 3:
            numero_um =int(input('Digite seu primeiro numero: '))
            numero_dois = int(input('Digite seu segundo numero: '))
            print(f'O resultado é: {soma(numero_um,numero_dois)}')
        elif resultado == 1 or 2:
            numero_um =int(input('Digite seu primeiro numero: '))
            numero_dois = int(input('Digite seu segundo numero: '))
            print(f'O resultado é: {subtracao(numero_um,numero_dois)}')
        elif resultado == 1:
            numero=int(input('Digite um numero: '))
            print(f'O resultado é: {eh_par(numero)}')
            
menu_primcipal()
