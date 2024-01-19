print("hello wold");
#(#) it's use to comment
print("hello\nwold")
# (\n) it's use to print in next line 
'''this 
is 
devendra'''
# (''' & ''') it's use to maltiple line comment
''' (5) its called integer data type
("john")its called string data type
(2.3)its called float  data type
(none)its called non data type
(true/false)its bulien integer data type'''
# sequence data type 1.list 2.tuple
# dictionary data type  => set data type
# if you (name Name ) they are diffrent variable
# are you use one function and run so resultent is last value you add
name = "ram";
print(name);                    
name="soniya";
print(name);
rollnombber= 112;
parcentage= 77;
student =True;
# this type we use to print more variable
print(name,rollnombber,student);
print("my name is",name,"my rool numbber is ",rollnombber,"parcentage is ",parcentage,"i am a student",student);
#this type we use to change mathimaticaly ;
print("my new parcentage",parcentage-1);
#(sep="") we use to creat sepretter;
print(name,rollnombber,parcentage,student,sep="-");
# ascii and unicode value;
# ord()function is give you every cherecter numerical value (ascii to unicode);
#chr()function is give you numeric value change in ascii value;
chr = "a";
print(ord(chr));
ascii = 68;
#print(chr(ascii)); it's part of code but codn;t work;
# taking input (input) is used to take value from user ;
# worning: input value always give you  string datatype;
NAME=input("enter your name");
# we use "type" to now the type of data types
print(type(NAME));

# type casting converting one data type to another data type;
'''ROLLNUMBER= (input("enter your roll number"));
print(type(ROLLNUMBER + 1));'''
# it's being pragent error ,becose string code not add any number;
#in next line "int" is a type casting
ROLLNUMBER= int(input("inter your roll number"));
print(type(ROLLNUMBER + 1));

# we creat first project succsessfuly creat code for sum two number;

