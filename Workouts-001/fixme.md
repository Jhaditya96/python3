# Fix the below in paper -

## Mandatory : Dont use compiler till you solve in paper

Input: -

Expected Output: GUVI
```
myname='GUVI'
print(Myname)
```

---------------------------------------
Expected Output: GUVI

```

if True<=False:
	op = "GUVI"
else:
	op ="Geeks" 
print(op)

```

---------------------------------------

Expected Output: GUVI

```
if 3.5 % 1.5 == 0:
	op = "GUVI"
else:
	op ="Geek" 
print(op)
```
---------------------------------------
Whats the output?

```
a = 3.5 

if( a == 7//2 ):
	print("GUVI")
else:
	print("Geek")
```

---------------------------------------
Whats the output?

```
for i in range(7):
	if i==3: continue
print(i)


for i in range(7):
    if i==3: break
print(i)

```
---------------------------------------

Input: -

Expected Output: 3

```
data = 0
for i in range(7):
	if i==3: continue
	else: data = i
print(data)
```

---------------------------------------
Expected Output: print "HELLO" 5 times
```
for i in range(1, 10,3):
    print("HELLO")
```
---------------------------------------

Input: -

Expected Output: 13579
```
a = range(1,10,2)
print (a)
```
---------------------------------------
Input: 50

Expected Output: 1275

```
a=input("Enter a number")
sum=0
for i in range (1,a):
    sum=sum+i
print(sum)
```

---------------------------------------
Whats the output?

```

a = [1,2,3]
a[0] = 0
a[1] = 1
a[2] = 2

i=0

while (i<3):
	a[i] = 1
	i+=1
	
print(a)
```

---------------------------------------

Input: guvi

Expected Output: You entered an alphabet

```
a=input("Press any key...\n")
if a.isalpha() == 0:
    print("You entered an alphabet")
else:
    print("Please try again")
  ```
---------------------------------------	

Input: A

Expected Output: You entered a vovel

```	
a=input("Enter an ALPHABET...\n")
if a=='a'or a=='e'or a=='i'or a=='o'or a=='u':
    print("You entered a vowel")
else:
    print("You entered a consonant")
```
---------------------------------------
Input: 100 12 2

Expected Output: 24

```
p=input("Enter the principal amount")
r=input("Enter the rate")
t=input("Enter the time")
SI=p*t*r/100
print(SI)
```
---------------------------------------
Whats the output?

```
a = [1,2,3,4]
print(a[:1:-1])

a=[0,1,2,3,4]
print(a[-1])

','.join('12345')

```
---------------------------------------

Expected Output: ['a', 'b', 'c', 'e']

```
mydict={'a':1,'b':2,'c':3,'e':5}
a = [mydict.keys()]
print(a)
```
---------------------------------------
Input: 5

Expected Output: {1: 1, 2: 4, 3: 9, 4: 16}


```
n=int(input())
d=dict()
for i in range(0,n+1):
	d[i]=i*i
	print(d)
```
---------------------------------------
Whats the output?

```	
a, b = 2, 3
minvalue = a if a < b else b
print(minvalue)
```
---------------------------------------
Whats the output?

```
g = lambda x, y : x*y
print(g(1, 2))
```
---------------------------------------
Whats the output?

```
g = lambda x, y = 0, z = 0: x+y+z
print(g(1))
```
---------------------------------------
Whats the output?

```
global_var = "GUVI" # global variable
def info():
    addr = "World"     # local variable
    email = "reach@guvi.in"
    print(f'{global_var} address:{addr} and his email is {email}')

info()
```
---------------------------------------

Whats the output?

```

this_is_confusing=3,4,5
print(this_is_confusing)

```

---------------------------------------
Whats the output?

```
a = 1
try:
    a += 1
except:
    a += 1
else:
    a += 2
finally:
    a += 1
print(a)
```
---------------------------------------
Whats the output?

```
my_list = [num for num in range(0, 100)]
my_slice = my_list[30:70:2]
print(my_slice)

```
---------------------------------------
Whats the output?

