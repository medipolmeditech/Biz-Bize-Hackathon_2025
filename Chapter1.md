
# Question 1
#### The Temple of the Dual OracleThe Temple of the Dual OracleIn ancient times, on the lost continent of Zylos, stood the Temple of the Dual Oracle, a structure rumored to whisper the secrets of the future. The temple's greatest mystery was the mechanism that unlocked these prophecies, known as the Wheel of Fate.Arcanist Lyra is the temple's last guardian, and she must re-activate the Wheel. The Wheel is composed of $N$ circular segments, and each segment can only be set to one of two fundamental energy states: Ascendant Light (1) or Dormant Shadow (0).To fully reveal the prophecies, Lyra must attempt every single possible combination of Ascendant Light and Dormant Shadow across all $N$ segments of the Wheel. The power of the temple depends on this complete variety.The Task:Help Lyra by providing her with a list of all unique binary strings of length $N$, composed of the digits $0$ and $1$. Otherwise, the ancient wisdom of Zylos will be lost forever.
---

## Input Format 
The only line contains an integer N, number of flying saucers.

---

## Output Format
Print N binary strings in 2^N lines, in alphanumerical order.

---

## Constraints
1 ≤ N ≤ 20

---

## Sample Input
```bash
3
```

---

## Sample Output
```bash
000
001
010
011
100
101
110
111
```

# Question 2
When we solve problems with code, two big things matter: time and space. Time complexity is all about how long the code takes to run as the input size grows. Think of it as asking, “If we had more data to handle, how much slower would the program get?”

For example:

If you’re just printing the first item in a list, it doesn’t matter how long the list is. This is O(1) or constant time.

But if you have to look at every item in a list to find something, the time grows with the size of the list—this is O(n), or linear time.

And if you’re comparing every pair of items in a list (like checking if two people have matching costumes at a party), the time grows much faster, like O(n2), or quadratic time.

With this approach, we can estimate how long a program will take to run. On average, a program can perform approximately 10^8 basic operations in one second (of course it depends on the programming language). For example, if the input size of a problem is 10^6 and you devise a solution with quadratic time complexity, it will likely be too slow to execute successfully. However, if you manage to create a linear time solution, it is far more likely to perform efficiently within the given constraints.

We also think about space complexity, which is how much memory the program uses while running. Balancing both time and space is what makes for efficient solutions.

---

Arda has got in his house N number of candies for the M number of children visiting his house on Halloween. The children hang around as a group. It means whenever Arda's bell rings, M number of children appears in front of his door. Arda himself doesn't like candies. So he wants to give all candies in his house to the children. Arda, who wants every child who comes to visit him to have an equal number of candies, will not give candy to any child if it is not possible to distribute the candies fairly.

---

## Input Format
The first line contains M, the number of children.

The second line contains M space-separated integers Ai, which represents the number of candies i-th child had before they came to visit Arda.

The third line contains integer N — the total number of candies Arda has.

---

## Output Format
Print 1 if it's possible for Arda to hand out all his candies to the children so that every child has an equal amount of candy after visiting Arda. If it's not possible print 0.

---

## Constraints
1 ≤ M ≤ 10

1 ≤ N ≤ 10^5

1 ≤ Ai ≤ 100

---

## Sample Input 1 
```bash
3
5 3 2
8
```

## Sample Output 1
```bash
1
```
### Explanation 1

#### When the first child gets 1, the second child 3 and the third child 4 candies, the number of candies the children have becomes equal and Arda gets rid of all of his candies.
---

## Sample Input 2 
```bash
3
10 20 15
14
```

## Sample Output 2
```bash
0
```

---

# Question 3
A Tutor named BUders is a very famous mathematician among the engineering students.  He gives his students one number per minute and he expects them to say whether these numbers are prime or not. A computer can calculate whether any number is prime or not. However, this calculation process may take seconds or years depending on the size of the number. BUders guarantees that the size of the numbers will not exceed 10^8. A very optimized algorithm is required to check if the given number per minute is prime. There are many test cases. Write this algorithm and decide whether the given numbers are prime or not.

---

## Input Format 
In the first line there will be T, N.

---

## Output Format 
Print the “Yes” or “No” whether the given number is prime or not.

---

## Constraints
1 ≤ T ≤ 10^3
 
1 ≤ N ≤ 10^8

---

## Sample Input 1
```bash
1
6
```
## Sample Output 1
```bash
No
```

---

## Sample Input 2
```bash
8
5 9 6 7 9 6 6 8
```
## Sample Output 2
```bash
Yes
No
No
Yes
No
No
No
No
```
