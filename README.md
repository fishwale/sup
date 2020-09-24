# sup
if you need help
float() converting a value a floating point value
int()
bool() converting a value to a boolian
str() converting A VALUE INTO A streanin


birth_year=input("enter your birth year")

age = 2020 - int(birth_year)
print(age)
int()
float()

exercises 
birth_year=input("first")
year = input("second")
age = int(birth_year) + int(year)
print(age)

DATA
10 is a number
"mosh" is string's
true is ulion  
to convert
10 is a intager and 10.1 is a float

STRING'S
to replace someting in a sting
print(course.replace('for','4'))


Arthmetic Operators 
if you use print(10/3) you will get a floating type # 3.3333333333333335
print(10//2) 3 an interger
print(10 % 3) ramainder of 10/3 1
print(10 ** 3) is 10 to the power of 3 1000
x = 10
x = x + 3 or you can use this
x = 10
x += 3
LIST
names = ["john","name","mary"]
names[0] = "jon"
print(names[0:2])


camparison Operators
covert value to certan condition's 
> grater than 
>= greator than or equel to
< less than
<= less than or equel to
== equel
!= not equel

logical Operator's
are to build complex rules and condition
al  5 logical op
and (both)
or (at least one)
not

if statement's 
is a way to make descions for python
like
temperature = 25
if temperature > 30:
    print(" it's a hot day")
    print("drink plenty have water")
elif temperature > 20: #20.30]
    print(" it's a nice DAY")
elif temperature > 10: #(10. 20]
    print("it's a bit cold")
else:
print("it's cold")
    print("done")

exercise
weight = float(input("weight: "))
weight = float(input("weight: "))
unit = input("(K)g or (L)bs: ")
if unit.upper() == "K":
    converted = weight /0.45
    print("weight in lbs: " + converted)
else:
    converted = weight * 0.45
    print("weight in kgs: " + str(converted))



LOOP'S    
i = 1     
while i <= 10: 
    print(i)
    i = i+1
this will output to 
1
2
3
4
5
6
7
8
9
10

i = 1
while i <= 10:
    print(i * '*')
    i = i+1 will output to 
*
**
***
****
*****
******
*******
********
*********
**********
