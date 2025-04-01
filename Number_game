
import random

start_num = 1
end_num = 100
sys_num = random.randint(start_num, end_num)  # Generate a random number
guess = 0
isrunning = True

while isrunning:
    user_num = input("Enter a number between 1 to 100: ")
    
    if user_num.isdigit():  # Check if input is a number
        user_num = int(user_num)
        guess += 1
        
        if user_num < start_num or user_num > end_num:
            print("Please enter a valid number within the range.")
            continue  # Skip the rest of the loop and ask for input again

        if user_num < sys_num:
            print("Too low, try again!")
        elif user_num > sys_num:
            print("Too high, try again!")
        else:
            print("Correct! 🎉")
            print(f"You guessed the number in {guess} attempts.")
            isrunning = False  # Stop the game
    else:
        print("Invalid input. Please enter a number between 1 and 100.")
