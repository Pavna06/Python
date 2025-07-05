# Swap 2 numbers

## Method 1: using a 3rd variable

### Code
x,y=map(int,input("Enter 2 numbers: ").split())
temp=x
x=y
y=temp
print("Swapped values: ",x,y)

## Method 2: without using a 3rd variable

### Code
x,y=map(int,input("Enter 2 numbers: ").split())
x=x+y
y=x-y
x=x-y
print("Swapped values: ",x,y)
