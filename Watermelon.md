# Watermelon (Codeforces 4A)

Problem Statement:
<br>
Given the weight w of a watermelon, determine whether it can be divided into two parts, such that:
<br>
(a) Each part has a positive even number of kilos.
<br>
(b) The parts do not need to be equal.
<br>
(c)If it can be divided in this way, print "YES", otherwise print "NO".
<br>
Input:
<br>
An integer w such that:
1 ≤ w ≤ 100 — the weight of the watermelon.
<br>
Output:
<br>
Print:
<br>
"YES" — if w can be split into two even, positive parts.
<br>
"NO" — otherwise.

### Code
w = int(input("Enter weight of watermelon: "))
if w > 2 and w % 2 == 0:
    print("YES")
else:
    print("NO")
