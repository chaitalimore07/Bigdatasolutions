Q1. Why do we call Python as a general purpose and high-level programming language?
--> Python is easy to utilize,powerful,and versatile,making it a great cull for beginners and experts kindred.
    Python readability makes it a great first programming language-it sanctions you to think like a programmer and not waste time with confusing syntax.
    Python is great for backend web development,data analysis,artificial intelligence,and scientific computing.


--------------------------------------------------------------------------------------------------------------------
Q2. Why is Python called a dynamically typed language?
--> In Python there is no need to declare the type of the variable.Because the type checking takes place during run time only.
    Therefore python is called as dynamically typed language.

--------------------------------------------------------------------------------------------------------------------
Q3. List some pros and cons of Python programming language?
--> The pros of Python:
                       > Python is easy to learn and read.
 		       > Python enhances the productivity.
                       > It has a vast collection of libraries.
		       > It is free,open-source,and has a vibrant community.
		       > It is a portable programming language.
    The cons of python:
		       > Python has speed limitations.
		       > Python can have runtime errors.
		       > It comsumes a lot of memory space.
                       > It is not easy to test. 

--------------------------------------------------------------------------------------------------------------------
Q4. In what all domains can we use Python?
--> Python is used as programming language for domains such as artificial intelligence, machine learning and deep learning and also a fundamental tool for any data scientist.


--------------------------------------------------------------------------------------------------------------------
Q5. What are variable and how can we declare them?
--> Python variable is container which store values or A Python variable is only a name given to a memory location.
    For declaring variable: 
 			   first name the variable and then assign required value to it. 
			   The data type of the variable will be automatically determined from the value assigned,we need not define it explicitly.
           For ex:  To declare an integer variable 
                     x = 4
                     print(x)
		     print(type(x))
		Here X is the variable name & value assign to it is 4.
		Output will be:  4
				< class 'int'>


--------------------------------------------------------------------------------------------------------------------
Q6. How can we take an input from the user in Python?
--> In python, we use input function to take input from the user.Whatever you enter as input,the input function converts it into a string.If you enter an integer value
    still input()function convert it into a string.
   for example:
		# Take input from the user
		name = input()
		print(name)
   Output: Shreya
 # Taking input from the user:
     name = input("Enter the name:")
     print(name)
  Output: Enter the name:Rohit
     	  Rohit