```
mylist=[0,1,2,3,4,5,6,7,8]
print(mylist[-3:-1])
```
---------------------------------------
Input: 0

Expected Output: "You entered Zero"


```
a=input("Enter a number...\n")
a=int(a)
if a >= 0:
    print("The number is Positive")
elif a<= 0:
    print("The number is Negitive")
else:
    print("You entered Zero")
```
---------------------------------------
Input: -

Expected Output: [10]

```
List = [1,2,3,4,5,6,7,8,9,10]
print(List[:])
```
---------------------------------------
Input: -

Expected Output: [9,8,7]

```	
List = [1,2,3,4,5,6,7,8,9,10]
print(List[:])
```

---------------------------------------
Input: -

Expected Output: ['2002', '2009', '2016']


```
l=[]
for i in range(2000, 2020):
    if (i%7==0) and (i%5==0):
        l.append(str(i))
print(l)
```

---------------------------------------
Input: This is some text

Expected Output: THIS IS SOME TEXT


```
while True:
    s = input()
    if s:
        lines.append(s.upper())
    else:
        break;

for sentence in lines:
    print(sentence)
```

---------------------------------------
Input: GUVI 123456789

Expected Output: Alphabets 4
				 Nums 9


```	
s = input()
for c in s:
    if c.isdigit():
        d["Nums"]=1
    elif c.isalpha():
        d["Alphabets"]=1
    else:
        pass
print("Alphabets", d["Alphabets"])
print ("Nums", d["Nums"])

```

---------------------------------------
Whats the output?

```
import random

my_list = [num for num in range(0, 10) if num % 2 == 0]

my_dict = {num:random.randint(0, 10) for num in my_list}
print(my_dict)

```

---------------------------------------
Whats the output?

```
import random
names = ["ABD", "Virat", "Dravid", "Smith"]
scores = [random.randint(0, 100) for name in names]
print(scores)

for name, score in zip(names, scores):
    print(f"{name} got a score of {score}")
	
for p in zip(names, scores):
    print(p)
	
```

---------------------------------------
Input: -

Expected Output: I drive a BMW X1. It runs on Petrol.

```
class Vehicle:

    def __init__(self, make, model, fuel="gas"):
        self.make = make
        self.model = model
        self.fuel = fuel

daily_driver = Vehicle("BMW", "X1")
# By default, this is how python represents our object:
print(daily_driver)

# The variables we saved to the instance are available like this:
print(f"I drive a {daily_driver.__} {daily_driver.__}. It runs on {daily_driver.__}.")

```

---------------------------------------
Input: -

Expected Output: Most vehicles have 4 wheels.

```
#Don't Touch the class
class Vehicle:
    number_of_wheels = 0
    def __init__(self, make, model, fuel="gas"):
        self.make = make
        self.model = model
        self.fuel = fuel

daily_driver = Vehicle("BMW", "Ferrari")

#Set the value here for number_of_wheels

 
#Class variable
print(f"Most vehicles have {Vehicle.number_of_wheels} wheels.")

```

---------------------------------------
Input: -

Expected Output: 

Is my daily driver a car? True
Is my Car a Vehicle? False
Is my truck a Car? False
Is a Car a subclass of Vehicle? False

```

class Vehicle:

    def __init__(self, make, model, fuel="gas"):
        self.make = make
        self.model = model
        self.fuel = fuel


class Car():

    number_of_wheels = 4


class Truck(Vehicle):

    number_of_wheels = 6

    def __init__(self, make, model, fuel="diesel"):
        super().__init__(make, model, fuel)


daily_driver = Car()
truck = Truck("Ford", "F350")



print(f"Is my daily driver a car? {isinstance(daily_driver, Car)}")
print(f"Is my Car a Vehicle? {isinstance(daily_driver, Vehicle)}")
print(f"Is my truck a Car? {isinstance(truck, Car)}")

print(f"Is a Car a subclass of Vehicle? {issubclass(Car, Vehicle)}")

```
