# Introduction to Python — Week 1 Assignment
**Due:** Next weekly class

Submit a separate `.py` file for each question (e.g., `Q1.py`, `Q2.py`, …).

---

**Q1.** Create four variables — your full name, your age, your GPA, and whether you are a student (True/False). Print each variable on a separate line along with its data type using `type()`.

**Sample Output:**
```
Alice Johnson   <class 'str'>
20              <class 'int'>
8.5             <class 'float'>
True            <class 'bool'>
```

---

**Q2.** Ask the user to enter two integers. Print the result of all seven arithmetic operations on them: `+`, `-`, `*`, `/`, `//`, `%`, `**`. Label each result clearly.

**Sample Input:**
```
Enter a: 10
Enter b: 3
```
**Sample Output:**
```
10 + 3  = 13
10 - 3  = 7
10 * 3  = 30
10 / 3  = 3.3333333333333335
10 // 3 = 3
10 % 3  = 1
10 ** 3 = 1000
```

---

**Q3.** Ask the user to enter two numbers. Print the result of all six comparison operations on them: `==`, `!=`, `>`, `<`, `>=`, `<=`. Label each result clearly.

**Sample Input:**
```
Enter first number : 7
Enter second number: 10
```
**Sample Output:**
```
7 == 10  →  False
7 != 10  →  True
7 >  10  →  False
7 <  10  →  True
7 >= 10  →  False
7 <= 10  →  True
```

---

**Q4.** Ask the user for an integer. Print whether the number is **Even** or **Odd**.
*(Hint: use the `%` operator)*

**Sample Input 1:**
```
Enter a number: 14
```
**Sample Output 1:**
```
14 is Even
```
**Sample Input 2:**
```
Enter a number: 7
```
**Sample Output 2:**
```
7 is Odd
```

---

**Q5.** Ask the user to enter a temperature in Celsius. Convert it to Fahrenheit using the formula **F = (C × 9/5) + 32** and print the result rounded to 2 decimal places.

**Sample Input 1:**
```
Enter temperature in Celsius: 100
```
**Sample Output 1:**
```
100.0 °C = 212.0 °F
```
**Sample Input 2:**
```
Enter temperature in Celsius: 37.5
```
**Sample Output 2:**
```
37.5 °C = 99.5 °F
```

---

**Q6.** Ask the user for their name and their favourite programming language. Print a single sentence using both values.

**Sample Input:**
```
Enter your name: Alice
Enter your favourite language: Python
```
**Sample Output:**
```
Hello Alice! Great choice learning Python.
```

---

**Q7.** Ask the user to enter 5 integers, one at a time. Store them in a list. Then print the full list, the first element, the last element, and the total count of elements.

**Sample Input:**
```
Enter number 1: 10
Enter number 2: 20
Enter number 3: 30
Enter number 4: 40
Enter number 5: 50
```
**Sample Output:**
```
List  : [10, 20, 30, 40, 50]
First : 10
Last  : 50
Count : 5
```

---

**Q8. (Bonus)** Ask the user for their birth year. Calculate their age as of 2026 and print whether their age is odd or even.

**Sample Input:**
```
Enter your birth year: 2005
```
**Sample Output:**
```
You are 21 years old.
21 is Odd
```
