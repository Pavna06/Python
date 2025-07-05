# A B C Fruit selector

Write a Python program in which the user enters either 'A', 'B', or 'C'. If 'A' is entered, the  
program should display the word 'Apple'; if 'B' is entered, it displays 'Banana'; and if 'C' is  
entered, it displays 'Coconut'.

### Code
x=input("Enter 'A', 'B' or 'C': ")
x=x.upper()
dict={'A':"Apple",'B':"Banana",'C':"Coconut"}
print(dict[x])
