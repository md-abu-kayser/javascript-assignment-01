# Javascript Assignment Document

## Important Notes

Read each problem carefully, try to find the logic first, and then solve it with code.

In every problem, you will see that some specific values must be printed using `console.log()` only. Do not print anything extra on your own. If you do, you may lose marks even if your code is correct.

Do not change any of the variable names given in the problems.

Declare all variables using `var`.

Try to make sure the variable names used in one problem do not conflict with the variable names in another problem.

---

## Problem 01 - Divide the Asset

Rahim and Karim are two brothers. Their father owns a piece of land whose area is stored in a variable named `area`. Their father wants to divide the land into 2 equal parts.

Write a program to find out how much land each brother will get, and show the output as in the examples below.

**Value of `area`** `(0 < number <= 10^9)`

**Output** `(number)`

Examples:

- `100` → `50`
- `15` → `7.5`
- `2060` → `1030`

Copy the code snippet below, complete the program, and print the output using `console.log()`.

```javascript
/** Problem - 01 ( Divide the Asset ) */
var area = 800;
// write your code here
```

---

## Problem 02 - Cycle or Laptop

Montu got GPA 5 in the SSC exam. He insists that his father must buy him either a cycle or a laptop.

The amount of money Montu’s father has is stored in a variable named `money`. Based on the conditions below, his father will decide what to buy:

- If the money is **25000 or more**, buy a **Laptop**.
- If the money is **10000 or more**, buy a **Cycle**.
- If the money is less than that, buy a **Chocolate** as a consolation prize.

Write a program for Montu’s father and show what Montu will get as output.

**Value of `money`** `(0 < number <= 10^9)`

**Output** `(string)`

Examples:

- `45000` → `Laptop`
- `10000` → `Cycle`
- `9999` → `Chocolate`

Copy the code snippet below, complete the program, and print the output using `console.log()`.

```javascript
/** Problem - 02 ( Cycle or Laptop ) */
var money = 10000;
// write your code here
```

---

## Problem 03 - Medicine Planner

On the 1st day of the month, Raima Begum was given medicine by a doctor. She has to take it every 3 days.

The last day until which she has to take the medicine is stored in a variable named `lastDay`.

You need to write a program that creates a list showing which days she will take medicine and which days she will rest. Show the output exactly like the examples below.

**Value of `lastDay`** `(3 < number <= 30)`

**Output** `(string)`

Examples:

- `4`
  - `1 - rest`
  - `2 - rest`
  - `3 - medicine`
  - `4 - rest`

- `6`
  - `1 - rest`
  - `2 - rest`
  - `3 - medicine`
  - `4 - rest`
  - `5 - rest`
  - `6 - medicine`

Copy the code snippet below, complete the program, and print the output exactly as shown using `console.log()`.

```javascript
/** Problem - 03 ( Medicine Planner ) */
var lastDay = 11;
// write your code here
```

---

## Problem 04 - Delete / Store

Suma’s computer has too many files. She wants to keep only PDF files, DOCX files, and files whose names start with `#`. All other files should be deleted.

The file name is stored in a variable named `fileName`.

Write a program that tells Suma whether she should keep the file or delete it.

- If the file name starts with `#`, output: **Store**
- If the file is a `pdf`, output: **Store**
- If the file is a `docx`, output: **Store**
- For everything else, output: **Delete**

**Value of `fileName`** `(string)`

**Output** `(string)`

Examples:

- `result.pdf` → `Store`
- `data.docx` → `Store`
- `pdfData.jpg` → `Delete`
- `#exp.mp4` → `Store`
- `docx.txt` → `Delete`
- `docx.xpdf` → `Delete`
- `slipdf.txt` → `Delete`

Copy the code snippet below, complete the program, and print the output exactly as shown using `console.log()`.

```javascript
/** Problem 04 - (Delete / Store) */
var fileName = "pdfData.jpg";
// write your code here
```

---

## Problem 05 - PH Email Generator

Consider the object structure below:

```javascript
{ name: string, roll: number, department: string }
```

A student studying at PH University is stored in a variable named `student`.

You need to write a program that generates an email based on the `student` object data. The email should follow this exact structure:

`name + roll + "." + department + "@ph.ac.bd"`

Look at the examples below.

**Value of `student`** `(object)`

**Output** `(string)`

Examples:

- `{ name: "jhankar", roll: 1014, department: "cse" }` → `jhankar1014.cse@ph.ac.bd`
- `{ name: "monu", roll: 99, department: "eee" }` → `monu99.eee@ph.ac.bd`
- `{ name: "mewo", roll: 96, department: "cse" }` → `mewo96.cse@ph.ac.bd`

Copy the code snippet below, complete the program, and print the output using `console.log()`.

```javascript
/** Problem 05 - ( PH Email Generator ) */
var student = { name: "jhankar", roll: 1014, department: "cse" };
// write your code here
```

---

## Problem 06 - Current Salary (Challenge Problem)

Hasan Sir works in a government job. The number of years he has worked is stored in a variable named `experience`.

His starting salary is stored in a variable named `startingSalary`.

Every year, Hasan Sir’s salary increases by **5%**.

Write a program to find his current salary. The result should have at most **2 digits after the decimal point**.

**Value of `startingSalary`** `(0 < number <= 10^6)`

**Value of `experience`** `(0 < number <= 50)`

**Output** `(up to 2 decimal places)`

Examples:

- `45000`, `30` → `194487.41`
- `15000`, `3` → `17364.38`
- `30000`, `40` → `211199.66`

Copy the code snippet below, complete the program, and print the output exactly as shown using `console.log()`.

```javascript
/** Problem 06 : (Current Salary) */
var experience = 30;
var startingSalary = 45000;
// write your code here
```
