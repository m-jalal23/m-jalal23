a = int(input("Guess a Number"))
import random
n = random.randint(1,400)
a = -1
guesses=0
while (a != n):
    guesses +=1
    a = int(input("Guess a Number:"))
    if (a>n):
        print("Lower number please")
    else:
        print("Higher number please")

print(f"You guess the correct number in {guesses} attempts")
<!---
m-jalal23/m-jalal23 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
