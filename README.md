# **Exercício 1:** Escreva um programa que use a função `range()` para gerar os números pares de 2 a 20 e, em seguida, imprima cada número. Utilize os métodos que vimos até então. 
lista1 = list(range(2,21,2))
print(lista1)



# **Exercício 2:** Escreva um programa que use a função `range()` para gerar os múltiplos de 5 em 5 a 50 e, em seguida.
lista2 = list(range(0,51,5))
print(lista2)



# **Exercício 3:** Escreva um programa que use a função `type()` para verificar o tipo de uma variável.
variavel1 = 'texto'
print(type(variavel1))



# **Exercício 4:** Escreva um programa que use a função `print()` para imprimir uma mensagem de saudação personalizada, incluindo o nome do usuário.
usuario = input('Nome do usuário: ')
mensagem = input('Escreva uma saudação: ')
print(usuario,"escreveu",mensagem)



# **Exercício 5:** Escreva um programa que use a função `range()` para gerar os números ímpares de 1 a 10 e, em seguida, calcule e imprima a média desses números.
impar = list(range(1,11,2))
total = sum(impar)
divisao = len(impar)
media = (total/divisao)
print('A media da lista é', media)





# **Exercício 6:** Descubra o máximo e o mínimo da sequência criada no  exercício 5
maximo = max(impar)
print('O maior numero da lista é: ', maximo)
minimo = min(impar)
print('O menor numero da lista é: ', minimo)


# **Exercício 7:** Ordene a lista  -  [10,56,40,5,4,9,7,1,0,56]
lista3 = [10,56,40,5,4,9,7,1,0,56]
organizacao = sorted(lista3)
print(organizacao)


# **Exercícios 8:**  some todos os valores da lista ordenada no exercício 7
soma = sum(lista3)
print('A soma da lista é:', soma)
