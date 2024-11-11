# Лінійні проєкти


## Робота з числовими змінними: 

**На уроці:**
Створіть програму, яка знайде суму двох чисел, введених користувачем.
<details>
  <summary>
    Задача
  </summary>
  
  ```python
    a = int(input("Введіть перше число:"))
    b = int(input("Введіть друге число:"))
    s = a+b
    print("Сума:", s)  
  ```
</details>

**Самостійне завдання:**
Доповніть програму ще однією  змінною. Створіть нову змінну, в яку запишіть добуток введених чисел, та виведення її на екран
<details>
  <summary>
    Розвʼязок
  </summary>
  
  ```python
    a = int(input("Введіть перше число:"))
    b = int(input("Введіть друге число:"))
    s = a+b
    g = a*b
    print("Сума:", s)
    print("Добуток:", g)  
  ```
</details>


## Задачі з числовими змінними: 

**На уроці:**
1. Створіть програму, для обчислення периметра квадрату.
<details>
  <summary>
    Задача
  </summary>
  
  ```python
    a = int(input("Введіть довжину сторони квадрата:"))
    p = a*4
    print("Периметр квадрата: ", p)  
  ```
</details>

**Самостійно:**
1. Створіть програму, для обчислення периметра прямокутника.
<details>
  <summary>
    Розвʼязок
  </summary>
  
  ```python
    a = int(input("Введіть довжину 1 сторони прямокутника:"))
    b = int(input("Введіть довжину 2 сторони прямокутника:"))
    p = (a+b)*2
    print("Периметр прмокутника: ", p)  
  ```
</details>

2. Створіть програму, для обчислення периметра і площі прямокутника.
<details>
  <summary>
    Розвʼязок
  </summary>
  
  ```python
    a = int(input("Введіть довжину 1 сторони прямокутника:"))
    b = int(input("Введіть довжину 2 сторони прямокутника:"))
    p = (a+b)*2
    s = a*b
    print("Периметр прмокутника: ", p)
    print("Площа прмокутника: ", s)  
  ```
</details>


## Задачі з умовою (розгалуженням): 
**На уроці:**
1. Створіть програму, для обчислення периметра прямокутника. Додайте перевірку, що б введена сторна не була відʼємним числом.
<details>
  <summary>
    Розвʼязок
  </summary>
  
  ```python
    d = int(input("Введіть довжину сторони квадрата:"))
    if d <= 0:
        print('Довжина не може бути відʼємною')
    else:
        p = d*4
        print("Периметр квадрата: ", p)  
  ```
</details>   

2. Стоворіть програму, яка визначе додатнє чи відʼємне число ввів користувач
<details>
  <summary>
    Розвʼязок
  </summary>
  
  ```python
    d = int(input("Введіть число:"))
    
    if d > 0:
        print('Число додатнє')
    elif d < 0:
        print("Число відємне")
    else:
        print('Число = 0')
  ```
</details>   
