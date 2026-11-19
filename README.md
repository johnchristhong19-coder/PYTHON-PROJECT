print("====================================================")
print("             WELCOME TO PYTHON TUTORIAL             ")
print("             LET'S TEST YOUR KNOWLEDGE              ")
print("====================================================")
print("")
input("NAME:")
input("YEAR & SECTION:")
print("")
print("====================================================")
print("                        START                       ")
print("====================================================")

while True:
   
    print("")
    print("PICK A LESSON:")
    print("""
    PRELIM LESSONS
          1.INTRODUCTION TO PROGRAMMING
          2.PYTHON BASIC SYNTAX
          3.ARITHMETIC OPERATORS AND EXPRESSION
          4.BASIC INPUT AND OUTPUT IN PYTHON
    MIDTERM LESSONS      
          5.CONDITIONAL STATEMENT IN PYTHON
          6.LOGICAL OPERATORS
    FINALS LESSON      
          7.INTRODUCTION TO ITERATION AND LOOPS
          8.EXIT                                  """)
         
    lesson = int(input("CHOOSE A LESSON (0-8): "))
   
    #EXIT
    if lesson == 0 or lesson == 8:
        print("THANK YOU FOR TRYING PYHTON TUTORIAL")
        break
   
    #LESSONS
    elif lesson == 1:
        print("============================================")
        print("        INTRODUCTION TO PROGRAMMING         ")
        print("============================================")
        print("""Python is a widely used, high-level, interpreted, and general-purpose programming language.
        It was created by Dutch software engineer Guido van Rossum in 1991. Python was designed to make programming simple, readable, and easy to learn while remaining powerful for professional software development.
        It is a great programming language for beginners because its syntax is easy to understand and looks almost like English.
        Python is also versatile and can be used in different fields such as artificial intelligence, web development, automation, and game development.
        Another reason to learn Python is its large community, which provides support, tutorials, and libraries. To start learning Python programming, you need a computer and a suitable programming environment.
        Some popular professional IDEs and code editors for Python are PyCharm, Visual Studio Code (VS Code), and Jupyter Notebook or JupyterLab.
        These tools help programmers write, edit, run, and test their Python code. Overall, Python is a useful and beginner-friendly programming language that helps people develop their programming skills
        and create different kinds of applications.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        N O H T Y P
       
        A popular programming language created by Guido van Rossum""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "python":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is python")
           
        #WORD2
        print("""
       
        M A R G O P R
       
        A thing who writes and develops computer program""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "program":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is program")
           
        #WORD3
        print("""
       
        M A H R C Y P
       
        A professional IDE used for Python programming""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "pycharm":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is pycharm")
           
        #TOTAL score
        print("\n=============GAME SCORE================")
        print("Your total score:", score, "/ 3")
       
        if score == 3:
            print("EXCELLENT!")
        elif score == 2:
            print("GOODJOB!")
        elif score == 1:
            print("NICE TRY!")
        else:
            print("TRY AGAIN!")
           
    elif lesson == 2:
        print("============================================")
        print("            BASIC PYTHON SYNTAX             ")
        print("============================================")
        print("""Data types are categories that tell Python what kind of data a variable stores.
        The four basic data types in Python are integer (int), float, string (str), and Boolean (bool).
        An integer represents whole numbers, while a float represents decimal numbers. A string contains text or characters inside quotation marks, while a Boolean represents True or False values.
        In programming, variables are used to store data, and we assign values to them using the equal sign, which is called the assignment operator.
        A variable is a named storage location used to keep data in a program, and its value can change while the program is running.
        Variable names are case-sensitive, which means that age and AGE are considered two different variables.
        A variable name must start with a letter or an underscore and cannot start with a number. Variable names can be short, like x and y, or descriptive, like age, carname, and total_volume.
        Lastly, Python's print() function is used to display information such as your full name, age, favorite subject, dream job, inspirational quote, and creative ASCII art without using variables or the input() function.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        T I N E G R E
       
        A data type that represents whole numbers.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "integer":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is integer")
           
        #WORD2
        print("""
       
        A B L E V I R A
       
        A named storage location used to keep data in a program""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "variable":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is variable")
           
        #WORD3
        print("""
       
        T A F O L
       
        A data type that represents decimal number""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "float":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is float")
           
        #TOTAL score
        print("\n=============GAME SCORE================")
        print("Your total score:", score, "/ 3")
       
        if score == 3:
            print("EXCELLENT!")
        elif score == 2:
            print("GOODJOB!")
        elif score == 1:
            print("NICE TRY!")
        else:
            print("TRY AGAIN!")
           
    elif lesson == 3:
        print("============================================")
        print("    ARITHMETIC OPERATORS AND EXPRESSION     ")
        print("============================================")
        print("""Arithmetic operators are symbols used in Python to perform mathematical calculations on numbers much like everyday math. They include addition, subtraction, multiplication, float division, floor division, modulus, and exponentiation, each serving a distinct purpose such as finding a remainder or raising a value to a power.
        When values, variables, and operators are combined to evaluate a result, they form an expression in Python. To evaluate expressions accurately, Python follows the order of operations known as PEMDAS, starting with parentheses and exponents before moving through multiplication, division, addition, and subtraction. For example, in an expression where a = 2, b = 3, and c = 4, multiplying b * c first yields 12, and adding a gives a final result of 14.
        Similarly, adding a = 10 and b = 5 in a basic program evaluates to 15 and displays the output. Practical exercises apply these concepts by storing numbers in variables to compute useful values, such as finding an average grade from math, science, and English scores. Geometry exercises also rely on variables and expressions, using formulas like length * width for area and 2 * (length + width) for perimeter. With a length of 12 and a width of 8, a rectangle produces an area of 96 and a perimeter of 40.
        Mastering operators, expressions, and PEMDAS equips programmers to solve real-world computational problems clearly and reliably.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        T O R E P O A R
       
        These symbols are used on numbers to perform mathematical calculations like addition, subtraction, and multiplication.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "operator":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is operator")
           
        #WORD2
        print("""
       
        S E R X P S I O N E
       
        This is a combination of values, variables, and operators in python that evaluates to result.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "expression":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is expression")
           
        #WORD3
        print("""
       
        S D M E P A
       
        This is the order of operations that python follows, beginning with paranthesis and exponents and ending with subtraction""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "pemdas":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is pemdas")
           
        #TOTAL score
        print("\n=============GAME SCORE================")
        print("Your total score:", score, "/ 3")
       
        if score == 3:
            print("EXCELLENT!")
        elif score == 2:
            print("GOODJOB!")
        elif score == 1:
            print("NICE TRY!")
        else:
            print("TRY AGAIN!")
           
    elif lesson == 4:
        print("============================================")
        print("     BASIC INPUT AND OUTPUT IN PYTHON       ")
        print("============================================")
        print("""Accepting user input in programming allows software to communicate with users, much like asking someone for their name and responding in everyday conversation.
        In Python, the input() function captures user responses using the syntax variable = input("Prompt message: ").
        Because input() stores every response as a string by default, programs often need to convert values into other data types before processing them.
        For instance, converting input into a float lets a program handle decimal values such as a student's grade. Programs can also format and display gathered values clearly by separating text and variables with commas inside print().
        By evaluating conditions on user answers—such as checking answer.lower() == "yes"—developers can create boolean values that represent True or False.
        Combining string, integer, and float inputs in one script makes it possible to collect multiple details and display them together using formatted output.
        Beginners can practice these concepts through mini exercises focused on variables, print statements, and basic arithmetic operations. Building a simple final grade calculator is a practical way to apply input handling and calculations together.
        Ultimately, understanding user input, output formatting, and type conversion helps programmers write responsive and useful Python applications.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        R P T O M P
       
        This is the message shown inside input to guide the user on what information to enter """)
       
        answer = input("ANSWER:")
       
        if answer.lower() == "prompt":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is prompt")
           
        #WORD2
        print("""
       
        T R I N G S
       
        This is the default data types of every value returned by python's input function""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "string":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is string")
           
        #WORD3
        print("""
       
        R I P T N
       
        This python function displays output on the screen and can use commas to format multiple items.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "print":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is nested")
           
        #TOTAL score
        print("\n=============GAME SCORE================")
        print("Your total score:", score, "/ 3")
       
        if score == 3:
            print("EXCELLENT!")
        elif score == 2:
            print("GOODJOB!")
        elif score == 1:
            print("NICE TRY!")
        else:
            print("TRY AGAIN!")
           
    elif lesson == 5:
        print("============================================")
        print("     CONDITIONAL STATEMENT IN PYTHON        ")
        print("============================================")
        print("""Conditional statements allow a Python program to make decisions based on whether a condition evaluates to True or False. To test values, programs use relational or comparison operators—such as ==, !=, >, <, >=, and <=—which always return either True or False.
        An if statement runs an indented block of code only when its condition is True, skipping the block when the condition is False.
        When you want an alternative action if the if condition is False, you can add an else block so that only one path is executed. For multiple conditions, the if-elif-else structure checks conditions from top to bottom and executes the block for the first True condition before skipping the rest.
        If none of the if or elif conditions are True, Python runs the else block as a fallback. Developers can also place one condition inside another to create a nested condition, where an inner condition is checked only if the outer condition is True. For example, determining debutant eligibility can first check gender and then check whether a male is at least 21 or a female is at least 18.
        Practice exercises like age classification apply if-elif-else to sort ages into ranges while handling invalid or negative inputs. Together, comparison operators and conditional structures enable programs to respond dynamically to different inputs and scenarios.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        N I C O D T I N O
       
        This expression or rule is evaluated as True or False to decide which code block runs in a decision statement. """)
       
        answer = input("ANSWER:")
       
        if answer.lower() == "condition":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is condition")
           
        #WORD2
        print("""
       
        L E S E
       
        This keyword provides an alternative block of code when an if condition—or all preceding conditions—evaluates to False.  """)
       
        answer = input("ANSWER:")
       
        if answer.lower() == "else":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is else")
           
        #WORD3
        print("""
       
        S T E D N E
       
        This describes a condition placed inside another condition so that the inner check runs only if the outer condition is true.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "nested":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is nested")
           
        #TOTAL score
        print("\n=============GAME SCORE================")
        print("Your total score:", score, "/ 3")
       
        if score == 3:
            print("EXCELLENT!")
        elif score == 2:
            print("GOODJOB!")
        elif score == 1:
            print("NICE TRY!")
        else:
            print("TRY AGAIN!")

    elif lesson == 6:
        print("============================================")
        print("            LOGICAL OPERATORS               ")
        print("============================================")
        print("""Logical operators in Python are used to combine or reverse conditions, often working alongside if, elif, and else statements. The three logical operators in Python are and, or, and not.
        The and operator requires all combined conditions to be True in order to return True, returning False if any condition is False. For example, checking if a person is at least 18 and has an ID evaluates to True only when both requirements are met.
        By contrast, the or operator returns True whenever at least one condition is True, and only returns False when both conditions are False. A program checking whether a day is "Saturday" or "Sunday" evaluates to True when either condition matches.
        The not operator reverses the boolean result of a condition, turning True into False and False into True. For instance, if is_raining is False, then not is_raining becomes True and allows the program to print that you can go outside.
        Truth tables make these behaviors easy to visualize and remember across all possible true and false combinations. Mastering and, or, and not helps programmers combine multiple conditions and build practical real-life decision-making programs.""")
        print("")
        print("==============JUMBLED WORDS GAME===============")
       
        score = 0
       
        #WORD1
        print("""
       
        N D A
       
        This logical operator returns True only when all combined conditions are True.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "and":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is and")
           
        #WORD2
        print("""
       
        R O
       
        This logical operator returns True when at least one condition is True.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "or":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is or")
           
        #WORD3
        print("""
       
        T O N
       
        This logical operator reverses a condition's result, changing True to False and False to True.""")
       
        answer = input("ANSWER:")
       
        if answer.lower() == "not":
            print("CORRECT!")
            score = score + 1
        else:
            print("WRONG! The correct answer is not")
           
        #TOTAL score
        print("\
