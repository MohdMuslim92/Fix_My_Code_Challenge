**0x00. Fix my code
Background Context

Fix my code is a new type of project, where we’ll jump into an existing code base and fix it! Sometimes you will know the language, sometimes not.


Table of Contents

FizzBuzz

Print Square

Sort

User Password

Double Linked List

FizzBuzz

Problem:

The code in Need_Fix/0-fizzbuzz.py is not generating the correct output for FizzBuzz.

Current Output:

rubyCopy code

$ ./0-fizzbuzz.py 50 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz

Expected Output:

Copy code

1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 FizzBuzz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 FizzBuzz 46 47 Fizz 49 Buzz

Solution:

The code in 0-fizzbuzz.py contains the fixed FizzBuzz implementation.

Print Square

Problem:

The code in Need_Fix/1-print_square.js is not generating the correct output for printing a square.

Current Output:

shellCopy code

$ ./1-print_square.js 4 #### #### #### #### $ ./1-print_square.js 10 ################ ################ ################ ################ ################ ################ ################ ################ ################ ################

Expected Output:

shellCopy code

$ ./1-print_square.js 10 ########## ########## ########## ########## ########## ########## ########## ########## ########## ##########

Solution:

The code in 1-print_square.js contains the fixed implementation for printing a square.

Sort

Problem:

The code in Need_Fix/2-sort.rb is not correctly sorting the arguments.

Current Output:

kotlinCopy code

$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32 31 32 12 41 2 9 -9 -1

Expected Output:

kotlinCopy code

-9 -1 2 2 9 12 12 31 31 32 32 41 41 C fun

Solution:

The code in 2-sort.rb contains the fixed implementation for sorting the arguments.

end

User Password

Problem:

The code in Need_Fix/3-user.py is not correctly validating user passwords.

Current Output:

sqlCopy code

$ ./3-user.py Test User is_valid_password should return True if it's the right password

Expected Output:

The test should not print any errors.

Solution:

The code in 3-user.py contains the fixed implementation of the User class.

Double Linked List

Problem:

The code in the directory Need_Fix/4-delete_dnodeint/ is not correctly handling the doubly linked list.

Current Output:

diffCopy code

$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint $ ./delete_dnodeint 0 1 2 3 4 98 402 1024 ----------------- 0 1 2 3 4 0 402 1024 ----------------- 1 2 3 4 0 402 1024 ----------------- 2 3 4 0 402 1024 ----------------- 3 4 0 402 1024 ----------------- 4 0 402 1024 ----------------- 0 402 1024 ----------------- 402 1024 ----------------- ----------------- ----------------- ----------------- ----------------- ----------------- ----------------- ----------------- -----------------

Expected Output:

The output should display the doubly linked list correctly.

Solution:

The code in the directory 4-delete_dnodeint/ contains the fixed implementation of the doubly linked list.






