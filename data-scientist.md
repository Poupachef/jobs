### Data scientist

The data scientist position involves, but is not limited to, upgrading our precious pricing algorithm - written in Python 3.7 - and our price mining and import routines, such as our serverless function that loads new data into the database. The job also includes creating and monitoring web crawlers that collect the information of food ingredient’s public prices, which will then be used to feed Poupachef’s internal pricing algorithm.

**Requirements:** Python

## Coding tests

Choose 2 of the following 3 problems and send the answers by email to [devs](mailto:devs@poupachef.com.br). The tests can be  solved in any programming language.

### 1

UTF-8 is a variable leght character encoding that maps each symbol to one, two, three, or four bytes. The rules for mapping characters are as follows:

- For a single-byte character, the first bit must be zero.
- For an n-byte character, the first byte starts with n ones and a zero. The other n - 1 bytes all start with 10.

Visually, this can be represented as follows.

```
 Bytes   |           Byte format
-----------------------------------------------
   1     | 0xxxxxxx
   2     | 110xxxxx 10xxxxxx
   3     | 1110xxxx 10xxxxxx 10xxxxxx
   4     | 11110xxx 10xxxxxx 10xxxxxx 10xxxxxx
```

Write a program that takes in an array of integers representing byte values, and returns whether it is a valid UTF-8 encoding.

---

### 2

Implement the function fib(n), which returns the nth number in the Fibonacci sequence, using only O(1) space.

---

### 3

Spreadsheets often use this alphabetical encoding for its columns: "A", "B", "C", ..., "AA", "AB", ..., "ZZ", "AAA", "AAB", ....

Given a column number, return its alphabetical column id. For example, given 1, return "A". Given 27, return "AA".

### Good luck

