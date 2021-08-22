#guessthe num from harry python series
print("Welcome to Guess the Number , you have only Four chance to guess !")
comp_num=20
user_num=int(input(print("Enter your number")))
if user_num == comp_num:
    print("wins")

for i in range(3):

    if user_num != comp_num :
        print("Your guess is not what expected ! Guess again")
        user_num = int(input(print("Enter your number")))
        if user_num == comp_num:
            print("wins")
            break




