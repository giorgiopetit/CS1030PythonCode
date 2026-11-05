import random

# List of valid choices
choices = ["rock", "paper", "scissors"]

print("Welcome to Rock, Paper, Scissors!")

while True:
  # Get user input and convert to lowercase
  player_choice = (
      input("Enter your choice (rock, paper, scissors) or 'q' to quit: ")
      
  )

  

  if player_choice not in choices:
    print("Invalid choice. Please try again.\n")
    continue

  # Computer randomly picks from the list
  computer_choice = random.choice(choices)
  print(f"Computer chose: {computer_choice}")

  # Determine the winner
  if player_choice == computer_choice:
    print("It's a tie!\n")
  elif (
      (player_choice == "rock" and computer_choice == "scissors")
      or (player_choice == "paper" and computer_choice == "rock")
      or (player_choice == "scissors" and computer_choice == "paper")
  ):
    print("You win this round!\n")
  else:
    print("Computer wins this round!\n")



  