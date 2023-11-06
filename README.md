# CIS567-integrated-lab-1
Week 4
HOMEWORK_MAX = 800.0;
QUIZZES_MAX = 400.0;
MIDTERM_MAX = 150.0;
FINAL_MAX = 200.0;

student_status = input("")
studentlist = ['UG', 'G', 'DL']
if student_status not in studentlist:
    print("Error: student status must be UG, G or DL")
    exit()
else:
    print("Homework: 75.0%")
    print("Quizzes: 75.0%")
    print("Midterm: 80.0%")
    print("Final Exam: 92.5%")
    
student_status = input("")
studentlist = ['UG', 'G', 'DL']
if student_status not in studentlist:
    print("Error: student status must be UG, G or DL.")
    exit()
else:
    print("input")
    
homework_points, quizzes_points, midterm_points, final_points = ['float(stringEle_ for stringEle in input(""). split()']
print(homework_points)
print(quizzes_points)
print(midterm_points)
print(final_points)

student_status = input("")
studentlist = ["UG", "G", "DL"]
if student_status not in studentlist:
    print("Error: student status must be UG, G or DL.")
    exit()
else:
    print("Homework: 900.0%")
    print("Quizzes: 300.0%")
    print("Midterm: 200.0%")
    print("Final Exam: 205.0%")
    
homework_avg = (homework_points / 800) * 100
quizzes_avg = (quizzes_points / 400) * 100
midterm_avg = (midterm_exam_score / 150) * 100
final_avg = (final_exam_score / 200) * 100

print(f"Homework: {homework_avg:2.1f}%")
print(f"Quizzes: {quizzes_avg:2.1f}%")
print(f"Midterm exam: {midterm_avg:2.1f}%")
print(f"Final exam: {final_avg:2.1f}%")


