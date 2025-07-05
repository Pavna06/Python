# DTP Work Billing Program

Write a program to calculate the bill of a DTP work as follows. Use if-else statement to 
determine if the user wants typing or copying done.
<br>
a. The rate of typing Rs. 3/Page 
<br>
b. Printing of first copy Rs.5/page and later every copy Rs.3/Page. Given the number of pages,
print the total cost.

### Code
work = input("Enter type of work (typing/copying): ").lower()
pages = int(input("Enter number of pages: "))
if work == "typing":
    cost = pages * 3
    print("Total cost for typing: Rs.", cost)
elif work == "copying":
    copies = int(input("Enter number of copies: "))
    if copies >= 1:
        cost = pages * 5  # First copy
        cost += pages * 3 * (copies - 1)  # Remaining copies
        print("Total cost for copying:", "Rs.", cost)
    else:
        print("Invalid number of copies.")
else:
    print("Invalid work type entered.")
