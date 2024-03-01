---
title: "Programming Through C"
date: 2019-07-06T15:27:17+06:00
draft: false
# page title background image
bg_image: "images/backgrounds/page-title.jpg"
# meta description
description : ""
# course thumbnail
image: "images/courses/course-4.jpg"
# taxonomy
category: "Programming"
# teacher
teacher: "Devid Luis"
# duration
duration : "1 semester"
# weekly
weekly : "Will be Updated"
# course fee
fee : "Will be Updated"
# apply url
apply_url : "#"
# type
type: "course"
---

#### About Course
This course is designed for individuals who are new to programming and want to master the C 
Programming Language. The course aims to introduce the problem statements various coding platforms 
such as Hackerrank, GeeksforGeeks, leetcode, etc and include concepts of operators, control structures, 
functions, and arrays.

#### <br>Course Syllabus

#### Problems

#### <br>Problem 1
  A positive integer is called a palindrome if its representation in the decimal system is the same when read from left to right and from right to left. For a given positive integer K of not more than 1000000 digits, write the value of the smallest palindrome larger than K to output. Numbers are always displayed without leading zeros.

**Input Format**    
    The first line contains integer t,thenumber of test cases .Integers K are given in the next t lines.
**Output Format:**    
    For each K, output the smallest palindrome larger than K.
    Input:  2
            808
            2133
    Output: 18
            2222
#### <br>Problem 2
Print hollow diamond pattern using '*'. See examples for more 
details.

**Input Format:**   
    First line of input contains T - number of test cases. Its followed by T lines, each line contains a single odd integer N - the size of the diamond.

    Input : 2
            3
            7
            
    Output : Case #1:   *
                       * *
                        *

            Case #2:    *
                       * *
                      *   *
                     *     *
                      *   *
                       * * 
                        *   
 
#### <br>Problem 3
Given 2 numbers, find their LCM and HCF.<br>
Note: Do not use any inbuilt functions/libraries for your main logic.

**Input Format**    
    First line of input contains T - number of test cases. Its followed 
by T lines, each contains 2 numbers A and B.

**Output Format**    
    For each test case, print their LCM and HCF separated by space, 
separated by newline
**Constraints:**
    1 <= T <= 105<br>
    1 <= A,B <= 109
    Input:  4
            4 710
            13 1
            6 4
            605904 
            996510762
    Output: 1420 2
            13 1
            12 2
            7740895599216 
            78

#### Problem 4
  Given a number N, find the least palindromic number K, such 
that K>N.

**Input Format**    
    First line of input contains T - number of test cases. Its followed 
by T lines, each contains a single number N.
    
**Output Format:**    
    For each test case, print the least palindromic number K, such 
that K>N, separated by newline.


    Input:  2
            11
            121
    
    Output: 22
            131

#### <br>Problem 5
  Given a number N, find the number of bits that are set to 1 in 
its binary representation.
   
    Input:  15
    
    Output: 4

#### <br>Problem 6
  Given a number, check if it is a power of 2.

**Input Format**    
    First line of input contains T - number of test cases. Its followed 
by T lines, each line containing a single positive integer.
    
**Output Format:**    
    For each test case, print "True" or "False", separated by new line.

    Input:  5
            1
            8
            10
            25
            512
    
    Output: True
            True

#### <br>Problem 7
  Given an array of size N, it contains all the numbers from 1 to 
N+1 inclusive, except one number. You have to find the missing 
number.

**Input Format**    
    First line of input contains T - number of test cases. Its followed 
by 2T lines, first line of each test case contains N - size of the 
array and the next line contains N integers - the elements of the 
array.
    
**Output Format:**    
    For each test case, print the missing number, separated by 
newline.

    Input:  3
            8
            1 2 7 9 5 6 3 8
            7
            3 5 8 1 4 7 2
            10
            8 11 10 2 7 4 3 5
            1 6
    
    Output: 4
            6
            9

#### <br>Problem 8
  Given two numbers X and Y, find the number whose binary 
representation has X 1's followed by Y 0's.

    Input:  4 3
    
    Output: 120

#### <br>Problem 9
  You are given two numbers A and B. Write a program to count 
the number of bits to be flipped to change the number A to the 
number B. Flipping a bit of a number means changing a bit from 
1 to 0 or vice versa.

    Input:  20 10
    
    Output: 4

#### <br>Problem 10
  Given 2 numbers - a and b, evaluate ab.
Note: Do not use any inbuilt functions/libraries for your main 
logic.

    Input:  5 2
    
    Output: 24

#### <br>Problem 11
  Given an array of unique integer elements, print all the subsets 
of the given array in lexicographical order.

    Input:  3 15 5
    
    Output: 3
            3 5
            3 5 15
            3 15
            5
            5 15
            15

#### <br>Problem 12
  Given an array of size 3X+1, where every element occurs three 
times, except one element, which occurs only once. Find the 
element that occurs only once.

    Input:  5 7 8 7 7 5 5 9 8 8
    
    Output: 9

#### <br>Problem 13
  The Tower of Hanoi (also called the Tower of Brahma or Lucas') 
is a mathematical game or puzzle. It consists of three rods, and 
a number of disks of different sizes which can slide onto any 
rod. The puzzle starts with the disks in a neat stack in ascending 
order of size on one rod, the smallest at the top, thus making a 
conical shape.<br>
The objective of the puzzle is to move the entire stack to 
another rod, obeying the following simple rules:
Only one disk can be moved at a time.
Each move consists of taking the upper disk from one of the 
stacks and placing it on top of another stack i.e. a disk can only 
be moved if it is the uppermost disk on a stack.
No disk may be placed on top of a smaller disk.
Your task is that given N disks, print the minimum number of 
moves required in order to solve the problem, followed by the 
actual moves.<br>
<br>*Assumptions*
* The rods are named A, B and C.
* All the disks are initially placed on rod A.
* You have to move all the disks from rod A to rod C.

        Input:  1
                3

        Output: 1
                Move 1 from A to
                C
                7
                Move 1 from A to
                C
                Move 2 from A to
                B
                Move 1 from C to
                B
                Move 3 from A to
                C
                Move 1 from B to
                A
                Move 2 from B to
                C
                Move 1 from A to


### <br>References
* Yeshvanth Kanethkar., Let Us C, 5th Edition, BPB Publications , New Delhi, 2017.
*  B.A. Forouzan and R.F. Gilberg, Computer Science: A Structured Programming Approach 
Using C, 3rd Edition, Thompson Learning, 2007.
* E Balagurusamy., Programming in ANSI C, 8th Edition, Tata McGRAW HILL, New
Delhi, 2019.
*  Byron Gottfried. , Programming with C , 4th Edition,Schaum's Outlines , Mc GRAW
HILL Edition, 2018.

### Online Resources
* **[Solve C | HackerRank(https://www.hackerrank.com/domains/c?badge_type=c)**
*  **[Courses (neetcode.io)] (https://neetcode.io/courses)**
* **[C Tutorial - Learn C Programming Language (geeksforgeeks.org)](https://www.geeksforgeeks.org/c-programming-language/?ref=shm)**
* **[Problem Solving Through Programming In C - Course (nptel.ac.in)](https://onlinecourses.nptel.ac.in/noc22_cs101/preview)** 

### Syllabus
- **[Click here to view](#)**
