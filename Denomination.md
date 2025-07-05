# Minimum Coins to Make X Rupees

Chef has infinite coins in denominations of rupees 5 and rupees 10. Find 
the minimum number of coins Chef needs, to pay exactly X rupees. The following 
conditions are true for the question given above. 
X is a number that is divisible by 5. 

### Code
X = int(input("Enter the amount (divisible by 5): "))
if X % 5 != 0:
    print("Invalid amount. Must be divisible by 5.")
else:
    tens = X // 10
    remainder = X % 10
    fives = remainder // 5
    total_coins = tens + fives
    print("Minimum number of coins needed:", total_coins)
