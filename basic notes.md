# Python
* Python is popular programming language user on server to create web application.

### Python ia used for :
- Web developement
- Software developement
- Mathmatics
- System scripting

What can Python do?

   -  Python can be used on a server to create web applications.
- Python can be used alongside software to create workflows.
-   Python can connect to database systems. It can also read and modify files.
- Python can be used to handle big data and perform complex mathematics.
-  Python can be used for rapid prototyping, or for production-ready software development.
- ".py" is file extension is python.

## Python Indentation:

- Python indentation is refer to space at the begining of code line.
- where in other programing language indentation is only for readiblity of code but in python indentation is most important.
- python use indentation to indicate block of code.

## Python Variable:
- Variables are container to store data.
- Varibles are created when you assign value to it.

## Comments:
- Comments are used to explain something like note.
- Comments is start with #, rest of line will consider as comments.
- Multiple line comments are three double quote or single quote at the begining and ending of line ("""abc""")/('''abc''').
- Comments cannot be executed while running the program.

## Variables:
- Variable are container for storing data values.
- Python has no command for declaring variable.
- A variable is created the moment you first assign a value to it.
- Variables do not need to be declared with any particular type, and can even change type after they have been set.
## Casting Variables:
- If we want to specify a data type it can be done with casting.
- We change datatype with the help of casting. 
   - int to str 
   - int to float
- We can get the type of variable by "type()".
## Variable Names:
- Variable names are "Case Sensitive".
- A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

    - A variable name must start with a letter or the underscore character.
    - A variable name cannot start with a number.
    - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ).
    - Variable names are case-sensitive (age, Age and AGE are three different variables).
    - A variable name cannot be any of the Python keywords.

    - myvar = "John"
    - my_var = "John"
    - _my_var = "John"
    - myVar = "John"
    - MYVAR = "John"
    - myvar2 = "John".

### Multi Words Variable Names:

#### Camel Case:
- Each word except first letter in capital.
- myFirstName = "Gayatri".

#### Pascal Case:
- Each word start with capital letter.
- MyFirstName = "Gayatri".

#### Snake Case:
- Each word is separated by an underscore character.
- my_first-name = "Gayatri".
#### Assign Multiple Values:
- Many values to multiple variable.
- Python allows you to assign values to multiple variables in one line:

- x, y, z = 1, 2, 3
#### One Value To Multiple Variables : 
- x=y=z= "Orange"

#### Unpack Collection : 
- If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.

- fruits = ["Apple", "Banana", "Cherry"]
- x,y,z = fruits

#### Output Variable : 
- The python output print() funstion is often used to output variable.
- x= "I am Data Analyst" 
    - print (x)
- In print() function you output multiple variable, seperated by comma.
  - x = "I"
  - y = "am"
  - z = "Data analyst"
   - Print(x,y,z)

- You can also use the + operator to output multiple variables:

   - x = "I"
   - y = "am"
   - z = "Data analyst"
   - Print(x+y+z)

- When you try numbers and string concatination by using + operator it will show error best way is to seperate them by comma it supports all data type.


### Global Variable : 
- Global variable are created outside of a function.
- Global variables are used by everyone inside and outside the function.
#### Created outside the function and used inside the function.
- x = "awesome"

- def myfunc():
    - print("Python is " + x)

- myfunc() 

- Variable x is created outside function and is global variable, we can use it inside and outside of function.

