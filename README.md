# Basic-Calculator

def Add(a,b):
    answer_is= a+b
    print(str(a) + " + " + str(b) + " = " + str(answer_is) + "\n")

def Sub(a,b):
    answer_is=a-b
    print(str(a) + " - " + str(b) + " = " + str(answer_is) + "\n")

def Mul(a,b):
    answer_is=a*b
    print(str(a) + " * " + str(b) + " = " + str(answer_is) + "\n")

def Div(a, b):
    answer_is=a/b
    print(str(a) + " / " + str(b) + " = "+ str(answer_is) + "\n")

while True:
        print('A.Addition')
        print('B. Subtration')
        print('C.Multiplication')
        print('D.Division')
        print('E.Exit')


        choice=input('input your choice : ')

        if choice == 'a' or choice == 'A':
            print('Addition')
            a=int(input('Input Frist Number : '))
            b=int(input('Input Secoud Number : '))
            Add(a,b)

        elif choice == 'b' or choice == 'B':
            print('Subtraction')
            a=int(input('Input Frist Number : '))
            b=int(input('Input Secound Number : '))
            Sub(a,b)

        elif choice == 'c' or choice == 'C':
            print('Multiplication')
            a=int(input('Input Frist Number : '))
            b=int(input('Input Secound Number : '))
            Mul(a,b)

        elif choice == 'd' or choice =='D':
            print('Division')
            a=int(input('Input Frist Number : '))
            b=int(input('Input Secound Number : '))
            Div(a,b)

        elif choice == 'e' or choice == 'E':
            print("Program Ended")
            quit()


