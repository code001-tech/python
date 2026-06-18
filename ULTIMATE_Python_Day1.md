# 🐍 THE ULTIMATE PYTHON DAY 1 TEXTBOOK
## Complete Professional Guide with Visual Explanations, All Error Types, 10 Full Projects & 15 Worksheets

**Edition:** 2.0 (ENHANCED)  
**Target:** Complete Beginner → Professional AI/ML Developer  
**Pages:** 80+  
**Code Examples:** 300+  
**Error Scenarios:** 25+  
**Projects:** 10 Complete  
**Worksheets:** 15 with Solutions  
**Total Study Time:** 15-20 hours  

---

## MEGA TABLE OF CONTENTS

### PART 1: FOUNDATIONS
- [1.1 Programming Fundamentals](#section-11)
- [1.2 Python Philosophy & Why It Matters](#section-12)
- [1.3 Setting Up Your Professional Environment](#section-13)
- [1.4 Your First Day Success Checklist](#section-14)

### PART 2: CORE CONCEPTS
- [2.1 The print() Function - Complete Deep Dive](#section-21)
- [2.2 Variables - The Foundation of All Code](#section-22)
- [2.3 Data Types - Every Single One Explained](#section-23)
- [2.4 Operators - Mathematical & Logical Operations](#section-24)
- [2.5 Input & User Interaction](#section-25)
- [2.6 String Methods - 30+ Methods With Examples](#section-26)

### PART 3: ERROR MASTERY
- [3.1 All 25 Common Errors With Solutions](#section-31)
- [3.2 Debugging Strategies Like a Senior](#section-32)
- [3.3 Error Handling Best Practices](#section-33)

### PART 4: PROFESSIONAL PRACTICES
- [4.1 How Senior Engineers Code](#section-41)
- [4.2 Code Quality & Best Practices](#section-42)
- [4.3 Performance Optimization Day 1](#section-43)

### PART 5: HANDS-ON LEARNING
- [5.1 10 Complete Projects With Explanations](#section-51)
- [5.2 15 Practice Worksheets With Solutions](#section-52)
- [5.3 Challenge Problems](#section-53)

---

# PART 1: FOUNDATIONS

## <a id="section-11"></a> 1.1 Programming FUNDAMENTALS - THE COMPLETE PICTURE

### What Happens When You Run Python Code?

```
YOUR CODE (day1.py)          PYTHON INTERPRETER         COMPUTER
┌──────────────────┐         ┌─────────────────┐       ┌──────────┐
│ print("Hello")   │ ────→   │ 1. Read code    │       │ Execute  │
│ x = 10           │         │ 2. Check syntax │ ────→ │ Display  │
│ print(x + 5)     │         │ 3. Translate    │       │ Output   │
└──────────────────┘         │ 4. Execute      │       └──────────┘
                             └─────────────────┘
```

**Step-by-step breakdown:**

1. **You write code** in a `.py` file
2. **Python reads it** line by line (top to bottom)
3. **Python checks** if syntax is correct
4. **Python executes** each instruction
5. **Computer performs** the action
6. **Result appears** on screen

### The Programming Pyramid (What You're Learning)

```
        ┌─────────────┐
        │   ADVANCED  │  AI/ML, Web, Games (Phase 5+)
        │             │
        ├─────────────┤
        │   MEDIUM    │  Functions, Classes, Files (Phase 2-3)
        │             │
        ├─────────────┤
        │   BASIC     │  ← YOU ARE HERE (Day 1)
        │  Variables, │
        │  Types,     │
        │  Input/Out  │
        └─────────────┘
```

### Core Programming Concepts (All Will Use Today)

```
PROBLEM SOLVING
    ↓
VARIABLES (containers for data)
    ↓
DATA TYPES (what kind of data)
    ↓
OPERATORS (do things with data)
    ↓
INPUT/OUTPUT (talk to users)
    ↓
ERROR HANDLING (when things go wrong)
```

---

## <a id="section-12"></a> 1.2 PYTHON PHILOSOPHY & WHY IT MATTERS

### The Zen of Python (Read This Every Day)

```python
import this
```

Running this in Python shows 20 principles. Key ones:

| Principle | Meaning |
|---|---|
| Beautiful is better than ugly | Code should look clean |
| Explicit is better than implicit | Clear code beats "clever" code |
| Simple is better than complex | Don't overcomplicate |
| Readability counts | Others will read your code |
| Now is better than never | Start coding NOW |

### Why Python For AI/ML?

```
Language    Speed    Learning Curve    Libraries    Industry Use
─────────────────────────────────────────────────────────────────
Python      Medium   VERY EASY         Excellent    MOST USED ✓
Java        Fast     Hard              Good         Legacy
C++         Very Fast Hard             Good         Speed-critical
JavaScript  Medium   Easy              OK           Web
```

**Reality Check:** 90% of AI/ML jobs require Python. If you learn Python well, you'll work everywhere.

---

## <a id="section-13"></a> 1.3 SETTING UP YOUR PROFESSIONAL ENVIRONMENT

### The Complete Setup Process

#### Step 1: Install Python (CRITICAL - Don't Skip!)

**For Windows:**
```
1. Go to python.org/downloads
2. Click "Download Python 3.12.0"
3. Run the installer
4. ✅ CHECK "Add Python to PATH" ← MOST IMPORTANT
5. Click Install
6. Verify: Open cmd, type "python --version"
```

**Visual Setup Process:**

```
Step 1: Download                Step 2: Run Installer
┌──────────────────┐           ┌──────────────────────────┐
│ Browser Window   │           │ Installation Dialog      │
│                  │           │ ☑ Add Python to PATH ← │
│ [Download]       │────────→  │ [Install]                │
└──────────────────┘           └──────────────────────────┘
                                        ↓
                              Step 3: Verification
                              ┌──────────────────────────┐
                              │ C:\> python --version   │
                              │ Python 3.12.0           │
                              │ ✓ Success!              │
                              └──────────────────────────┘
```

#### Step 2: Install VS Code

```
1. Download from code.visualstudio.com
2. Run installer (take defaults)
3. Open VS Code
4. Click Extensions (4 blocks icon)
5. Search "Python" (by Microsoft)
6. Click Install
7. Reload VS Code
```

#### Step 3: Create Your Workspace

```
Desktop/
└── PythonLearning/  ← Create this folder
    ├── day1.py
    ├── projects/
    │   ├── project1.py
    │   ├── project2.py
    │   └── ...
    └── worksheets/
        ├── worksheet1.py
        └── ...
```

#### Step 4: Your First Test

```python
# File: test.py
print("Python is working!")

# Run it:
# Right-click → Run Python File in Terminal
# Output: Python is working!
```

**If output appears:** ✅ Setup complete!  
**If error:** Check that Python is in PATH (reinstall if needed)

---

## <a id="section-14"></a> 1.4 DAY 1 SUCCESS CHECKLIST

```
MORNING (Setup)
☐ Python installed and in PATH verified
☐ VS Code installed with Python extension
☐ PythonLearning folder created
☐ test.py runs successfully

AFTERNOON (Learning)
☐ Watch freeCodeCamp 0:00-0:50 (pause often)
☐ Type every single example yourself (DON'T copy-paste)
☐ Make intentional mistakes and read errors
☐ Complete all 5 exercises in print() section

EVENING (Practice)
☐ Build 2 projects from Chapter 5
☐ Complete Worksheet 1 (all exercises)
☐ Write 5 concepts in notebook (by hand)
☐ Git push your code (if using GitHub)

SUCCESS CRITERIA
✓ Can print text, numbers, and calculations
✓ Can get user input and store it
✓ Can convert between data types
✓ Understand what errors mean
✓ Built 2 working programs from scratch
```

---

# PART 2: CORE CONCEPTS - COMPLETE DEEP DIVE

## <a id="section-21"></a> 2.1 THE print() FUNCTION - EXTREME DEPTH

### Visual: How print() Works

```
INPUT                   PYTHON                      OUTPUT
─────────────────────────────────────────────────────────────
"Hello" ─────→ [print function] ─────→ Screen shows: Hello

Multiple: ─────→ [print function]  ─────→ One line with
"A", "B"        (joins with sep)        spaces between

Calculation:────→ [print function] ─────→ Evaluated
10 + 20         (evaluates first)       30 appears
```

### The print() Signature (What Programmers Call It)

```python
print(value1, value2, ..., sep=' ', end='\n', file=sys.stdout, flush=False)
```

**Breaking every parameter:**

| Parameter | Default | What it does |
|---|---|---|
| `value1, value2, ...` | (required) | What to print |
| `sep=' '` | Space | Character between items |
| `end='\n'` | Newline | What comes at end |
| `file` | stdout | Where to print (screen) |
| `flush` | False | Whether to flush buffer |

### Complete print() Examples Catalog

#### Category 1: Basic Printing

```python
# Example 1.1: Text
print("Hello World")
# Output: Hello World

# Example 1.2: Numbers
print(42)
# Output: 42

# Example 1.3: Decimals
print(3.14159)
# Output: 3.14159

# Example 1.4: Empty line
print()
# Output: (blank line)

# Example 1.5: Boolean
print(True)
# Output: True
```

#### Category 2: Multiple Values

```python
# Example 2.1: Multiple strings
print("Name:", "Chandresh", "Age:", 20)
# Output: Name: Chandresh Age: 20

# Example 2.2: Mixed types
print("Price: ₹", 100, "Quantity: ", 5)
# Output: Price: ₹ 100 Quantity:  5

# Example 2.3: Calculations inline
print("Sum of 10 + 20 =", 10 + 20)
# Output: Sum of 10 + 20 = 30

# Example 2.4: Variables mixed with text
name = "Alice"
score = 95
print("Student:", name, "Score:", score)
# Output: Student: Alice Score: 95
```

#### Category 3: Using sep Parameter

```python
# Default sep (space)
print("A", "B", "C")
# Output: A B C

# Custom sep examples
print("2024", "01", "15", sep="-")  # Output: 2024-01-15

print("User", "Name", "Email", sep=" | ")  # Output: User | Name | Email

print("Python", "Java", "C++", sep=", ")  # Output: Python, Java, C++

print("🌟", "Python", "🌟", sep="")  # Output: 🌟Python🌟

# Practical: Creating CSV
names = ["Alice", "Bob", "Charlie"]
ages = [20, 21, 22]
for i in range(len(names)):
    print(names[i], ages[i], sep=",")  # CSV format
# Output:
# Alice,20
# Bob,21
# Charlie,22
```

#### Category 4: Using end Parameter

```python
# Default end (newline)
print("Line 1")
print("Line 2")
# Output:
# Line 1
# Line 2

# Custom end
print("Loading", end="")
print(".")
print(".")
# Output: Loading..

# Practical: Progress indicator
for i in range(5):
    print(f"Step {i+1}", end=" → ")
print("Done!")
# Output: Step 1 → Step 2 → Step 3 → Step 4 → Step 5 → Done!

# End with custom character
print("Question", end="?")  # Output: Question? (no newline after)

# End with tabs
print("Column1", end="\t")
print("Column2", end="\t")
print("Column3")
# Output: Column1  Column2  Column3 (tab-separated)
```

#### Category 5: The flush Parameter

```python
# flush=False (default): buffered
import time
print("Processing", end="", flush=False)
time.sleep(1)
print(".")  # Appears together

# flush=True: immediate
print("Processing", end="", flush=True)
time.sleep(1)
print(".")  # "Processing" shows immediately

# When to use flush=True:
# - Real-time output needed (progress bars)
# - Debugging (see output immediately)
# - Interactive programs
```

#### Category 6: Escape Sequences

```
ESCAPE SEQUENCES (special characters using backslash)
───────────────────────────────────────────────────
\n = Newline (next line)
\t = Tab (4 spaces)
\\ = Backslash (literal)
\" = Double quote (inside double quotes)
\' = Single quote (inside single quotes)
\r = Carriage return (go to line start)
\b = Backspace (erase previous character)
```

**Examples:**

```python
# \n - newline
print("Line 1\nLine 2\nLine 3")
# Output:
# Line 1
# Line 2
# Line 3

# \t - tab
print("Name\tAge\tCity")
print("Alice\t20\tMumbai")
# Output:
# Name    Age     City
# Alice   20      Mumbai

# \\ - backslash
print("Path: C:\\Users\\Documents\\file.txt")
# Output: Path: C:\Users\Documents\file.txt

# \" - quote in string
print("He said \"Hello World\"")
# Output: He said "Hello World"

# \r - overwrite
print("Progress: 0%", end="\r")
time.sleep(1)
print("Progress: 100%")
# Output shows as "Progress: 100%"
```

### F-Strings Deep Dive (Modern Python)

#### F-String Basics

```python
# F-string formula:
# f"text {variable} more text"
#  ↑  ↑                  ↑
#  |  |                  └─ Regular text
#  |  └─────────────────── Variable in braces
#  └────────────────────── The 'f' prefix (REQUIRED)

name = "Chandresh"
age = 20

# Basic f-string
print(f"Name: {name}, Age: {age}")
# Output: Name: Chandresh, Age: 20

# Calculation inside
x = 10
y = 20
print(f"{x} + {y} = {x + y}")
# Output: 10 + 20 = 30

# Method calls inside
text = "python"
print(f"Uppercase: {text.upper()}")
# Output: Uppercase: PYTHON

# Conditional inside
age = 25
print(f"Adult: {age >= 18}")  # Boolean
# Output: Adult: True
```

#### F-String Formatting (Numbers)

```
FORMAT SPECS:
{value:format_spec}

NUMBER FORMATS:
:.2f  = 2 decimal places
:05d  = Pad with zeros to 5 digits
:,.0f = Thousand separators
:.1%  = Percentage to 1 decimal
:>10  = Right-align in 10 spaces
:<10  = Left-align in 10 spaces
:^10  = Center in 10 spaces
```

**Examples:**

```python
# Decimal places
price = 19.9876
print(f"Price: ${price:.2f}")  # Price: $19.99

# Zero padding
id_num = 42
print(f"ID: {id_num:05d}")  # ID: 00042

# Thousands separator
population = 1000000
print(f"Population: {population:,}")  # Population: 1,000,000

# Percentage
accuracy = 0.9567
print(f"Accuracy: {accuracy:.1%}")  # Accuracy: 95.7%

# Alignment
name = "AI"
print(f"|{name:>10}|")  # |        AI| (right-aligned)
print(f"|{name:<10}|")  # |AI        | (left-aligned)
print(f"|{name:^10}|")  # |    AI    | (centered)

# Combined: price formatting
amount = 1234.5678
print(f"Invoice: ${amount:>10,.2f}")  # Invoice: $ 1,234.57

# Real ML use case: logging
epoch = 1
loss = 0.1234567
accuracy = 0.9812
print(f"Epoch {epoch:3d} | Loss: {loss:.4f} | Acc: {accuracy:.4f}")
# Epoch   1 | Loss: 0.1235 | Acc: 0.9812
```

#### F-String Advanced Tricks

```python
# Nested expressions
data = {"name": "Alice", "age": 25}
print(f"User: {data['name']}, {data['age']} years old")
# Output: User: Alice, 25 years old

# Dictionary access
person = {"name": "Bob", "score": 95}
print(f"{person['name']}: {person['score']}%")
# Output: Bob: 95%

# List access
scores = [85, 90, 78, 92]
print(f"Best: {max(scores)}, Worst: {min(scores)}")
# Output: Best: 92, Worst: 78

# Conditional expression
age = 17
status = "Minor" if age < 18 else "Adult"
print(f"Status: {status}")
# Output: Status: Minor

# One-liner madness (not recommended but possible)
x, y = 10, 20
print(f"Result: {(x + y) * 2 if x > 5 else 'Too small'}")
# Output: Result: 60
```

### Comparison: All String Formatting Methods

```python
name = "Chandresh"
age = 20

# Method 1: String concatenation (OLD - BAD)
result = "Name: " + name + ", Age: " + str(age)

# Method 2: % operator (LEGACY)
result = "Name: %s, Age: %d" % (name, age)

# Method 3: format() method (OKAY)
result = "Name: {}, Age: {}".format(name, age)

# Method 4: f-string (BEST - MODERN)
result = f"Name: {name}, Age: {age}"

# All produce: "Name: Chandresh, Age: 20"
# But f-string is fastest and clearest
```

---

## <a id="section-22"></a> 2.2 VARIABLES - THE FOUNDATION OF ALL CODE

### Visual Memory Model

```
BEFORE:                    AFTER: x = 10
(memory is empty)          
                           Memory Address #2048
                           ┌──────────────┐
                           │      10      │
                           └──────────────┘
                                  ↑
                                  │
                           x ─────┘
                           (label points here)

WHEN YOU USE x:
print(x)  → Go to memory #2048 → Get value 10 → Print 10
```

### Variable Naming Deep Rules

```
RULE 1: First character must be letter or underscore
✅ name = "Bob"
✅ _private = 42
✅ Name2 = 3.14
❌ 2name = "invalid"  # Starts with number

RULE 2: Only alphanumeric and underscore after first
✅ student_name = "Alice"
✅ test_score_2024 = 95
❌ test-score = 95     # Hyphen not allowed
❌ test score = 95     # Space not allowed

RULE 3: Case-sensitive
x = 10
X = 20
print(x)  # Output: 10 (lowercase x)
print(X)  # Output: 20 (uppercase X)
# They are DIFFERENT variables!

RULE 4: Can't use Python keywords
❌ class = "Physics"    # class is a keyword
❌ def = 5              # def is a keyword
❌ if = True            # if is a keyword
✅ my_class = "Physics" # This works
```

### Professional Naming Conventions

```
STYLE 1: snake_case (PYTHON STANDARD - USE THIS)
student_name = "Alice"
total_score = 95
is_graduated = True
def calculate_average():
    pass

STYLE 2: camelCase (Some use in Python, don't)
studentName = "Alice"
totalScore = 95
isGraduated = True

STYLE 3: PascalCase (For class names, not variables)
class StudentInfo:
    pass

CONVENTION: Constants (values that never change)
PI = 3.14159
MAX_STUDENTS = 50
DATABASE_URL = "localhost:5432"
# Written in UPPERCASE
```

### Variable Types & Scope

```
SCOPE = Where a variable exists and can be used

GLOBAL SCOPE
├── Exists everywhere in program
├── Created at top level
└── Accessible in functions
    
LOCAL SCOPE
├── Exists only in function
├── Created inside function
└── Forgotten when function ends
```

**Example:**

```python
# GLOBAL scope
global_var = "I exist everywhere"

def my_function():
    # LOCAL scope
    local_var = "I only exist here"
    print(global_var)  # ✅ Works (can access global)
    print(local_var)   # ✅ Works (inside function)

print(global_var)   # ✅ Works (global scope)
print(local_var)    # ❌ ERROR (local_var doesn't exist here)
```

### Variable Reassignment & Mutation

```
REASSIGNMENT (changing value)
x = 10
print(x)  # Output: 10

x = 20    # Old value (10) is forgotten
print(x)  # Output: 20

REASSIGNMENT WITH OPERATION
x = 10
x = x + 5  # x becomes 15
print(x)   # Output: 15

SHORTHAND
x = 10
x += 5     # Same as x = x + 5
print(x)   # Output: 15
```

### Multiple Assignment Patterns

```python
# Pattern 1: Assign same value to multiple variables
x = y = z = 0
print(x, y, z)  # Output: 0 0 0

# Pattern 2: Unpacking (assign multiple values)
a, b, c = 1, 2, 3
print(a)  # Output: 1
print(b)  # Output: 2
print(c)  # Output: 3

# Pattern 3: Swap variables
x = 5
y = 10
x, y = y, x
print(x)  # Output: 10
print(y)  # Output: 5

# Pattern 4: From list
names = ["Alice", "Bob", "Charlie"]
first, second, third = names
print(first)  # Output: Alice
```

---

## <a id="section-23"></a> 2.3 DATA TYPES - EVERY SINGLE ONE

### The Data Type Universe

```
PYTHON DATA TYPES
│
├── NUMERIC
│   ├── int (integers: 10, -5, 0)
│   ├── float (decimals: 3.14, -2.5)
│   └── complex (advanced: 3+4j)
│
├── SEQUENCE
│   ├── str (text: "hello")
│   ├── list (ordered: [1, 2, 3])
│   ├── tuple (ordered immutable: (1, 2, 3))
│   └── range (range: range(0, 10))
│
├── MAPPING
│   └── dict (key-value: {"name": "Alice"})
│
├── SET
│   ├── set (unique: {1, 2, 3})
│   └── frozenset (immutable set)
│
└── SPECIAL
    ├── bool (True/False)
    └── NoneType (None)
```

### STRINGS (str) - Complete Reference

#### String Creation

```python
# Single quotes
text1 = 'Hello'

# Double quotes
text2 = "Hello"

# Triple quotes (multi-line)
text3 = """This is a
multi-line string
that can span multiple lines"""

# Raw string (escape sequences as literal)
path = r"C:\Users\Name\file.txt"  # Backslashes literal

# F-string (with expressions)
name = "Alice"
greeting = f"Hello, {name}!"

# All are equivalent
print(text1 == text2)  # Output: True
```

#### String Indexing

```
       0   1   2   3   4   5
       H   e   l   l   o  \0
      -6  -5  -4  -3  -2  -1

text = "Hello"
text[0]    # "H" (first character)
text[4]    # "o" (last character)
text[-1]   # "o" (last character, negative index)
text[-2]   # "l" (second-to-last)
```

**Examples:**

```python
text = "Python"

print(text[0])     # P (index 0)
print(text[5])     # n (index 5, last)
print(text[-1])    # n (last, negative)
print(text[-6])    # P (first, negative)

# Out of bounds
print(text[10])    # ❌ ERROR: IndexError
```

#### String Slicing

```
SLICING SYNTAX: string[start:end:step]

       0   1   2   3   4   5
       H   e   l   l   o
      -6  -5  -4  -3  -2  -1

[start:end] → includes start, excludes end
[::step]    → every nth character
```

**Examples:**

```python
text = "Python"

# Slice from index 0 to 3 (excludes 3)
print(text[0:3])     # "Pyt"

# Slice from index 2 to end
print(text[2:])      # "thon"

# Slice from start to index 4
print(text[:4])      # "Pyth"

# Every 2nd character
print(text[::2])     # "Pto"

# Reverse string
print(text[::-1])    # "nohtyP"

# Last 3 characters
print(text[-3:])     # "hon"

# Practical: Get domain from email
email = "user@example.com"
domain = email[email.index("@")+1:]
print(domain)  # "example.com"
```

#### String Methods - The Complete Catalog

##### Transformation Methods

```python
text = "Hello World"

# upper() - all uppercase
print(text.upper())  # "HELLO WORLD"

# lower() - all lowercase
print(text.lower())  # "hello world"

# capitalize() - first letter uppercase
print(text.capitalize())  # "Hello world"

# title() - each word capitalized
print(text.title())  # "Hello World"

# swapcase() - swap uppercase/lowercase
print(text.swapcase())  # "hELLO wORLD"

# casefold() - aggressive lowercase (Unicode)
print(text.casefold())  # "hello world"
```

##### Searching Methods

```python
text = "hello world hello"

# count() - count occurrences
print(text.count("hello"))  # 2
print(text.count("o"))      # 2

# find() - position of substring
print(text.find("world"))   # 6
print(text.find("xyz"))     # -1 (not found)

# index() - position (error if not found)
print(text.index("world"))  # 6
# print(text.index("xyz"))  # ValueError!

# startswith() - check beginning
print(text.startswith("hello"))  # True

# endswith() - check ending
print(text.endswith("hello"))    # True

# __contains__ (in operator)
print("world" in text)     # True
print("xyz" in text)       # False
```

##### Modification Methods

```python
text = "hello world"

# replace() - replace substring
print(text.replace("world", "python"))  # "hello python"

# replace() - limited replacements
text = "cat cat cat"
print(text.replace("cat", "dog", 1))   # "dog cat cat"

# split() - split into list
print(text.split())  # ["hello", "world"]
print(text.split("o"))  # ["hell", " w", "rld"]

# join() - join list into string
words = ["hello", "world", "python"]
print(" ".join(words))  # "hello world python"

# strip() - remove whitespace
text = "  hello  "
print(f"|{text.strip()}|")   # "|hello|"
print(f"|{text.lstrip()}|")  # "|hello  |"
print(f"|{text.rstrip()}|")  # "|  hello|"

# strip() with characters
text = "xxxhelloxxx"
print(text.strip("x"))  # "hello"

# lstrip() / rstrip()
text = "001200"
print(text.lstrip("0"))  # "1200"
print(text.rstrip("0"))  # "0012"

# removeprefix() / removesuffix() (Python 3.9+)
url = "https://example.com"
print(url.removeprefix("https://"))  # "example.com"
```

##### Checking Methods

```python
# isdigit() - all digits?
print("12345".isdigit())      # True
print("123abc".isdigit())     # False

# isalpha() - all letters?
print("hello".isalpha())      # True
print("hello123".isalpha())   # False

# isalnum() - letters and digits only?
print("hello123".isalnum())   # True
print("hello-123".isalnum())  # False

# isspace() - all whitespace?
print("   ".isspace())        # True
print(" a ".isspace())        # False

# islower() - all lowercase?
print("hello".islower())      # True
print("Hello".islower())      # False

# isupper() - all uppercase?
print("HELLO".isupper())      # True
print("Hello".isupper())      # False

# istitle() - title case?
print("Hello World".istitle())  # True
print("hello world".istitle())  # False

# isidentifier() - valid variable name?
print("my_var".isidentifier())  # True
print("my-var".isidentifier())  # False
```

##### Formatting Methods

```python
# center() - center in field
print("hello".center(15))      # "     hello     "
print("hello".center(15, "*"))  # "*****hello*****"

# ljust() - left-justify
print("hello".ljust(10))       # "hello     "
print("hello".ljust(10, "."))  # "hello....."

# rjust() - right-justify
print("hello".rjust(10))       # "     hello"
print("hello".rjust(10, "."))  # ".....hello"

# zfill() - pad with zeros
print("42".zfill(5))           # "00042"
print("-42".zfill(5))          # "-0042"

# expandtabs() - expand tabs
text = "hello\tworld"
print(text.expandtabs(4))  # Expands tab to 4 spaces
```

### NUMBERS - int and float

#### Integer Operations

```python
# Basic operations
a = 10
b = 3

print(a + b)       # 13 (addition)
print(a - b)       # 7 (subtraction)
print(a * b)       # 30 (multiplication)
print(a / b)       # 3.333... (division, returns float)
print(a // b)      # 3 (floor division, returns int)
print(a % b)       # 1 (modulo, remainder)
print(a ** b)      # 1000 (exponentiation, 10³)

# Chained operations
result = 2 + 3 * 4  # Multiplication first (precedence)
print(result)       # 14, not 20

# Parentheses override precedence
result = (2 + 3) * 4
print(result)       # 20
```

#### Float Operations

```python
x = 10.5
y = 3.2

print(x + y)       # 13.7
print(x - y)       # 7.3
print(x * y)       # 33.6
print(x / y)       # 3.28125
print(x // y)      # 3.0 (still float)
print(x % y)       # 1.0999... (remainder)
print(x ** y)      # Large number

# Precision issues (floating point)
print(0.1 + 0.2)   # 0.30000000000000004 (not 0.3!)
# This is a computer limitation, not Python

# Solution: Use decimal for precision
from decimal import Decimal
a = Decimal("0.1")
b = Decimal("0.2")
print(a + b)       # 0.3 (exact)
```

#### Type Conversion

```python
# String to int
age_text = "20"
age_num = int(age_text)
print(age_num + 5)  # 25

# String to float
price_text = "19.99"
price_num = float(price_text)
print(price_num + 1)  # 20.99

# Int to string
number = 42
text = str(number)
print("Number: " + text)  # "Number: 42"

# Int to float
x = 10
y = float(x)
print(y)  # 10.0

# Float to int (truncates)
z = 3.9
w = int(z)
print(w)  # 3 (loses 0.9)

# String with decimals to int (ERROR)
# int("3.14")  # ValueError!
# Solution:
int(float("3.14"))  # Convert to float first, then int
# Result: 3
```

#### Useful Number Functions

```python
# abs() - absolute value
print(abs(-10))      # 10
print(abs(5.5))      # 5.5

# round() - round to decimals
print(round(3.14159, 2))  # 3.14
print(round(10.5))        # 10 (banker's rounding)

# pow() - power (same as **)
print(pow(2, 8))     # 256
print(pow(2, 8, 3))  # 2^8 mod 3

# divmod() - division and remainder
quotient, remainder = divmod(10, 3)
print(quotient)      # 3
print(remainder)     # 1

# min() / max()
print(min(10, 5, 20))    # 5
print(max(10, 5, 20))    # 20

# sum()
print(sum([1, 2, 3, 4, 5]))  # 15
```

### BOOLEANS (bool)

```python
# True and False are capitalized
is_student = True
is_graduated = False

# From comparisons
age = 20
is_adult = age >= 18  # True
is_child = age < 13   # False

# Boolean operations
print(True and True)   # True
print(True and False)  # False
print(True or False)   # True
print(not True)        # False

# Practical: User permission system
is_admin = True
can_edit = is_admin or user_permissions
print(can_edit)  # Depends on user_permissions
```

### NONE TYPE (Special)

```python
# None means "no value"
result = None

# Check for None
if result is None:
    print("No result")

# Useful for "not yet set"
user_email = None
# Later:
if some_condition:
    user_email = "user@example.com"

# Common mistake
print(None == False)     # False (None is not False)
print(None is None)      # True (correct way to check)
```

---

## <a id="section-24"></a> 2.4 OPERATORS - ALL TYPES

### Arithmetic Operators Complete

```
OPERATOR  NAME           EXAMPLE      RESULT
────────────────────────────────────────────
+         Addition       10 + 3       13
-         Subtraction    10 - 3       7
*         Multiplication 10 * 3       30
/         Division       10 / 3       3.333...
//        Floor Division 10 // 3      3
%         Modulo         10 % 3       1
**        Exponent       10 ** 3      1000
```

**Detailed Examples:**

```python
# Addition
print(10 + 5)         # 15
print(10 + 3.5)       # 13.5
print("Hello" + " World")  # "Hello World" (concatenation)

# Subtraction
print(10 - 3)         # 7
print(10 - 15)        # -5

# Multiplication
print(4 * 5)          # 20
print(3.5 * 2)        # 7.0
print("Ha" * 3)       # "HaHaHa" (repeat string)

# Division (always returns float)
print(10 / 2)         # 5.0
print(10 / 3)         # 3.333...
print(10 / 0)         # ❌ ZeroDivisionError

# Floor Division (returns int)
print(10 // 3)        # 3
print(-10 // 3)       # -4 (rounds down, not toward zero)

# Modulo (remainder)
print(10 % 3)         # 1
print(10 % 2)         # 0
print(10 % 0)         # ❌ ZeroDivisionError

# Practical modulo uses:
# Check if even
if number % 2 == 0:
    print("Even")

# Cycle through list
index = 5
items = [1, 2, 3]
print(items[5 % 3])   # items[2] = 3

# Exponent
print(2 ** 8)         # 256
print(4 ** 0.5)       # 2.0 (square root)
print((-1) ** 0.5)    # Complex number!
```

### Comparison Operators

```
OPERATOR  MEANING             EXAMPLE    RESULT
────────────────────────────────────────────────
==        Equal to           10 == 10   True
!=        Not equal to       10 != 5    True
>         Greater than       10 > 5     True
<         Less than          10 < 5     False
>=        Greater/equal      10 >= 10   True
<=        Less/equal         10 <= 5    False
is        Same object        x is y     (identity)
is not    Different object   x is not y
in        Contains           "a" in "abc" True
not in    Doesn't contain    "x" in "abc" False
```

**Important Differences:**

```python
# == vs is
a = [1, 2, 3]
b = [1, 2, 3]

print(a == b)    # True (same content)
print(a is b)    # False (different objects in memory)

# Use == for values, is for identity

# String comparison
print("apple" == "apple")      # True
print("apple" < "banana")      # True (alphabetical)
print("Apple" < "apple")       # True (uppercase comes first)

# Chained comparisons
age = 25
if 18 <= age <= 65:
    print("Working age")  # Output: Working age

# Equivalent to:
if age >= 18 and age <= 65:
    print("Working age")
```

### Logical Operators

```
OPERATOR  DESCRIPTION                  TRUTH TABLE
──────────────────────────────────────────────────
and       Both must be True           T and T = T
                                      T and F = F
                                      F and T = F
                                      F and F = F

or        At least one must be True   T or T = T
                                      T or F = T
                                      F or T = T
                                      F or F = F

not       Reverses True/False         not T = F
                                      not F = T
```

**Examples:**

```python
# AND
age = 25
has_license = True
if age >= 18 and has_license:
    print("Can drive")  # Output: Can drive

# OR
day = "Saturday"
if day == "Saturday" or day == "Sunday":
    print("Weekend!")  # Output: Weekend!

# NOT
is_admin = False
if not is_admin:
    print("Not admin")  # Output: Not admin

# Complex logic
age = 30
income = 50000
credit_score = 700

if (age >= 21 and income > 30000) or credit_score > 750:
    print("Loan approved")  # Output: Loan approved
```

### Short-Circuit Evaluation

```python
# AND: if first is False, second not evaluated
def print_and_return():
    print("Called")
    return True

# This prints because 5 > 0 is True
result = (5 > 0) and print_and_return()  # Prints "Called"

# This doesn't print because 5 < 0 is False
result = (5 < 0) and print_and_return()  # Doesn't print

# Practical use: safe access
if user and user.is_active:  # Only checks is_active if user exists
    print("Active user")
```

### Assignment Operators

```
OPERATOR  EQUIVALENT        EXAMPLE
─────────────────────────────────────
=         Assignment        x = 10
+=        Add and assign    x += 5    →  x = x + 5
-=        Subtract assign   x -= 3    →  x = x - 3
*=        Multiply assign   x *= 2    →  x = x * 2
/=        Divide assign     x /= 4    →  x = x / 4
//=       Floor div assign  x //= 3   →  x = x // 3
%=        Modulo assign     x %= 2    →  x = x % 2
**=       Exponent assign   x **= 2   →  x = x ** 2
```

**Examples:**

```python
x = 10

x += 5   # x = 15
x -= 3   # x = 12
x *= 2   # x = 24
x /= 3   # x = 8.0
x //= 2  # x = 4.0
x %= 3   # x = 1.0
x **= 2  # x = 1.0

# String
text = "Hello"
text += " World"  # "Hello World"

# List
numbers = [1, 2]
numbers += [3, 4]  # [1, 2, 3, 4]
```

### Membership Operators (in / not in)

```python
# Check in string
text = "Python"
print("P" in text)       # True
print("xyz" in text)     # False
print("Py" in text)      # True (substring)

# Check in list
numbers = [1, 2, 3, 4, 5]
print(3 in numbers)      # True
print(10 in numbers)     # False

# Check not in
print("x" not in text)   # True

# Real use: email validation
email = "user@example.com"
if "@" in email and "." in email:
    print("Might be valid email")
```

### Operator Precedence (CRITICAL)

```
PRECEDENCE (highest to lowest):
1. ()               Parentheses
2. **              Exponentiation
3. +x, -x, ~x      Unary operators
4. *, /, //, %     Multiplication/Division
5. +, -            Addition/Subtraction
6. <, <=, >, >=    Comparisons
7. ==, !=          Equality
8. is, is not      Identity
9. in, not in      Membership
10. not            Logical NOT
11. and            Logical AND
12. or             Logical OR
```

**Examples:**

```python
# Without understanding precedence
print(2 + 3 * 4)        # 14, NOT 20!
# Multiplication first: 3 * 4 = 12
# Then addition: 2 + 12 = 14

# Use parentheses for clarity
print((2 + 3) * 4)      # 20

# Comparison chains
age = 25
if 18 < age < 65:       # Checks both conditions
    print("Working age")  # Output: Working age

# Logic operators
if (age > 18) and (salary > 30000) or (credit_score > 750):
    print("Loan approved")
# Parsed as: ((age > 18) and (salary > 30000)) or (credit_score > 750)
```

---

## <a id="section-25"></a> 2.5 INPUT & USER INTERACTION

### The input() Function Deep Dive

#### What input() Does

```
USER KEYBOARD                    PYTHON                OUTPUT
──────────────────────────────────────────────────────────────
Types: "Chandresh"  ─────→  input() reads  ────→  Returns "Chandresh"
                            Waits for Enter        (as a STRING!)
                            Stores in variable
```

#### input() Return Type (CRITICAL)

```python
# input() ALWAYS returns a STRING, even if user enters numbers

# User enters: 20
age_text = input("Age: ")
print(type(age_text))  # <class 'str'>
print(age_text + 5)    # ❌ ERROR: can't add int to str

# CORRECT: Convert first
age_number = int(input("Age: "))
print(type(age_number))  # <class 'int'>
print(age_number + 5)    # ✅ Works, result is 25
```

#### Complete input() Examples

```python
# Example 1: Simple text input
name = input("What is your name? ")
print(f"Hello, {name}!")

# Example 2: Number input with conversion
age = int(input("Enter your age: "))
birth_year = 2024 - age
print(f"Born in: {birth_year}")

# Example 3: Multiple inputs
first_name = input("First name: ")
last_name = input("Last name: ")
full_name = f"{first_name} {last_name}"
print(f"Full name: {full_name}")

# Example 4: Float input
price = float(input("Enter price: "))
tax = price * 0.18
total = price + tax
print(f"Total with tax: {total:.2f}")

# Example 5: Input from comma-separated values
values = input("Enter numbers (comma-separated): ").split(",")
numbers = [int(x) for x in values]  # Convert each to int
print(f"Sum: {sum(numbers)}")
```

#### Professional Input Handling

```python
# Bad: No validation
age = int(input("Age: "))  # Crashes if user enters "abc"

# Good: With error handling
try:
    age = int(input("Age: "))
except ValueError:
    print("Please enter a valid number")
    age = 0

# Better: With loop until valid
while True:
    try:
        age = int(input("Age: "))
        if 0 <= age <= 150:
            break
        else:
            print("Age must be 0-150")
    except ValueError:
        print("Please enter a valid number")

print(f"You are {age} years old")
```

#### Input with Default Values

```python
# Prompt with hint about default
country = input("Country (default: India): ")
if not country:  # Empty string is falsy
    country = "India"
print(f"Country: {country}")

# Using or operator
country = input("Country (default: India): ") or "India"
print(f"Country: {country}")
```

#### Multi-line Input

```python
# Getting multiple lines
print("Enter your address (press Enter twice when done):")
address_lines = []
while True:
    line = input()
    if not line:
        break
    address_lines.append(line)
address = "\n".join(address_lines)
print("Your address:")
print(address)
```

---

## <a id="section-26"></a> 2.6 STRING METHODS - 30+ METHODS

### Complete String Methods Reference

I've already covered 20+ methods earlier. Here are the remaining ones plus advanced usage:

#### Advanced Methods

```python
# partition() - split into 3 parts
text = "hello@example.com"
before, sep, after = text.partition("@")
print(before)  # "hello"
print(after)   # "example.com"

# rpartition() - from right
text = "a.b.c.d"
before, sep, after = text.rpartition(".")
print(after)   # "d"

# translate() - replace multiple characters
text = "hello"
translation = str.maketrans("helo", "1234")
print(text.translate(translation))  # "13224"

# encode() - convert to bytes
text = "Hello"
encoded = text.encode("utf-8")
print(encoded)  # b'Hello'
print(type(encoded))  # <class 'bytes'>

# Decode (bytes to string)
decoded = b'Hello'.decode("utf-8")
print(decoded)  # "Hello"
```

#### Method Chaining

```python
# You can chain methods (one after another)
text = "  Hello World  "

# Without chaining
text = text.strip()     # "Hello World"
text = text.lower()     # "hello world"
text = text.replace(" ", "-")  # "hello-world"

# With chaining (same result)
result = text.strip().lower().replace(" ", "-")
print(result)  # "hello-world"

# Real world: cleaning user input
email = input("Email: ").strip().lower()
# Automatically removes spaces and normalizes case
```

---

# PART 3: ERROR MASTERY

## <a id="section-31"></a> 3.1 ALL 25 COMMON ERRORS WITH SOLUTIONS

### Syntax Errors (Caught Before Running)

#### ERROR 1: Missing Colon

```python
# ❌ WRONG
if age > 18
    print("Adult")
# SyntaxError: invalid syntax (: expected after if)

# ✅ CORRECT
if age > 18:
    print("Adult")

# All colon-requiring statements:
if condition:      # if needs :
    pass
elif condition:    # elif needs :
    pass
else:              # else needs :
    pass
for item in list:  # for needs :
    pass
while condition:   # while needs :
    pass
def function():    # def needs :
    pass
class MyClass:     # class needs :
    pass
try:               # try needs :
    pass
except:            # except needs :
    pass
```

#### ERROR 2: Incorrect Indentation

```python
# ❌ WRONG
if age > 18:
print("Adult")  # Not indented!
# IndentationError: expected an indented block

# ✅ CORRECT
if age > 18:
    print("Adult")  # 4 spaces or 1 tab

# Python uses indentation to define blocks
# MUST be consistent (4 spaces = Python standard)
```

#### ERROR 3: Missing Parentheses

```python
# ❌ WRONG (Python 2 syntax)
print "Hello"
# SyntaxError: invalid syntax

# ✅ CORRECT (Python 3)
print("Hello")

# print is a FUNCTION in Python 3, needs ()
```

#### ERROR 4: Mismatched Quotes

```python
# ❌ WRONG
text = "Hello'  # Opens with " closes with '
# SyntaxError: EOL while scanning string literal

# ✅ CORRECT
text = "Hello"  # Both double
text = 'Hello'  # Both single
text = """Hello"""  # Both triple

# Quotes must match!
```

#### ERROR 5: Missing Closing Bracket

```python
# ❌ WRONG
print("Hello"  # Missing )
# SyntaxError: '(' was never closed

# ✅ CORRECT
print("Hello")

# TIP: Count your brackets
# ( → requires )
# [ → requires ]
# { → requires }
```

#### ERROR 6: Using Python Keywords as Variables

```python
# ❌ WRONG
class = "Physics"   # class is a keyword
if = 5              # if is a keyword
def = 10            # def is a keyword
import = "module"   # import is a keyword

# ✅ CORRECT
my_class = "Physics"
my_if = 5
my_def = 10
my_import = "module"

# Python keywords you can't use as variable names:
# and, or, not, if, elif, else, while, for, break, continue
# def, class, return, import, from, as, try, except, finally
# with, pass, raise, assert, yield, lambda, is, in, None, True, False
```

#### ERROR 7: Invalid Variable Name

```python
# ❌ WRONG
2name = "invalid"      # Starts with number
my-var = 5             # Hyphen not allowed
my var = 10            # Space not allowed
my!var = 20            # Exclamation not allowed

# ✅ CORRECT
name2 = "valid"
my_var = 5
myVar = 10  # camelCase also works
_my_var = 20

# Variable names:
# - Start with letter or underscore
# - Continue with letters, numbers, underscores
# - Case-sensitive (name ≠ Name)
```

#### ERROR 8: Tab vs Space Mixing

```python
# ❌ WRONG (mixing tabs and spaces)
if True:
    print("A")  # 4 spaces
	print("B")  # tab character
# TabError: inconsistent use of tabs and spaces

# ✅ CORRECT (all spaces)
if True:
    print("A")
    print("B")

# RULE: Use 4 spaces (not tabs)
# Set VS Code: "editor.insertSpaces": true
```

### Runtime Errors (Program Crashes While Running)

#### ERROR 9: NameError

```python
# ❌ WRONG
print(name)  # name doesn't exist
# NameError: name 'name' is not defined

# ✅ CORRECT
name = "Bob"
print(name)

# CAUSES:
# 1. Using variable before defining it
# 2. Typo in variable name
# 3. Variable in wrong scope (local vs global)
```

#### ERROR 10: TypeError - Wrong Type

```python
# ❌ WRONG 1: Adding incompatible types
result = "10" + 20  # Can't add string and int
# TypeError: can only concatenate str (not "int") to str

# ✅ CORRECT 1:
result = "10" + str(20)  # Convert to same type
result = int("10") + 20  # Convert to same type

# ❌ WRONG 2: Calling non-callable
value = 5
value()  # Can't call a number
# TypeError: 'int' object is not callable

# ✅ CORRECT 2:
value = 5  # Don't call it

# ❌ WRONG 3: Wrong method on wrong type
numbers = [1, 2, 3]
result = numbers.upper()  # Lists don't have upper()
# AttributeError: 'list' object has no attribute 'upper'

# ✅ CORRECT 3:
text = "hello"
result = text.upper()  # Strings have upper()
```

#### ERROR 11: ValueError - Wrong Value

```python
# ❌ WRONG
age = int("abc")  # Can't convert "abc" to int
# ValueError: invalid literal for int() with base 10: 'abc'

# ✅ CORRECT 1: Validate first
age_text = input("Age: ")
if age_text.isdigit():
    age = int(age_text)
else:
    print("Please enter a number")

# ✅ CORRECT 2: Use try-except
try:
    age = int(input("Age: "))
except ValueError:
    print("Invalid number")
    age = 0
```

#### ERROR 12: IndexError

```python
# ❌ WRONG
text = "Hello"
print(text[10])  # Index 10 doesn't exist!
# IndexError: string index out of range

# ✅ CORRECT
print(text[0])   # Valid index (0-4 for "Hello")
print(text[-1])  # Valid (last character)

# Check length first:
if len(text) > 10:
    print(text[10])
else:
    print("Index out of range")

# For lists:
numbers = [1, 2, 3]
print(numbers[5])   # ❌ IndexError
print(numbers[2])   # ✅ OK (0, 1, 2 are valid)
```

#### ERROR 13: KeyError (Dictionaries)

```python
# ❌ WRONG
person = {"name": "Alice", "age": 25}
print(person["city"])  # Key doesn't exist
# KeyError: 'city'

# ✅ CORRECT 1: Check key exists
if "city" in person:
    print(person["city"])

# ✅ CORRECT 2: Use get() with default
print(person.get("city", "Unknown"))  # Returns "Unknown"

# ✅ CORRECT 3: Use try-except
try:
    print(person["city"])
except KeyError:
    print("City not found")
```

#### ERROR 14: ZeroDivisionError

```python
# ❌ WRONG
result = 10 / 0  # Can't divide by zero
# ZeroDivisionError: division by zero

# ✅ CORRECT
denominator = 2
if denominator != 0:
    result = 10 / denominator
else:
    print("Cannot divide by zero")

# Modulo by zero also fails:
print(10 % 0)  # ❌ ZeroDivisionError
```

#### ERROR 15: AttributeError

```python
# ❌ WRONG 1: Wrong method name/typo
text = "hello"
print(text.Upper())  # Capital U
# AttributeError: 'str' object has no attribute 'Upper'

# ✅ CORRECT 1:
print(text.upper())  # Lowercase u

# ❌ WRONG 2: Accessing non-existent attribute
person = {"name": "Alice"}
print(person.age)  # Dicts don't have dot notation attributes
# AttributeError: 'dict' object has no attribute 'age'

# ✅ CORRECT 2:
print(person["age"])  # Use brackets for dicts
# Or use get():
print(person.get("age"))
```

#### ERROR 16: AssertionError

```python
# ❌ WRONG
assert False, "This will always fail"
# AssertionError: This will always fail

# ✅ CORRECT: Use assertions for debugging
age = 20
assert age >= 0, "Age cannot be negative"  # Passes
assert age <= 120, "Age too high"           # Passes
```

#### ERROR 17: ImportError

```python
# ❌ WRONG
import nonexistent_module
# ModuleNotFoundError: No module named 'nonexistent_module'

# ✅ CORRECT 1: Import existing module
import random

# ✅ CORRECT 2: Install if needed
# pip install module_name
```

#### ERROR 18: RecursionError

```python
# ❌ WRONG: Infinite recursion
def bad_function():
    bad_function()  # Calls itself endlessly

bad_function()
# RecursionError: maximum recursion depth exceeded

# ✅ CORRECT: Base case stops recursion
def factorial(n):
    if n <= 1:
        return 1  # Base case
    return n * factorial(n - 1)  # Recursive case
```

#### ERROR 19: FileNotFoundError

```python
# ❌ WRONG
file = open("nonexistent.txt")  # File doesn't exist
# FileNotFoundError: [Errno 2] No such file or directory

# ✅ CORRECT 1: Check if file exists
import os
if os.path.exists("myfile.txt"):
    file = open("myfile.txt")

# ✅ CORRECT 2: Use try-except
try:
    file = open("myfile.txt")
except FileNotFoundError:
    print("File not found")
```

#### ERROR 20: UnboundLocalError

```python
# ❌ WRONG
x = 10

def my_function():
    print(x)  # x not defined locally
    x = 20    # But defined later (makes it local)

my_function()
# UnboundLocalError: local variable 'x' referenced before assignment

# ✅ CORRECT 1: Use global keyword
x = 10

def my_function():
    global x
    print(x)  # Now x refers to global
    x = 20

# ✅ CORRECT 2: Don't redefine local with same name
x = 10

def my_function():
    local_x = 20  # Different name
    print(x)      # Use global x
```

#### ERROR 21: MemoryError

```python
# ❌ WRONG: Creating huge list
huge_list = list(range(10**9))  # Too much memory
# MemoryError

# ✅ CORRECT: Use generator or process in chunks
for i in range(10**9):  # Generator, not list
    process(i)
```

#### ERROR 22: OverflowError

```python
# ❌ WRONG: Number too large
result = 10 ** 100000  # VERY large
# Might cause OverflowError in some cases

# ✅ CORRECT: Python handles big integers
result = 10 ** 1000  # Python handles this fine
print(result)  # Shows huge number
```

#### ERROR 23: StopIteration

```python
# ❌ WRONG: Using next() when no items
iterator = iter([])
next(iterator)  # No items!
# StopIteration

# ✅ CORRECT: Check if items exist
iterator = iter([1, 2, 3])
try:
    value = next(iterator)
except StopIteration:
    print("No more items")
```

#### ERROR 24: IndentationError (Different From TabError)

```python
# ❌ WRONG
if True:
  print("A")   # 2 spaces
    print("B") # 4 spaces - Inconsistent!
# IndentationError: unexpected indent

# ✅ CORRECT
if True:
    print("A")   # 4 spaces
    print("B")   # 4 spaces
```

#### ERROR 25: SyntaxError - Invalid Syntax (Catch-All)

```python
# Various syntax errors:

# ❌ Wrong operator placement
x = + * 5
# SyntaxError: invalid syntax

# ❌ Missing operator
x = 5 3
# SyntaxError: invalid syntax

# ❌ Wrong keyword usage
my_list = [1, 2, 3]
for in my_list:  # Missing 'item'
    print(item)
# SyntaxError: invalid syntax
```

---

## <a id="section-32"></a> 3.2 DEBUGGING STRATEGIES LIKE A SENIOR

### Technique 1: Print Debugging (Most Common)

```python
# Problem: Variable has wrong value
name = "  Chandresh  "
age = int("20")
result = f"{name} is {age}"
print(result)  # "  Chandresh   is 20" (extra spaces!)

# SOLUTION: Add debug prints
name = "  Chandresh  "
print(f"DEBUG: name = '{name}'")  # Shows the spaces!

age = int("20")
print(f"DEBUG: age = {age}")

result = f"{name} is {age}"
print(f"DEBUG: result = '{result}'")

# FIX: Strip the whitespace
name = "  Chandresh  ".strip()
print(result)  # "Chandresh is 20" (correct!)
```

### Technique 2: Error Message Reading

```
Error: TypeError: unsupported operand type(s) for +: 'int' and 'str'

BREAK IT DOWN:
1. TypeError         ← Type mismatch error
2. unsupported      ← Operation not allowed
3. operand type(s)  ← Data type issue
4. for +            ← Addition operator
5. 'int' and 'str'  ← Mixing int and string

SOLUTION: Convert to same type
```

### Technique 3: Check Assumptions

```python
# Assumption: input() returns a number
age = input("Age: ")

# Check assumption
print(type(age))  # <class 'str'> - not an int!

# Fix
age = int(input("Age: "))
print(type(age))  # <class 'int'> - correct!
```

### Technique 4: Isolate the Problem

```python
# Complex code with error
x = 10
y = 20
z = x + y
result = z / 0  # Where's the error?

# Isolate each part
x = 10
print(f"x = {x}")  # OK

y = 20
print(f"y = {y}")  # OK

z = x + y
print(f"z = {z}")  # OK

result = z / 0  # ← ERROR IS HERE
print(f"result = {result}")  # Won't reach here
```

### Technique 5: Use a Debugger

```python
# VS Code Python Debugger
# Set breakpoint (click line number)
# Debug → Start Debugging
# Step through code line by line
# Inspect variables at each step
```

### Technique 6: Write Tests

```python
# Function to test
def calculate_age(birth_year):
    return 2024 - birth_year

# Test cases
assert calculate_age(2004) == 20, "Born 2004 should be 20"
assert calculate_age(2000) == 24, "Born 2000 should be 24"
assert calculate_age(1990) == 34, "Born 1990 should be 34"

print("All tests passed!")
```

---

## <a id="section-33"></a> 3.3 ERROR HANDLING BEST PRACTICES

### Basic Try-Except

```python
try:
    age = int(input("Age: "))
except ValueError:
    print("Please enter a valid number")
    age = 0
```

### Multiple Except Blocks

```python
try:
    # Multiple things can go wrong
    file = open("data.txt")
    age = int(file.read())
except FileNotFoundError:
    print("File not found")
except ValueError:
    print("Invalid age in file")
except Exception as e:
    print(f"Unexpected error: {e}")
```

### Try-Except-Else-Finally

```python
try:
    age = int(input("Age: "))
except ValueError:
    print("Invalid number")
else:
    print(f"Age: {age}")  # Only runs if no error
finally:
    print("Done!")  # Runs regardless
```

---

# PART 4: PROFESSIONAL PRACTICES

## <a id="section-41"></a> 4.1 HOW SENIOR ENGINEERS CODE

### Principle 1: Clarity Over Cleverness

```python
# ❌ CLEVER (confusing)
x = [n**2 for n in range(100) if n%2==0]

# ✅ CLEAR (everyone understands)
even_numbers = []
for n in range(100):
    if n % 2 == 0:  # Is even
        even_numbers.append(n ** 2)
```

### Principle 2: Fail Fast

```python
# ❌ WEAK (processes wrong data silently)
def process_user(age):
    # ... processes wrong age later ...
    if age < 0:  # Check too late!
        return None

# ✅ STRONG (validate immediately)
def process_user(age):
    if age < 0:
        raise ValueError("Age cannot be negative")
    # ... now we know age is valid ...
```

### Principle 3: DRY (Don't Repeat Yourself)

```python
# ❌ WRONG (repeated code)
print("Name:", user1_name)
print("Age:", user1_age)
print("Name:", user2_name)
print("Age:", user2_age)

# ✅ CORRECT (reusable function)
def print_user(name, age):
    print("Name:", name)
    print("Age:", age)

print_user(user1_name, user1_age)
print_user(user2_name, user2_age)
```

### Principle 4: Meaningful Names

```python
# ❌ BAD
x = input()
y = int(x)
z = y * 100
if z > 80:
    print("Pass")

# ✅ GOOD
student_name = input("Enter name: ")
test_score = int(input("Enter score: "))
percentage = test_score * 100
if percentage > 80:
    print("Pass")
```

### Principle 5: Comments (Strategic)

```python
# ❌ USELESS COMMENTS
x = 10  # Set x to 10
print(x)  # Print x

# ✅ USEFUL COMMENTS
# Maximum login attempts before account lockout
MAX_ATTEMPTS = 10

# Calculate compound interest (A = P(1 + r/n)^nt)
interest = principal * (1 + rate) ** years
```

### Principle 6: Defensive Programming

```python
# Assume everything can go wrong

# User input
email = input("Email: ").strip().lower()  # Clean immediately

# Validation
if "@" not in email or "." not in email:
    print("Invalid email")
else:
    process_email(email)

# Edge cases
if user and user.is_active and user.email:  # Check all conditions
    send_email(user.email)
```

---

## <a id="section-42"></a> 4.2 CODE QUALITY & BEST PRACTICES

### Style Guide (PEP 8)

```python
# Variable names: lowercase_with_underscores
student_name = "Alice"

# Class names: PascalCase
class StudentInfo:
    pass

# Constants: UPPERCASE
MAX_STUDENTS = 50

# Private variables: leading underscore
_internal_value = 42

# Two blank lines between functions
def function1():
    pass


def function2():
    pass

# Limit line length to 79 characters
# Use \ to continue long lines
long_result = very_long_variable1 + very_long_variable2 + \
    very_long_variable3

# Spaces around operators
x = 10 + 20  # ✅
x=10+20     # ❌
```

### Documentation

```python
def calculate_grade(score):
    """
    Convert numeric score to letter grade.
    
    Args:
        score: Integer between 0-100
        
    Returns:
        String: 'A', 'B', 'C', 'D', or 'F'
        
    Raises:
        ValueError: If score not 0-100
    """
    if not isinstance(score, (int, float)) or score < 0 or score > 100:
        raise ValueError("Score must be 0-100")
    
    if score >= 90:
        return 'A'
    # ... more grades ...
```

---

## <a id="section-43"></a> 4.3 PERFORMANCE OPTIMIZATION DAY 1

### Don't Pre-Optimize

```python
# ❌ Over-optimized for a simple problem
# Uses complex logic when simple works fine
result = 10 if x > 5 else (20 if x > 3 else 30)

# ✅ Simple and clear
if x > 5:
    result = 10
elif x > 3:
    result = 20
else:
    result = 30

# Rule: Write clear code first, optimize later if needed
```

### Efficiency Concepts (Awareness Only)

```python
# ❌ Inefficient: Creating list in loop
result = []
for i in range(10):
    result = result + [i]  # Creates new list each time!

# ✅ Efficient: Append to list
result = []
for i in range(10):
    result.append(i)  # Add to existing list

# ✅ Best: List comprehension
result = [i for i in range(10)]
```

---

# PART 5: HANDS-ON LEARNING

## <a id="section-51"></a> 5.1 TEN COMPLETE PROJECTS

### PROJECT 1: Personal Information System

```python
"""
Project 1: Personal Information System
Demonstrates: input(), string methods, formatting, basic logic
Difficulty: Beginner
Time: 15 minutes
"""

print("=" * 50)
print("PERSONAL INFORMATION SYSTEM")
print("=" * 50)

# Get information with validation
while True:
    name = input("\nEnter your full name: ").strip().title()
    if name and all(c.isalpha() or c.isspace() for c in name):
        break
    print("Invalid name! Use letters only.")

while True:
    try:
        age = int(input("Enter your age: "))
        if 0 <= age <= 150:
            break
        else:
            print("Age must be 0-150")
    except ValueError:
        print("Please enter a valid number")

while True:
    email = input("Enter your email: ").strip().lower()
    if "@" in email and "." in email:
        break
    print("Invalid email format")

city = input("Enter your city: ").strip().title()
country = input("Enter your country: ").strip().title()

# Calculate derived information
birth_year = 2024 - age
years_to_retirement = 60 - age if age < 60 else 0

# Display formatted output
print("\n" + "=" * 50)
print("YOUR INFORMATION")
print("=" * 50)
print(f"Name: {name.upper()}")
print(f"Age: {age} years old")
print(f"Birth Year: {birth_year}")
print(f"Email: {email}")
print(f"Location: {city}, {country}")
print("-" * 50)

if years_to_retirement > 0:
    print(f"Years until retirement: {years_to_retirement}")
else:
    print("Retirement age reached!")

print("=" * 50)

# Save to file
try:
    with open("user_info.txt", "w") as file:
        file.write(f"Name: {name}\n")
        file.write(f"Age: {age}\n")
        file.write(f"Email: {email}\n")
        file.write(f"Location: {city}, {country}\n")
    print("\n✓ Information saved to user_info.txt")
except Exception as e:
    print(f"\n✗ Error saving file: {e}")
```

**Output Example:**
```
==================================================
PERSONAL INFORMATION SYSTEM
==================================================

Enter your full name: chandresh singh
Enter your age: 20
Enter your email: chandresh@example.com
Enter your city: mumbai
Enter your country: india

==================================================
YOUR INFORMATION
==================================================
Name: CHANDRESH SINGH
Age: 20 years old
Birth Year: 2004
Email: chandresh@example.com
Location: Mumbai, India
--------------------------------------------------
Years until retirement: 40
==================================================

✓ Information saved to user_info.txt
```

### PROJECT 2: Advanced Calculator

```python
"""
Project 2: Advanced Calculator
Demonstrates: Float/int operations, error handling, formatted output
Difficulty: Beginner
Time: 20 minutes
"""

def get_valid_number(prompt):
    """Get valid number from user"""
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Invalid! Please enter a number.")

def calculate():
    """Main calculation function"""
    print("\n" + "=" * 40)
    print("ADVANCED CALCULATOR")
    print("=" * 40)
    
    num1 = get_valid_number("\nEnter first number: ")
    num2 = get_valid_number("Enter second number: ")
    
    print("\nOperations:")
    print("1. Addition (+)")
    print("2. Subtraction (-)")
    print("3. Multiplication (*)")
    print("4. Division (/)")
    print("5. Floor Division (//)")
    print("6. Modulo (%)")
    print("7. Exponentiation (**)")
    
    operation = input("\nSelect operation (1-7): ").strip()
    
    # Define operations
    operations = {
        "1": (lambda a, b: a + b, "Addition", "+"),
        "2": (lambda a, b: a - b, "Subtraction", "-"),
        "3": (lambda a, b: a * b, "Multiplication", "*"),
        "4": (lambda a, b: a / b if b != 0 else "ERROR", "Division", "/"),
        "5": (lambda a, b: a // b if b != 0 else "ERROR", "Floor Division", "//"),
        "6": (lambda a, b: a % b if b != 0 else "ERROR", "Modulo", "%"),
        "7": (lambda a, b: a ** b, "Exponentiation", "**"),
    }
    
    if operation not in operations:
        print("Invalid operation!")
        return
    
    func, op_name, op_symbol = operations[operation]
    result = func(num1, num2)
    
    # Display results
    print("\n" + "-" * 40)
    print(f"Operation: {op_name}")
    print(f"Calculation: {num1} {op_symbol} {num2}")
    
    if isinstance(result, str):  # ERROR
        print(f"Result: Cannot divide by zero")
    else:
        if isinstance(result, float) and result == int(result):
            print(f"Result: {int(result)}")
        else:
            print(f"Result: {result:.6f}")
    
    print("-" * 40)

# Run calculator
calculate()
```

**Output Example:**
```
========================================
ADVANCED CALCULATOR
========================================

Enter first number: 15
Enter second number: 3

Operations:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Floor Division (//)
6. Modulo (%)
7. Exponentiation (**)

Select operation (1-7): 4

----------------------------------------
Operation: Division
Calculation: 15.0 / 3.0
Result: 5.000000
----------------------------------------
```

### PROJECT 3: Grade Calculator with Statistics

```python
"""
Project 3: Grade Calculator with Statistics
Demonstrates: Lists (preview), loops (preview), calculations, string methods
Difficulty: Beginner-Intermediate
Time: 25 minutes
"""

def get_valid_grade(subject):
    """Get and validate grade for a subject"""
    while True:
        try:
            marks = float(input(f"{subject} marks (0-100): "))
            if 0 <= marks <= 100:
                return marks
            else:
                print("Marks must be 0-100")
        except ValueError:
            print("Invalid! Enter a number.")

def grade_to_letter(marks):
    """Convert marks to letter grade"""
    if marks >= 90:
        return "A"
    elif marks >= 80:
        return "B"
    elif marks >= 70:
        return "C"
    elif marks >= 60:
        return "D"
    else:
        return "F"

def grade_to_points(marks):
    """Convert marks to GPA points"""
    if marks >= 90:
        return 4.0
    elif marks >= 80:
        return 3.5
    elif marks >= 70:
        return 3.0
    elif marks >= 60:
        return 2.5
    else:
        return 0.0

# Main program
print("=" * 50)
print("GRADE CALCULATOR WITH STATISTICS")
print("=" * 50)

# Get student info
student_name = input("\nStudent name: ").strip().title()
roll_number = input("Roll number: ").strip()

# Define subjects
subjects = ["Math", "Science", "English", "History", "Geography"]

# Get marks for each subject
print("\nEnter marks for each subject:")
marks_list = []
for subject in subjects:
    marks = get_valid_grade(subject)
    marks_list.append(marks)

# Calculations
total_marks = sum(marks_list)
average_marks = total_marks / len(marks_list)
highest_marks = max(marks_list)
lowest_marks = min(marks_list)
overall_grade = grade_to_letter(average_marks)

# Calculate GPA
gpa_points = [grade_to_points(mark) for mark in marks_list]
gpa = sum(gpa_points) / len(gpa_points)

# Display detailed report
print("\n" + "=" * 50)
print("DETAILED REPORT")
print("=" * 50)
print(f"Student: {student_name}")
print(f"Roll Number: {roll_number}")
print("\n" + "-" * 50)
print("SUBJECT-WISE PERFORMANCE")
print("-" * 50)

for i, subject in enumerate(subjects):
    marks = marks_list[i]
    letter_grade = grade_to_letter(marks)
    status = "✓ PASS" if marks >= 40 else "✗ FAIL"
    print(f"{subject:12} {marks:6.1f}/100  Grade: {letter_grade}  {status}")

print("-" * 50)
print("OVERALL STATISTICS")
print("-" * 50)
print(f"Total Marks: {total_marks:.1f}/{len(subjects)*100}")
print(f"Average: {average_marks:.2f}")
print(f"Highest: {highest_marks:.1f}")
print(f"Lowest: {lowest_marks:.1f}")
print(f"Overall Grade: {overall_grade}")
print(f"GPA: {gpa:.2f}/4.0")

# Result summary
print("-" * 50)
if overall_grade in ["A", "B"]:
    print("✓ EXCELLENT PERFORMANCE!")
elif overall_grade == "C":
    print("✓ GOOD PERFORMANCE")
elif overall_grade == "D":
    print("⚠ SATISFACTORY PERFORMANCE")
else:
    print("✗ NEEDS IMPROVEMENT")
print("=" * 50)
```

**Output Example:**
```
==================================================
GRADE CALCULATOR WITH STATISTICS
==================================================

Student name: Chandresh Singh
Roll number: 001

Enter marks for each subject:
Math marks (0-100): 85
Science marks (0-100): 92
English marks (0-100): 78
History marks (0-100): 88
Geography marks (0-100): 95

==================================================
DETAILED REPORT
==================================================
Student: Chandresh Singh
Roll Number: 001

--------------------------------------------------
SUBJECT-WISE PERFORMANCE
--------------------------------------------------
Math          85.0/100  Grade: B  ✓ PASS
Science       92.0/100  Grade: A  ✓ PASS
English       78.0/100  Grade: C  ✓ PASS
History       88.0/100  Grade: B  ✓ PASS
Geography     95.0/100  Grade: A  ✓ PASS
--------------------------------------------------
OVERALL STATISTICS
--------------------------------------------------
Total Marks: 438.0/500
Average: 87.60
Highest: 95.0
Lowest: 78.0
Overall Grade: B
GPA: 3.60/4.0
--------------------------------------------------
✓ EXCELLENT PERFORMANCE!
==================================================
```

(Continuing with 7 more projects...)

### PROJECT 4: Temperature Unit Converter

```python
"""
Project 4: Temperature Unit Converter
Demonstrates: Math operations, f-strings, input validation
Difficulty: Beginner
Time: 15 minutes
"""

print("=" * 40)
print("TEMPERATURE CONVERTER")
print("=" * 40)

print("\nConversion options:")
print("1. Celsius to Fahrenheit")
print("2. Fahrenheit to Celsius")
print("3. Celsius to Kelvin")
print("4. Kelvin to Celsius")

choice = input("\nSelect conversion (1-4): ").strip()

try:
    if choice == "1":
        celsius = float(input("Enter Celsius: "))
        fahrenheit = (celsius * 9/5) + 32
        print(f"\n{celsius}°C = {fahrenheit:.2f}°F")
    
    elif choice == "2":
        fahrenheit = float(input("Enter Fahrenheit: "))
        celsius = (fahrenheit - 32) * 5/9
        print(f"\n{fahrenheit}°F = {celsius:.2f}°C")
    
    elif choice == "3":
        celsius = float(input("Enter Celsius: "))
        kelvin = celsius + 273.15
        print(f"\n{celsius}°C = {kelvin:.2f}K")
    
    elif choice == "4":
        kelvin = float(input("Enter Kelvin: "))
        celsius = kelvin - 273.15
        print(f"\n{kelvin}K = {celsius:.2f}°C")
    
    else:
        print("Invalid choice!")

except ValueError:
    print("Invalid temperature entered!")
```

### PROJECT 5: Password Strength Checker

```python
"""
Project 5: Password Strength Checker
Demonstrates: String methods, conditionals, error handling
Difficulty: Beginner
Time: 15 minutes
"""

def check_password_strength(password):
    """Analyze password and return strength level"""
    score = 0
    feedback = []
    
    # Length check
    if len(password) >= 8:
        score += 1
    else:
        feedback.append("- At least 8 characters")
    
    # Uppercase check
    if any(c.isupper() for c in password):
        score += 1
    else:
        feedback.append("- At least one uppercase letter")
    
    # Lowercase check
    if any(c.islower() for c in password):
        score += 1
    else:
        feedback.append("- At least one lowercase letter")
    
    # Digit check
    if any(c.isdigit() for c in password):
        score += 1
    else:
        feedback.append("- At least one digit")
    
    # Special character check
    special_chars = "!@#$%^&*()_+-=[]{}|;:,.<>?"
    if any(c in special_chars for c in password):
        score += 1
    else:
        feedback.append("- At least one special character")
    
    # Determine strength
    if score == 5:
        strength = "VERY STRONG"
        emoji = "🔒"
    elif score >= 4:
        strength = "STRONG"
        emoji = "🔐"
    elif score >= 3:
        strength = "MODERATE"
        emoji = "⚠️"
    elif score >= 2:
        strength = "WEAK"
        emoji = "🔓"
    else:
        strength = "VERY WEAK"
        emoji = "⚠️"
    
    return strength, emoji, feedback, score

# Main program
print("=" * 50)
print("PASSWORD STRENGTH CHECKER")
print("=" * 50)

password = input("\nEnter password: ")

strength, emoji, feedback, score = check_password_strength(password)

print(f"\nPassword Strength: {emoji} {strength} ({score}/5)")

if feedback:
    print("\nSuggestions for improvement:")
    for suggestion in feedback:
        print(suggestion)
else:
    print("\n✓ Excellent password! No improvements needed.")

print("=" * 50)
```

### PROJECT 6: Currency Converter

```python
"""
Project 6: Currency Converter
Demonstrates: Math operations, dictionaries (preview), formatted output
Difficulty: Beginner-Intermediate
Time: 20 minutes
Real World: Used in banking, travel apps, e-commerce
"""

# Currency rates (base: INR)
RATES = {
    "INR": 1.0,
    "USD": 0.012,
    "EUR": 0.011,
    "GBP": 0.0094,
    "JPY": 1.79,
    "AED": 0.044,
    "SGD": 0.016,
}

print("=" * 50)
print("PROFESSIONAL CURRENCY CONVERTER")
print("=" * 50)

print("\nAvailable currencies:")
for i, currency in enumerate(RATES.keys(), 1):
    print(f"  {i}. {currency}")

# Get amount
while True:
    try:
        amount = float(input("\nEnter amount: "))
        if amount < 0:
            print("Amount cannot be negative")
            continue
        break
    except ValueError:
        print("Invalid amount. Enter a number.")

# Get source currency
while True:
    from_currency = input("From currency (e.g., INR): ").upper().strip()
    if from_currency in RATES:
        break
    print(f"Invalid currency. Choose from: {', '.join(RATES.keys())}")

# Get target currency
while True:
    to_currency = input("To currency (e.g., USD): ").upper().strip()
    if to_currency in RATES:
        break
    print(f"Invalid currency. Choose from: {', '.join(RATES.keys())}")

# Convert: source → INR → target
amount_in_inr = amount / RATES[from_currency]
result = amount_in_inr * RATES[to_currency]

# Display result
print("\n" + "=" * 50)
print("CONVERSION RESULT")
print("=" * 50)
print(f"  Amount: {amount:,.2f} {from_currency}")
print(f"  Rate:   1 {from_currency} = {RATES[to_currency]/RATES[from_currency]:.6f} {to_currency}")
print(f"  Result: {result:,.4f} {to_currency}")
print("=" * 50)
print("Note: Rates are approximate. Use bank rates for actual transactions.")
```

**Output Example:**
```
==================================================
PROFESSIONAL CURRENCY CONVERTER
==================================================

Available currencies:
  1. INR
  2. USD
  3. EUR
  4. GBP
  5. JPY
  6. AED
  7. SGD

Enter amount: 10000
From currency (e.g., INR): INR
To currency (e.g., USD): USD

==================================================
CONVERSION RESULT
==================================================
  Amount: 10,000.00 INR
  Rate:   1 INR = 0.012000 USD
  Result: 120.0000 USD
==================================================
Note: Rates are approximate. Use bank rates for actual transactions.
```

---

### PROJECT 7: BMI Calculator with Health Report

```python
"""
Project 7: BMI Calculator with Full Health Report
Demonstrates: Math, formatted output, conditionals, input validation
Difficulty: Beginner-Intermediate
Time: 20 minutes
Real World: Used in every hospital, gym, and health app
"""

def calculate_bmi(weight_kg, height_m):
    """Calculate Body Mass Index"""
    return weight_kg / (height_m ** 2)

def get_bmi_category(bmi):
    """Return BMI category and health risk"""
    if bmi < 16.0:
        return "Severely Underweight", "HIGH RISK", "🔴"
    elif bmi < 18.5:
        return "Underweight", "MODERATE RISK", "🟡"
    elif bmi < 25.0:
        return "Normal Weight", "LOW RISK", "🟢"
    elif bmi < 30.0:
        return "Overweight", "MODERATE RISK", "🟡"
    elif bmi < 35.0:
        return "Obese Class I", "HIGH RISK", "🔴"
    elif bmi < 40.0:
        return "Obese Class II", "VERY HIGH RISK", "🔴"
    else:
        return "Obese Class III", "EXTREME RISK", "🔴"

def get_ideal_weight(height_m, gender):
    """Calculate ideal weight range using Devine formula"""
    if gender == "M":
        ideal = 50 + 2.3 * ((height_m * 100 / 2.54) - 60)
    else:
        ideal = 45.5 + 2.3 * ((height_m * 100 / 2.54) - 60)
    return max(0, ideal - 5), max(0, ideal + 5)

print("=" * 55)
print("       BMI CALCULATOR & HEALTH REPORT")
print("=" * 55)

# Get name
name = input("\nYour name: ").strip().title()

# Get gender
while True:
    gender = input("Gender (M/F): ").upper().strip()
    if gender in ["M", "F"]:
        break
    print("Enter M or F only.")

# Get age
while True:
    try:
        age = int(input("Age: "))
        if 2 <= age <= 120:
            break
        print("Age must be 2-120.")
    except ValueError:
        print("Enter a valid number.")

# Get weight
while True:
    try:
        weight = float(input("Weight (kg): "))
        if 2 <= weight <= 500:
            break
        print("Weight must be 2-500 kg.")
    except ValueError:
        print("Enter a valid number.")

# Get height
while True:
    try:
        height_cm = float(input("Height (cm): "))
        if 50 <= height_cm <= 250:
            height_m = height_cm / 100
            break
        print("Height must be 50-250 cm.")
    except ValueError:
        print("Enter a valid number.")

# Calculations
bmi = calculate_bmi(weight, height_m)
category, risk, emoji = get_bmi_category(bmi)
ideal_low, ideal_high = get_ideal_weight(height_m, gender)
weight_diff = weight - (ideal_low + ideal_high) / 2

# Generate health report
print("\n" + "=" * 55)
print(f"  HEALTH REPORT FOR {name.upper()}")
print("=" * 55)
print(f"  Age:        {age} years")
print(f"  Weight:     {weight:.1f} kg")
print(f"  Height:     {height_cm:.1f} cm ({height_m:.2f} m)")
print("-" * 55)
print(f"  BMI:        {bmi:.2f}")
print(f"  Category:   {emoji} {category}")
print(f"  Risk Level: {risk}")
print("-" * 55)
print(f"  Ideal Weight Range: {ideal_low:.1f} - {ideal_high:.1f} kg")

if weight_diff > 0:
    print(f"  Action:     Lose approx. {weight_diff:.1f} kg")
elif weight_diff < 0:
    print(f"  Action:     Gain approx. {abs(weight_diff):.1f} kg")
else:
    print(f"  Action:     Maintain current weight!")

print("-" * 55)
print("  RECOMMENDATIONS:")
if category == "Normal Weight":
    print("  ✓ Keep up your healthy lifestyle!")
    print("  ✓ Exercise 150 min/week")
    print("  ✓ Maintain balanced diet")
elif "Underweight" in category:
    print("  ⚠ Increase caloric intake gradually")
    print("  ⚠ Add protein-rich foods to diet")
    print("  ⚠ Consult a nutritionist")
else:
    print("  ⚠ Reduce caloric intake")
    print("  ⚠ Increase physical activity")
    print("  ⚠ Consult a doctor")
print("=" * 55)
print("  ⚕ Disclaimer: Consult a doctor for medical advice.")
print("=" * 55)
```

---

### PROJECT 8: Number Guessing Game (Advanced)

```python
"""
Project 8: Number Guessing Game
Demonstrates: Loops (preview), conditionals, string methods, input validation
Difficulty: Intermediate
Time: 25 minutes
Real World: Game logic - same used in actual games
"""

import random

def get_difficulty():
    """Let player choose difficulty level"""
    print("\nSelect difficulty:")
    print("  1. Easy   (1-50,  10 attempts)")
    print("  2. Medium (1-100, 7 attempts)")
    print("  3. Hard   (1-200, 5 attempts)")

    while True:
        choice = input("Your choice (1-3): ").strip()
        if choice == "1":
            return 50, 10, "Easy"
        elif choice == "2":
            return 100, 7, "Medium"
        elif choice == "3":
            return 200, 5, "Hard"
        else:
            print("Invalid. Enter 1, 2, or 3.")

def get_hint(guess, target, attempts_left):
    """Give hints based on how close guess is"""
    diff = abs(guess - target)
    if diff == 0:
        return "🎯 CORRECT!"
    elif diff <= 5:
        direction = "higher" if target > guess else "lower"
        return f"🔥 Very hot! Go {direction}!"
    elif diff <= 15:
        direction = "higher" if target > guess else "lower"
        return f"♨️  Hot! Go {direction}!"
    elif diff <= 30:
        direction = "higher" if target > guess else "lower"
        return f"🌤 Warm! Go {direction}!"
    else:
        direction = "higher" if target > guess else "lower"
        return f"🧊 Cold! Go {direction}!"

# Game intro
print("=" * 50)
print("   🎮 NUMBER GUESSING GAME")
print("=" * 50)

player_name = input("\nEnter your name: ").strip().title()
print(f"\nWelcome, {player_name}! Let's play!")

# Game setup
max_number, max_attempts, difficulty = get_difficulty()
target = random.randint(1, max_number)

print(f"\n[{difficulty}] I'm thinking of a number between 1 and {max_number}")
print(f"You have {max_attempts} attempts. Good luck!\n")

# Game loop
attempts_used = 0
won = False
guesses_history = []

while attempts_used < max_attempts:
    remaining = max_attempts - attempts_used
    print(f"Attempt {attempts_used + 1}/{max_attempts} ({remaining} left)")

    # Get guess
    while True:
        try:
            guess = int(input("Your guess: "))
            if 1 <= guess <= max_number:
                break
            print(f"Enter a number between 1 and {max_number}")
        except ValueError:
            print("Enter a valid number.")

    attempts_used += 1
    guesses_history.append(guess)

    # Get hint
    hint = get_hint(guess, target, remaining - 1)
    print(f"  {hint}")

    if guess == target:
        won = True
        break
    print()

# Game result
print("\n" + "=" * 50)
if won:
    score = max(0, 100 - (attempts_used - 1) * 15)
    print(f"🎉 CONGRATULATIONS, {player_name.upper()}!")
    print(f"You guessed {target} in {attempts_used} attempt(s)!")
    print(f"Score: {score}/100")
    if attempts_used == 1:
        print("⭐ PERFECT SCORE! First try!")
    elif attempts_used <= 3:
        print("⭐ Excellent!")
    else:
        print("Good job!")
else:
    print(f"💔 GAME OVER, {player_name}!")
    print(f"The number was: {target}")
    print(f"Your guesses were: {' → '.join(map(str, guesses_history))}")

print("=" * 50)
```

---

### PROJECT 9: Student Report Card Generator

```python
"""
Project 9: Student Report Card Generator
Demonstrates: Complex string formatting, multiple calculations, file output
Difficulty: Intermediate
Time: 30 minutes
Real World: Schools and coaching centers use these to generate reports
"""

def get_marks(subject, max_marks=100):
    while True:
        try:
            marks = float(input(f"  {subject} ({max_marks} marks): "))
            if 0 <= marks <= max_marks:
                return marks
            print(f"  Marks must be 0-{max_marks}")
        except ValueError:
            print("  Enter a valid number.")

def grade(percentage):
    if percentage >= 90: return "A+", "Outstanding"
    elif percentage >= 80: return "A", "Excellent"
    elif percentage >= 70: return "B+", "Very Good"
    elif percentage >= 60: return "B", "Good"
    elif percentage >= 50: return "C", "Average"
    elif percentage >= 40: return "D", "Pass"
    else: return "F", "Fail"

def rank_suffix(rank):
    if rank == 1: return "1st"
    elif rank == 2: return "2nd"
    elif rank == 3: return "3rd"
    else: return f"{rank}th"

print("=" * 60)
print("       STUDENT REPORT CARD GENERATOR")
print("=" * 60)

# School info
school = input("\nSchool name: ").strip().title()
academic_year = input("Academic year (e.g., 2024-25): ").strip()
cls = input("Class/Grade: ").strip()

# Student info
print("\nEnter student details:")
name = input("  Full name: ").strip().title()
roll = input("  Roll number: ").strip()
dob = input("  Date of birth (DD/MM/YYYY): ").strip()

# Subjects and marks
subjects_config = [
    ("Mathematics", 100),
    ("Science", 100),
    ("English", 100),
    ("Hindi", 100),
    ("Social Science", 100),
]

print("\nEnter marks for each subject:")
results = []
for subject, max_m in subjects_config:
    m = get_marks(subject, max_m)
    pct = (m / max_m) * 100
    g, desc = grade(pct)
    results.append({
        "subject": subject,
        "marks": m,
        "max": max_m,
        "percentage": pct,
        "grade": g,
        "desc": desc,
        "pass": pct >= 40
    })

# Summary calculations
total_marks = sum(r["marks"] for r in results)
total_max = sum(r["max"] for r in results)
overall_pct = (total_marks / total_max) * 100
overall_grade, overall_desc = grade(overall_pct)
all_passed = all(r["pass"] for r in results)

# Generate report card
line = "=" * 60
thin = "-" * 60

report = f"""
{line}
{school.center(60)}
{("Report Card - " + academic_year).center(60)}
{line}
{"Class: " + cls:<30}{"Roll No: " + roll:>30}
{"Name: " + name:<30}{"DOB: " + dob:>30}
{thin}
{"SUBJECT":<22} {"MAX":>5} {"MARKS":>7} {"  %":>6} {"GR":>4}  {"REMARKS":<15}
{thin}"""

for r in results:
    status = "✓" if r["pass"] else "✗"
    report += f"\n{r['subject']:<22} {r['max']:>5} {r['marks']:>7.1f} {r['percentage']:>6.1f}% {r['grade']:>4}  {r['desc']:<15} {status}"

report += f"""
{thin}
{"TOTAL":<22} {total_max:>5} {total_marks:>7.1f} {overall_pct:>6.1f}% {overall_grade:>4}  {overall_desc}
{line}
RESULT: {"PASS ✓" if all_passed else "FAIL ✗"}
Overall Performance: {overall_desc} ({overall_grade})
{line}
Class Teacher Signature: _______________   Principal Signature: _______________
{line}
Generated by: Student Report Card Generator | Python Project
"""

print(report)

# Save report
filename = f"report_{roll}_{name.replace(' ', '_')}.txt"
try:
    with open(filename, "w") as f:
        f.write(report)
    print(f"Report saved to: {filename}")
except Exception as e:
    print(f"Could not save: {e}")
```

---

### PROJECT 10: Personal Finance Tracker (Capstone Day 1 Project)

```python
"""
Project 10: Personal Finance Tracker (CAPSTONE)
Demonstrates: ALL Day 1 concepts combined
- Variables, data types, string methods
- Arithmetic operators, f-strings
- Input validation, error handling
- Formatted output, file saving
Difficulty: Intermediate-Hard
Time: 40 minutes
Real World: Banks and fintech apps build exactly this
This is your most impressive Day 1 project for your resume
"""

# ─── Constants ───────────────────────────────────────
CATEGORIES = {
    "1": "Food & Dining",
    "2": "Transport",
    "3": "Education",
    "4": "Entertainment",
    "5": "Shopping",
    "6": "Medical",
    "7": "Utilities",
    "8": "Other",
}

# ─── Helper Functions ─────────────────────────────────

def get_float(prompt, min_val=0):
    """Get a valid float from user"""
    while True:
        try:
            val = float(input(prompt))
            if val >= min_val:
                return val
            print(f"Value must be >= {min_val}")
        except ValueError:
            print("Enter a valid number.")

def get_category():
    """Let user pick expense category"""
    print("\n  Categories:")
    for k, v in CATEGORIES.items():
        print(f"    {k}. {v}")
    while True:
        choice = input("  Select category (1-8): ").strip()
        if choice in CATEGORIES:
            return CATEGORIES[choice]
        print("  Invalid choice. Enter 1-8.")

def format_money(amount):
    """Format amount as Indian currency"""
    return f"₹{amount:,.2f}"

def bar_chart(label, amount, max_amount, width=20):
    """Create a simple text bar chart"""
    if max_amount == 0:
        filled = 0
    else:
        filled = int((amount / max_amount) * width)
    bar = "█" * filled + "░" * (width - filled)
    return f"  {label:<18} [{bar}] {format_money(amount)}"

# ─── Main Program ─────────────────────────────────────

print("=" * 55)
print("       💰 PERSONAL FINANCE TRACKER")
print("=" * 55)

# Setup
user_name = input("\nYour name: ").strip().title()
month = input("Month (e.g., January 2024): ").strip().title()

print(f"\nHello {user_name}! Let's track your finances for {month}.")

# Income
print("\n─── INCOME ─────────────────────────────────────")
salary = get_float("  Monthly salary: ₹", 0)
other_income = get_float("  Other income (0 if none): ₹", 0)
total_income = salary + other_income

# Budget
print("\n─── BUDGET ──────────────────────────────────────")
budget = get_float("  Total monthly budget: ₹", 0)

# Expenses
print("\n─── EXPENSES ────────────────────────────────────")
print("  Add your expenses (type 'done' when finished)")

expenses = []
category_totals = {v: 0.0 for v in CATEGORIES.values()}

while True:
    print(f"\n  Expense #{len(expenses) + 1}")
    desc = input("  Description (or 'done' to finish): ").strip()
    if desc.lower() == "done":
        if len(expenses) == 0:
            print("  Add at least one expense!")
            continue
        break

    amount = get_float("  Amount: ₹", 0.01)
    category = get_category()

    expenses.append({
        "desc": desc.title(),
        "amount": amount,
        "category": category,
    })
    category_totals[category] += amount

    total_so_far = sum(e["amount"] for e in expenses)
    print(f"  ✓ Added! Total spent so far: {format_money(total_so_far)}")

    if total_so_far > budget:
        print(f"  ⚠ WARNING: You've exceeded your budget of {format_money(budget)}!")

# ─── Calculations ─────────────────────────────────────
total_expenses = sum(e["amount"] for e in expenses)
savings = total_income - total_expenses
budget_remaining = budget - total_expenses
savings_rate = (savings / total_income * 100) if total_income > 0 else 0
budget_used_pct = (total_expenses / budget * 100) if budget > 0 else 0

# Largest expense
largest = max(expenses, key=lambda e: e["amount"])
# Most spending category
top_category = max(category_totals, key=category_totals.get)

# ─── Full Report ──────────────────────────────────────
report_lines = []
report_lines.append("=" * 55)
report_lines.append(f"   💰 FINANCE REPORT — {month.upper()}")
report_lines.append(f"   {user_name}")
report_lines.append("=" * 55)

report_lines.append("\n─── INCOME SUMMARY ──────────────────────────────")
report_lines.append(f"  Salary:          {format_money(salary)}")
report_lines.append(f"  Other Income:    {format_money(other_income)}")
report_lines.append(f"  TOTAL INCOME:    {format_money(total_income)}")

report_lines.append("\n─── EXPENSE BREAKDOWN ───────────────────────────")
report_lines.append(f"  {'#':<4} {'Description':<20} {'Category':<18} {'Amount':>10}")
report_lines.append(f"  {'─'*4} {'─'*20} {'─'*18} {'─'*10}")
for i, e in enumerate(expenses, 1):
    report_lines.append(
        f"  {i:<4} {e['desc']:<20} {e['category']:<18} {format_money(e['amount']):>10}"
    )

report_lines.append("\n─── BY CATEGORY ─────────────────────────────────")
max_cat = max(category_totals.values()) if category_totals else 1
for cat, amt in category_totals.items():
    if amt > 0:
        report_lines.append(bar_chart(cat, amt, max_cat))

report_lines.append("\n─── FINANCIAL SUMMARY ───────────────────────────")
report_lines.append(f"  Total Income:       {format_money(total_income)}")
report_lines.append(f"  Total Expenses:     {format_money(total_expenses)}")
report_lines.append(f"  Budget Set:         {format_money(budget)}")
report_lines.append(f"  Budget Used:        {budget_used_pct:.1f}%")
report_lines.append(f"  Budget Remaining:   {format_money(budget_remaining)}")
report_lines.append(f"  NET SAVINGS:        {format_money(savings)}")
report_lines.append(f"  Savings Rate:       {savings_rate:.1f}%")
report_lines.append(f"  Largest Expense:    {largest['desc']} ({format_money(largest['amount'])})")
report_lines.append(f"  Top Category:       {top_category}")

report_lines.append("\n─── ANALYSIS ────────────────────────────────────")
if savings_rate >= 30:
    report_lines.append("  ⭐ Excellent savings rate! You're building wealth.")
elif savings_rate >= 20:
    report_lines.append("  ✓ Good savings rate. Try to push above 30%.")
elif savings_rate >= 10:
    report_lines.append("  ⚠ Moderate savings. Reduce discretionary spending.")
elif savings >= 0:
    report_lines.append("  ⚠ Low savings rate. Review your expenses.")
else:
    report_lines.append("  ✗ You spent more than you earned! Urgent review needed.")

if budget_used_pct > 100:
    report_lines.append(f"  ✗ Over budget by {format_money(abs(budget_remaining))}!")
elif budget_used_pct > 90:
    report_lines.append("  ⚠ Almost at budget limit.")
else:
    report_lines.append(f"  ✓ Within budget. {format_money(budget_remaining)} remaining.")

report_lines.append("\n─── TIPS ────────────────────────────────────────")
report_lines.append("  1. Aim to save at least 20% of income (rule of thumb)")
report_lines.append("  2. Emergency fund = 6 months of expenses")
report_lines.append("  3. Track every rupee — small leaks sink big ships")
report_lines.append("=" * 55)

full_report = "\n".join(report_lines)
print("\n" + full_report)

# Save to file
filename = f"finance_{user_name.replace(' ', '_')}_{month.replace(' ', '_')}.txt"
try:
    with open(filename, "w", encoding="utf-8") as f:
        f.write(full_report)
    print(f"\n✓ Report saved to: {filename}")
except Exception as e:
    print(f"\n✗ Could not save report: {e}")
```

---

## <a id="section-52"></a> 5.2 FIFTEEN PRACTICE WORKSHEETS WITH FULL SOLUTIONS

---

### WORKSHEET 1: Print Mastery

**Objective:** Master all print() parameters

**Exercise 1.1** — Print your name, city, and country each on separate lines.
```python
# YOUR CODE HERE

# SOLUTION:
print("Chandresh")
print("Lucknow")
print("India")
```

**Exercise 1.2** — Print them on ONE line separated by " | "
```python
# SOLUTION:
print("Chandresh", "Lucknow", "India", sep=" | ")
# Output: Chandresh | Lucknow | India
```

**Exercise 1.3** — Print "Hello..." then "World" on same line using end parameter
```python
# SOLUTION:
print("Hello", end="...")
print("World")
# Output: Hello...World
```

**Exercise 1.4** — Print this exactly (with tab spacing):
```
Name:    Chandresh
Age:     20
City:    Lucknow
```
```python
# SOLUTION:
print("Name:\tChandresh")
print("Age:\t20")
print("City:\tLucknow")
```

**Exercise 1.5** — Print a formatted table using sep and alignment:
```
ID   Name       Score
1    Alice      95
2    Bob        88
3    Charlie    72
```
```python
# SOLUTION:
print("ID", "Name".ljust(10), "Score")
print(1, "Alice".ljust(10), 95)
print(2, "Bob".ljust(10), 88)
print(3, "Charlie".ljust(10), 72)
```

---

### WORKSHEET 2: Variables & Data Types

**Objective:** Practice creating, modifying, and checking variable types

**Exercise 2.1** — Create one variable of each type (str, int, float, bool, None) and print both the value and its type.
```python
# SOLUTION:
my_str  = "Python"
my_int  = 42
my_flt  = 3.14
my_bool = True
my_none = None

for val in [my_str, my_int, my_flt, my_bool, my_none]:
    print(f"Value: {str(val):<10}  Type: {type(val).__name__}")
# Output:
# Value: Python      Type: str
# Value: 42          Type: int
# Value: 3.14        Type: float
# Value: True        Type: bool
# Value: None        Type: NoneType
```

**Exercise 2.2** — Swap two variables WITHOUT using a third variable.
```python
# SOLUTION:
a = 10
b = 20
print(f"Before: a={a}, b={b}")

a, b = b, a  # Python tuple swap

print(f"After:  a={a}, b={b}")
# Output:
# Before: a=10, b=20
# After:  a=20, b=10
```

**Exercise 2.3** — Predict the output BEFORE running:
```python
x = 5
x += 3
x *= 2
x -= 4
x //= 2
print(x)
```
```python
# TRACE:
# x = 5
# x += 3  → x = 8
# x *= 2  → x = 16
# x -= 4  → x = 12
# x //= 2 → x = 6
# ANSWER: 6
```

**Exercise 2.4** — Fix these variable names (all are broken):
```python
# ❌ BROKEN:
2name = "Alice"
my-age = 25
class = "Python"
my var = 10

# ✅ FIXED SOLUTION:
name2   = "Alice"      # can't start with digit
my_age  = 25           # no hyphens
my_class = "Python"    # can't use keywords
my_var  = 10           # no spaces
```

**Exercise 2.5** — Without running, which of these are True/False?
```python
print(type(10) == int)
print(type(10.0) == int)
print(type("10") == str)
print(isinstance(10, (int, float)))
print(isinstance(True, int))
```
```python
# ANSWERS:
# True   (10 is int)
# False  (10.0 is float, not int)
# True   ("10" is str)
# True   (10 is int, which is in the tuple)
# True   (bool is a subclass of int in Python)
```

---

### WORKSHEET 3: F-Strings & String Formatting

**Objective:** Master all f-string features

**Exercise 3.1** — Format a price to 2 decimal places with ₹ symbol
```python
# SOLUTION:
price = 1999.5
print(f"Price: ₹{price:.2f}")
# Output: Price: ₹1999.50
```

**Exercise 3.2** — Format a large number with comma separators
```python
# SOLUTION:
population = 1410000000
print(f"India's population: {population:,}")
# Output: India's population: 1,410,000,000
```

**Exercise 3.3** — Print percentage from a fraction
```python
# SOLUTION:
correct = 45
total = 50
print(f"Score: {correct/total:.1%}")
# Output: Score: 90.0%
```

**Exercise 3.4** — Right-align names in a 20-character field
```python
# SOLUTION:
names = ["Alice", "Bob", "Christopher"]
for name in names:
    print(f"|{name:>20}|")
# Output:
# |               Alice|
# |                 Bob|
# |         Christopher|
```

**Exercise 3.5** — Create a receipt format:
```
========== RECEIPT ==========
Item         Qty     Price
Notebook       2   ₹ 80.00
Pen            5   ₹ 25.00
=============================
Total              ₹105.00
```
```python
# SOLUTION:
print("=" * 30)
print("RECEIPT".center(30))
print("=" * 30)
print(f"{'Item':<14} {'Qty':>4} {'Price':>9}")
print(f"{'Notebook':<14} {2:>4} ₹{80.00:>7.2f}")
print(f"{'Pen':<14} {5:>4} ₹{25.00:>7.2f}")
print("=" * 30)
print(f"{'Total':<19} ₹{105.00:>7.2f}")
```

---

### WORKSHEET 4: Arithmetic Operators

**Objective:** Understand every arithmetic operator and its edge cases

**Exercise 4.1** — Predict the result of each:
```python
print(10 / 3)
print(10 // 3)
print(10 % 3)
print(-10 // 3)
print(-10 % 3)
print(2 ** 10)
```
```python
# ANSWERS:
# 3.3333333333333335  (regular division = float)
# 3                   (floor division = round down)
# 1                   (remainder after 3×3=9)
# -4                  (floor division rounds toward -∞)
# 2                   (Python modulo always non-negative)
# 1024                (2 to the power 10)
```

**Exercise 4.2** — Write a program that checks if a number is even or odd
```python
# SOLUTION:
number = int(input("Enter a number: "))
if number % 2 == 0:
    print(f"{number} is EVEN")
else:
    print(f"{number} is ODD")
```

**Exercise 4.3** — Calculate compound interest
Formula: A = P(1 + r/n)^(nt)
```python
# SOLUTION:
P = float(input("Principal (₹): "))
r = float(input("Annual rate (%): ")) / 100
n = int(input("Compounding per year: "))
t = int(input("Years: "))

A = P * (1 + r/n) ** (n * t)
interest = A - P

print(f"\nFinal Amount:  ₹{A:,.2f}")
print(f"Interest Earned: ₹{interest:,.2f}")
```

**Exercise 4.4** — Calculate how many days, hours, minutes in N years
```python
# SOLUTION:
years = int(input("Enter number of years: "))
days    = years * 365
hours   = days * 24
minutes = hours * 60
seconds = minutes * 60

print(f"{years} years = {days:,} days")
print(f"           = {hours:,} hours")
print(f"           = {minutes:,} minutes")
print(f"           = {seconds:,} seconds")
```

**Exercise 4.5** — Convert seconds to HH:MM:SS format
```python
# SOLUTION:
total_seconds = int(input("Enter seconds: "))

hours   = total_seconds // 3600
minutes = (total_seconds % 3600) // 60
seconds = total_seconds % 60

print(f"Time: {hours:02d}:{minutes:02d}:{seconds:02d}")
# e.g. 3661 seconds → 01:01:01
```

---

### WORKSHEET 5: String Methods Challenge

**Objective:** Apply 15+ string methods to real scenarios

**Exercise 5.1** — Clean and normalize user input
```python
# Given messy input, clean it:
raw_email = "  USER@EXAMPLE.COM  "
raw_name  = "  john SMITH  "

# SOLUTION:
clean_email = raw_email.strip().lower()
clean_name  = raw_name.strip().title()

print(f"Email: '{clean_email}'")  # 'user@example.com'
print(f"Name:  '{clean_name}'")   # 'John Smith'
```

**Exercise 5.2** — Validate email format
```python
# SOLUTION:
def is_valid_email(email):
    email = email.strip().lower()
    has_at  = "@" in email
    has_dot = "." in email
    not_starts_at = not email.startswith("@")
    not_ends_dot  = not email.endswith(".")
    at_before_dot = email.index("@") < email.rindex(".") if has_at and has_dot else False
    return has_at and has_dot and not_starts_at and not_ends_dot and at_before_dot

# Test
test_emails = ["user@example.com", "invalid", "@bad.com", "no_at.com"]
for e in test_emails:
    status = "✓ VALID" if is_valid_email(e) else "✗ INVALID"
    print(f"{e:<25} {status}")
```

**Exercise 5.3** — Count vowels and consonants in a word
```python
# SOLUTION:
word = input("Enter a word: ").lower()
vowels     = "aeiou"
vowel_count     = sum(1 for c in word if c in vowels)
consonant_count = sum(1 for c in word if c.isalpha() and c not in vowels)

print(f"Word:       {word}")
print(f"Vowels:     {vowel_count}")
print(f"Consonants: {consonant_count}")
```

**Exercise 5.4** — Reverse words in a sentence (not characters)
```python
# SOLUTION:
sentence = "Hello World Python"
words    = sentence.split()
reversed_words = " ".join(reversed(words))
print(reversed_words)
# Output: Python World Hello
```

**Exercise 5.5** — Check if a string is a palindrome
```python
# SOLUTION:
text  = input("Enter word/phrase: ").lower()
clean = "".join(c for c in text if c.isalnum())  # letters/digits only
is_palindrome = clean == clean[::-1]

print(f"Original: {text}")
print(f"Reversed: {clean[::-1]}")
print(f"Palindrome: {'YES ✓' if is_palindrome else 'NO ✗'}")
# "racecar" → YES, "hello" → NO
```

---

### WORKSHEET 6: Input & Validation

**Objective:** Build robust input-handling programs

**Exercise 6.1** — Get a valid integer between 1 and 10 from user, keep asking until valid
```python
# SOLUTION:
while True:
    try:
        number = int(input("Enter a number (1-10): "))
        if 1 <= number <= 10:
            print(f"You entered: {number}")
            break
        else:
            print("Must be between 1 and 10!")
    except ValueError:
        print("That's not a number!")
```

**Exercise 6.2** — Ask for YES or NO and loop until valid
```python
# SOLUTION:
while True:
    answer = input("Continue? (yes/no): ").strip().lower()
    if answer in ["yes", "y", "no", "n"]:
        break
    print("Please type yes or no.")

if answer in ["yes", "y"]:
    print("Continuing...")
else:
    print("Stopping.")
```

**Exercise 6.3** — Multi-input on one line: "Enter 3 numbers: 10 20 30"
```python
# SOLUTION:
raw = input("Enter 3 numbers separated by spaces: ")
parts = raw.split()

if len(parts) != 3:
    print("Please enter exactly 3 numbers!")
else:
    try:
        a, b, c = int(parts[0]), int(parts[1]), int(parts[2])
        print(f"Sum: {a + b + c}")
        print(f"Average: {(a + b + c) / 3:.2f}")
    except ValueError:
        print("All values must be whole numbers!")
```

**Exercise 6.4** — Password entry with confirmation
```python
# SOLUTION:
while True:
    password = input("Set password: ")
    if len(password) < 6:
        print("Password must be at least 6 characters.")
        continue

    confirm = input("Confirm password: ")
    if password == confirm:
        print("✓ Password set successfully!")
        break
    else:
        print("✗ Passwords do not match. Try again.")
```

**Exercise 6.5** — Collect items until user types "done", then print all
```python
# SOLUTION:
shopping_list = []
print("Enter shopping items (type 'done' when finished):")

while True:
    item = input(f"  Item {len(shopping_list) + 1}: ").strip().title()
    if item.lower() == "Done":
        break
    if item:
        shopping_list.append(item)
        print(f"  ✓ Added: {item}")

print(f"\nShopping List ({len(shopping_list)} items):")
for i, item in enumerate(shopping_list, 1):
    print(f"  {i}. {item}")
```

---

### WORKSHEET 7: Error Identification & Fixing

**Objective:** Read broken code, identify errors, fix them

**Exercise 7.1** — Find and fix ALL errors (there are 5):
```python
# BROKEN CODE:
nme = input("Enter name )
age = input("Enter age: "
print("Hello" + nme)
print("Age:" age)
print(age + 5)
```
```python
# SOLUTION (5 errors fixed):
nme = input("Enter name: ")     # Fix 1: missing closing "
age = input("Enter age: ")       # Fix 2: missing closing )
print("Hello " + nme)            # Fix 3: missing space before +nme (minor)
print("Age:", age)               # Fix 4: missing comma
print(int(age) + 5)              # Fix 5: age is string, must convert to int
```

**Exercise 7.2** — What error does each line cause?
```python
# Identify the error type for each:
print(undefined_variable)        # ?
print(10 / 0)                    # ?
print("Hi" + 5)                  # ?
x = int("hello")                 # ?
text = "Hello"; print(text[20])  # ?
```
```python
# ANSWERS:
# NameError:         undefined_variable not defined
# ZeroDivisionError: cannot divide by zero
# TypeError:         cannot add str and int
# ValueError:        "hello" cannot be converted to int
# IndexError:        string index out of range (max is 4)
```

**Exercise 7.3** — Fix the logic error (code runs but wrong result):
```python
# BROKEN (logic error — can you spot it?):
total = 0
grade_a = 5
grade_b = 3
grade_c = 2
total = grade_a + grade_b  # Bug: forgot grade_c
print(f"Total students: {total}")
```
```python
# SOLUTION:
total = 0
grade_a = 5
grade_b = 3
grade_c = 2
total = grade_a + grade_b + grade_c  # Fixed: include grade_c
print(f"Total students: {total}")    # Now prints 10, not 8
```

**Exercise 7.4** — Add error handling to this fragile code:
```python
# FRAGILE (crashes on any bad input):
a = int(input("Enter a: "))
b = int(input("Enter b: "))
result = a / b
print(f"Result: {result}")
```
```python
# SOLUTION (robust):
try:
    a = int(input("Enter a: "))
    b = int(input("Enter b: "))

    if b == 0:
        print("Error: Cannot divide by zero")
    else:
        result = a / b
        print(f"Result: {result:.4f}")

except ValueError:
    print("Error: Please enter whole numbers only")
```

**Exercise 7.5** — Trace through this code and predict every line of output:
```python
x = 10
y = 3
print(f"A: {x + y}")
print(f"B: {x - y}")
print(f"C: {x * y}")
print(f"D: {x / y:.2f}")
print(f"E: {x // y}")
print(f"F: {x % y}")
print(f"G: {x ** y}")
print(f"H: {x > y}")
print(f"I: {x == y}")
```
```python
# ANSWERS:
# A: 13
# B: 7
# C: 30
# D: 3.33
# E: 3
# F: 1
# G: 1000
# H: True
# I: False
```

---

### WORKSHEET 8: Real-World Data Formatting

**Objective:** Format data as professionals do

**Exercise 8.1** — Format a phone number: input "9876543210" → output "+91-98765-43210"
```python
# SOLUTION:
number = input("Enter 10-digit mobile number: ").strip()
if len(number) == 10 and number.isdigit():
    formatted = f"+91-{number[:5]}-{number[5:]}"
    print(f"Formatted: {formatted}")
else:
    print("Invalid number!")
```

**Exercise 8.2** — Format an Aadhaar number: "123456789012" → "1234 5678 9012"
```python
# SOLUTION:
aadhaar = input("Enter 12-digit Aadhaar: ").strip().replace(" ", "")
if len(aadhaar) == 12 and aadhaar.isdigit():
    masked = f"XXXX XXXX {aadhaar[8:]}"  # mask first 8
    print(f"Formatted: {masked}")
else:
    print("Invalid Aadhaar number")
```

**Exercise 8.3** — Build a name formatter: input any casing → output "Last, First M."
```python
# SOLUTION:
first = input("First name: ").strip().title()
middle = input("Middle name (or press Enter): ").strip().title()
last = input("Last name: ").strip().title()

if middle:
    formatted = f"{last}, {first} {middle[0]}."
else:
    formatted = f"{last}, {first}"

print(f"Formatted: {formatted}")
# e.g. "Singh, Chandresh K."
```

**Exercise 8.4** — Display a bank account statement header
```python
# SOLUTION:
account_name = input("Account holder: ").strip().title()
account_no   = input("Account number: ").strip()
balance      = float(input("Balance: ₹"))
bank_name    = "Python National Bank"

masked_acc = "XXXX" + account_no[-4:]  # Show last 4 digits only

print()
print("=" * 50)
print(bank_name.center(50))
print("ACCOUNT STATEMENT".center(50))
print("=" * 50)
print(f"  Name:       {account_name}")
print(f"  Account No: {masked_acc}")
print(f"  Balance:    ₹{balance:>12,.2f}")
print("=" * 50)
```

**Exercise 8.5** — Progress bar display
```python
# SOLUTION:
def progress_bar(done, total, width=30, label="Progress"):
    pct   = done / total if total > 0 else 0
    filled = int(pct * width)
    bar   = "█" * filled + "░" * (width - filled)
    return f"{label}: [{bar}] {pct:.1%} ({done}/{total})"

# Test it
for step in range(0, 11):
    print(progress_bar(step, 10, label="Downloading"))

# Output progression:
# Downloading: [░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 0.0% (0/10)
# Downloading: [███░░░░░░░░░░░░░░░░░░░░░░░░░░░] 10.0% (1/10)
# ... up to 100%
```

---

### WORKSHEET 9: Logical Operators Deep Practice

**Objective:** Master and/or/not in real conditions

**Exercise 9.1** — Create a loan eligibility checker
```python
# SOLUTION:
print("=== LOAN ELIGIBILITY CHECK ===")
age     = int(input("Age: "))
income  = float(input("Monthly income ₹: "))
score   = int(input("Credit score (300-900): "))
emp     = input("Employment type (salaried/self): ").lower().strip()

age_ok    = 21 <= age <= 65
income_ok = income >= 25000
score_ok  = score >= 650
emp_ok    = emp in ["salaried", "self"]

eligible = age_ok and income_ok and score_ok and emp_ok

print("\n── Eligibility Breakdown ──")
print(f"  Age (21-65):          {'✓' if age_ok else '✗'}")
print(f"  Income (≥₹25000):     {'✓' if income_ok else '✗'}")
print(f"  Credit Score (≥650):  {'✓' if score_ok else '✗'}")
print(f"  Employment:           {'✓' if emp_ok else '✗'}")
print(f"\n  Result: {'✓ ELIGIBLE' if eligible else '✗ NOT ELIGIBLE'}")
```

**Exercise 9.2** — Predict True/False without running:
```python
a, b, c = True, False, True

print(a and b)
print(a or b)
print(not b)
print(a and b or c)
print(not (a and c))
print(a and (b or c))
```
```python
# ANSWERS:
# False   (True and False)
# True    (True or False)
# True    (not False)
# True    ((False) or True)
# False   (not True)
# True    (True and True)
```

**Exercise 9.3** — Write a program that determines if a year is a leap year
```python
# SOLUTION:
# Leap year rules:
# 1. Divisible by 4
# 2. NOT divisible by 100, UNLESS
# 3. Also divisible by 400

year = int(input("Enter a year: "))

is_leap = (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)

print(f"{year} is {'a LEAP' if is_leap else 'NOT a leap'} year")

# Tests: 2000=leap, 1900=not, 2024=leap, 2023=not
```

**Exercise 9.4** — Grade pass/fail with multiple conditions
```python
# SOLUTION:
# Pass only if:
# 1. Overall average >= 40
# 2. NO individual subject below 33
# 3. Attendance >= 75%

subjects  = ["Math", "Science", "English"]
marks     = []
for s in subjects:
    m = float(input(f"{s} marks: "))
    marks.append(m)

attendance = float(input("Attendance %: "))
average    = sum(marks) / len(marks)
has_fail   = any(m < 33 for m in marks)

passed = average >= 40 and not has_fail and attendance >= 75

print(f"\nAverage:    {average:.1f}")
print(f"Any fail:   {'Yes' if has_fail else 'No'}")
print(f"Attendance: {attendance}%")
print(f"Result:     {'PASS ✓' if passed else 'FAIL ✗'}")
```

**Exercise 9.5** — Classify number (positive/negative/zero, even/odd)
```python
# SOLUTION:
n = int(input("Enter a number: "))

# Sign
if n > 0:
    sign = "Positive"
elif n < 0:
    sign = "Negative"
else:
    sign = "Zero"

# Even/odd (only for non-zero)
if n != 0:
    parity = "Even" if n % 2 == 0 else "Odd"
else:
    parity = "Neither"

print(f"{n} is {sign} and {parity}")
# e.g. "-4 is Negative and Even"
```

---

### WORKSHEET 10: Type Conversion Practice

**Objective:** Master converting between types without errors

**Exercise 10.1** — Convert all types to string and back
```python
# SOLUTION:
num   = 42
flt   = 3.14
bl    = True

# To string
s_num = str(num)
s_flt = str(flt)
s_bl  = str(bl)
print(f"Strings: '{s_num}', '{s_flt}', '{s_bl}'")

# Back to original
print(f"Back:    {int(s_num)}, {float(s_flt)}, {s_bl == 'True'}")
```

**Exercise 10.2** — Handle failed conversion gracefully
```python
# SOLUTION:
def safe_int(value, default=0):
    try:
        return int(value)
    except (ValueError, TypeError):
        return default

print(safe_int("42"))      # 42
print(safe_int("abc"))     # 0  (default)
print(safe_int("3.14"))    # 0  (can't convert float-string to int directly)
print(safe_int(None))      # 0  (None can't convert)
print(safe_int("  7  "))   # 7  (strip happens automatically in int())
```

**Exercise 10.3** — Build a type-safe calculator
```python
# SOLUTION:
def safe_calculate(a_str, b_str, op):
    try:
        a = float(a_str)
        b = float(b_str)
    except ValueError:
        return "Error: Invalid numbers"

    if op == "+" : return a + b
    elif op == "-": return a - b
    elif op == "*": return a * b
    elif op == "/":
        if b == 0: return "Error: Division by zero"
        return a / b
    else:
        return "Error: Unknown operator"

result = safe_calculate(
    input("A: "),
    input("B: "),
    input("Operator (+,-,*,/): ")
)
print(f"Result: {result}")
```

**Exercise 10.4** — Convert list of strings to floats (with error tracking)
```python
# SOLUTION:
raw_data = "10.5, 20, abc, 30.7, None, 45"
items    = raw_data.split(", ")

converted = []
errors    = []

for item in items:
    try:
        converted.append(float(item))
    except ValueError:
        errors.append(item)

print(f"Converted: {converted}")
print(f"Errors:    {errors}")
print(f"Sum:       {sum(converted):.2f}")
# Converted: [10.5, 20.0, 30.7, 45.0]
# Errors:    ['abc', 'None']
# Sum:       106.20
```

**Exercise 10.5** — Integer overflow doesn't exist in Python (big number demo)
```python
# SOLUTION:
# Python handles arbitrarily large integers!
big = 2 ** 1000
print(f"2^1000 has {len(str(big))} digits")
print(f"First 10 digits: {str(big)[:10]}")

# Factorial of 100
import math
fact = math.factorial(100)
print(f"\n100! has {len(str(fact))} digits")
# Python handles all of this natively!
```

---

### WORKSHEET 11: String Slicing Deep Practice

**Exercise 11.1** — Extract components from a formatted date string "2024-01-15"
```python
# SOLUTION:
date_str = "2024-01-15"
year  = date_str[:4]
month = date_str[5:7]
day   = date_str[8:]
print(f"Year: {year}, Month: {month}, Day: {day}")
# Output: Year: 2024, Month: 01, Day: 15
```

**Exercise 11.2** — Reverse a string using slicing
```python
# SOLUTION:
text = "Hello, Python!"
reversed_text = text[::-1]
print(reversed_text)
# Output: !nohtyP ,olleH
```

**Exercise 11.3** — Extract file extension from filename
```python
# SOLUTION:
filename = "document_final_v2.pdf"
dot_pos  = filename.rfind(".")  # rfind = find from right
name      = filename[:dot_pos]
extension = filename[dot_pos+1:]
print(f"Name:      {name}")
print(f"Extension: .{extension}")
# Name:      document_final_v2
# Extension: .pdf
```

**Exercise 11.4** — Extract username from email
```python
# SOLUTION:
email    = "chandresh.singh@example.co.in"
at_pos   = email.index("@")
username = email[:at_pos]
domain   = email[at_pos+1:]
print(f"Username: {username}")
print(f"Domain:   {domain}")
# Username: chandresh.singh
# Domain:   example.co.in
```

**Exercise 11.5** — Create initials from a full name
```python
# SOLUTION:
full_name = input("Enter full name: ").strip().title()
parts     = full_name.split()
initials  = ".".join(p[0] for p in parts) + "."
print(f"Initials: {initials}")
# "Chandresh Kumar Singh" → "C.K.S."
```

---

### WORKSHEET 12: Professional Code Style Practice

**Exercise 12.1** — Rewrite this messy code in PEP 8 style
```python
# MESSY:
X=10
Y=20
Z=X+Y
print(Z)

# CLEAN SOLUTION:
first_number  = 10
second_number = 20
total         = first_number + second_number
print(f"Total: {total}")
```

**Exercise 12.2** — Add appropriate comments to this code
```python
# ORIGINAL:
P = 100000
R = 8.5
N = 5

A = P * (1 + R/100)**N
I = A - P
print(A)
print(I)
```
```python
# WITH COMMENTS:
# Initial investment amount (Indian Rupees)
principal = 100000

# Annual interest rate (percentage)
annual_rate = 8.5

# Investment duration (years)
years = 5

# Compound interest formula: A = P(1 + r/100)^t
final_amount = principal * (1 + annual_rate / 100) ** years
interest_earned = final_amount - principal

print(f"Final Amount:    ₹{final_amount:,.2f}")
print(f"Interest Earned: ₹{interest_earned:,.2f}")
```

**Exercise 12.3** — Identify which naming convention is used and fix:
```python
# FIX THESE:
StudentName = "Alice"    # Should be: student_name
USERPASSWORD = "abc"     # Should be: password or user_password
calcresult = 0           # Should be: calc_result
MY_VARIABLE = 10         # OK if constant, not if regular var
```

**Exercise 12.4** — Reduce duplication with variables
```python
# DUPLICATED:
print("Customer: " + "John Smith")
print("Account: " + "John Smith" + " - Active")
print("Welcome, " + "John Smith" + "!")

# CLEAN SOLUTION:
customer_name = "John Smith"
print(f"Customer: {customer_name}")
print(f"Account: {customer_name} - Active")
print(f"Welcome, {customer_name}!")
```

**Exercise 12.5** — Write defensive code with all edge cases handled
```python
# SOLUTION: Safe division with full edge cases
def safe_divide(numerator, denominator):
    """
    Safely divide two numbers.
    Returns float or error string.
    """
    # Type check
    if not isinstance(numerator, (int, float)):
        return "Error: numerator must be a number"
    if not isinstance(denominator, (int, float)):
        return "Error: denominator must be a number"

    # Zero division check
    if denominator == 0:
        return "Error: cannot divide by zero"

    # Infinity check
    if abs(denominator) < 1e-10:  # Extremely small
        return "Error: denominator too small"

    return numerator / denominator

# Tests
print(safe_divide(10, 2))      # 5.0
print(safe_divide(10, 0))      # Error: cannot divide by zero
print(safe_divide("a", 2))     # Error: numerator must be a number
print(safe_divide(10, 0.0))    # Error: cannot divide by zero
```

---

### WORKSHEET 13: Real-World Mini Programs

**Exercise 13.1** — ATM Interface (20 lines max)
```python
# SOLUTION:
print("=== ATM ===")
try:
    balance = float(input("Enter balance: ₹"))
    amount  = float(input("Withdrawal amount: ₹"))

    if amount <= 0:
        print("Amount must be positive")
    elif amount % 100 != 0:
        print("Use denominations of ₹100")
    elif amount > balance:
        print(f"Insufficient balance (Available: ₹{balance:,.2f})")
    elif amount > 20000:
        print("Daily limit ₹20,000 exceeded")
    else:
        balance -= amount
        print(f"✓ ₹{amount:,.0f} dispensed")
        print(f"Remaining balance: ₹{balance:,.2f}")
except ValueError:
    print("Invalid amount entered")
```

**Exercise 13.2** — Simple inventory check
```python
# SOLUTION:
print("=== INVENTORY CHECKER ===")
product = input("Product name: ").strip().title()
stock   = int(input("Current stock: "))
minimum = int(input("Minimum required: "))
ordered = int(input("Units ordered by customer: "))

print(f"\nProduct: {product}")
print(f"Current stock:  {stock}")
print(f"Customer wants: {ordered}")

if ordered > stock:
    print(f"✗ Only {stock} available. Cannot fulfill order.")
else:
    remaining = stock - ordered
    print(f"✓ Order confirmed. Remaining stock: {remaining}")
    if remaining < minimum:
        reorder = minimum * 3 - remaining
        print(f"⚠ LOW STOCK! Reorder {reorder} units.")
```

**Exercise 13.3** — URL parser
```python
# SOLUTION:
url = input("Enter URL: ").strip()

# Determine protocol
if url.startswith("https://"):
    protocol = "HTTPS"
    rest = url[8:]
elif url.startswith("http://"):
    protocol = "HTTP"
    rest = url[7:]
else:
    protocol = "Unknown"
    rest = url

# Extract domain and path
if "/" in rest:
    slash_pos = rest.index("/")
    domain    = rest[:slash_pos]
    path      = rest[slash_pos:]
else:
    domain = rest
    path   = "/"

print(f"Protocol: {protocol}")
print(f"Domain:   {domain}")
print(f"Path:     {path}")
# "https://www.example.com/page/1" →
# Protocol: HTTPS, Domain: www.example.com, Path: /page/1
```

**Exercise 13.4** — Simple chatbot with keyword matching
```python
# SOLUTION:
print("=== PyBot ===")
print("Hi! I'm PyBot. Type 'bye' to exit.\n")

responses = {
    "hello": "Hello! How are you?",
    "hi"   : "Hey there!",
    "help" : "I can answer questions about Python!",
    "python": "Python is an amazing language for AI and ML!",
    "name" : "I'm PyBot, your Python learning assistant!",
    "age"  : "I was born when Python was installed!",
}

while True:
    user = input("You: ").strip().lower()
    if user in ["bye", "exit", "quit"]:
        print("PyBot: Goodbye! Keep coding! 🚀")
        break

    found = False
    for keyword, reply in responses.items():
        if keyword in user:
            print(f"PyBot: {reply}")
            found = True
            break

    if not found:
        print("PyBot: Interesting! Tell me more or ask about Python.")
    print()
```

**Exercise 13.5** — Simple quiz with scoring
```python
# SOLUTION:
questions = [
    ("What does print() do?",
     ["a) Store data", "b) Display output", "c) Input data", "d) Delete data"],
     "b"),
    ("Which symbol is used for comments?",
     ["a) //", "b) /*", "c) #", "d) --"],
     "c"),
    ("What type is 3.14?",
     ["a) int", "b) str", "c) bool", "d) float"],
     "d"),
    ("What does input() return?",
     ["a) int", "b) str", "c) float", "d) list"],
     "b"),
    ("Which converts string to int?",
     ["a) str()", "b) float()", "c) int()", "d) bool()"],
     "c"),
]

print("=== PYTHON BASICS QUIZ ===\n")
score = 0

for i, (question, options, answer) in enumerate(questions, 1):
    print(f"Q{i}: {question}")
    for opt in options:
        print(f"     {opt}")

    while True:
        user_ans = input("  Your answer (a/b/c/d): ").strip().lower()
        if user_ans in ["a", "b", "c", "d"]:
            break
        print("  Enter a, b, c, or d")

    if user_ans == answer:
        print("  ✓ Correct!\n")
        score += 1
    else:
        correct_opt = [o for o in options if o.startswith(answer)][0]
        print(f"  ✗ Wrong! Answer was: {correct_opt}\n")

pct = (score / len(questions)) * 100
print(f"═══════════════════════")
print(f"Score: {score}/{len(questions)} ({pct:.0f}%)")
if pct == 100:
    print("Perfect score! 🏆")
elif pct >= 80:
    print("Excellent! ⭐")
elif pct >= 60:
    print("Good job! 👍")
else:
    print("Keep studying! 📚")
```

---

### WORKSHEET 14: Challenge Problems (Hard)

**Exercise 14.1** — Caesar Cipher (shift letters by N)
```python
# SOLUTION:
def caesar_cipher(text, shift, mode="encode"):
    if mode == "decode":
        shift = -shift

    result = ""
    for char in text:
        if char.isalpha():
            base  = ord("A") if char.isupper() else ord("a")
            shifted = (ord(char) - base + shift) % 26 + base
            result += chr(shifted)
        else:
            result += char
    return result

text  = input("Enter text: ")
shift = int(input("Shift amount: "))

encoded = caesar_cipher(text, shift, "encode")
decoded = caesar_cipher(encoded, shift, "decode")

print(f"Original: {text}")
print(f"Encoded:  {encoded}")
print(f"Decoded:  {decoded}")
# "Hello" shift 3 → "Khoor"
```

**Exercise 14.2** — Number to words (0-99)
```python
# SOLUTION:
ones  = ["", "one", "two", "three", "four", "five", "six",
         "seven", "eight", "nine", "ten", "eleven", "twelve",
         "thirteen", "fourteen", "fifteen", "sixteen", "seventeen",
         "eighteen", "nineteen"]
tens  = ["", "", "twenty", "thirty", "forty", "fifty",
         "sixty", "seventy", "eighty", "ninety"]

def num_to_words(n):
    if n == 0:
        return "zero"
    elif n < 20:
        return ones[n]
    elif n < 100:
        ten  = tens[n // 10]
        one  = ones[n % 10]
        return ten + ("-" + one if one else "")
    else:
        return "out of range"

num = int(input("Enter number (0-99): "))
print(f"{num} = {num_to_words(num)}")
# 47 → forty-seven
```

**Exercise 14.3** — FizzBuzz (classic interview question)
```python
# SOLUTION:
n = int(input("Enter n: "))
for i in range(1, n + 1):
    if i % 15 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```

**Exercise 14.4** — Digital root (sum digits until single digit)
```python
# SOLUTION:
def digital_root(n):
    steps = 0
    while n >= 10:
        digit_sum = sum(int(d) for d in str(n))
        print(f"  {' + '.join(str(n))} = {digit_sum}")
        n = digit_sum
        steps += 1
    return n, steps

number = int(input("Enter a number: "))
root, steps = digital_root(number)
print(f"Digital root: {root} (in {steps} step{'s' if steps != 1 else ''})")
# 9875 → 9+8+7+5=29 → 2+9=11 → 1+1=2 → root: 2
```

**Exercise 14.5** — Simple encryption using ASCII
```python
# SOLUTION:
def encrypt(text, key=5):
    return "".join(chr(ord(c) + key) for c in text)

def decrypt(text, key=5):
    return "".join(chr(ord(c) - key) for c in text)

original  = input("Message to encrypt: ")
key       = int(input("Key (1-20): "))
encrypted = encrypt(original, key)
decrypted = decrypt(encrypted, key)

print(f"Original:  {original}")
print(f"Encrypted: {encrypted}")
print(f"Decrypted: {decrypted}")
print(f"Match:     {'✓ YES' if original == decrypted else '✗ NO'}")
```

---

### WORKSHEET 15: Self-Assessment Test (Exam Style)

**Time limit: 60 minutes | Total marks: 100**

**Q1 (5 marks)** — Write the output exactly:
```python
x = "Python"
print(x[0], x[-1], x[2:4], x[::-1], sep="|")
```
```python
# ANSWER: P|n|th|nohtyP
```

**Q2 (5 marks)** — Fix all errors:
```python
age = int(input(Enter age: ))
print("You are" age "years old")
```
```python
# ANSWER:
age = int(input("Enter age: "))
print("You are", age, "years old")
```

**Q3 (10 marks)** — Write a program to determine if a number is prime.
```python
# SOLUTION:
n = int(input("Enter a number: "))
if n < 2:
    print(f"{n} is NOT prime")
else:
    is_prime = True
    for i in range(2, int(n**0.5) + 1):  # only up to sqrt(n)
        if n % i == 0:
            is_prime = False
            break
    print(f"{n} is {'PRIME' if is_prime else 'NOT prime'}")
```

**Q4 (10 marks)** — Format a table of 5 students with name, marks, grade:
```python
# SOLUTION:
students = [
    ("Alice",    85),
    ("Bob",      72),
    ("Charlie",  91),
    ("Diana",    60),
    ("Evan",     78),
]

def get_grade(m):
    if m >= 90: return "A"
    elif m >= 80: return "B"
    elif m >= 70: return "C"
    elif m >= 60: return "D"
    else: return "F"

print(f"{'Name':<12} {'Marks':>6} {'Grade':>6}")
print("-" * 26)
for name, marks in students:
    print(f"{name:<12} {marks:>6} {get_grade(marks):>6}")
```

**Q5 (20 marks)** — Build a complete BMI + advice program (all input validated)
```python
# SOLUTION: (Refer to Project 7 above)
```

**Q6 (25 marks)** — Build a word frequency counter (count how many times each word appears in a sentence)
```python
# SOLUTION:
text = input("Enter a sentence: ").lower()
# Remove punctuation
for char in ".,!?;:\"'":
    text = text.replace(char, "")

words    = text.split()
freq     = {}
for word in words:
    freq[word] = freq.get(word, 0) + 1

sorted_freq = sorted(freq.items(), key=lambda x: x[1], reverse=True)

print(f"\nWord frequencies ({len(words)} total, {len(freq)} unique):")
print(f"{'Word':<15} {'Count':>6} {'Bar'}")
print("-" * 35)
for word, count in sorted_freq:
    bar = "█" * count
    print(f"{word:<15} {count:>6}  {bar}")
```

**Q7 (25 marks)** — Build a mini contact book: add name+phone, search by name, display all
```python
# SOLUTION:
contacts = {}

def add_contact(name, phone):
    contacts[name.title()] = phone
    print(f"✓ Added {name.title()}")

def search_contact(name):
    result = contacts.get(name.title())
    if result:
        print(f"  {name.title()}: {result}")
    else:
        print(f"  '{name}' not found")

def display_all():
    if not contacts:
        print("  No contacts saved.")
        return
    print(f"\n  {'Name':<20} {'Phone':>12}")
    print(f"  {'─'*20} {'─'*12}")
    for name, phone in sorted(contacts.items()):
        print(f"  {name:<20} {phone:>12}")

print("=== CONTACT BOOK ===")
while True:
    print("\n1. Add  2. Search  3. View all  4. Exit")
    choice = input("Choice: ").strip()
    if choice == "1":
        n = input("  Name: ").strip()
        p = input("  Phone: ").strip()
        add_contact(n, p)
    elif choice == "2":
        n = input("  Search name: ").strip()
        search_contact(n)
    elif choice == "3":
        display_all()
    elif choice == "4":
        print("Goodbye!")
        break
    else:
        print("Invalid choice")
```

---

# CONCLUSION & NEXT STEPS

## What You've Learned on Day 1

✅ Programming fundamentals  
✅ Python syntax and setup  
✅ Print, variables, data types, operators  
✅ User input and output  
✅ 25+ error types and solutions  
✅ String methods and manipulations  
✅ Professional coding practices  
✅ 10 complete projects  
✅ 15 practice worksheets  

## What's Next (Days 2-3)

- Conditionals (`if/elif/else`)
- Loops (`for`, `while`, `break`, `continue`)
- Lists and dictionaries
- Functions and scope
- Error handling with `try/except`

## Your Day 1 Challenge

Choose ANY 3 projects from the 10 provided and complete them. Push to GitHub.

## Resources for Continued Learning

- Python Docs: https://docs.python.org/3/
- LeetCode: https://www.leetcode.com/
- GeeksforGeeks: https://www.geeksforgeeks.org/python/
- freeCodeCamp: https://youtube.com/c/freecodecamp

---

**YOU CAN DO THIS! 🚀**

Remember: Every expert programmer started exactly where you are right now. Keep coding!

---

**END OF ULTIMATE PYTHON DAY 1 TEXTBOOK**

**Total:** 80+ pages | 300+ code examples | 25+ errors | 10 projects | 15 worksheets


---

## SENIOR ENGINEER CHEAT SHEET — KEEP THIS BESIDE YOU

```
PRINT:
  print("text")                 → text
  print("A", "B", sep="-")     → A-B
  print("A", end="")           → no newline
  print(f"x={x:.2f}")          → x=3.14

VARIABLES:
  name = "Alice"                → string variable
  age = 25                      → int variable
  gpa = 3.8                     → float variable
  is_student = True             → bool variable

TYPE CONVERSION:
  int("20")       → 20
  float("3.14")   → 3.14
  str(42)         → "42"
  bool(0)         → False
  bool(1)         → True

STRING METHODS (most used):
  .strip()     → remove whitespace
  .lower()     → lowercase
  .upper()     → uppercase
  .title()     → Title Case
  .split()     → split to list
  .join()      → join list to string
  .replace()   → replace text
  .find()      → find position
  .count()     → count occurrences
  .startswith()→ check beginning
  .endswith()  → check ending

OPERATORS:
  +  -  *  /    → basic math
  //             → floor division
  %              → remainder
  **             → exponent
  ==  !=  >  <  >=  <=   → compare
  and  or  not   → logical

ERRORS TO REMEMBER:
  NameError      → variable not defined
  TypeError      → wrong type (e.g. "a" + 1)
  ValueError     → bad value (e.g. int("abc"))
  IndexError     → index out of range
  ZeroDivisionError → divide by 0
  SyntaxError    → grammar mistake
  IndentationError → wrong indent
  AttributeError → wrong method name
```

---

## FINAL MOTIVATIONAL NOTE

You started today as a complete beginner.

By completing this textbook and all worksheets, you now know:

- ✅ How a computer executes code
- ✅ Python installation and environment setup
- ✅ The print() function in every detail (sep, end, flush, escape sequences)
- ✅ f-Strings with all formatting options
- ✅ Variables: creation, naming, scope, reassignment
- ✅ All data types: str, int, float, bool, None
- ✅ All operators: arithmetic, comparison, logical, assignment, membership
- ✅ User input with validation and error handling
- ✅ 30+ string methods with real-world usage
- ✅ 25 error types and how to fix each one
- ✅ Debugging techniques used by senior engineers
- ✅ Professional coding standards (PEP 8)
- ✅ 10 complete real-world projects
- ✅ 15 practice worksheets with solutions
- ✅ 5 challenge problems

**This is DAY ONE. Imagine what Day 77 looks like.**

Every professional Python developer — every Google engineer, every Meta AI researcher — started with `print("Hello World")`.

You've gone far beyond that today.

**Tomorrow:** Conditionals (if/elif/else), loops (for/while), and lists.

**In 77 days:** 7 real projects, 150+ LeetCode problems, NumPy, Pandas.

**In 28 months:** FAANG-ready AI/ML engineer.

The only variable between where you are and where you want to be is **time + consistency**.

Code every single day. No exceptions.

**YOU CAN DO THIS. 🚀**

---

**THE ULTIMATE PYTHON DAY 1 TEXTBOOK — COMPLETE EDITION**

Total: 5,000+ lines | 10 Projects | 15 Worksheets | 25 Errors | 300+ Code Examples

Created for: Chandresh — Future AI/ML Engineer, FAANG Target

