# APCSA — MCQ

## Scope of *this* assignment

**Primary goal:** Log **all** incorrect **Barron** book (and Barron Online MCQ, if required) **multiple-choice** questions—chapter reviews, diagnostics, and full **practice exams**—one row per missed question under **## Barron** below.

Sections **5 Steps** and **Past papers** are for **other** work unless your teacher tells you to use them for the same assignment.

**FRQ / free-response** material belongs in `frq.md`, not here.

---

- Optional **date** in *Source* helps over time, e.g. `2026-04-15 | Practice Exam 2 MCQ Q17`.
- For **code-tracing** MCQs, *My wrong answer* can be your wrong traced result or a **one-line** snippet; otherwise use **A–D** or a short phrase.

## Barron

| Source | What this question is testing | My wrong answer | Correct answer | Why I got it wrong | Correct rule / fix | Reminder |
|z|a|-----------------|----------------|-------------------|-------------------|----------|
|--------|--------------------------------|-----------------|----------------|-------------------|-------------------|----------|
|Barron online test 1 Q3 |evaluation of boolean expression |B |D |I didn't consider the precedence |&&(and) has higher precedence than (or) |Even if (or) appears first than (and) in the expression, we need to consider (and) first. Also study shortcut evaluation, De morgans law, boolean algebra|

|Barron online test 1 Q4 |reading an external file|D |C |I didn't consider that additional next() method moves the pointer to the next line before splitting by underscore.  |next() method moves the file pointer to the next line| To read an external file, import java.util.Scanner, create file object (File file = new File("example.txt")), create Scanner object(Scanner sc = new Scanner(file)), read the file(String input = sc.nextLine())|

|Barron online test 1 Q18 |for loop and index |B |D | for(int i=arr.length-1; i>=0; i--){list.add(i,arr[i])} throw IndexOutOfBoundsException. because for example, if the array has 8 elements, it will try to add an element to an empty list at position 7. list is empty, there is no position 7 yet, error occurs| Rule: Put something in the next empty spot at the end, OR Put something where a spot already exists|

|Barron online test 1 Q26 |implement an increment of variable |A |C |I thought checking before incrementing would work, but the value never equals the rollover limit, so it never resets. |Check carefully for order of operations(incrementing first or change first), boundary conditions of variable.|

|Barron online test 1 Q31 |assignment of variables, setter, getter methods |C |A |I chose 1142.1 because I thought r3’s value would update in the last line, but setPr only changes the value if the new time is lower. Since 1142.1 is higher than 1117.4, the value does not change.
|Reference variables can point to the same object, so changes made through one reference affect all others pointing to that object.|

|Barron online test 1 Q34 |search algorithm |C |B |I didn't consider that sorting before searching requires more examination of every record. so inefficient |sorting and then searching requires more time than just searching |
Remember binary search should be sorted|

|Barron online test 1 Q36 |nested for loop with 2D array |C |D |I didn't consider the choice that says all works

|Barron online test 1 Q37 |creating object and correct use of constructor |C |B |I didn't consider the type and the number of parameter lists correctly |parameters type should be matched when creating an object. |

|Barron online test 1 Q40 |change codes to work as intended. logic, if statement, for loop |A |B | I didn't consider that when the last index in the array is reached, arr[i+1] is out of range. so it will throw ArrayIndexOutOfBoundsException| should be arr.length-1 when using int i=0;|

|Barron onlne test 2 Q1 |time complexities  |C |D |I didn't know the execution times. |for loop is executed log2 n times |If I substitute n with a small number like 16, I can easily calculate execution time without memorizing.|
## 5 Steps to a 5

*(Optional — not part of the Barron-only assignment unless assigned.)*

| Source | What this question is testing | My wrong answer | Correct answer | Why I got it wrong | Correct rule / fix | Reminder |
|--------|--------------------------------|-----------------|----------------|-------------------|-------------------|----------|
| | | | | | | |

## Past papers

*(Optional — College Board released MCQs, if assigned.)*

| Source | What this question is testing | My wrong answer | Correct answer | Why I got it wrong | Correct rule / fix | Reminder |
|--------|--------------------------------|-----------------|----------------|-------------------|-------------------|----------|
| | | | | | | |
