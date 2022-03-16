# Alexey-Ruzhov
https://replit.com/@Sh1Ze96/Ruzhov-205

"Поколение Python": курс для начинающих Курс с кучей тренировочных задач, удобный как для самостоятельного изучения, так и для работы в группе в рамках внеурочной деятельности. 

https://stepik.org/course/Поколение-Python-курс-для-начинающих-58852/

"Поколение Python": курс для начинающих"

<h1><strong>2  Ввод-вывод данных</h1></strong>

<strong>2.1 Введение. Знакомство с Python!</strong> 
![Opera Снимок_2022-02-01_212459_stepik org](https://user-images.githubusercontent.com/97594421/152031504-e4476815-0cc3-4464-b900-19e4d990efaa.png)
<strong><h1><strong>2.2 Команды print и input</strong>

Код№1 - print('Здравствуй, мир!')

Код№2 - print('4', '8', '15', '16', '23', '42')

Код№3 - print('4')
        print('8')
        print('15')
        print('16')
        print('23')
        print('42')
        
Код№4 - print('*')
        print('**')
        print('***')
        print('****')
        print('*****')
        print('******')
        print('*******')
        
Код№5 - name=input()
        print('Привет,', name)
        
Код№6 - name=input()
        print(name,'- чемпион!')
        
Код№7 - name1=input()
        name2=input()
        name3=input()
        print(name1)
        print(name2)
        print(name3)
        
Код№8 - name3=input()
        name2=input()
        name1=input()
        print(name1)
        print(name2)
        print(name3)
        ![Opera Снимок_2022-02-01_222735_stepik org](https://user-images.githubusercontent.com/97594421/152037381-80ca8a24-64af-4e71-8921-27a80decd0eb.png)
        
<strong>2.3 Параметры sep и end</strong>

Код№1 - print('I', 'like', 'Python', sep='***')

Код№2 - a=input()
        b=input()
        c=input()
        d=input()
        print(b, c, d, sep=a) 

Код№3 - name=input() 
        print('Привет,', name, end='!')
        ![изображение_2022-02-08_212815](https://user-images.githubusercontent.com/97594421/153052251-6c047927-a40d-4f20-a1d9-8da81c8ba01e.png)
<strong>2.4 Целочисленная арифметика</strong>

Код№1 - a = int(input()) print(a) print(a + 1) print(a + 2)

Код№2 - a = int(input()) b = int(input()) c = int(input()) print(a + b + c)

Код№3 - a = int(input()) print('Объем =', a * a * a) print('Площадь полной поверхности =', 6 * a * a)

Код№4 - a = int(input()) b = int(input()) print(3 * (a+b) * (a+b) * (a+b) + 275 * b * b - 127 * а - 41)

Код№5 - a = int(input()) print('Следующее за числом', a, 'число:', a + 1) print('Для числа', a, 'предыдущее число:', a - 1)

Код№6 - a = int(input()) b = int(input()) c = int(input()) d = int(input()) print(3 * (a + b + c + d))

Код№7 - a = int(input()) b = int(input()) print(f"{a} + {b} = {a+b}") print(f"{a} - {b} = {ab}") print(f"{a} * {b} = {a*b}")

Код№8 - a = int(input()) b = int(input()) c = int(input()) d = a + b * (c - 1) print(d) Код№9 - a = int (input()) print(a, 2 * a, 3 * a, 4 * a, 5 * a, sep='---')
        ![image](https://user-images.githubusercontent.com/97594421/158534249-37c44025-bc3c-41cc-ad62-8d3fb450e303.png)


<strong>2.5 Целочисленная арифметика</strong>

Код№1 - b1 = int(input()) q = int(input()) n = int(input()) print(b1 * q ** (n-1))

Код№2 - ab = int(input()) b = ab // 100 print(b)

Код№3 - sch = int(input()) fru = int(input()) print(fru//sch) print(fru%sch)

Код№4 - ребята = int(input()) print(ребята//2 + ребята%2)

Код№5 - a = int(input()) print((a-1) // 4 + 1)

Код№6 - min = int(input()) print(min, f'мин - это {min // 60} час {min % 60} минут.')

Код№7 - abcd = int(input()) print('Сумма цифр =', abcd//100 + (abcd % 100) // 10 + abcd%10) print('Произведение цифры =', (abcd// 100) * ((abcd % 100) // 10) * (abcd% 10))

Код№8 - abc = int(input()) c = abc % 10 b = (abc % 100) // 10 a = abc // 100 print(a, b, c, sep='') print(a, c,b, sep='') print(b,a,c, sep='') print(b,c,a, sep='') print(c,a,b, sep='') print( в, б, а, раздел = '')

Код№9 - a = int(input()) a1 = a // 1000 a2 = (a // 100) % 10 a3 = (a // 10) % 10 a4 = a % 10 print("Цифра в позиции тысяч равным", a1) print("Цифра в позиции примерно равной", a2) print("Цифра в позиции примерно равной", a3) print("Цифра в позиции примерно равной", a4)
        ![image](https://user-images.githubusercontent.com/97594421/158534306-dabff4e3-8fcc-4fa5-b1c3-d64620367f43.png)

4.1 Выбор из двух

Код№1 - a = input() b = input() if a == b: print('Пароль принят') else: print('Пароль не принят')

Код№2 - a = int(input()) if a % 2 == 0: print('Четное') else: print('Нечетное')

Код№3 - a = int(input()) b = a // 1000 c = a // 100 - (a // 1000 * 10) d = (a % 100 - a % 10) / 10 e = a % 10 if b + e == c - d: print('ДА') else: print('НЕТ')

Код№4 - age = int(input()) if age >= 18: print('Доступ разрешен') else: print('Доступ запрещен')

Код№5 - a = int(input()) b = int(input()) c = int(input()) if b - a == c - b: print('ДА') else: print('НЕТ ')

Код№6 - a = int(input()) b = int(input()) if a > b: print(b) else: print(a)

Код№7 - a = int(input()) b = int(input()) c = int(input()) d = int(input()) e = min(a, b, c, d) print( д)

Код№8 - a = int(input()) if a <= 13: print('детство') elif a >= 14 и a <= 24: print('молодость') elif a >= 25 и a <= 59: print('зрелость') elif a >= 60: print('старость')

Код№9 - a = int(input()) b = int(input()) c = int(input()) d = int() d = 0, если a > 0: d = d + a, если b > 0 : d = d + b, если c > 0 d = d + c print(d)
