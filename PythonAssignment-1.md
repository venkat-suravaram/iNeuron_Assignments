## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
	Python works well for everywhere ,can be used in any field like science, accouting, network , programmed in 
	easy to read struicture called High-level lang later interpreted into low level language, which can run on any
	computer without any modifications.

Q2. Why is Python called a dynamically typed language?
	The type of variable is determined only during runtime.Doesn't have to declare the type of variable, it stats the
	kind during runtime
	
	It stores that value at some memory location and then binds that variable name to that memory container. And makes the contents
 	of the container accessible through that variable name. So the data type does not matter. As it will get to know 
	the type of the value at run-time.

Q3. List some pros and cons of Python programming language?
	Pros:Open-source , easy to read, Dynamically typed, Interpreted, Portability , extensive libraries
	Cons: slow execution, not memory efficient, Need improvements in DB access 
	
	Due to interpreted ,Dynamically typed (line by line execution of code often leads to slow execution.
	Uses large amount of Memory.
	Due to dynamically typed lang, A variable containing integer number may hold a string in the future, which can lead to Runtime Errors.
	The Python’s database access layer is primitive and underdeveloped in comparison to the popular technologies like JDBC and ODBC

Q4. In what all domains can we use Python?
	Python can be used in everywhere ( all fields)

Q5. What are variable and how can we declare them?
	Variable is a name given to a specific memory location / Container for storing value.
	A Python variable is a symbolic name that is a reference or pointer to an object. Once an object is assigned to a variable, you can refer to the object by that name. But the data itself is still contained within the object.
		A = 5 (variable declaration & assignment )
		Int_var = 10 // Old: int a = 10;
		Float_var = 18.25


Q6. How can we take an input from the user in Python?
	Input or feed data to Python using function - input()
	a=input()
	print(type(a))

Q7. What is the default datatype of the value that has been taken as an input using input() function?
	Answer: <class 'str'>

Q8. What is type casting?
	Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
	Yes , x, y = input().split()

Q10. What are keywords?
	Python has a set of keywords that are reserved words that cannot be used as variable names, function names, or any other identifiers
	Ex. def, del, elif, else, False, global, raise

Q11. Can we use keywords as a variable? Support your answer with reason.
	Python has a set of keywords that are reserved words that cannot be used as variable names.

Q12. What is indentation? What's the use of indentaion in Python?
	Python relies on indentation (whitespace at the beginning of a line) to define scope in the code. Other programming languages often use curly-brackets for this purpose.Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
	Using print() function

Q14. What are operators in Python?
	Operators are used to perform operations on variables and values.
	In the example below, we use the + operator to add together two values:
	Arithmetic / Numeric operators
	Assignment operators
	Compare operators
	Logical operators
	Identity operators
	Membership operators
	Bitwise operators


Q15. What is difference between / and // operators?
	# / for float division - Divide left operand by the right one which always results into float
	# // for integer division - division that results into whole number adjusted to the left in the number line

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
	a='iNeuron'
	print(a*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
	number=int(input("Enter the number:"))
	if number%2==0:
    	print("It is a even number")
	else: print("It is a odd number")

Q18. What are boolean operator?
	Logical operators: ( logical check happen for expression results ) 
	The logical operators and, or and not are also referred to as boolean operators
	and     -> returns true if both statements are true    x < 5 and  x < 10
 	or       ->      returns true if one of the statement is true     x < 5 or x < 4
 	not    -> returns the result, returns false if the result is true   not(x < 5 and x < 10)

Q19. What will the output of the following?
```
	1 or 0 = True

	0 and 0 = True

	True and False and True = False

	1 or 0 or 0 = True
```

Q20. What are conditional statements in Python?
	Python supports the usual logical conditions from mathematics:
	Equals: a == b
	Not Equals: a != b
	Less than: a < b
	Less than or equal to: a <= b
	Greater than: a > b
	Greater than or equal to: a >= b
	In python there are 3 conditional statemts if,if-else,if-elif-else

Q21. What is use of 'if', 'elif' and 'else' keywords?
	If :The keyword if evaluates as true, the block of code will execute 
	Elif:Multiple conditions can be checked by including one or more elif checks after your initial if statement. But these statements will be executed 
	Else:It is an optional to add an else response that will execute if the condition is false

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	Age=int(input("EnterAge:"))
	ifAge>=18:
	print("Icanvote")
	elifAge<18:
	print("Itisaoddnumber")
	

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
	numbers=[12,75,150,180,145,525,50]
	n2=[]
	foriinnumbers:
	ifi%2==0:
	n2.append(i)
	print(n2)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
	x,y,z=input(),input(),input()
	print(max(x,y,z))
	
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
	numbers=[12,75,150,180,145,525,50]
	For x in numbers:
	If x%5==0:
	print(x)
	For x in numbers:
	If x>150:
	print(x)
	For x in numbers:
	Print(x)
	If x > 500 :
	Break
