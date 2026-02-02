# LeetCode Solution: Remove Duplicate Letters

## Problem Description
Given a string `s`, remove duplicate letters so that every letter appears once and only once. Ensure that the result is the **smallest in lexicographical order** among all possible results.

- **Link:** [316. Remove Duplicate Letters](
)
- **Difficulty:** Medium

## Approach
This solution follows a basic approach to:
1. Iterate through the string to identify unique characters.
2. Store unique characters in a temporary string.
3. Convert the result to a character array and sort it to ensure lexicographical order.

### Complexity Analysis
- **Time Complexity:** O(N * K + K log K), where N is the length of the string and K is the number of unique characters.
- **Space Complexity:** O(K) to store the unique characters.

## How to Run
1. Clone this repository.
2. Compile the Java file: `javac RemoveDuplicateLetters.java`
3. Run with your own test cases or via the [
