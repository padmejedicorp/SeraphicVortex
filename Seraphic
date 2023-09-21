import random

def generate_random_number():
    return random.randint(1, 100)

def play_seraphic_vortex_game():
    print("Welcome to the SeraphicVortex Game!")
    print("I'm thinking of a number between 1 and 100.")
    secret_number = random.randint(1, 100)
    attempts = 0

    while True:
        try:
            guess = int(input("Take a guess: "))
            attempts += 1

            if guess < secret_number:
                print("Too low! Try again.")
            elif guess > secret_number:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You've guessed the secret number ({secret_number}) in {attempts} attempts.")
                break
        except ValueError:
            print("Invalid input. Please enter a valid number.")

if __name__ == "__main__":
    play_seraphic_vortex_game()


if __name__ == "__main__":
    random_number = generate_random_number()
    print(f"Random Number: {random_number}")
