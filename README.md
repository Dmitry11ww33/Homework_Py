Homework Python
-----------------------------
Ex.1

Выведите столбец чисел от 1 до 100, используя цикл while

n = 1
for i in range (1, 100): 
    print(f"{n + i}")
    
-----------------------------
Ex.2

Дано число n. Вывести степени этого числа с 1 по 10
пример
n=2
2^1=2
2^2=4
…
2^9=512
2^10 = 1024
 
n = 2
for i in range (1, 10):
    print(f'{n**i}')
