## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans - Python is called a general purose and high-level programming language because of its easy to read and comprehend format. High-level proramming language are closer to natural language like English 

Q2. Why is Python called a dynamically typed language?

Ans - It is called a dynamically typed language because the interpretor determines the type of the initiated varible only during runtime.

Q3. List some pros and cons of Python programming language?

Ans - Pros: 
a) easy to learn & understand high level programming language
b) dynamic and portable
c) diverse applications in almost all domains, eg - web structures, gaming apps, data science & ML/AI, fullstack engineering etc
d) extensive support for libraries & packages
e) enhanced intergration with other tools like MySQL, Spark, C++, Java etc.

Cons:
a) due to flexibility in data types, python has a relatively larger memory consumption
b) being a high level language, it is distant to machine level language and thus makes it less efficient when it comes to processing time
b) its easy to read and understand nature might prove difficult for coders to learn/adapt to much complex programming languages in future as they get accustomed to it


Q4. In what all domains can we use Python?

Ans - It can be used in multiple domains listed below but not limited to -
a) Machine learning and AI
b) Data Analytics & Visualization
c) Web development 
d) Game development
e) Embedded Systems & IOT
f) Software development

Q5. What are variable and how can we declare them?

Ans - Variables are declarables which can be defined in python and they store values. They are basically container for storing data values and points to a specific memory location. It can be either be string variable or numeric variable or float (decimal) variable.
Declaring a varibale is very easy in Python and can be done in the following steps -
a) define the varible
b) assign a value to it

Using above two steps, one can create and declare a variable in Python.

Q6. How can we take an input from the user in Python?

Ans - To take an input from user in Python, we have to use predefined 'input()' function. 

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans - String

Q8. What is type casting?

Ans - Type casting is used to convert one datatype to another datatype. Multiple predefined functions are there in Python for this - int(), float(), set(), etc.
For ex- by using typecasting you can change a variable which stores 38 as an integer to a different type which is specified by the user. 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans - We can take more than one input using single input() function. For this we can ask the user to provide the multiple input he has separated by a comma (or any different delimiter). Laer on, we can
use inbuilt split() function to split the input string at each comma.
In a scenario where a Python is supposed to take a limited and relatively smaller amount of input from the user, a user can use split() function in series with input function. But for this we need to initiate the required number of variables accordingly.

Q10. What are keywords?

Ans - Keywords are those specially reserved words which are used in prior by the Python language to have some meaning or to define the syntax of the code. User won't be able to use any keywords as a 
variable, user-defined functions etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans - As stated above, keywords can not be used as a variable. The reason for this is that they are predefined and have meaning to the structure and syntax of Python language.

Q12. What is indentation? What's the use of indentaion in Python?

Ans - Indentation is used to create whitespace at the start of code line. It is done so to -
a) identify a block of code 
b) have easier readability

Q13. How can we throw some output in Python?

Ans - By using predefined print() function

Q14. What are operators in Python?

Ans - Operators are special symbolic characters in Python which are used to preform different calculations or operations. Different type of operators - Arithmetic, Logical, Assignment, Bitwise, Comparison, etc.

Q15. What is difference between / and // operators?

Ans - Operator / provides the output as a normal division. output data type is float regardless of data type of operands
Operator // provide the ouput as a floor division i.e., quotient is returned when using // operator. output data type can be int or float depending on the initial values of operands

Q16. Write a code that gives following as an output.

```
iNeuroniNeuroniNeuroniNeuron
```
Ans - Code below --

```
print("iNeuron" * 4)
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans - Code below --


```x = int(input("Provide the number: "))

if x%2 == 0:
  print("The given number is even")
else:
  print("The given number is odd")
```

Q18. What are boolean operator?

Ans - The logical operators 'and', 'or' and 'not' are also referred to as boolean operators. They are used to perform conditional operations and to return the output as either TRUE or FALSE depending on whether the conditions are met or not.

Q19. What will the output of the following?
```
1 or 0 -- 1

0 and 0 -- 0

True and False and True -- False

1 or 0 or 0 -- 1
```
Ans - The answer for each logical computation is mentioned above after the hyphen

Q20. What are conditional statements in Python?

Ans - Conditional statements are used to guide the Python program in deciding the outcome of a given statement depending on the conditions encountered by the program. In short, it is used to handle conditions. There are three major condition handling statement types in python - 'if', 'if-else', 'nested if-else'

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans - 'if', 'elif', 'else' are called conditional statement keywords and are used to direct the flow of Python program. They help in decision making based on the multiple conditions that are mentioned in the program. Based on whether the mentioned conditions are met or not, the respective statements will be executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans - Code below --

```
x = int(input("Provide your age: "))

if x >=18:
  print("I can vote")
else:
  print("I can't vote")
```

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans - Code below --

```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for i in numbers:
  sum = sum + i

print(sum)
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans - Code below --

```
x,y,z = (input("Provide any three numbers: ")).split()

x = int(x) 
y = int(y)
z = int(z)

if x > y and x > z:
  print(x, "is the largest")
elif y > x and y > z:
  print(y, "is the largest")
else:
  print(z, "is the largest")
```


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans - Code below --

```
numbers = [12, 75, 150, 180, 501, 145, 50]

for i in numbers:
  if i > 500:
    break
  if i > 150:
    continue  
  if i % 5 == 0:
      print(i)
```