# orthmatic operators
number1= 12;
number2= 14;
# sum(+) 
print(number1+number2);
# (-)
print(number1-number2);
# maltiplai(*)
print(number1*number2);
# divide(/)
print(number1/number2);
# expocasion(**)" power me lekhne ke liye"
print( number1** number2);
# flow dividion(//)
print("flow division",number1//number2);
# modulo(%)
print("rimender",number1%number2);

# Assignment operator
n1=5;
n2=5;
print(n1+n2);
# n2+=n1( result n2(new) = n2(old)+n1);
n2+=n1;
# n2*=n1( result n2(new) = n2(old)*n1);
n2*=n1;
# n2-=n1( result n2(new) = n2(old)-n1);
n2-=n1;
# n2/=n1( result n2(new) = n2(old)/n1);
n2/=n1;
print(n1,n2);

#comparision operator
#comparision operator give you bulion value (true\false);
# chake equal( ==);
print(n1==n2);
# chake not equal ( !=);
print(n1!=n2);
# chake grater than(>);
print(n1>n2);
# chake less than(<);
print(n1<n2);
# chake greter than or equle(>=);
print(n1>=n2);
# chake less than or equle(<=);
print(n1<=n2);

#logical operator
# it's work on bulion value;
expration1=2>1;
expration2=5<4;
# (and) gave true only true and true combenation;
print(expration1 and expration2);
# (or) give you false only on false or false;
print(expration1 or expration2);
# (not) output give you oposite value ;
print( not expration1);

# identity operator
x=5;
y=5;
# variable have same object ( is)
print(x is y);
#variable have diffrent object( is not);
print(x is not y);

#membership operator
fruts=["banana","apple", "mongo","greps"];
# (in) we use to check they are axist; 
print("banana"in fruts);
# (not in) we use to check they are not axist;
print("orenge" not in fruts);

# bitwise operator
a=5;
b=3;
# and(&);
print(a&b);
#or(|);
print(a|b);
# zor (^);
print(a^b);
# not(~);
#print(a~b);
#left sift( <<);
# right sift(>>);

# operators precedence
# follow bord mass low during run program;

chapter2
# conditionals and loops;
#control statements: they allow us to control the flow of program;

# conditionals;
# If - else; 
number= float(input(" enter a number"));
if number>0:
    print(" number is possitive");
# then if and else those are feald then exgicute elif;
# you use elif a more time;                               
elif number==0:
  print("number is zero")
else:
    print(" number is negitive");

# useing logical operation in if else
# alresdy complet
n1=float(input("enter first number"));
n2=float(input("enterr secound number"));
n3=float(input("enter therd number"));

# if a first is gretest number

if n1>n2 and n1>=n3:
   print(n1,"is gretest intiger number");
elif  n2>n1 and n3>=n3 :
   print(n2,"is gretest intiger number");
else :
   print(n3,"is gretest intiger number"); 

#  useing nested if else      

if n1>n2:
   #if n1 is gretest intiger number
   if n1>n3:
      print(n1,"is gretest intiger number");
   else:
      print(n3,"is gretest intiger number");
else:
   print(n2," is gretest intiger number");

#match case 

num1=int(input("enter first number"));
num2=int(input("enter number 2"));

operator=input("enter opreter");

match operator:
  case "+":
     print("sum of number=",num1+num2);
  case "-":
     print("subtrection of number=",num1-num2) ;
  case "*":
      print("prodect of number=",num1*num2);
  case "/":
      print("division of number=",num1/num2);
  case _ :
      print("enter velid operator");

# ternary operator
#  we use this mathedilogy to compres the code

a=int(input("enter a number for cheack even or odd"));

output= "even" if a/2==0 else "odd";
print( 'output is',output);

# loops 
# 1.for loop 
# in range first is starting and secound is stoping and third is term of incrige's i value by 1,3,5,2 etc 
for i in range(1,11,3): 
 print(i,"hello world");
#and use like this
fruts=[ "bannana","mongo", "apple"];
for i in fruts:
    print(i);

# 2.while loop
i = 1
while i < 100:
    print(i)
    i += 1

# print ***** in n colam and 4 row
n=int(input("enter a row number"))
for i in range(1, n+1, 1):
      print(5 * "*")

# print 1234 in 4 colam 4 row
for _ in range(1, 5, 1):
      print("1234")

#print 123456 in 6 row and 6 colam
for _ in range(0,7,1):
   print("123456")

# print privious example
n=int(input("enter number for drow petern"))
for i in range(n): # number of row
    for j in range(1,n+1):# number of colum
        print(j , end="")
    print()

# print 1,12,123 ,1234 this petern
n=int(input("enter number for drow petern"))
for i in range(1,n+1):# loop for row 
    for j in range(1,i+1): # loop for colum
        print(j , end="")
    print()

#print trengal petern  
n = int(input("enter number of row number"))

for i in range(1,n+1): # loop for rows
    print(" " *(n-i), end="")

    for j in range(1,2*i-1+1):
        print(j , end="")
    print()
chapter 3
# collection 
# list is muteableodderd,,idexing,dupplecate allowed, mix datatype,any datatype,
# 1.list
fruts=[ "apple","banana", "mongo"] # creat the the list 
print(fruts) # who to print a list
print(type(fruts)) # check type of list
print(len(fruts)) # check the length of the list 
# check banana in list
if "banana" in fruts:
    print(" banana in the list")
# check not the list
if "chery" not in fruts:
    print(" chery is not in list")

# indexying in list 
print(fruts[2]) # mongo
print(fruts[-3])   # apple
print(fruts[0:2]) # apple mongo

# adding elements to a list 
# use append to end of list
fruts.append("chery")
print(fruts)
# use insert to number of place in list
fruts.insert( 2,"greps")
print(fruts)
# use extend to end of list
frutss=[ " jaja"]
fruts.extend(frutss)
print(fruts)

# remove in the list 
fruts.remove("banana")
print(fruts)
fruts.pop(2)
print(fruts)

# changing the list 
fruts[1] = "banana"
print(fruts)
fruts[1:3] = [ "greps"]
print(fruts)

# sorting a list 
fruts.sort() # this is by difolt acending way
print( fruts)
fruts.sort(reverse=True)
print(fruts)

# list comprehension
new_list= [ fruts for fruts in fruts if "a" in fruts]
print(new_list)

# copy the list
new__fruts=fruts.copy()
print(new__fruts)

new__fruts=new_list+fruts
print(new__fruts)

# nested list
fruts.insert(2,[ "civi,poteto"])
print(fruts)

# change a member of list number 
n = (int (input( "enter a number for number of list aliment")))

list=[]
for _ in range(n):
    num=int(input())
    list.append(num)

in1=int(input(" enter index"))
in2=int(input(" enter index"))
print(list)
# sopping the value
temt=list[in1]
list[in1] = list[in2]
list[in2] = temt

print(list)

# tuple
# tuple is odderd,unmutable,idexing,dupplecate allowed, mix datatype,any datatype,
# creating a tuple
color=( "red", "blue", "green")

# if you want a make single variable tuple 
fruits=("apple",)

# check type of color
print(type(color))

# check a lenght of tuple
print(len(color))

# accessing a tuple
print(color[0])# this is positive indexing
print(color[-1])# this is negitive indexing
print(color[0:2])# this is range indexing
print(color[-1:-3])# this is negitive indexing

# check a variable in tuple
if "green" in color :
    print("green is part of tuple")

# print a every variable of tuple (trivers the tuple)
for _ in color:
    print(_)

# concetinet two tuple
new_color=("oreng","pink")
color=color+new_color
print(color)

# unpaking a tuple
color1,color2,color3,color4,color5=color
print(color1,color2,color3,color4,color5)

# example
input_tuple=(1,2,3,4,)

list=[]
for _ in reversed(input_tuple):
    list.append(_)

input_tuple=tuple(list)
print(input_tuple)

# 2.sets
# unodered,unidexing,inmuttable(unchange),dupplecate not allowed,any datatype,mixdatatype
# how to creat a sets
name={ "siya","riya","roshana"}
print(name)
print(type(name))# check type of name
print(len(name))# check length of set

# accexing of items in a set
for x in name:
    print(x)

# check if items in a list 
if "siya" in name :
    print("siya is part of set")

# adding a item in a set 
name.add("shita")
print(name)

# if i want a add another siquians 
name_list={ "rohan","mohit"}
name.update(name_list)
print(name)

# remove a item in set
name.remove("riya")
print(name)

# discard function  will not throw error if value is not in a set
name.discard("ram")
print(name)

# joining two set
s1={ 1,2,3,4}
s2={ 4,6,7,8}
print(s1,s2)

# one way two join
s3=s1.union(s2)
print(s3)
# another way to join  two set
s1.update(s2)
print(s1)

# if i want join two sets then i have only duplicate value will give me
s1.intersection_update(s2)
print(s1)

# keep all value accept duplicate
s1.symmetric_difference_update(s2)
print(s1)

#example
# given 
ar1={1,5,12,20,40,80}
ar2={6,7,20,80,100}
ar3={3,4,15,20,30,70,80,120}

# first wecheck a comman items in ar1 and ar2
ar1.intersection_update(ar2)
# secondly we check ar1 and ar3 (another way "ar1.intersection_update(ar3)")
set=ar1.intersection_update(ar3)
print(set)

# 3.dictionary
# odered, changeable,unidex,duplecate not allow(for key),any data type
# how to create a dictionary
phone={
    "reya": 124578,
    "ram": 123654,
    "sona":32654
}
print(phone)
print(type(phone))# check a type of phone
print(len(phone))# check a length of dictionary

#accesing of item
print(phone["ram"])
print(phone.get("ram"))

# print all of the key
print(phone.keys())

# update value in dict
phone["ram"]=12546
print(phone)

# add items 
phone["jhon"]=789456
print(phone)

# another dictionary add
new_phone={
    "roma":456321
}
phone.update(new_phone)
print(phone)

# remove items in dict
phone.pop("roma")
print(phone)

phone.popitem()# this will remove last add item
print(phone)

#phone.clear()# this will empty over dict
#print(phone)

# how can loop use 
for x in phone:
    print(x)
'''for n in phone:
   print(phone(n))'''

for x in phone.items():# x change x,y then x is key and y is value
    print(x)

# nested dict
phones={
    "area1":{
        "x":1,
        "y":5,
        "z":4
    },
    "area2":{
        "a":8,
        "b":7,
        "c":6
    }
}
print(phones["area1"]["x"])

#example
dict={
    "a":100,
    "b":200,
    "c":300
}
print("sum of the number is",sum(dict.values()))

# example
# Example
input_string = input("Enter a string: ")
a = int(input("Enter a number for start mirror operation: "))

# Create a dictionary for mirror operation
alphabets = "abcdefghijklmnopqrstuvwxyz"
reversed_alphabets = alphabets[::-1]
dict1 = dict(zip(alphabets, reversed_alphabets))

# Find the parts of the alphabet to apply a mirror operation
prefix = input_string[0:a-1]
suffix = input_string[a-1:]

# Finding the mirror string
string = ""
for char in suffix:#this is another way "for i in range[0,len(sfix)]:string=string+dict1[sfix(i)]"
 string += dict1[char] if char in dict1 else char

# Create the final string
result = prefix + string
print("The result is:", result)

chapter 4
 # function
# what And why we run same program agen and agen to solve same problem  there for we use function  to save your time
# type of function : 1 bult in 2 user defind

# wright a function  thet print hello

def printhello():
    # which was a body of function
    print("hell wold")

# call a function
printhello()

# which function add which take two number return there sum
def adding(n1=0,n2=0):
    sum = n1 + n2
    return sum

x=3
y=4
print( " the sum is",adding(x,y))

# possition argument 
print( "this is sum of ", adding(5,4))

# keyword argument ( name argument)
print( "this is sum of ", adding(n1=5,n2=4))

# difolt argument
print( "this is sum of ", adding(5,))

# arbitry argumdent( there we use maltiple value)
def addallnumber(*arg):
    sum = 0
    for i in arg:
        sum+=i
    return sum

output=addallnumber(1,2,3,4,4)
print(" addallnumber",output)

#keyword argument
def studentinput(**lenvariable):
    for x,y in lenvariable.items():
        print(x,y)

studentinput(name="ram",age=22,city="jaipur")

# nested function
def ram (n1,):
    y=n1
    def jai (n2):
        for i in jai:
            y+=i
    return sum


#  pass by value 
def addone(x):
    x = x+1
    print("pass by value x:",x)# its could not change origlan value

x=5
addone(x)
print("og value x",x)
#pass by reference 
def modifinglist(list):
    list.append(4)
    print("inside function",list)# effect the orignal value

list=[ 1,2,3]
modifinglist(list)
print( "og value", list)

# built-in function
# learn this your self becose built in function is more amout exist

# Example: Create a function to calculate factorial

def factorial(n):
    ans = 1
    if n == 0:
        ans = 1
    else:
        for i in range(1, n + 1):  # Use parentheses for range, not square brackets
            ans *= i

    return ans

# Enter an input
n = int(input("Enter a number to calculate its factorial: "))

output = factorial(n)
print("The factorial is", output)

chapter 5
# recursion
def fectorial(n):

    #base case
    if n==0:
        return 1
    
    # recursive case
    ans =n * fectorial(n-1)
    return ans

n=int(input("enter a number"))
print(fectorial(n))

# example
# print number 54321 
def num(n):
    #base case
    if n==0:
        return 
    
    print(n)
# recursive case
    num(n-1)

print(num(5))

# example sum of n number
def sum(n):

    # base case 
    if n == 1:
        return 1
    
    # recesive 
    ans = n+sum(n-1)
    return ans

n = int(input("enter a number"))
print(sum(n))

# example a the pawer b
def power(a,b):

    # base case 
    if b ==0:
        return 1
    
    #recursive case
    ans = a*power(a,b-1)
    return ans

a=int(input("enter value of a"))
b=int(input("enter value of b"))
 
print("power of a,b:",power(a,b))

# fibunaki siquenc
def fibunaki(n):

    if n == 1: # base case 
        return 0
    elif n==2: # base case 
        return 1
    else : # recursive case
        return fibunaki(n-1)+fibunaki(n-2)
    
n= int(input("enter a num"))
for i in range(1,n+1): # if you did not write this row you take thet only value on number
  print(" fibunaki siriz",fibunaki(i))
  
chapter 6
# strings
# use single , doble,triple codes
# inmutable, indexing
name = 'dev'
name1 = "ram"
name2 = '''shohan'''

print( name,name1,name2)
print(type( name))
print(type( name1))
print(type( name2))

# multiple line string in triple codes
peregraph = ''' dfjckd cdkcncjjsndds'''

# exesing idex 
print(name[1]) 
print(name1[1])

# 
for i in name :
    print(i)

# 
list=[ name for name in name]
print(list)

# lenth 
print(len(name))

# find a string and sub string
print(name.find("e")) # this retune index value

# slicing a string 
#use get a part of string
print(name[:2])
print(name1[-1:-3]) # negitive idexing

# midifaing
# chage lower - uper case 
str= name.upper()
print(str)

#change uper - lower case
str= name.lower()
print(str)

# for chapetalising a first leter of string
str = name.capitalize()
print(str)

# for striping or removing any triling space
str = '  sa '
print(str.strip())
print(str)

# replace()
str="jai ram jai jai ram bolo ram ram shita ram"

ans=str.replace( "ram ","krishna",1)# if i am not give a time then chage the all substring

print(ans)

# split()
str1= "riya shiya miya chiya"
list=str.split(" ",) # if i give a number then only thet time split it
print(list)

# concetinet a string
str2= " hello world"
str3= " what a great place this is"

print(str2+str3)

#format()
student_name="pallawi"
student_mark= 98

str="student name is {f1} and mark is {f2}".format(f1=student_name,f2=student_mark)
print(str)

# escape character 
# spesal string print to useing escape

chapter 7
# oops (object orented progtamming)
#class
from typing import Any

class student:

    def set_name(self,name):
        self.name = name # class atributs

    def get_name(self):
        return self.name
    
student1 = student()
student1.set_name("ram")
print(student1.name)
print(student1.get_name())

student2 = student()
student2.set_name("kanha")
print(student2.name)

class Rectangle:
    def set_dimension(self, height, width):
        self.height = height
        self.width = width

    def area(self):
        return self.height * self.width

    def perimeter(self):
        return 2 * (self.height + self.width)

# Creating an object
rectangle1 = Rectangle()
rectangle1.set_dimension(4, 3)

print("Rectangle height and width:", rectangle1.height, rectangle1.width)
print("This is the area:", rectangle1.area())
print("This is the perimeter:", rectangle1.perimeter())

#class constuctor
class Rectangle:
    def __init__(self, height, width):
        self.height = height
        self.width = width

    def area(self):
        return self.height * self.width

    def perimeter(self):
        return 2 * (self.height + self.width)

# Creating an object with height 4 and width 3
rectangle1 = Rectangle(4, 3)

print("Rectangle height and width:", rectangle1.height, rectangle1.width)
print("This is the area:", rectangle1.area())
print("This is the perimeter:", rectangle1.perimeter())

# atributs

# access modifiers
# public

#privet

#secur

# inheritance
class perent:
    def __init__(self) :
        self.super_atribut = True
        print("this is perent class")

class child(perent):
    def __init__(self):
        super().__init__()
        print("this is cild class")
        print(self.super_atribut)

child_object=child()

#example
class Vihcal:

    def __init__(self, sitting_capacity):
        self.sitting_capacity = sitting_capacity

    def get_fear(self):
        return self.sitting_capacity * 100

class Bus(Vihcal):

    def __init__(self, sitting_capacity):
        super().__init__(sitting_capacity)

    def get_fear(self):
        the_vahcal_fear = super().get_fear()
        maintenance = 0.1 * the_vahcal_fear
        total = maintenance + the_vahcal_fear
        return total

vahcal1 = Vihcal(15)
print("This is a Vihcal fear:", vahcal1.get_fear())

bus1 = Bus(15)
print("Bus fear is:", bus1.get_fear())

#polymorphism

#comple time polymorphism

#run time polymorphism

# abstraction

#encapsulation

# exception handling in oops

#try
#except
#finally

If I ==10
Break(loop ko off ) \continue(value ko jump )

Doc is a like comment but it’s not ignore buy reader and it’s write after the function name ether it’s not work it’s write like this(
def name()
    ‘’’this is doc’’’
 Print(name.__doc__)
Pep 8 is help to python learning

The zin of python


















