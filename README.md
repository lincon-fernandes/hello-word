n1 = int(input('digite um valor: '))
n2 = int(input('digite outro valor: '))
while True:
    
    print('\n[1] somar')
    print('[2] multiplicar')
    print('[3] maior')
    print('[4] novos numeros') 
    print('[5] sair do programa\n')

    opt = int(input('selecione alguma opção: '))
    
    if opt == 1:
        soma = n1 + n2
        print('\nA soma de {} e {} é: {}'.format( n1, n2, soma))
        
    elif opt == 2:
        prod = n1 * n2
        print('\nO produto de {} e {} é: {}'.format(n1, n2, prod))
        
    elif opt == 3:
        if n1 > n2:
            print('\nO maior numero entre {} e {} é {}'.format(n1, n2, n1))
        elif n2 > n1:
            print('\nO maior numero entre {} e {} é {}'.format(n1, n2, n2))
        else:
            print('\n{} e {} sao iguais'.format(n1, n2))

    elif opt == 4:
        print(' ')
        n1 = int(input('digite um valor: '))
        n2 = int(input('digite outro valor: '))
        print(' ')
    elif opt == 5:
        break
    else:
        opt = input('opçao invalida.. tente novamente: ')
print('volte sempre')
#first python project, simple, but I had to start from somewhere
