# Final population calculator

## There were initially X million people in a town, out of which Y million people left the town 
## and Z million people immigrated to this town. Determine the final population of town in 
## millions. Remember that your code must work for any value of X, Y and Z and not just for 
## the sample input given below. The following conditions are true for the question given 
## above.

### Code
x=int(input("Enter number of people in town: "))
y=int(input("Enter number of people who left: "))
z=int(input("Enter number of people who immigrated to town: "))
if(x>0 and y<=x and z>0):
    current_population=x-y+z
    print("Current population: ",current_population)
else:
    print("Please enter valid values")
