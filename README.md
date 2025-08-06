# fake_headline
for breaking news app 
 #  1- import the random module
import random

# 2 - crreate subjects
subjects = [
    "roshan saw"
    "sumit saw"
    "ritik saw"
    "vishal saw"
    "verr saw"
]
actions = [
    "launches"
    "cancels"
    "dance"
    "backchodi karna "
    "eats"
]

places_or_things = [
    " at  red fort"
    "at road "
    "at village "
    "at ghar"
    "at home"
]
 #  3 start  the readline  generation loop
while True:
    subject = random.choice(subjects)
    action = random.choice(actions)
    places_or_things = random.choice(places_or_things)

    headline = f" BREAKING NEWS: {subject} {action} {places_or_things} "
    print("IN" + headline)

    user_input = input("/n do you  want another headline? (yes/no)"). strip()
    if user_input == "no":
        break

# print goodbye message
print("/nThanks  for using the fake News headline Generator. Have a fun day ")    
 

 
