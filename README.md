# Learn Enough Command Line to Be Dangerous
All exercises in Question and Answer form, from Hartl's Learn Enough Command Line to Be Dangerous

## Table of Contents

- [1: Basics](#1-basics)
  - [1.2: Running a terminal](#11-running-a-terminal)
    - [Exercise: 2](#exercise-2)
  - [1.3: Our first command](#12-our-first-command)
    - [Exercise: 1](#exercise-1)
    - [Exercise: 2](#exercise-2-1)
  - [1.4: Man pages](#13-man-pages)
    - [Exercise: 1](#exercise-1-1)
    - [Exercise: 2](#exercise-2-2)
  - [1.5: Editing the line](#14-editing-the-line)
    - [Exercise: 1](#exercise-1-2)
    - [Exercise: 2](#exercise-2-3)
  - [1.6: Cleaning up](#15-cleaning-up)
    - [Exercise: 1](#exercise-1-3)
    - [Exercise: 2](#exercise-2-4)
  - [1.7: Summary](#16-summary)
    - [Exercise: 1](#exercise-1-4)
    - [Exercise: 2](#exercise-2-5)
- [2: Manipulating files](#2-manipulating-files)
  - [2.1: Redirecting and appending](#21-redirecting-and-appending)
    - [Exercise: 1](#exercise-1-5)
    - [Exercise: 2](#exercise-2-6)
    - [Exercise: 3](#exercise-3-3)
  - [2.2: Listing](#22-listing)
    - [Exercise: 1](#exercise-1-6)
    - [Exercise: 2](#exercise-2-7)
    - [Exercise: 3](#exercise-3-1)
  - [2.3: Renaming, copying, deleting](#23-renaming-copying-deleting)
    - [Exercise: 1](#exercise-1-7)
    - [Exercise: 2](#exercise-2-8)
    - [Exercise: 3](#exercise-3-2)
    - [Exercise: 4](#exercise-4)
  - [2.4: Summary](#24-summary)
    - [Exercise: 1](#exercise-1-8)
    - [Exercise: 2](#exercise-2-9)
    - [Exercise: 3](#exercise-3-3)
    - [Exercise: 4](#exercise-4-1)
- [3: Inspecting files](#3-inspecting-files)
  - [3.1: Downloading a file](#31-downloading-a-file)
    - [Exercise: 1](#exercise-1-9)
    - [Exercise: 2](#exercise-2-10)
    - [Exercise: 3](#exercise-3-4)
    - [Exercise: 4](#exercise-4-2)
  - [3.2: Making heads and tails of it](#32-making-heads-and-tails-of-it)
    - [Exercise: 1](#exercise-1-10)
    - [Exercise: 2](#exercise-2-11)
    - [Exercise: 3](#exercise-3-5)
    - [Exercise: 4](#exercise-4-3)
  - [3.3: Less is more](#33-less-is-more)
    - [Exercise: 1](#exercise-1-11)
    - [Exercise: 2](#exercise-2-12)
    - [Exercise: 3](#exercise-3-6)
    - [Exercise: 4](#exercise-4-4)
  - [3.4: Grepping](#34-grepping)
    - [Exercise: 1](#exercise-1-12)
    - [Exercise: 2](#exercise-2-13)
    - [Exercise: 3](#exercise-3-7)
    - [Exercise: 4](#exercise-4-5)
    - [Exercise: 5](#exercise-5)
  - [3.5: Summary](#35-summary)
    - [Exercise: 1](#exercise-1-13)
    - [Exercise: 2](#exercise-2-14)
    - [Exercise: 3](#exercise-3-8)
    - [Exercise: 4](#exercise-4-6)
    - [Exercise: 5](#exercise-5-1)
- [4: Directories](#4-directories)
  - [4.1: Structure](#41-structure)
    - [Exercise: 1](#exercise-1-14)
    - [Exercise: 2](#exercise-2-15)
    - [Exercise: 3](#exercise-3-9)
  - [4.2: Making directories](#42-making-directories)
    - [Exercise: 1](#exercise-1-15)
    - [Exercise: 2](#exercise-2-16)
    - [Exercise: 3](#exercise-3-10)
  - [4.3: Navigating directories](#43-navigating-directories)
    - [Exercise: 1](#exercise-1-16)
    - [Exercise: 2](#exercise-2-17)
    - [Exercise: 3](#exercise-3-11)
    - [Exercise: 4](#exercise-4-7)
  - [4.4: Renaming, coping, deleting directories](#44-renaming-copying-deleting-directories)
    - [Exercise: 1](#exercise-1-17)
    - [Exercise: 2](#exercise-2-18)
    - [Exercise: 3](#exercise-3-12)
    - [Exercise: 4](#exercise-4-8)
  - [4.5: Summary](#45-summary)
    - [Exercise: 1](#exercise-1-18)
    - [Exercise: 2](#exercise-2-19)
    - [Exercise: 3](#exercise-3-13)
    - [Exercise: 4](#exercise-4-9)

## 1: Basics

### 1.2: Running a terminal

#### Exercise: 2

Q: By examining the menu items for your terminal program, figure out how to create a new tab. 

   Extra credit: Learn the keyboard shortcut for creating a new tab.

A: Press `ctrl + t`

---

### 1.3: Our first command

#### Exercise: 1

Q: Write a command that prints out the string “hello, world”. 

Extra credit: As in Listing 1.1, do it two different ways, both with and without using quotation marks. 

A: Type `echo "hello, world"` , `echo hello, world`

#### Exercise: 2

Q: Type the command echo 'hello (with a mismatched single quote), and then get out of trouble using the technique from Box 1.4. 

A: Type `echo "hello` , press `'ctrl + c'`

---

### 1.4: Man Pages 

#### Exercise: 1

Q:  According to the man page, what are the official short and long descriptions of `echo` on your system? 

A: Display a line of text, write arguments to the standard output

#### Exercise: 2

Q:  By reading the man page for `echo`, determine the command needed to print out “hello” without the trailing newline, and verify using your terminal that it works as expected.

A: Type `echo -n [text]`

---

### 1.5: Editing the Line

#### Exercise: 1

Q:  Using the up arrow, print to the screen the strings “fee”, “fie”, “foe”, and “fum” without retyping echo each time.

A: Type `echo fee`, use up arrow each time to replace each letter

#### Exercise: 2

Q:  Starting with the line in Listing 1.6, use any combination of ⌃A, ⌃E, arrow keys, or Option-click to change the occurrences of the short s to the archaic long s “ſ” in order to match the appearance of the original (Figure 1.11). In other words, the argument to `echo` should read “FRom faireſt creatures we deſire increaſe,”.

A: Use up arrow to get to the line.  Use Option-click to replace letter "s" with "f" to resemble this line: "FRom faireſt creatures we deſire increaſe,"

---

### 1.6: Cleaning Up

#### Exercise: 1

Q:  Clear the contents of the current tab. 

A: Press `CMD + K` or type `CLEAR`

#### Exercise: 2

Q:  Open a new tab, execute echo 'hello', and then exit. 

A: Press `CMD + T` to open new tab, type `echo 'hello' , press `CMD + W` to exit.

##### Note: Best to consult terminal `"File" tab` to learn commands.

---

### 1.7: Summary

#### Exercise: 1

Q:  Write a command to print the string `Use "man echo"`, including the quotes; i.e., take care not to print out `Use man echo` instead.

A: Type `echo 'Use "man echo"'`

#### Exercise: 2

Q:  By running `man sleep`, figure out how to make the terminal “sleep” for 5 seconds, and execute the command to do so. 

A: Type `man sleep` , press `Q` to quit manual, type `sleep 5`

#### Exercise: 3

Q:  Execute the command to sleep for 5000 seconds, realize that’s well over an hour, and then use the instructions from Box 1.4 to get out of trouble. 

A: Type `sleep 5000` , press `CTRL + C`

---
