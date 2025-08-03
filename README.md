# python-practice-questions
Solutions to basic Python practice questions including shape check, number comparison, attendance, and grading system.
# python-practice-questions
Solutions to basic Python practice questions including shape check, number comparison, attendance, and grading system.

# Question 1: Check if rectangle is square
length = float(input("Enter length: "))
breadth = float(input("Enter breadth: "))
if length == breadth:
    print("It is a square.")
else:
    print("It is not a square."
  


    # Question 2: Find greatest among three numbers
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))

if a >= b and a >= c:
    print("Greatest number:", a)
elif b >= c:
    print("Greatest number:", b)
else:
    print("Greatest number:", c)

    
# Question 3: Attendance check
attendance = float(input("Enter attendance percentage: "))
if attendance < 75:
    print("Not allowed to sit in exam.")
else:
    print("Allowed to sit in exam.")


# Question 4: Grading system
marks = float(input("Enter your marks: "))
if marks < 25:
    grade = "F"
elif marks <= 44:
    grade = "E"
elif marks <= 49:
    grade = "D"
elif marks <= 59:
    grade = "C"
elif marks <= 79:
    grade = "B"
elif marks <= 89:
    grade = "A"
else:
    grade = "A+"

print("Your grade is:", grade)

