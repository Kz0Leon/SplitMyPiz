print("Welcome to Split my Pizz")
print("How many slices of pizza would you like to have?")
pizzaSlices = int(input())
print("How many people are you sharing the pizza?")
people = int(input())

Slices = pizzaSlices // people

RemainingSlices = pizzaSlices % people

print (f"There are going to be {Slices} Pineapple Pizza slices per person")
print (f"There are {RemainingSlices} remaining Pieapple Pizza slices")
