# rolling-dice
import random
while True:
  roll = input("roling the dice y/n: " ).lower()
  if roll == "y":
    dice1 == random.randint(1, 6)
    dice2 == random.randint(1, 6)
    print({dice1}, {dice2})
  if roll == "n": 
    print("bye")
    break
  else:
    print("invalid input")
