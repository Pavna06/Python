# Internet Browsing Bill Calculator

Write a program to calculate the bill for internet browsing. The conditions are given below.
<br>
a. 1 hour - 20 Rs.
<br>
b. 1/2 hour - 10 Rs.(Time less than half an hour should be considered as half hour. Time 
   between half hour to one hour should be considered as an hour).
<br>
c. If hours is greater than 4 to unlimited hours in a day - 90 Rs. The input should be hours and minutes. 
   The user should enter the time as hours and minutes , spent on browsing in one day.

### Code
hours = int(input("Enter hours spent: "))
minutes = int(input("Enter minutes spent: "))
total_minutes = hours * 60 + minutes
if total_minutes > 240:
    cost = 90
else:
    if total_minutes <= 30:
        cost = 10
    elif total_minutes <= 60:
        cost = 20
    else:
        full_hours = total_minutes // 60
        remainder = total_minutes % 60
        if remainder <= 30 and remainder > 0:
            cost = full_hours * 20 + 10
        elif remainder > 30:
            cost = (full_hours + 1) * 20
        else:
            cost = full_hours * 20
print("Total cost for browsing: Rs.", cost)
