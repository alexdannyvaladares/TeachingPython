
# Data Types
There are many different data types in Python, some are much more common than others. Some of the basic and most common data types in Python are:

* int : this type of data consists of numbers and particularly integers.
* float : this type of data refers to numbers with decimals
* str : standing for string, an str type of variable keeps data as a text string.

**WARNING** : This lesson has relatively more reading parts.

## Fundamentals
Data is used at every point of programming and it can be important to understand what type 
of data you’re dealing with and the implications that come with it.

* **int** is used where numbers are needed to be stored;
```Python
    number1= 1
    number2= 2 
    number3= 3
    print(number1)
    print(number2)
    print(number3)
```
```Python
  1
  2     
  3
   ```
* **float** is used when decimals are needed;
```Python
    number1= 1.0
    number2= 2.2
    number3= 3.333333
    print(number1)
    print(number2)
    print(number3)
```
```Python
  1.0
  2.2   
  3.333333
   ```
*  **str** stores data in a string format and can include any letters, symbols or numbers but int
   and float can not include symbols or letters and they are consisted of numbers.
```Python  
 
   string= "Hello World"
   number=3
   print(string)
   print(str(number))
   ```
```Python 
'Hello World'
'3' 
```
*  **bool** consists of only two values: True or False. It’s important to note that while bool 
   type is being initiated or assigned True or False values won’t be in quotation marks. 
  You can think of boolean type as your light switch. It’s always either on or off. 
   In Python it’s either True or False. Note that, boolean type True or False is never in quotes
   which separates it from strings. So in short, True and “True” are two different data types
   in Python, latter is a str type while former is a bool.
   
   
**NOTE:** This may seem confusing but you can do math operations on bool type data. True will be treated as 1 and False as 0. 
This is accurate with the bit representation on very low level programming 
```Python
Assign_True= True
Assign_False= False 
result = Assign_True*Assign_False
print(Assign_True)
print(Assign_False)
print(result)

```
result :
```Python
True
False
0
```
