# diffrent_types_of_loops
I am enthusiastic about the Python programming language. I have explained the code I found at¨https://www.quizcure.com/python/different-types-of-loops-in-python¨ here.

## In this program, we get familiar with different types of loops:
#### 1-simple loop (while,for)

I wrote a program for calculating Fahrenheit degrees by using an infinite loop.

    while True : 
        C=float(input("enter weather degree in celsius"))
        F=1.8*C+32
        print("farenheit: ",F)

#### 2-Nested loop
A nested loop includes two types of loop (Inner loop, Outer loop); note that we could have several other loops

In the following, I wrote a simple program to display the names of students and courses together.


    students=["Joe","John","Jerry"]
    courses=["C1","C2","C3"]
    for x in students: #Outer loop
      for y in courses: #Inner loop
        print(x," ",y)
