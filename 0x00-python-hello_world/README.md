# 0x00-python-hello_world
## 0. [Run Python file](/0-run)

Write a Shell script that runs a Python script.

The Python file name will be saved in the environment variable $PYFILE
```
guillaume@ubuntu:~/py/0x00$ cat main.py 
#!/usr/bin/python3
print("Best School")

guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py
guillaume@ubuntu:~/py/0x00$ ./0-run
Best School
guillaume@ubuntu:~/py/0x00$
```

## 1. [Run inline](/1-rin_inline)
Write a Shell script that runs Python code.

The Python code will be saved in the environment variable $PYCODE
```
guillaume@ubuntu:~/py/0x00$ export PYCODE='print(f"Best School: {88+10}")'
guillaume@ubuntu:~/py/0x00$ ./1-run_inline 
Best School: 98
guillaume@ubuntu:~/py/0x00$ 
```

## 2. [Hello, print](/2-print.py)
Write a Python script that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.

Use the function print
```
guillaume@ubuntu:~/py/0x00$ ./2-print.py 
"Programming is like building a multilingual puzzle
guillaume@ubuntu:~/py/0x00$
```

