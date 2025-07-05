# Random Number > 10 Checker

Write a Python program to generate a random number within 1 to 50. If the generated  number        
is greater than 10, then display “The number generated is greater than 10” else  display “The      
number generated is not greater than 10”.

### Code
import random
num = random.randint(1, 50)
print("Random number generated:", num)
if num > 10:
    print("The number generated is greater than 10")
else:
    print("The number generated is not greater than 10")
