```

████╗  ░█████╗░██████╗░████████╗██╗░█████╗░███╗░░██╗░█████╗░██╗░░░░░  ████╗
██╔═╝  ██╔══██╗██╔══██╗╚══██╔══╝██║██╔══██╗████╗░██║██╔══██╗██║░░░░░  ╚═██║
██║░░  ██║░░██║██████╔╝░░░██║░░░██║██║░░██║██╔██╗██║███████║██║░░░░░  ░░██║
██║░░  ██║░░██║██╔═══╝░░░░██║░░░██║██║░░██║██║╚████║██╔══██║██║░░░░░  ░░██║
████╗  ╚█████╔╝██║░░░░░░░░██║░░░██║╚█████╔╝██║░╚███║██║░░██║███████╗  ████║
╚═══╝  ░╚════╝░╚═╝░░░░░░░░╚═╝░░░╚═╝░╚════╝░╚═╝░░╚══╝╚═╝░░╚═╝╚══════╝  ╚═══╝

██╗░░░██╗░█████╗░░██████╗░██████╗░░█████╗░███╗░░██╗████████╗
██║░░░██║██╔══██╗██╔════╝░██╔══██╗██╔══██╗████╗░██║╚══██╔══╝
╚██╗░██╔╝███████║██║░░██╗░██████╔╝███████║██╔██╗██║░░░██║░░░
░╚████╔╝░██╔══██║██║░░╚██╗██╔══██╗██╔══██║██║╚████║░░░██║░░░
░░╚██╔╝░░██║░░██║╚██████╔╝██║░░██║██║░░██║██║░╚███║░░░██║░░░
░░░╚═╝░░░╚═╝░░╚═╝░╚═════╝░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚══╝░░░╚═╝░░░
```



<br><br><br>



# Concepts

For this project, we expect you to look at this concept:

* [Using Vagrant on your personal computer](https://intranet.alxswe.com/concepts/81)


<br><br>


#### Vagrant - or - how to code in your local computer

Sandboxes are great, but you can also do your ALX assessments on your local computer - having a virtual machine (VM) is the perfect tool for that.

Let’s dig into <b>Vagrant</b> today!

Also:

* This project is <b>100% optional</b>
* This project <b>can’t be done in Sandboxes</b> - it can be done only in your local computer.



<br><br>


# Resources

<b>Read or watch:</b>

* [Virtual machine](https://intranet.alxswe.com/rltoken/eoV8V_5fgzW_UhJ3PtVyWw)
* [man uname](https://intranet.alxswe.com/rltoken/Z4MowYniH5YJoZo4jZgIBw)



<br><br>

# Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/g5OVhHRsT0jjsvUI1Y8jgw), without the help of Google:
### General

* What is a virtual machine
* What is Vagrant
* Who wrote Vagrant
* What is Ubuntu
* What does “Ubuntu” mean
* How to use VMs with Vagrant
* What does the command `uname` do

### Copyright - Plagiarism

* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.





<br><br>

# Requirements

### General

* A `README.md` file at the root of the repo, containing a description of the repository
* A `README.md` file, at the root of the folder of this project (i.e. `0x00-vagrant`), describing what this project is about




<br><br>

# More Info

### Install `git`

If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

### Warning

This project <b>can’t be done in Sandboxes</b> - it can be done only in your local computer. Please refer to our concept pages for your operating system.





<br><br>


# Tasks


<br>>=============================================================================<br>

### 0. Create and setup your Git and GitHub account


You will need Git for this project, you might have to [install it](https://intranet.alxswe.com/rltoken/7kPsched1VMPOY2bdvZvGQ) on your computer if it’s not done yet.

* Configure your basic info (name, email) on your local machine – they will be part of your* commits. [Tips](https://intranet.alxswe.com/rltoken/oAAqmPJ1ftZZhUjaw7FvjA)

On [GitHub.com](https://intranet.alxswe.com/rltoken/4vp5Qze3WATHKtytzT2_UA):

* Using the graphic interface on the website, create the repository (if it’s not done yet)
    * Description: `This is my first repository as a full-stack engineer`
    * Public repo: `zero_day`
    * No `README`, `.gitignore`, or license

On your computer, open a terminal and do the following:

* Navigate to your home directory. [Tips](https://intranet.alxswe.com/rltoken/YeOwsN-vhfSCbNjgE01Gag)
* Create a directory `zero_day`. [Tips](https://intranet.alxswe.com/rltoken/hWrqqlilEv8L6yqpyt1TTA)
* Navigate to this new directory. [Tips](https://intranet.alxswe.com/rltoken/za58mq537U6U775osQ8bfQ)
* Initialize git and add the remote origin
* Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://intranet.alxswe.com/rltoken/VV79mKOEf5mXVbKpH4i63Q) text to present this project. <b>This file is mandatory in projects</b>
* Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your <b>first repository</b> of the <b>first task</b> of your <b>first School project</b>.

#### Repo:

* GitHub repository: `zero_day`
* File: `README.md`




<br>>=============================================================================<br>



### 1. Hello Ubuntu


Inside the `zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory.

`ssh` into your Ubuntu VM. What does the command `uname` print when you run it without any option?

Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file accordingly as shown below.

#### Repo:

* GitHub repository: `zero_day`
* Directory: `0x00-vagrant`
* File: `0-hello_ubuntu`




