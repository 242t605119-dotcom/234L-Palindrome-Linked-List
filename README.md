# LeetCode 234 - Palindrome Linked List

## Problem

Given the head of a singly linked list, return `true` if the linked list is a palindrome.

A palindrome reads the same forward and backward.

## Example

### Input

```text
head = [1,2,2,1]
```

### Output

```text
true
```

### Example 2

```text
head = [1,2]
```

Output:

```text
false
```

## Approach

Traverse the linked list and store all node values in a Python list.

A linked list is a palindrome if the list of values is equal to its reversed version.

For example:

```text
[1, 2, 2, 1]
```

is the same as:

```text
[1, 2, 2, 1]
```

when reversed.

## Algorithm

1. Create an empty list.
2. Traverse the linked list.
3. Store each node's value in the list.
4. Compare the list with its reversed version.
5. Return `true` if they are equal.
6. Otherwise, return `false`.

## Complexity

* Time Complexity: `O(n)`
* Space Complexity: `O(n)`

Where `n` is the number of nodes in the linked list.

## Language

Python

## LeetCode

Problem: 234 - Palindrome Linked List

## Author

**T.Nandhini**
