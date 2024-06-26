### 0x00. Fix my code

### Background Context
- `Fix my code` is a new type of project, where we’ll jump into an existing code base and fix it!

- Sometimes you will know the language, sometimes not.

- Please download the repository [0x00-Fix_My_Code_Challenge](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge) and use it as initial files for all solutions.

- You should not recode everything, just fix it!

### Requirements
#### General

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be compiled on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory

### Tasks

0. [FizzBuzz](./0-fizzbuzz.py)

- Please take a look at my implementation of FizzBuzz in Python: [source code](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py)

- Something is going wrong…
```sh
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ls
README.md
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# vi 0-fizzbuzz.py
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# chmod u+x 0-fizzbuzz.py
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ls
0-fizzbuzz.py  README.md
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 FizzBuzz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 FizzBuzz 46 47 Fizz 49 Buzz
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge#
```

- `15` should print `FizzBuzz` not `Fizz`

* **Repo:**

	- GitHub repository: `Fix_My_Code_Challenge`
	- Directory: `0x00-challenge`
	- File: `0-fizzbuzz.py`

1. [Print square](./1-print_square.js)

- Please take a look at my implementation of printing a square in Javascript: [source code](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js)

- Something is going wrong…
```sh
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```

- `./1-print_square.js 10` should print a square of size 10…

* **Repo:**

	- GitHub repository: `Fix_My_Code_Challenge`
	- Directory: `0x00-challenge`
	- File: `1-print_square.js`

2. [Sort](./2-sort.rb)

- Please find here my implementation of sorting arguments in Ruby: [source code](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb)

- Something is going wrong…
```sh
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# vi 2-sort.rb
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# chmod u+x 2-sort.rb
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ls
0-fizzbuzz.py  1-print_square.js  2-sort.rb  README.md
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
-9
-1
2
9
12
31
32
41
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge#
```

* **Repo:**

	- GitHub repository: `Fix_My_Code_Challenge`
	- Directory: `0x00-challenge`
	- File: `2-sort.rb`

3. [User password](./3-user.py )

- Please find here my implementation of a User class in Python: [source code](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/blob/master/3-user.py)

- Something is going wrong…
```sh
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# vi 3-user.py
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# chmod u+x 3-user.py
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ls
0-fizzbuzz.py  1-print_square.js  2-sort.rb  3-user.py  README.md
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ./3-user.py 
Test User
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge#
```

- My tests should not print any error…

* **Repo:**

	- GitHub repository: `Fix_My_Code_Challenge`
	- Directory: `0x00-challenge`
	- File: `3-user.py`

4. [Double linked list](./4-delete_dnodeint/)

- Please find here my implementation of a Double linked list in C: [source code](https://github.com/alx-tools/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint)

- Something is going wrong…
```sh
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# mkdir 4-delete_dnodeint/
mkdir: cannot create directory ‘4-delete_dnodeint/’: File exists
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# ls
0-fizzbuzz.py  1-print_square.js  2-sort.rb  3-user.py  4-delete_dnodeint  README.md
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge# cd 4-delete_dnodeint/
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge/4-delete_dnodeint# gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge/4-delete_dnodeint# ls
add_dnodeint_end.c  delete_dnodeint  delete_dnodeint_at_index.c  free_dlistint.c  lists.h  main.c  print_dlistint.c
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge/4-delete_dnodeint# ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
402
1024
-----------------
1
2
3
4
402
1024
-----------------
2
3
4
402
1024
-----------------
3
4
402
1024
-----------------
4
402
1024
-----------------
402
1024
-----------------
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
root@e1714dc5a3c9:~/Fix_My_Code_Challenge/0x00-challenge/4-delete_dnodeint#
```

- It doesn’t look right…

* **Repo:**

	- GitHub repository: `Fix_My_Code_Challenge`
	- Directory: `0x00-challenge`
	- File: `4-delete_dnodeint/`
