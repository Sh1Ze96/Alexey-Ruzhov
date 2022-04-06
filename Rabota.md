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

<strong>4.1 Выбор из двух</strong>

Код№1 - a = input() b = input() if a == b: print('Пароль принят') else: print('Пароль не принят')

Код№2 - a = int(input()) if a % 2 == 0: print('Четное') else: print('Нечетное')

Код№3 - a = int(input()) b = a // 1000 c = a // 100 - (a // 1000 * 10) d = (a % 100 - a % 10) / 10 e = a % 10 if b + e == c - d: print('ДА') else: print('НЕТ')

Код№4 - age = int(input()) if age >= 18: print('Доступ разрешен') else: print('Доступ запрещен')

Код№5 - a = int(input()) b = int(input()) c = int(input()) if b - a == c - b: print('ДА') else: print('НЕТ ')

Код№6 - a = int(input()) b = int(input()) if a > b: print(b) else: print(a)

Код№7 - a = int(input()) b = int(input()) c = int(input()) d = int(input()) e = min(a, b, c, d) print( д)

Код№8 - a = int(input()) if a <= 13: print('детство') elif a >= 14 и a <= 24: print('молодость') elif a >= 25 и a <= 59: print('зрелость') elif a >= 60: print('старость')

Код№9 - a = int(input()) b = int(input()) c = int(input()) d = int() d = 0, если a > 0: d = d + a, если b > 0 : d = d + b, если c > 0 d = d + c print(d)
        ![image](https://user-images.githubusercontent.com/97594421/158535532-48f02508-41d8-47c8-9240-ad5a92171eba.png)
        
<strong>4.2 Логические операции</strong>
Код№1 -a = int(input())
if a > -1 and a < 17:
    print('Принадлежит')
else:
    print('Не принадлежит')
Код№2 -n = int(input())
if not (-3 < n < 7):
    print('Принадлежит')
else:
    print('Не принадлежит')
                    
Код№3 - a = int(input())                 
if (a > -30 and a <= -2) or (a > 7 and a <= 25):
    print('Принадлежит')
else:
    print('Не принадлежит')
                                               
Код№4 - a = int(input())
if (a % 7 == 0 or a % 17 == 0) and (a >= 1000 and a <= 9999):
    print('YES')
else:
    print('NO')
                                                            
Код№5 - a = int(input())
b = int(input())
c = int(input())
if (a < (b + c)) and (b < (a + c)) and (c < (a + b)):
    print("YES")
else:
    print("NO")

Код№6 - import calendar
print("YES" if calendar.isleap(int(input())) else "NO")

Код№7 - a, b, c, d = int(input()), int(input()), int(input()), int(input())
if a == c or b == d:
    print('YES')
else:
    print('NO')

Код№8 - a, b, c, d = int(input()), int(input()), int(input()), int(input())
if (-1 <= a - c <= 1) and (-1 <= b - d <= 1):
    print('YES')
else:
    print('NO')
        ![image](https://user-images.githubusercontent.com/97594421/159642277-c2a013bb-7c28-49d1-a781-375871e74a14.png)
        
<strong>4.3 Вложенные и каскадные условия</strong>

Код№1 - a = int(input()) b = int(input()) если b > a: print("ДА") если a > b: print("НЕТ") если a == b: print( "Не знаю")

Код№2 - a = int(input()) b = int(input()) c = int(input()) if a == b == c: print("Равносторонний") if (a == b или a == c или b == c) и (a != c или a != b или b != c): print("Равнобедренный"), если a != b и a != c и c != b: print("Разносторонний")

Код№3 - a, b, c = int(input()), int(input()), int(input()) если a < b < c или a > b > c: print(b) elif b < c < a или b > c > a: print(c) else: print(a)

Код№4 - m = int(input()) if m == 2: print('28') elif m <= 7: print(30 + m%2 ) else: print(31 - m%2 )

Код№5 - n = int(input()) if n < 60: print('Легкий вес') elif n < 64: print('Первый полусредний вес') elif n < 69: print('Полусредний вес')

Код№6 - a, b = int(input()), int(input()) s = input() if s == '+': print(a + b) elif s == '-': print( a - b) elif s == '*': print(a * b) elif s == '/': if b == 0: print('На ноль делиться нельзя!') else: print(a / b) else: print('Неверная операция')

Код№7 - color1, color2 = input(), input() if color1 == 'красный' и color2 == 'синий' или (color1 == 'синий' и color2 == 'красный'): print('фиолетовый ') elif color1 == 'желтый' and color2 == 'синий' или (color1 == 'синий' and color2 == 'желтый'): print('зеленый') elif color1 == 'красный' and color2 == 'желтый' или (color1 == 'желтый' и color2 == 'красный'): print('оранжевый') elif color1 == 'красный' и color2 == 'красный' или color1 == 'желтый' и color2 = = 'желтый' или color1 == 'синий' и color2 == 'синий': print(color1) else: print('ошибка цвета')

Код№8 - n = int(input())

если n < 0 или n > 36: print('ошибка ввода') elif n == 0: print('зеленый') elif 1 <= n <= 10: if n % 2 == 0: print('черный' ) else: print('красный') elif 11 <= n <= 18: if n % 2 == 0: print('красный') else: print('черный') elif 19 <= n <= 28: if n % 2 == 0: print('черный') else: print('красный') elif 29 <= n <= 36: if n % 2 == 0: print('красный') else: print('черный ')

Код№9 - a1, b1, a2, b2 = int(input()), int(input()), int(input()), int(input())

if a2 < a1: if b2 < a1: print('пустое множество' elif b2 == a1: print(b2) elif a1 < b2 <= b1: print(a1, b2) elif b2 > b1: print(a1, b1 ) elif a2 == a1: if b2 <= b1: print(a2, b2) else: print(a2, b1) elif a2 < b1: if b2 <= b1: print(a2, b2) else: print(a2, b2) b1) elif a2 == b1: print(a2) else: print('пустое множество')
![photo1649225812](https://user-images.githubusercontent.com/97594421/161908570-3b24d56d-3713-4f17-a0dd-bb3b36aa1bde.jpeg)
