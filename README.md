# Synergy
homework_2
Создайте программу-калькулятор, которая будет выполнять простые математические операции: сложение, вычитание. Программа должна предложить пользователю выбрать операцию, затем ввести два числа и вывести результат операции.

#Шаги:

#Поприветствуйте пользователя и покажите список доступных операций: "+", "-"
Попросите пользователя выбрать операцию, введя соответствующий символ.
Затем попросите пользователя ввести первое число.
Затем попросите пользователя ввести второе число.
Выполните выбранную операцию над введенными числами.
Выведите результат пользователю.


print("Привет! Это простой калькулятор")

print("Доступные операции")

print("+ - сложение")

print("- - вычитание")

operation = input("Выберите операцию(введите соответствующий символ )")

num1 = float(input("Введите первое число:"))

num2 = float(input("Введите второе число:"))

if operation == "+":
    result = num1 + num2
elif operation == "-":
    result = num1 - num2
else:
    print("Недопустимая операция")
    exit()

print("Результат: ",result)



