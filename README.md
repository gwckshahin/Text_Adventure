# Text_Adventure

import random

character = ["Monkey D Luffy","Roronoa Zoro", "Vinsmoke Sanji","Usopp","Nami","Tony Tony Chopper","Nico Robin","Brook", "Franky"]
print(character[0])
character[0]= 1
print(character[0])

print(character[len(character)-1])

print(character)
del character[5]
print(character)

character.append("Jinbei")
print(character)

secure_random = random.SystemRandom()
print(secure_random.choice(character))

list=["Monkey D Luffy", "Trafalgar D Water Law", "Eustass Captain Kid", "Killer", "Roronoa Zoro", "Capone Bege", "Jewelry Bonny"]
secure_random = random.SystemRandom()
print(secure_random.choice(list))


emperor=["Shanks", "Whitebeard", "Blackbeard", "Big Mom","Kaido"]
secure_random = random.SystemRandom()
print(secure_random.choice(emperor))
