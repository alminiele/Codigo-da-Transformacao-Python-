# Codigo-da-Transformacao/Python-
bloco de código

cauculadora 
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
