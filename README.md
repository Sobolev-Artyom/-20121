Отчет № 1
 Соболев Артём
 


from itertools import permutations 

listw = input().split()     # Ввод списка с клавиатуры

rev = permutations (listw)   # Изменение позиций в списке
print(rev)
for i in list(rev):
    print(i)                # Выводятся полученные списки
