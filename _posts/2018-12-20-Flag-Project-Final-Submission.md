---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-20
---

## Flag of the United Kingdom by Lucas Alcantara

## Describe your program

-   I designed the flag of the United Kingdom also known as the Union Jack. 
-   What grade do you expect? 



## Current output


* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.


I had a basic understanding of the project, there weren't many problems that arouse other than trying to figure out how to translate the dimensions into code which my friend Noah Johnson helped with). For some reason I had a lot of trouble getting the DW and DR (diagonal whites and reds) to get on the proper angle I needed them to be in. Other than that it was a fun and challenging task.

<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_




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

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


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
