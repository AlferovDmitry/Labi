#7 Запросите у пользователя температуру в градусах Цельсия и сохраните ее в переменной. Выведите это значение, а затем преобразуйте его в градусы Фаренгейта и также выведите.

#Решение
celsius = float(input("Enter the temperature in Celsius: "))
print("Temperature in Celsius:", celsius)
fahrenheit = celsius * 9/5 + 32
print("Temperature in Fahrenheit:", fahrenheit)

#Итог
#Temperature in Celsius: 20.0
#Temperature in Fahrenheit: 68.0
