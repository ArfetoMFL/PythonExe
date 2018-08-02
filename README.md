# PythonExe
Tabuada Python

num = int (input('Digite um número para ver sua tabuada: '))
cont = 1
if num >= 1 and num <= 10:

    while cont <= 10:
        tab = num * cont
        print ('{} x {} = {}'.format(num,cont,tab)) 
        cont = cont + 1
else:
    print ('Apenas valores de 1 a 10')
