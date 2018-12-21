---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-20
---

## Flag of the United Kingdom by Lucas Alcantara

## Describe your program

-   I designed the flag of the United Kingdom also known as the Union Jack. 
-   Not to be concieted but, I believe I deserve a professional. It shows well in my program that I have an understanding on how to correctlty create the right dimensions for the given flag, and I am able to describe each part of the code correctly. 



## Current output


* * *
![fleg](/images/fleg.png) 
* * *

## Describe your process.


I had a basic understanding of the project, there weren't many problems that arouse other than trying to figure out how to translate the dimensions into code which my friend Noah Johnson helped with). For some reason I had a lot of trouble getting the DW and DR (diagonal whites and reds) to get on the proper angle I needed them to be in. Other than that it was a fun and challenging task.



## Explain your code.

This is how I started the flag code. Basically like said in the comment these are the basic parts of the flag, each individual piece creates the Union Jack. So on their own the Base-rectangle would just be a solid dark blue rectangle (2:3)
WR would be a white rectangle 
VertW would be the white verticle rectangle
DW1 and DW2 would be the diagonal white rectangles going in an X shape throughout the flag
DR1-4 would be the red diagonal rectangles going in that same shape
V and H would be the final two recatangles needed to make the Union Jack the beautiful flag it is.

As a whole, the simple parts let the program realize that these are the definitions needed to make the whole flag.
It gives us the oppurtunity to utilize each of the definitions to their fullest ability.


```
#simple parts for uk

Base=rectangle(length,height,"solid","dark-blue")

WR =rectangle(length,height / 3,"solid","white")

VertW =rectangle(length / 5,height,"solid","white")

DW1 =rectangle(dlength,height / 5,"solid","white")

DW2 =rectangle(dlength,height / 5,"solid","white")

DR1 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR2 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR3 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR4 =rectangle(dlength / 2,dwidth / 3,"solid","red")

V =rectangle(60,300,"solid","red")

H =rectangle(length,height / 5,"solid","red")
```



## Program code

```
Base=rectangle(length,height,"solid","dark-blue")

WR =rectangle(length,height / 3,"solid","white")

VertW =rectangle(length / 5,height,"solid","white")

DW1 =rectangle(dlength,height / 5,"solid","white")

DW2 =rectangle(dlength,height / 5,"solid","white")

DR1 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR2 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR3 =rectangle(dlength / 2,dwidth / 3,"solid","red")

DR4 =rectangle(dlength / 2,dwidth / 3,"solid","red")

V =rectangle(60,300,"solid","red")

H =rectangle(length,height / 5,"solid","red")

#combination of simple parts for uk

st =place-image(rotate(30,DW1),250,150,Base)

nd =place-image(rotate(150,DW2),250,150,st)

rd =place-image(rotate(150,DR1),100,75,nd)

th =place-image(rotate(30,DR2),360,75,rd)

f =place-image(rotate(150,DR3),445,250,th)

s =place-image(rotate(30,DR4),140,225,f)

se =place-image(WR,250,150,s)

e =place-image(VertW,250,150,se)

n =place-image(V,250,150,e)

uk =place-image(H,250,150,n)

```
