
# Question 1
#### Chef Zeynep's Gourmet Plate
Chef Zeynep works at a famous restaurant known for its minimalist and aesthetic presentations. For her new menu, she is preparing rectangularly cut appetizers (meze), each of which must have different dimensions.

Chef Zeynep adheres to strict rules:

The side lengths of the appetizers must be integers (in cm).

To maintain aesthetic balance on the presentation plate, the longer side must always be equal to or greater than the shorter side (including square cuts).

The total appetizer area in a single portion must not exceed a maximum value, N, specified in a special order.

Chef Zeynep needs to figure out how many different appetizer cut combinations (with different dimensions and ratios) she can offer to her guests while adhering to the maximum area limit N.

---

## Input Format:
A single line containing one integer N (the maximum total appetizer area in cm²).

---

## Output Format:
Print the number of possible different appetizer cut combinations.

---

## Constraints: 
1≤N≤10^6

---
## Sample Input 
```bash
5
```

## Sample Output 
```bash
6
```

### Explanation 1

There are ssix possible shapes of the appetizers we can create;

1 × 1
1 × 2
1 × 3
1 × 4
1 × 5
2 × 2

---

# Question 2
Omer is really upset because he can't figure out the password to a case containing a bunch of delicious candies. He's about to cry when Aybala walks in and sees how upset he is. Aybala wants to help Omer, so she asks him what the problem is.

Omer explains that he needs to find the number of contiguous subarrays in a given array of integers such that every element in the subarray is a factor of the next element. He's been struggling with this for hours and can't seem to find a solution.

Aybala decides to help Omer by writing a function that takes in an array of integers and returns the number of valid contiguous subarrays. Can you help Aybala save Omer's day by writing this function?

A contiguous subarray of an array A of N elements is a subarray A[i], A[i+1], …, A[j] such that 1 ≤ i ≤ j ≤ N.The subarray A[i], A[i+1], …, A[j] is considered valid if every element A[k] in the subarray satisfies the condition: A[k] | A[k+1] for all i ≤ k < j.

---

## Input Format
First line, N, the number of integers in the array.

Second line, N integers A1, A2, …, An, separated by space.

---

### Output Format
Single number: The number of contiguous subarrays such that every element in the subarray is a factor of the next element.

---

## Constraints
1 ≤ N ≤ 10^6
1 ≤ A[i] ≤ 10^9

---
## Sample Input 1 
```bash
5
2 4 7 14 56
```
## Sampler Output 1
```bash
9
```
---

## Sample Input 2
```bash
3
6 3 5
```
## Sampler Output 2
```bash
3
```

---

# Question 3
Ebrar's teacher gave her two strings containing only lowercase letters (their sizes are N and M) and a rubber. Then told her to reach two same strings with only deleting some of the letters in given strings with her rubber. She can't change the positions of the letters or add new letters. Please help Ebrar to find the longest possible string size which she can reach at the end.

Note: If you use Python for that question. Don't forget to use strip function while reading input. s=input().strip() .

---

## Input Format
Two strings given in two lines.

---

## Output Format
A single integer, size of the longest common subsequence of the strings.

---

## Constraints
1 ≤ N ≤ 1000
1 ≤ M ≤ 1000

---
## Sample Input 1 
```bash
abcdef
bdcnf
```

## Sample Output 1 
```bash
3
```

### Explanation 1

Ebrar can reach string bcf, if she deletes other characters. There is no solution longer that string.
