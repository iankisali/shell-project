# 0x16. C - Simple Shell
This is a project to create our own shell using C.

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

## Collaborators
Code done by [Mike Terer](https://github.com/terermike/) and [Ian Kisali](https://github.com/iankisali)