--------------------------------------------------------------------------------------------------------------------
Q7. What is the default datatype of the value that has been taken as an input using input() function?
--> By default input() function takes the user's input in a string.So,to take the input in the form of int you need to use int()
    along with the input function.
    for example:
   # Taking input from the user as integer
     num = int(input("Enter the number:")
     add = num + 1
   # Output
    print(add)

   Output:  Enter the number: 15
   16


--------------------------------------------------------------------------------------------------------------------
Q8. What is type casting?
--> Type casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.or Method to convert one data type into another data type.


--------------------------------------------------------------------------------------------------------------------
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
-->  Yes.
     Python user can take multiple values or inputs in one line by two methods. 

     Using split() method : 
     This function helps in getting multiple inputs from users. It breaks the given input by the specified separator. If a separator is not provided then any white space is a separator. Generally, users use a split() method to split a Python string but one can use it in taking multiple inputs.
        Syntax : 

	    input().split(separator, maxsplit)

        Example :
		
	# Python program showing how to
	# multiple input using split
	  
	# taking two inputs at a time
	x, y = input("Enter two values: ").split()
	print("Number of boys: ", x)
	print("Number of girls: ", y)
	print()
  
	# taking three inputs at a time
	x, y, z = input("Enter three values: ").split()
	print("Total number of students: ", x)
	print("Number of boys is : ", y)
	print("Number of girls is : ", z)
	print()
  
	# taking two inputs at a time
	a, b = input("Enter two values: ").split()
	print("First number is {} and second number is {}".format(a, b))
	print()
  
	# taking multiple inputs at a time 
	# and type casting using list() function
	x = list(map(int, input("Enter multiple values: ").split()))
	print("List of students: ", x) 



    Using List comprehension : 
    List comprehension is an elegant way to define and create list in Python. We can create lists just like mathematical statements in one line only. It is also used in getting multiple inputs from a user. 

	Example :
	# Python program showing
	# how to take multiple input
	# using List comprehension
  
	# taking two input at a time
	x, y = [int(x) for x in input("Enter two values: ").split()]
	print("First Number is: ", x)
	print("Second Number is: ", y)
	print()
  
	# taking three input at a time
	x, y, z = [int(x) for x in input("Enter three values: ").split()]
	print("First Number is: ", x)
	print("Second Number is: ", y)
	print("Third Number is: ", z)
	print()
  
	# taking two inputs at a time
	x, y = [int(x) for x in input("Enter two values: ").split()]
	print("First number is {} and second number is {}".format(x, y))
	print()
  
	# taking multiple inputs at a time 
	x = [int(x) for x in input("Enter multiple values: ").split()]
	print("Number of list is: ", x)

--------------------------------------------------------------------------------------------------------------------
Q10. What are keywords?
-->  Python keywords are special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes.
	list of the Python keywords.  

	False               class               from                or
	None                continue            global              pass
	True                def                 if                  raise
	and                 del                 import              return
	as                  elif                in                  try
	assert              else                is                  while
	async               except              lambda              with
	await               finally             nonlocal            yield
	break               for                 not

--------------------------------------------------------------------------------------------------------------------
Q11. Can we use keywords as a variable? Support your answer with reason.
--> Keywords are predefined, reserved words used in Python programming that have special meanings to the compiler.
    We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.


--------------------------------------------------------------------------------------------------------------------
Q12. What is indentation? What's the use of indentaion in Python?
-->  Indentation is the spaces at the beginning of the code line.Python uses indentation to indicate a block of code.
      Without properly indenting the python code,you will end up seeing IndentationError and the code will not get compiled.

--------------------------------------------------------------------------------------------------------------------
Q13. How can we throw some output in Python? 
--> We can throw output in command using print command.
	Example : 
	  string='iNeuron'

   	  result=string+string+string+string
	  print (result)

	Output : 
	  iNeuroniNeuroniNeuroniNeuron

--------------------------------------------------------------------------------------------------------------------
Q14. What are operators in Python?
-->  In Python,operators are special symbols that designate that some sort of computation should be performed.
     Operators are used to perform operations on variable and values.
     for ex: we use '+' operator to add together two values.
     The type of the operators are:
  			           1. Numerical operator
			           2. Assignment Operator
			           3. Comparison Operator
			           4. Logical Operator

--------------------------------------------------------------------------------------------------------------------
Q15. What is difference between / and // operators?
-->  In Python,you can perform division in two ways.The first one is float division("/") and second one is Integer division("//")
     or Floor division.
     In float division,if we performed some operation like 5/2 = 2.5 , here the number after the decimal point is taken into consideration.
     & In Integer division the number after the decimal point is not consider
       ex:  5/2 = 2 


---------------------------------------------------------------------------------------------------------------

Q16. Write a code that gives following as an output.
iNeuroniNeuroniNeuroniNeuron
-->
	string='iNeuron'

	result=string+string+string+string
	print (result)

Output : 
	iNeuroniNeuroniNeuroniNeuron


-----------------------------------------------------------------------------------------------------------------

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
-->
	num = int (input ("Enter the number: "))

	if num%2==0:
	    print ('It is even number.')
	elif num%2!=0:
	    print ('It is odd number.')

Output :

	Enter the number: 5
	It is odd number.
	PS C:\Users\Sai> & C:/Users/Sai/AppData/Local/Programs/Python/Python38-32/python.exe "c:/Users/Sai/Desktop/Bigdata Bootcamp 2.O/Python/file.py"
	Enter the number: 80
	It is even number.

-----------------------------------------------------------------------------------------------------------------

Q18. What are boolean operator?
--> Boolean Operators are simple words (AND, OR, NOT or AND NOT) used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results. This should save time and effort by eliminating inappropriate hits that must be scanned before discarding. 

--------------------------------------------------------------------------------------------------------------------

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
-->  The output of 1 or 0 is True.
     The output of 0 and 0 = False
     The output of True and False and True  = False
     The output of 1 or 0 or 0 = True



--------------------------------------------------------------------------------------------------------------------

Q20. What are conditional statements in Python?
--> Python has three key coditional statement: if statement
					      > if-else statement
				              > if-elif-else statement


--------------------------------------------------------------------------------------------------------------------
Q21. What is use of 'if', 'elif' and 'else' keywords?
-->  If-elif-else statement is used in Python for dicision making.That is the program will evaluate test expression and will execute the
     remaining statement only if the given test expression turns out to be true.This allows validation for multiple expressions.


--------------------------------------------------------------------------------------------------------------------
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
-->
	age = int (input ("Enter the age of person: "))

	if age >= 18:
	    print ('I can vote.')
	else:
	    print  ("I can't vote")

--> Output:

	PS C:\Users\Sai> & C:/Users/Sai/AppData/Local/Programs/Python/Python38-32/python.exe "c:/Users/Sai/Desktop/Bigdata Bootcamp 2.O/Python/file.py"
	Enter the age of person: 22
	I can vote.
	PS C:\Users\Sai> & C:/Users/Sai/AppData/Local/Programs/Python/Python38-32/python.exe "c:/Users/Sai/Desktop/Bigdata Bootcamp 2.O/Python/file.py"
	Enter the age of person: 17
	I can't vote

----------------------------------------------------------------------------------------------------------------

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]

-->

	numbers = [12, 75, 150, 180, 145, 525, 50]

	sum=0

	for i in numbers :
	    if i%2==0:
	        sum = sum + i

	print(sum)

Output : 392


-------------------------------------------------------------------------------------------------------------------

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

-->	a=int (input("Enter 1st number="))
	b=int (input("Enter 2nd number="))
	c=int (input("Enter 3rd number="))

	if a > b and a > c:
	    largest=a
	if b > a and b > c:
	    largest=b
	if c > a and c > b:
	    largest=c

	print(largest,"is the largest number among", a, b, c)

Output :

	PS C:\Users\Sai> & C:/Users/Sai/AppData/Local/Programs/Python/Python38-32/python.exe "c:/Users/Sai/Desktop/Bigdata Bootcamp 2.O/Python/file.py"
	Enter 1st number=1
	Enter 2nd number=2
	Enter 3rd number=10
	10 is the largest number among 1 2 10

--------------------------------------------------------------------------------------------------------------------


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

-->

	numbers = [12,75,150,180,145,525,50]

	for num in numbers:
	    if num%5==0:
	        if num>500:
	           break
	        elif num>150:
	           continue
	        else:
	             print(num)

Output : 
	PS C:\Users\Sai> & C:/Users/Sai/AppData/Local/Programs/Python/Python38-32/python.exe "c:/Users/Sai/Desktop/Bigdata Bootcamp 2.O/Python/file.py"
	75
	150
	145


