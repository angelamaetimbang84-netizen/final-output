print("===PYTHON TUTORIAL===")

while True:
    print("")
    print("[1] = Introduction to Programming")
    print("[2] = Basic Syntax")
    print("[3] = Arithmetic Operators")
    print("[4] = If-Else Statements")
    print("[5] = Loops")
    print("====="*5)

    score = 0
    lesson = int(input("Enter a lesson: "))

    if lesson == 0 or lesson >5:
        print("That's it!")
        break

    if lesson == 1:
        total_quiz = 3
        print("")
        print("[1] = Introduction to Programming")
        q1 = "Programming langauge is a special language that computers understand to perform tasks."
        print("")
        print("Q1:", q1)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")
        q2 = "Python was created by Guido van Rossum in 1990 and designed for the beginners."
        print("Q2:", q2)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because it was created in 1991")
        q3 = "Python is a high-level, easy-to-read programming language."
        print("Q3:", q3)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER,because the statement is correct")

    elif lesson == 2:
        total_quiz = 4
        print("")
        print("[2] = Basic Syntax")
        q1 = "Python Syntax refers to the set of rules that tells us how to correctly write a program in Python."
        print("")
        print("Q1:", q1)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q2 = "Case Sensitive is that Python treats uppercase & lowercase letters not differently."
        print("")
        print("Q2:", q2)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because Case Sensitive is that Python treats uppercase & lowercase letters differently.")

        q3 = "Indentation is required in Python to define blocks of code."
        print("")
        print("Q3:", q3)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q4 = "A variable name can start with a number like: 1name."
        print("")
        print("Q4:", q4)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, must start with a letter or underscore.")

    elif lesson == 3:
        total_quiz = 5
        print("")
        print("[3] = Arithmetic Operators")
        q1 = "To add two numbers, use the + symbol."
        print("")
        print("Q1:", q1)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q2 = "The - symbol subtracts one number from another."
        print("")
        print("Q2:", q2)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q3 = "* is used for multiplication in Python."
        print("")
        print("Q3:", q3)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q4 = "/ gives the remainder of a division"
        print("")
        print("Q4:", q4)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, / is division: % is remainder.")

        q5 = "** is used for exponents, example: 2**3=8"
        print("")
        print("Q5:", q5)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, ** means-to the power of")

    elif lesson == 4:
        total_quiz = 6
        print("")
        print("[4] = If-Else Statements")
        print("")
        q1 = "An if block runs only when its condition is True"
        print("Q1:", q1)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q2 = "An else block runs when the if condition is True"
        print("Q2:", q2)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, else runs when the condition is false.")

        q3 = "In if-elif-else, Python checks conditions from top to bottom."
        print("Q3:", q3)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, checks top first.")

        q4 = "The == symbol means if two values are equal."
        print("Q4:", q4)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, == means 'is equal to'.")

        q5 = "The != symbol means 'is not equal to."
        print("Q5:", q5)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, != means 'is not equal to'.")

        q6 = "Nested Statement means you cannot put an if statement inside another if statement."
        print("Q6:", q6)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, nested statement you can put an if statement inside another if statement.")

    elif lesson == 5:
        total_quiz = 5
        print("")
        print("[5] = Loops")
        print("")
        q1 = "A loop repeats a block of code multiple times."
        print("Q1:", q1)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")


        q2 = "A 'for loop' repeats a fixed number of times."
        print("Q2:", q2)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q3 = "A 'while loop' repeats as long as a condition stays true."
        print("Q3:", q3)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "T":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, because the statement is correct.")

        q4 = "Never stop a loop once it starts."
        print("Q4:", q4)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, use 'break' to stop a loop.")

        q5 = "Loops cannot be nested."
        print("Q5:", q5)
        user = input("Enter Answer (T OR F) :").upper()
        if user == "F":
            print("CORRECT")
            score += 1
        else:
            print("WRONG ANSWER, nested loops are allowed, one loop inside another.")
    else:
        print("Invalid lesson number!")
        total_quiz = 0

    if total_quiz > 0:
        print(f"Total Score: {score}/{total_quiz}")

print("Congrats, learn from it!")