#### Created variable inside and outside a function.
- x = "awesome"(#XA)

- def myfunc():
    - x = "fantastic"(#XB)
  print("Python is " + x)

- myfunc()

- print("Python is " + x) 

- XA is global variable and used anywhere inside and outside a function.
- XB is local variable and only used inside a function
- If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

#### The Global Keyword :
- Normally when we create a variable inside a function it is local and can only used inside that function.
- To create global variable inside a function we can use keyword "GLOBAL"

- def myfunc():
   -  global x
   -  x = "fantastic"

- myfunc()

- print("Python is " + x) 


- Also, use the global keyword if you want to change a global variable inside a function.

x = "awesome"

- def myfunc():
    - global x
    - x = "fantastic"

- myfunc()

- print("Python is " + x)


### Python Data Types :
- Variable can store data of different type, and different type of data can do different things.
- Python has following data types
   * Text    - String.
   - Numeric - Int,Float,Complex.
   * Sequence Type - List, Tuple, Range.
   * Mapping Type - Dict.
   * Set Type - Set, Frozen Set.
   * Boolean Type - Bool.
   * Binary Types - Bytes, Bytearray, Memoryview.
   * None Type - None.



#### Getting Data Type : 
- You can get the data type of any object by using the type() function.
- X = 5
- print(type(X))
##### Data types : 
- X = "Hello World" (String)
- X = 20 (int)
- x = 20.5(Complex)
- x = ["apple", "banana", "cherry"](List)
- x = ("apple","banana","cherry")(Tuple)
- x = range(x)(range)
- x = {1: "one", 2:"two", 3:"three"} 
- x = {"apple","bana","cherry"}(set)
- x = True(bool)
#### Setting the Specific Data Type :
- If you want to specify the data type, you can use the following constructor functions.

   * x = str("Hello World") 	str 	
   * x = int(20) 	int 	
   * x = float(20.5) 	float 	
   * x = complex(1j) 	complex 	
   * x = list(("apple", "banana", "cherry")) 	list 	
   * x = tuple(("apple", "banana", "cherry")) 	tuple 	
   * x = range(6) 	range 	
   * x = dict(name="John", age=36) 	dict 	
   * x = set(("apple", "banana", "cherry")) set


### Python Numbers : 
- There are three numeric types in Python:

    int
    float
    complex

Variables of numeric types are created when you assign a value to them.
   - x = 2 (int)
   - x = 2.4(float)
   - x = 2j(complex)
- To get the type use type(x)

#### Int : 
- Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.
   - x = 1
   - y = 35656222554887711
   - z = -3255522
#### Float : 
- Float, or "floating point number" is a number, positive or negative, containing one or more decimals.

   - x = 35e3
   - y = 12E4
   - z = -87.7e100
- Float can also be scientific numbers with an "e" to indicate the power of 10.


   - x = 35e3
   - y = 12E4
   - z = -87.7e100

### Casting : 
- There may be times when you want to specify a type on to a variable. This can be done with casting. Python is an object-orientated language, and as such it uses classes to define data types, including its primitive types.

- int() - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number).
- float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer).
- str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals.

### Python Strings :
- Strings in python are surrounded by either single quotation marks, or double quotation marks.

- Quotes Inside Quotes

- You can use quotes inside a string, as long as they don't match the quotes surrounding the string:
Example
   - print("It's alright")
   - print("He is called 'Johnny'")
   - print('He is called "Johnny"')

- Assign String to a Variable

- Assigning a string to a variable is done with the variable name followed by an equal sign and the string:
Example
   - a = "Hello"
   - print(a) 
- Multi line strings are assigned with three double quote or single quote.

#### Strings are Arrays : 
- Like many other programming language strings are array of bytes represeting the unicode.
- We can access any element by reffering index.
- we use square bracket to access the element.
  - a = "Hello, World!" 
  - print(a[1])

#### Looping through strings:
- String are array so we can loop through the charachters in a string with for loop.

   - for x in "banana" :
       - print(x) 


#### String Length :
- to get the length of string use len() function.
   - x = "Hello world"
        - len(x)

#### in Keyword in string : 
- We use in keyword to found specific charachter in string.

- Check if "free" is present in the following text:
   - txt = "The best things in life are free!"
   - print("free" in txt)

- To check if a certain phrase or character is NOT present in a string, we can use the keyword not in.


   - txt = "The best things in life are free!"
   - print("expensive" not in txt)


#### String Slicing : 
- Specify the start index and the end index, separated by a colon, to return a part of the string.
- Get the characters from position 2 to position 5 (not included):
- b = "Hello, World!"
   - print(b[2:5])

##### Slicing from start :

- By leaving out the start index, range will start at first charachter.
- x = "Hello world"
    - print(x[:5])

##### Slicing to end :
- By leaving out the end index, the range will go to the end.
- x = "Hello World"
   
    - print(x[2:])

#### Negetive Indexing :
- Use negetive indexing to start slicing from end.

- x = "Hello World"
   
    - print([-5:-2]).



### Modify String : 
- Upper Case : 
   - The upper() case write string in capital letter.
   - print(x.upper())

- Lower Case : 
   - The lower() return string into small letters.
   - print(x.lower())

- Remove White Space : 
  - The strip() method used to remove white space from before and after the text.

  - print(x.strip())

- Replace String : 
  - Replace string method used to replace string with another string.
  - print(x.replace("H", "J"))

- Split String : 
   - The split method return a list of string when seperating by a specified delimiter.

   - Split() method is built-in string method in python that divides a string into list of substring based on specific seperator(delimiter).

   - x = "Hello, World"
   - print(x.split(","))


- String Concatination : 
  - We can add two strings by method string concatination.
  - To concatenate, or combine, two strings you can use the + operator.

  - A = "I"
  - B = "Am Data Analyst"
  - print(A+B)--> IAm Data Analyst
- We need to add white space between them.
 - print(A+ " "+B)--> I Am Data Analyst.



 ### Escape Characters : 

 - To insert a characters that are illegal in string, use an escape charachter.

 - An escape charachter os \ (backslash) followed by characater we want to insert.
 - An example of illigle charachter is double quote inside the string which is surrounded by double quote.
   - txt = "i am \"Data analyst\" gayatri"




