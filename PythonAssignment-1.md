## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans: Because they are not written in machine-readable language, Python programs need to be processed before machines can run them.

Q2. Why is Python called a dynamically typed language?

ans: Python don't have any problem even if we don't declare the type of variable. It states the kind of variable in the runtime of the program. Python also take cares of the memory management which is crucial in programming.

Q3. List some pros and cons of Python programming language?
Ans: 
Pros:
It's Highly Compatible.
It is Object-Oriented.
It has Lots of Libraries.
It has Built-in Data Structures.

Cons:
1. Poor Memory Efficiency
2. Slow Speed
5. Runtime Errors



Q4. In what all domains can we use Python?

Ans:
1. Data science 
2. automation
3. AI & Machine Learning 


Q5. What are variable and how can we declare them?

A Python variable is a symbolic name that is a reference or pointer to an object
Python has no command for declaring a variable. A variable is created when some value is assigned to it.

Q6. How can we take an input from the user in Python?
ans: using input() function

Q7. What is the default datatype of the value that has been taken as an input using input() function?
ans: string
Q8. What is type casting?
ans: It is used for converting from one data type to other. for example we can convert integer value to string using str() function.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ans: Using one input() function we can take only one input and we can split it to make a list of inputs but we cant take multiple inputs from same input funtion again and again from the user.

Q10. What are keywords?
Ans: Keywords are some predefined and reserved words in python that have special meanings.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans: No we cant use keyword as a variable because it will be interpreted as reserved keyword and will not be interpreted as variable.

Q12. What is indentation? What's the use of indentaion in Python?
Ans: Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.


Q13. How can we throw some output in Python?

using print() funtion

Q14. What are operators in Python?
Ans: Operators are special symbols in Python that carry out arithmetic or logical computation

Q15. What is difference between / and // operators?

Ans: / will return a float value if the divisor is not a multiple dividend and // will return floor value after division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
print("iNeuroniNeuroniNeuroniNeuron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

def oddOrEven(num):
    if num%2 == 0:
        return "Even"
    else:
        return "Odd"
num = int(input("Enter a number"))
Print(oddOrEven(num))

Q18. What are boolean operator?
Ans : Boolean operators are used as conjunctions to combine or exclude keywords in a search, resulting in more focused and productive results
Q19. What will the output of the following?
```
1 or 0 --> 1

0 and 0 ---> 0

True and False and True --> False

1 or 0 or 0 ---> 1
```

Q20. What are conditional statements in Python?
ans: used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans : if there is only one condition to check IF is used
      Elif is used if there is condition to check and action to be performed if the 1st if condtion fails
      else block will have the code to be executed if all the above conditions fail.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ans: 

age= int(input("enter age"))

if age>=18:
    print("I can vote")
else:
    print("I cant vote")    

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
def oddOrEven(num):
    if num%2 == 0:
        return True
    else:
        return False

summation=0
for num in numbers:
    if oddOrEven(num):
        summation+=num
print(summation)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ans:

L = input().split()
print(max(L))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

for num in numbers:
    if num> 500:
        break
    elif num>150:
        continue
    elif num % 5 ==0:
        print(num)
