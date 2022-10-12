### wite a program that prints the numbers from 1 to 100. For multiples of three print "Fizz" instead of the number
- For the multiples of five print "Buzz" instead of the number For numbers which are multiples of both three and five print "FizzBuzz".
for x in range(100):
    if x%3==0 and x%5==0:
        print("fizzbuzz")
        continue
    elif x%3==0:
        print("fizz")
        continue
    elif x%5==0:
        print("buzz")
        continue
    print(x)
