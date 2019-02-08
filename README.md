# RAP-Problem1

# 1. Write a program that prints the numbers from 1 to N. But, for multiples of three,  print “Fizz” instead of the number and for the multiples of five print “Buzz”.For numbers which are multiples of both three and five print “FizzBuzz”.

n = int(input())
for i in range(1,n+1):
    if i%15 is 0:
        print ("FizzBuzz")
    elif i%5 is 0:
        print ("Buzz")
    elif i%3 is 0:
        print ("Fizz")
    else:
        print (i)

