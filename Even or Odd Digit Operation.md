# Sum of digits if Even, Product of digits if Odd

Determine whether a given three-digit number (entered by the user) is even or odd. If the number is even,
find and display the sum of digits of that number and if the number is odd, then find and display 
the product of the digits of the number.

### Code
x=int(input("Enter a 3 digit number: "))
if(x>99 and x<1000):
    d1=x//100
    d2=(x//10)%10
    d3=x%10
if(x&1):
    prod=d1*d2*d3
    print("The number is Odd")
    print("The product of digits is: ",prod)
else:
    sum=d1+d2+d3
    print("The number is Even")
    print("The sum of digits is: ",sum)
