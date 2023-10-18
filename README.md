# Alfie
Python Project CIS 105
# This is just the rough code i am working towords refinemint
print('Hello, my name is Alfie.')
Name = input('What is your name? ')
print(Name, ', your name is cool!')
# put all the code together for the first time on 10/17/2023
print(Name, ', how old are you?')
Age = int(input())
# Age Loop starts here
if Age <= 10:
    print(Age, ", wow that means you're in elementary school.")
else:
    if Age <= 13:
        print(Age, ", wow that means you're in middle school.")
    else:
        if Age <= 17:
            print(Age, ", wow that means you're in high school.")
        if Age == 17:
            print('wow, you even have your drivers license!')
        else:
            if Age <= 21:
                print(Age, ", wow you're old enough to go to college and you're an adult.")
            if Age == 21:
                print("you are the legal drinking age in the U.S.")
            else:
                if Age >= 22:
                    print("Yay, no more school!")

print(Name, ", what hobby do you like?")
Hobby = input()
# Hobby loop starts here
if Hobby == "Reading":
    print("Reading is amazing, nothing is better then a good book.")
    print("""Fun Fact:
Did you know that the longest sentence ever printed consists of 832 words?""")
else:
    if Hobby == "Golfing":
        print("Golfing is a very exciting sport, I have been known to play a round or two myself.")
        print("""Fun Fact:
Did you know that Golf was invented in 1457, Scotland?""")
    else:
        if Hobby == "Coding":
            print("Coding is amazing, I'm made entirely of code.")
            print("""Fun Fact:
Did you know that there are over 700 coding languages?""")
        else:
            if Hobby == "Dancing":
                print("Dancing is very fun, my favorite style is Disco!")
                print("""Fun Fact:
Did you know that dance is a universal language?""")
            else:
                if Hobby == "Hockey":
                    print("Hockey is awesome, that's my favorite sport to watch and my favorite team is the Flyers!")
                    print("""Fun Fact:
Did you know that the first indoor hockey game happened in 1875?""")

print("Did you enjoy that Fun Fact, ", Name, "?")
Fact = input("Yes or No: ")
# fact loop starts here
if Fact == "Yes":
    print("Well that is just lovely,thank you.")
else:
    if Fact == "No":
        print("Well I'm very sorry to hear that, I will endeavor to do better it the future.")

Summary = input("Would you like a summary of our encounter? ")
# Summary loop starts here
print("Okie dokie!")
if Summary == "Yes":
    print("Your name is", Name)
    print("My name is Alfie, but it's Alfred to my mother")
    print("You are", Age, "years old")
    print("I will not tell you my age cause a gentlemen never tells")
    print("Your hobby is", Hobby)
    print("My hobbies include but are not limited to, Reading, Golfing, Coding, Dancing, and Watching Hockey")
    print("I told you a Fun Fact about your hobby")
    print("And now we are here")
else:
    if Summary == "No":
        print("Well, ", Name, " it was a delight getting to know you.")
print("Until next time my dear friend, TTFN, Ta Ta For Now.")
