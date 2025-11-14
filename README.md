
#  **QUESTION 1 — Shop Receipt Program**

This program simulates a small shop where a user buys items and receives a printed receipt.

### **How it works**

1. A dictionary stores items and their prices:

   ```python
   items = {"Bread": 25, "Milk": 18, "Eggs": 2.5, "Sugar": 20}
   ```
2. Using a loop, the program asks the user how many of each item they want.
3. It calculates the subtotal by multiplying quantities by prices.
4. If the subtotal is **above 100 GHS**, a **10% discount** is applied.
5. A detailed receipt is printed using **string formatting**, showing:

   * Quantities
   * Cost per item
   * Subtotal
   * Discount
   * Final Total
6. It uses a dictionary method like `.items()` to loop through items and prices.

---

#  **QUESTION 2 — Student Score Manager**

This program manages student scores and calculates averages.

### **How it works**

1. A list of dictionaries stores students and their subject scores:

   ```python
   [{"name": "Ama", "Maths": 78, "Science": 82, "English": 74}, ...]
   ```
2. The program loops through each student and computes their average.
3. It uses `.update()` to add a new key `"Average"` to each student dictionary.
4. It prints each student’s results using formatted f-strings.
5. The student with the **highest average** is identified and displayed.

---

#  **QUESTION 3 — Employee Salary Adjustment**

This program adjusts employee salaries based on given rules.

### **How it works**

1. Two lists (`employees` and `salaries`) are combined into a dictionary using a loop.
2. Salary adjustment rules:

   * Add **7%** if salary < 3500
   * Add **4%** otherwise
3. The program calculates both old and new salaries.
4. Uses dictionary methods like `.update()` or `.items()`.
5. Prints results in a clean formatted structure:

   ```
   Kwame | Old: 3200.00 | New: 3424.00
   ```

---

# **QUESTION 4 — Number List Operations**

This program performs operations on a list using `range()` and list methods.

### **How it works**

1. Creates a list of even numbers from **2 to 20** using:

   ```python
   list(range(2, 21, 2))
   ```
2. Appends the number **22**.
3. Removes the smallest number using:

   * `pop(0)` or
   * `remove(2)`
4. Computes the **sum** and **average** of the updated list.
5. Prints:

   * Final list
   * Sum
   * Average (to two decimal places)

---

#  **QUESTION 5 — Vowel Counter**

This program counts how many times each vowel appears in a sentence.

### **How it works**

1. User enters a sentence.
2. A dictionary stores vowels as keys (`a, e, i, o, u`) and counts as values.
3. The program loops through each character and checks if it is a vowel.
4. It increments the correct count for each vowel found.
5. At the end, it prints the number of times each vowel appears.

---

# **Summary**

These programs demonstrate skills in:

* Dictionaries & dictionary methods
* Lists and loops
* Input handling
* Conditionals
* String formatting
* Basic algorithms
* Data processing

If you want, I can package all solutions into a **single Python file**, or generate a **PDF version** of the README.
