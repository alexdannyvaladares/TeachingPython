# Exercise 1 

Develop a program that prints a phrase "Hello World" on the terminal.
~~~~~~~~~~~
.hello.py
[source,Python]
----------------------------
def main():
    print("Hello World!")

if __name__ == "__main__":
    main()
----------------------------

~~~~~~~~~~~

# Exercise 2 

Create a program called `primes` that prints on the screen
prime numbers, one per line, up to a certain limit.
Use an `isPrime ()` helper function
that accepts an integer `n` and returns 1 or 0 according to` n`
cousin or not.
~~~~~~~~~~~
.prime.py
[source,Python]
----------------------------------
maximum_number = 50


def isPrime(value):
    # <Fill the blank>

def main():
    print("Starting to compute prime numbers up to " + str(maximum_number))

    for i in range(0, maximum_number):
        if isPrime(i):
            print('Number ' + str(i) + ' is prime.')
        else:
            print('Number ' + str(i) + ' is not prime.')

if __name__ == "__main__":
    main()
----------------------------------

With the help of the program, calculate how many prime numbers
less than 10000 have the digit 3.
The answer must be 561
~~~~~~~~~~~

# Exercício 3

Extend exercise 2 to:

* Print all calculated dividers for non-prime numbers;
* Use the colorama package to print prime numbers in green;
* Use _shebang line_ to simplify script execution;

# Exercício 4

Calculate perfect numbers (those whose sum of divisors equal the number)
such as 6 = 3 + 2 + 1.
In addition to `main ()` create the `isPerfect ()` function, which indicates whether the number is perfect.
~~~~~~~~~~~
.perfeitos.py
[source,Python]
----------------------------------
maximum_number = 100

def isPerfect(value):
    # <Fill the blanks>
    return False

def main():
    print("Starting to compute perfect numbers up to " + str(maximum_number))

    for i in range(0, maximum_number):
        if isPerfect(i):
            print('Number ' + str(i) + ' is perfect.')


if __name__ == "__main__":
    main()
----------------------------------
