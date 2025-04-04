points = int(input("Введіть кількість набраних балів: "))

if 0 <= points <= 49:
    print("Оцінка: незадовільно")
elif 50 <= points <= 69:
    print("Оцінка: задовільно")
elif 70 <= points <= 89:
    print("Оцінка: добре")
elif 90 <= points <= 100:
    print("Оцінка: відмінно")
else:
    print("Некоректне значення балів")
