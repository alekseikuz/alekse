# alekse
#this is the password for the app / game
he is so izi but this is my first job

print("*ЧТОБЫ ИГРАТЬ НУЖЕН ПАРОЛЬ*")
print(''.ljust(4, "*"))
print()
while True:
    print("Ввидите пароль:")
    b = input()
    a = (len(b))
    if 4 > a or a > 4:
        print(b.ljust(4, "*"))
        print('\nВ пароле 4-е цифры\n')
    elif str(b) == "0603":
        print('Пароль верный!')
        break
    else:
        print('Пароль неверный\nПопробуйте еще раз')
        print()
