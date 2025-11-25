Skip to content
Navigation Menu
Sudharsanan-18
19CS404-DBMS-Lab-Manual

Type / to search
Code
Pull requests
Actions
Projects
Security
Insights
Files
Go to file
t
Experiment10_Triggers
Experiment1_ER_Diagram
problem_statement.md
Experiment2_DDL_Commands
README.md
Experiment3_DML_Commands
README.md
Experiment4_AggregateGroupByHaving
README.md
Experiment5_Subqueries_Views
README.md
Experiment6_Joins
README.md
Experiment7_plsql
readme.md
Experiment8_Cursor
Experiment9_Procedures
README.md
You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork Yeshwanth58/19CS404-DBMS-Lab-Manual, so you can send a pull request.
19CS404-DBMS-Lab-Manual/Experiment7_plsql
/
readme.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing readme.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
# Experiment 7: PL/SQL – Variables, Control Structures and Loops

## AIM
To write and execute simple PL/SQL programs using variables, loops, and conditional statements.


## THEORY

PL/SQL, which stands for Procedural Language extensions to the Structured Query Language (SQL). It is a combination of SQL along with the procedural features of programming languages.

**Syntax:**
```sql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```

### Basic Components of PL/SQL Block:
- DECLARE: Section to declare variables and constants.
- BEGIN: The execution section that contains PL/SQL statements.
- EXCEPTION: Handles errors or exceptions that occur in the program.
- END: Marks the end of the PL/SQL block.

# PL/SQL Programs – Steps and Expected Output

## 1. Write a PL/SQL program to find the Greatest of Two Numbers

### Steps:
- Declare two numeric variables and initialize them.
- Use an `IF` statement to compare the values.
- Display the greater number using `DBMS_OUTPUT.PUT_LINE`.

**Expected Output:**  
Greater number is: 80
### Program:
```
DECLARE
    num1 NUMBER := 80;  -- First number
    num2 NUMBER := 50;  -- Second number
BEGIN
    IF num1 > num2 THEN
        DBMS_OUTPUT.PUT_LINE('Greater number is: ' || num1);
    ELSE
        DBMS_OUTPUT.PUT_LINE('Greater number is: ' || num2);
    END IF;
END;
```
### Output:


<img width="398" height="278" alt="514783700-dec6d66a-95b6-4c4b-a622-c9937356ff70" src="https://github.com/user-attachments/assets/1fbe0355-41f8-487a-8250-6a7bda1cb75b" />
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
