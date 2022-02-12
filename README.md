# assignment2-12-02-22
Write a program to compare two numbers are equal or Not equal.
a=int(input('enter a number:'))
b=int(input('enter b number:'))
if a==b:
    print('both values are equal')
elif a!=b and a>b:
    print('not equal,a is greater than b')
else:
    print('a is smaller than b')
enter a number:78
enter b number:44
not equal,a is greater than b
