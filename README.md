# python
#Ex 2:
numero = input('Digite o número desejado:') print('O número informado foi:', numero)

#Ex 3:
numero1 = input('Digite o primeiro número:') numero2 = input('Digite o segundo número:') soma = int(numero1) + int(numero2) print('A soma dos dois números foi:', soma)

#Ex 7:
comp = input('Digite o comprimento do quadrado:') larg = input('Digite a largura do quadrado:') area = int(comp) * int(larg) area2 = area * 2 print('A área do quadrado é:', area) print('O dobro desta área é:', area2)

#Ex 9:
fr = input('Digite a temperatura em graus fahrenheit:') celsius1 = int(fr) - 32 celsius2 = (celsius1 / 9) * 5 print('A temperatura em fahrenheit é:', fr) print('Essa temperatura convertida para graus celsius é:', celsius2)

#3.Faça um Programa que verifique se uma letra digitada é "F" ou "M". Conforme a letra escrever: F - Feminino, M - Masculino, Sexo Inválido:
genero = input('Digite o seu sexo indicando masculino com M ou feminino com F:') if genero == 'F' or genero == 'f': print('F-feminino') elif genero == 'M' or genero == 'm': print('M-Masculino') else: print('Sexo inválido')

#5.Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar:
a. A mensagem "Aprovado", se a média alcançada for maior ou igual a sete; b. A mensagem "Reprovado", se a média for menor do que sete; c. A mensagem "Aprovado com Distinção", se a média for igual a dez. nota1 = float(input('Digite a primeira nota:')) nota2 = float(input('Digite a segunda nota:')) media = (nota1 + nota2) / 2 if media >= 7 and media != 10: print('Aprovado') elif media == 10: print('Aprovado com Distinção') else: print('Reprovado')

#7. Faça um Programa que leia três números e mostre o maior e o menor deles.
a = int(input('Digite o primeiro valor:')) b = int(input('Digite o segundo valor:')) c = int(input('Digite o terceiro valor:')) maior = a if b > a and b > c: maior = b if c > a and c > b: maior = c menor = a if b < c and b < a: menor = b if c < b and c < a: menor = c print('O menor número digitado foi menor', menor) print('O maior número digitado foi', maior)

#1.
nota = float(input("Digite uma nota entre 0 e 10: ")) while (nota < 0 or nota > 10): nota = float(input("Valor invalido. Digite uma valor entre 0 e 10: "))

#9.
for i in range(1,51,2): print (i)
