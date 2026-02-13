

---

# **AIM:**

To study and implement various programs using the `while` loop in Python for repetition and iterative problem-solving.

---

# THEORY:

* **while loop:** Repeats a block of code as long as the given condition remains true.
* **Increment/Decrement:** Used inside loops to update the loop variable and avoid infinite looping.
* **break statement:** Terminates the loop immediately when a condition is met.
* **continue statement:** Skips the current iteration and moves to the next iteration.
* **Slicing `[::-1]`:** Used to reverse a string.
* **Arithmetic operators:** Used for factorial, reverse number, and digit counting logic.
* **Multiple assignment (`a,b = b,a+b`):** Used in Fibonacci series to swap values efficiently.

---

# ALGORITHMS:

---

## 1️ Print i as long as i < 6

1. Start the program.
2. Initialize i = 1.
3. Use while loop with condition i < 6.
4. Print i.
5. Increment i by 1.
6. Stop when condition becomes false.

---

## 2️ Print numbers from 1 to n

1. Start the program.
2. Take n as integer input.
3. Initialize i = 1.
4. Use while loop while i ≤ n.
5. Print i and increment i.
6. Stop.

---

## 3️ Factorial using decrement

1. Start the program.
2. Take n as input.
3. Initialize fact = 1.
4. While n > 0, multiply fact = fact × n.
5. Decrement n by 1.
6. Print factorial.
7. Stop.

---

## 4️ Factorial using increment

1. Start the program.
2. Take n as input.
3. Initialize fact = 1 and i = 1.
4. While i ≤ n, multiply fact = fact × i.
5. Increment i.
6. Print factorial.
7. Stop.

---

## 5️ Fibonacci series using count

1. Start the program.
2. Take n as input.
3. Initialize a = 0, b = 1, i = 1.
4. While i ≤ n, print a.
5. Compute c = a + b.
6. Update a = b and b = c.
7. Increment i.
8. Stop.

---

## 6️ Fibonacci series up to limit

1. Start the program.
2. Take limit as input.
3. Initialize a = 0, b = 1.
4. While a ≤ limit, print a.
5. Update a, b = b, a + b.
6. Stop.

---

## 7️ Reverse of a number

1. Start the program.
2. Take number as input.
3. Initialize rev = 0.
4. While number > 0:

   * Get last digit using num % 10.
   * Update rev = rev × 10 + digit.
   * Remove last digit using num // 10.
5. Print reversed number.
6. Stop.

---

## 8️ Check palindrome number

1. Start the program.
2. Take number as input.
3. Store original number in temporary variable.
4. Reverse the number using while loop.
5. Compare reversed number with original.
6. If equal → palindrome else not palindrome.
7. Stop.

---

## 9️ Check palindrome string (fixed string)

1. Start the program.
2. Set string value.
3. Initialize i = 0, j = len(s) - 1.
4. While i < j, compare characters.
5. If mismatch → break.
6. If loop completes → palindrome.
7. Stop.

---

## 10 Check palindrome string (user input)

1. Start the program.
2. Take string input.
3. Set i = 0 and j = len(s) - 1.
4. Compare characters while i < j.
5. If mismatch → not palindrome.
6. Else → palindrome.
7. Stop.

---

## 1️1️ Palindrome using slicing

1. Start the program.
2. Take string input.
3. Reverse string using slicing `[::-1]`.
4. Compare original and reversed string.
5. Print result.
6. Stop.

---

## 1️2️ Count digits in a number

1. Start the program.
2. Take number as input.
3. Initialize count = 0.
4. While number > 0:

   * Divide number by 10.
   * Increment count.
5. Print digit count.
6. Stop.

---

## 1️3️ Exit loop when i = 3 (break)

1. Start the program.
2. Initialize i = 1.
3. While i < 6, print i.
4. If i == 3, use break to exit loop.
5. Increment i.
6. Stop.

---

## 1️4️ Search element in list

1. Start the program.
2. Define list of numbers.
3. Take element to search as input.
4. Initialize i = 0.
5. While i < length of list:

   * If element found → print index and break.
   * Increment i.
6. If loop ends without break → print not found.
7. Stop.

---

## 1️5️ Print only odd numbers (1 to 10)

1. Start the program.
2. Initialize i = 0.
3. While i < 10:

   * Increment i.
   * If i % 2 == 0 → continue.
   * Print i.
4. Stop.

---

# **CONCLUSION :**

In this experiment, various programs were implemented using the while loop. We learned how repetition works using increment and decrement operations. Control statements like break and continue were also applied. The while loop helps solve problems such as factorial, Fibonacci series, palindrome checking, and searching efficiently.

---
