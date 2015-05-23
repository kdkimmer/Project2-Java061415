# Project2
##5 Problems from Project Euler and CoderByte

For this weekly assignment, you will be working through a set of problems, many from Project Euler (http://projecteuler.net) or CoderByte (http://coderbyte.com).
Each problem will build upon one of the concepts covered in class. Collaboration is encouraged, and full understanding of the underlying concepts is required.

These problems will not be formally graded, but you will be asked to formally present your solutions to your Team as your first official build.

----------

###Basic Flow-Control Exercises

-------------

**Exercise CheckPassFail** (if-else): Write a program called `CheckPassFail` which prints "PASS" if the `int` variable `mark` is more than or equal to 50; or prints "FAIL" otherwise.

**Exercise PrintNumberInWord** (nested-if, switch-case): Write a program called `PrintNumberInWord` which prints "ONE", "TWO",... , "NINE", "OTHER" if the `int` variable `number` is 1, 2,... , 9, or other, respectively. Use (a) a "nested-if" statement; (b) a "switch-case" statement.

--------------

###Loop Exercises

**Exercise SumAndAverage** (Loop): Write a program called `SumAndAverage` to produce the sum of 1, 2, 3, ..., to an upperbound (e.g., 100). Also compute and display the average. The output shall look like:
`The sum is 5050`
`The average is 50.5`
TRY:
1. Modify the program to use a "while" loop instead of "for" loop.
2. Modify the program to sum from 111 to 8899, and compute the average. Introduce an `int` variable called `count` to count the numbers in the specified range.
3. Modify the program to sum only the odd numbers from 1 to 100, and compute the average. (Hint: `n` is an odd number if `n % 2` is not `0`.)
4. Modify the program to sum those numbers from 1 to 100 that is divisible by 7, and compute the average.
5. Modify the program to find the "sum of the squares" of all the numbers from 1 to 100, i.e. 1*1 + 2*2 + 3*3 + ... + 100*100.

**Exercise CozaLozaWoza** (Loop & Condition): Write a program called `CozaLozaWoza` which prints the numbers 1 to 110, 11 numbers per line. The program shall print "Coza" in place of the numbers which are multiples of 3, "Loza" for multiples of 5, "Woza" for multiples of 7, "CozaLoza" for multiples of 3 and 5, and so on. The output shall look like:
```
1 2 Coza 4 Loza Coza Woza 8 Coza Loza 11 
Coza 13 Woza CozaLoza 16 17 Coza 19 Loza CozaWoza 22 
23 Coza Loza 26 Coza Woza 29 CozaLoza 31 32 Coza
```

--------------

###Even Fibonacci numbers

Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be:

1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.

---------

###Name Scores of an alphabetized list

Use the `names.txt` file, a 46K text file containing over five-thousand first names found in the `resources` directory.

**Part 1:**Begin by sorting the list into alphabetical order. Save this new file as `p4aNames.txt` in the `answers` directory.

**Part 2:** Using `p4aNames.txt`, take the alphabetical value for each name, and multiply this value by its alphabetical position in the list to obtain a name score.
For example, when the list is sorted into alphabetical order, COLIN, which is worth 3 + 15 + 12 + 9 + 14 = 53, is the 938th name in the list. So, COLIN would obtain a score of 938 × 53 = 49714.
Save the list of all name scores as `p4bNames.txt`.

**Part 3:**What is the total of all the name scores in the file?

---------

###Large sums

Use the `longnums.txt` file in the `resources` directory for this problem.

**Part 1:** Build an array of the 100 numbers (each 50 digits long) contained in `longnum.txt`, and sort them according to size (smallest numbers first). Save this file as `p5a.txt` in the `answers` directory.

**Part 2:** Find the first 10 digits of the sum of all 100 numbers, and print the answer to the console.

-----------

###Consecutive Numbers


**Part 1:** Build your own array of all of the prime numbers up to 100, and store that array in a text file `primearray.txt` in the `answers` directory. **Save your project files in the `answers` directory**.

**Part 2:** Have the class ` Consecutive` take an array of integers from `primearr.txt` and return the minimum number of integers needed to make the contents of the array consecutive from the lowest number to the highest number. For example: If `arr` contains `[4, 8, 6]` then the output should be 2, because two numbers need to be added to the array (5 and 7) to make it a consecutive array of numbers from 4 to 8. Print out the answers for arrays of the first 5 primes, the first 10 primes, the first 50 primes, and the first 100 prime numbers on separate lines.

-------------

###String Manipulation

Prompt a user to input a string of any kind into the console. Then, **ignoring special characters**, increment each letter one farther down the alphabet (e.g. a->b, o->p, z->a, etc.). Return the string to the console.
