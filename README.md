# 0x16. C - Simple Shell
This is a project to create our own shell using C.

If you are an ALX Student, don't use this repo as I have used global variables and that will not check Betty.

## About this project
This project is a simple version of the linux shell made for [ALX SOFTWARE ENGINEERING] taking part of the "Simple Shell - Linux and Unix system programming" Project.\
It is created using the **C programming Language** and it can do many functionalities that a real shell does.

## What is Shell?
A **shell** is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.


![Image 1](https://media-exp1.licdn.com/dms/image/C4E12AQEDSX9NeoGOvw/article-inline_image-shrink_1500_2232/0/1587095871027?e=1668038400&v=beta&t=t2LGkg7FNwScqSJg2MNIwVGNIfZsLwu1CR7JWY09GLw)

So, in general, a Shell is a user interface to use the services of a computer.Shell is broadly classified into two categories –

- Command Line Shell - the one we will build
- Graphical shell, like regular software such as Windows Office or Adobe suites.

## The prompt: an infite loop
The first step is to create an infinite loop that is always ready to take any command and prints the shell’s symbol –in the example above, the `“~$”`–. In this way we are setting a shell in an *interactive mode*. The *non-interactive* way is, for example, when you type 

`echo "/home/user/my_shell" | cd` 


![Image 2](https://media-exp1.licdn.com/dms/image/C4E12AQGVMYV-Jz53uw/article-inline_image-shrink_1000_1488/0/1587095762976?e=1668038400&v=beta&t=XrfWeA3cfEzm5ddjs-t0e6Rh-aS9z1n3c0kTKGrNujs)


**stdio.h** is a library that contains the functions to the input and output processes of the system. For example, it has functions to read commands from the user and to write in screen the results of his requests. At system startup, three streams of data are opened: stdio, stdout and stderr.

![Image 3](https://media-exp1.licdn.com/dms/image/C4E12AQFnWxtC20lrBg/article-inline_image-shrink_1000_1488/0/1587095896294?e=1668038400&v=beta&t=GXPt7YsKWEm07h8tC59A2DRQru_n_Djw9zwE9nourNA)


## Essential Functionalities of the Simple Shell:
> Displays a prompt "#cisfun$ " and waits for user input.\
> Runs all commands of type "executable program" (ls and /bin/ls).\
> Runs the following build_in commands: **exit**, **env**, **setenv** and **unsetenv**.\
> Handles commands with arguments.\
> Handles the PATH global variable.\
> Handles The EOF (End Of File) condition.\
> Handles the Ctrl + C signal -> It doesn't exit the shell

## USAGE
You can try our shell by following these steps:
> **Step 1:** Clone our repository using this command, (you need to have git installed on your machine first)
````
git clone https://github.com/iankisali/shell_project
````
> **Step 2:** Change directory to simple_shell:
````
cd shell_project
````
> **Step 3:** Compile the C files in this way:
````
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
````
> **Step 4:** Run the shell
````
./hsh
````
**Exiting the shell**
When you want to exit the shell, you can use one of the following methods:
> **1: Type the command "exit"**
````
exit
````
> **2: Press on Ctrl + D**



## Collaborators
- [Mike Terer](https://github.com/terermike/) 
- [Ian Kisali](https://github.com/iankisali)

## References
- [Tutorial to code a simple shell in C](https://www.linkedin.com/pulse/tutorial-code-simple-shell-c-ricardo-hincapi%C3%A9-trujillo/)
- [Introduction to Linux Shell and Shell Scripting](https://www.geeksforgeeks.org/introduction-linux-shell-shell-scripting/)
- [Making your own Linux Shell in C](https://www.geeksforgeeks.org/making-linux-shell-c/)
