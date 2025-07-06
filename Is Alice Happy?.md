# Is Alice Happy

**Problem Statement**
<br>
Alice has scored X marks in her test and Bob has scored Y marks in the same test.
Alice is happy if she scored at least twice the marks of Bob’s score. Determine whether she is happy or not.
<br>
**Input Format**
The first and only line of input contains two space-separated integers X, Y — the marks of Alice and Bob respectively.
<br>
**Output Format**
<br>
For each testcase, print Yes if Alice is happy and No if she is not, according to the problem statement.
The judge is case insensitive so you may output the answer in any case. In particular YES, yes, yEs are all considered equivalent to Yes.
<br>
**Constraints**
<br>
1 ≤ X, Y ≤ 100
<br>
Sample 1:
| Input | Output |
| ----- | ------ |
| 2 1   | Yes    |

**Explanation:**
Alice has scored X = 2 marks whereas Bob has scored Y = 1 mark. As Alice has scored twice as much as Bob (i.e. X ≥ 2 * Y), the answer is Yes.

### Code
x, y = map(int, input().split())
if x >= 2 * y:
    print("Yes")
else:
    print("No")
