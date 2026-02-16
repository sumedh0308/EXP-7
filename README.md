EXP-7

EXP 7 : To study while loop in python

Aim:

To study and implement the while loop in Python programming for performing repetitive tasks such as number printing, factorial calculation, Fibonacci series generation, palindrome checking, digit counting, searching elements in a list, and other logical operations.

Theory:

A while loop in Python is an entry-controlled looping statement that repeatedly executes a block of code as long as the given condition evaluates to True. It is generally used when the number of iterations is not fixed in advance and depends on a condition


---

## **ALGORITHM 1: Print numbers from 1 to 5**

1. Start
2. Initialize `i = 1`
3. Check if `i <= 5`
4. If True, print `i`
5. Increment `i` by 1
6. Repeat steps 3–5 until condition becomes False
7. Stop

---

## **ALGORITHM 2: Print numbers from 1 to N**

1. Start
2. Read value of `N`
3. Initialize `i = 1`
4. Check if `i <= N`
5. If True, print `i`
6. Increment `i` by 1
7. Repeat steps 4–6 until condition becomes False
8. Stop

---

## **ALGORITHM 3: Find Factorial of a Number**

1. Start
2. Read number `n`
3. Initialize `fact = 1`
4. While `n > 0`
5. Multiply `fact = fact × n`
6. Decrement `n` by 1
7. Repeat steps 4–6
8. Display factorial
9. Stop

---

## **ALGORITHM 4: Fibonacci Series (N Terms)**

1. Start
2. Read number of terms `n`
3. Initialize `a = 0`, `b = 1`, `i = 1`
4. While `i <= n`
5. Print `a`
6. Compute `c = a + b`
7. Assign `a = b`, `b = c`
8. Increment `i` by 1
9. Repeat steps 4–8
10. Stop

---

## **ALGORITHM 5: Fibonacci Series up to Limit**

1. Start
2. Read `limit`
3. Initialize `a = 0`, `b = 1`
4. While `a <= limit`
5. Print `a`
6. Update `a = b` and `b = a + b`
7. Repeat steps 4–6
8. Stop

---

## **ALGORITHM 6: Reverse a Number**

1. Start
2. Read number `num`
3. Initialize `rev = 0`
4. While `num > 0`
5. Extract digit = `num % 10`
6. Update `rev = rev × 10 + digit`
7. Remove last digit `num = num // 10`
8. Repeat steps 4–7
9. Display reversed number
10. Stop

---

## **ALGORITHM 7: Check Palindrome (Number)**

1. Start
2. Read number `num`
3. Store copy in `temp`
4. Initialize `rev = 0`
5. While `num > 0`
6. Update `rev = rev × 10 + (num % 10)`
7. Remove last digit `num = num // 10`
8. Repeat steps 5–7
9. If `temp == rev`, print “Palindrome”
10. Else print “Not Palindrome”
11. Stop

---

## **ALGORITHM 8: Check Palindrome (String using slicing)**

1. Start
2. Read string `st`
3. Reverse string using slicing
4. Compare original and reversed string
5. If equal, print “Palindrome”
6. Else print “Not Palindrome”
7. Stop

---

## **ALGORITHM 9: Check Palindrome (Using While Loop)**

1. Start
2. Initialize string `s`
3. Set `i = 0`, `j = length of string - 1`
4. Set flag `is_palindrome = True`
5. While `i < j`
6. Compare `s[i]` and `s[j]`
7. If not equal, set flag to False and break
8. Increment `i`, decrement `j`
9. After loop, check flag
10. If True, print “Yes”
11. Else print “No”
12. Stop

---

## **ALGORITHM 10: Count Digits in a Number**

1. Start
2. Read number `num`
3. Initialize `count = 0`
4. While `num > 0`
5. Increment `count`
6. Divide `num = num // 10`
7. Repeat steps 4–6
8. Print total digit count
9. Stop

---

## **ALGORITHM 11: Search an Element in a List**

1. Start
2. Initialize list `nums`
3. Read element `key`
4. Initialize index `i = 0`
5. While `i < length of list`
6. If `nums[i] == key`, print index and break
7. Else increment `i`
8. If loop completes without break, print “Element not found”
9. Stop

---

## **ALGORITHM 12: Print Only Odd Numbers (1 to 10)**

1. Start
2. Initialize `i = 0`
3. While `i < 10`
4. Increment `i`
5. If `i` is even, continue to next iteration
6. Else print `i`
7. Repeat steps 3–6
8. Stop

---

## **Conclusion:**

Thus, the experiment was successfully completed and the working of the **while loop** in Python was understood. Various programs were implemented to perform repetitive tasks based on conditions. Hence, the objective of studying and applying the while loop was achieved.

