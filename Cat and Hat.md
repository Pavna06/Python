# Cat and Hat

You are given a string str, you need to return True if the word "cat" and "hat" appear same number of times in str, otherwise return False.

### Code

str=input("Enter string: ")
cat=str.count("cat")
hat=str.count("hat")
if(cat==hat):
    print("True")
else:
    print("False")
