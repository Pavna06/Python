# College Year Status Checker

Write a Python program in which a student enters the number of college credits earned. If     
the number of credits is greater than 90, 'Senior Status' is displayed; if greater than 60,  
'Junior  Status' is displayed; if greater than 30, 'Sophomore Status' is displayed; else,      
'Freshman Status'  is displayed. 

### Code
credits = int(input("Enter number of college credits earned: "))
if credits > 90:
    print("Senior Status")
elif credits > 60:
    print("Junior Status")
elif credits > 30:
    print("Sophomore Status")
else:
    print("Freshman Status")
