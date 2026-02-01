def collatz(number):
    if number % 2 == 0:
        return number // 2
    if number % 2 == 1:
        return number * 3 + 1

while True:
    try:
        user_input = int(input('Enter a number: '))
        print(user_input, end=' ')
        while user_input != 1:
            user_input = collatz(user_input)
            print(user_input, end=' ')
        break
    except ValueError:
        print('Please enter interger number')
    continue
