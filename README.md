# student-grade-calculator
student grade calculator 
def calculate_grade(marks):
    if marks >= 90:
        return "A+"
    elif marks >= 80:
        return "A"
    elif marks >= 70:
        return "B"
    elif marks >= 60:
        return "C"
    elif marks >= 50:
        return "D"
    else:
        return "F"


marks = int(input("Enter your marks: "))

grade = calculate_grade(marks)

print("Marks:", marks)
print("Grade:", grade)