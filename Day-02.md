#  Day 2 – Python Variables and Data Types

## 1. What is a Variable?

A variable is a name used to store data in a program.

Example:age = 21
name = "Pooja"
print(age)
print(name)
**Output:**
21
Pooja
- `age` and `name` are variable names.
- `=` is the assignment operator.
- `21` and `"Pooja"` are stored values.

**Remember:**
- `print(name)` displays the stored value.
- `print("name")` displays the text `name`.

## 2. Rules for Naming Variables

1. Variable names cannot start with numbers.
2. Spaces are not allowed.
3. Special characters like `@` and `$` are not allowed.
4. Python keywords cannot be used as variable names.
5. Variable names are case-sensitive.

Correct  variables :'name','student_age','marks1' 
Incorrect variables  `2name` ,`student age`,`marks@` 

Example:
age = 20
Age = 25

print(age)
print(Age)

**Output:**
20
25

## 3. What are Data Types?

Data types tell Python what kind of value is stored in a variable.

### Six Important Python Data Types

| Data Type | Meaning | Example |

1.int : Whole numbers
2. float :Decimal numbers
3. str :Text 
4. bool : True or False 
5. list : Collection of values 
6.dict : Key-value pairs 

### Examples

**Integer and Float**
age = 21
marks = 85.5
print(age)
print(marks)

**String and Boolean**
name = "Pooja"
is_student = True
print(name)
print(is_student)

**List**
subjects = ["Python", "Java", "SQL", "HTML"]
print(subjects)

**Dictionary**
student = {
    "name": "harini",
    "age": 22,
    "branch": "ISE"
}
print(student)

## 4. How to Check Data Types?

Python provides the built-in `type()` function to identify the data type of a value.

Example:
name = "Pooja"
age = 21
marks = 85.5
is_student = True

print(type(name))
print(type(age))
print(type(marks))
print(type(is_student))

**Output:**
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>

## 5. Practical Program – Student Information
name = "Pooja"
age = 21
branch = "ISE"
marks = 90.5
is_student = True

print("Student Name:", name)
print("Age:", age)
print("Branch:", branch)
print("Marks:", marks)
print("Is Student:", is_student)

**Output:**
Student Name: Pooja
Age: 21
Branch: ISE
Marks: 90.5
Is Student: True

## 6. What I Learned Today

- Understood Python variables.
- Learned how to store and display values.
- Learned variable naming rules.
- Understood six important data types.
- Practised the `type()` function.
- Created a student information program.

## 7. Tomorrow's Learning Goal

Learn Python Operators:
- Arithmetic Operators
- Comparison Operators
- Logical Operators
- Assignment Operators

---

**Day 2 completed! 🚀**

#Python #Variables #DataTypes #Coding #LearningJourney #GitHub
