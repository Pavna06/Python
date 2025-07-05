# Maximum Fruit Chaarts Chef Can Make

Chef has closed his restaurant and decided to run a fruit stand instead. His signature dish 
is a fruit chaat consisting of 2 bananas and 1 apple. He currently has X bananas 
and Y apples. How many chaats can he make with the fruits he currently has? 

### Code
x=int(input("Enter number of bananas: "))
y=int(input("Enter number of apples: "))
max_chaats = min(x // 2, y)
print("Maximum number of chaats Chef can make:", max_chaats)
