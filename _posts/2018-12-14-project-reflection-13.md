---
 layout: Post
 title: "Lucas Alcantara, Project Relfection" 
 date: 2018-12-14
---
Flag of the United Kingdom
![fleg](/images/fleg.png) 



# My Understanding of the Flag Project

If you look at my previous weekly reflection (posibbly week 5 or 6) you can see that we had an assignment to code our choice of flags in Pyret. I was able to make two flags, Germany and Ghana. I had a basic understanding of the project 


# Code for the Flag

include image
height = 300
length = 500
dlength = 700
dwidth = 60

#simple parts for uk

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
