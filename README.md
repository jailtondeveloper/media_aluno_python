# media_aluno_python
Cálculo de notas usando While
aluno =  (input("Informe o nome do aluno: "))
contador = 1
soma = 0.0

while contador  <=4:
    print (contador, "ª nota: ")
    nota = float (input())
    soma+= nota
    contador +=1

print(f"A média do aluno {aluno} é {soma / 4}")
