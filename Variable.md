##### variable of python
facts: 
1. Untuk membuat variable di python mengunakan "="
  x = "variable1" # mengunakan "="
2. Tidak perlu mendeklarasikan tipe dan mendeklarasikan kembali jika menganti variablenya kembali
  x = 10 # pengantian tidak perlu dideklarasikan kembali
3. Untuk melakukan spesifikasi mengunakan casting 
  x = str(10) # data akan menjadi x will be '3'
4. Untuk melihat tipe data dapat mengunakan type()
  x = 5
  y = "adi"
  print(type(x))
  print(type(y))
5. untuk menyatakan data string mengunakan single dan double quote
  x= 'john'
  x = 'John'
6. Nama variabel itu sensitive perbedaan huruf besar dan kecil berarti variabel yang berbeda
   a = 5
   A = "john"
Aturan untuk variabel Python:
Nama variabel harus diawali dengan huruf atau karakter garis bawah.
Nama variabel tidak boleh diawali dengan angka.
Nama variabel hanya boleh berisi karakter alfanumerik dan garis bawah (A-z, 0-9, dan _).
Nama variabel peka terhadap huruf besar dan kecil (age, Age, dan AGE adalah tiga variabel yang berbeda).
Nama variabel tidak boleh berupa kata kunci Python apa pun.
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"

illegal name
2myvar = "John"
my-var = "John"
my var = "John"
There are several techniques you can use to make them more readable:
Camel Case ;myVariableName = "John"
Pascal Case: MyVariableName = "John"
Snake Case : my_variable_name = "John"

Many Values to Multiple Variables
Python allows you to assign values to multiple variables in one line:
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
One Value to Multiple Variables
And you can assign the same value to multiple variables in one line:
Example
x = y = z = "Orange"
print(x)
print(y)
print(z)
Unpack a Collection
If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking
Example
Unpack a list:
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
Output Variables
The print() function is often used to output variables.
x = "Python is awesome"
print(x)
In the print() function, you output multiple variables, separated by a comma:
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
You can also use the + operator to output multiple variables:
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
Notice the space character after "Python " and "is ", without them the result would be "Pythonisawesome".
For numbers, the + character works as a mathematical operator:

Example
x = 5
y = 10
print(x + y)
In the print() function, when you try to combine a string and a number with the + operator, Python will give you an error:Example
x = 5
y = "John"
print(x + y)The best way to output multiple variables in the print() function is to separate them with commas, which even support different data types:Example
x = 5
y = "John"
print(x, y)
