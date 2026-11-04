print("===PYTHON TUTORIAL===")

print("[1] = Introduction to Programming")
print("[2] = Basic Syntax")
print("[3] = Arithmetic Operators")

score = 0
lesson = int(input("Enter a lesson: "))
if lesson == 1:
    print("[1] = Introduction to Programming")
    q1 = "Programming langauge is a special language that computers understand and perform a tasks."
    print(q1)
    user = input("Enter Answer (T OR F) :").upper()
    if user == "T":
        print("CORRECT")
        score += 1
    else:
        print("WRONG ANSWER, because the statement is correct.")
    q2 = "Python Programming is a widely-used programming language that was created by Guido van Rossum in 1990, he designed Python for the beginners."
    print(q2)
    user = input("Enter Answer (T OR F) :").upper()
    if user == "F":
        print("CORRECT")
        score += 1
    else:
        print("WRONG ANSWER, because Guido van Rossum created python in 1991")
elif lesson == 2:
    print("[2] = Basic Syntax")
    q1 = "Python Syntax refers to the set of rules that tells us how to correctly write a program in Python."
    print(q1)
    user = input("Enter Answer (T OR F) :").upper()
    if user == "T":
        print("CORRECT")
        score += 1
    else:
        print("WRONG ANSWER, because the statement is correct.")

    q2 = "Case Sensitive is that Python treats uppercase & lowercase letters not differently."
    print(q2)
    user = input("Enter Answer (T OR F) :").upper()
    if user == "F":
        print("CORRECT")
        score += 1
    else:
        print("WRONG ANSWER, because Case Sensitive is that Python treats uppercase & lowercase letters differently.")
    q3 = "Indentation is that unlike other programming languages, Python uses indentation (spaces) to define blocks of code."
    print(q3)
    user = input("Enter Answer (T OR F) :").upper()
    if user == "T":
        print("CORRECT")
        score += 1
    else:
        print("WRONG ANSWER, because the statement is correct.")

elif lesson == 3:
    print("[3] = Arithmetic Operators")







print(f"Total Score: {score}")
