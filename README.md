# calculator
A simple calculator application that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. Designed with clean logic for user-friendly interaction, ensuring accurate results. Ideal for practicing fundamental programming concepts and operators.
print("CALCULATOR")
while True:
    num1=float(input('enter number1:'))
    num2=float(input('enter number2:'))
    operator=input('enter operator:')
    if operator=='+':
        print(f'addition {num1+num2}')
    elif operator=='-':
        print(f'substraction {num1-num2}')
    elif operator=='*':
        print(f'multiplication {num1*num2}')
    elif operator=='/':
        if num2!=0:
            print(f'division {num1/num2}')
        else:
            print('not allowed')
    else:
        print('invalid operation')
    break

