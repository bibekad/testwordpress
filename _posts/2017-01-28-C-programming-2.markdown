---
layout: post
title:  "C tutorial-2:Variables and Scanf"
date:   2017-01-28 09:23:17 +0530
categories: c-tutorial
permalink: /posts/c-tutorial-2
---
You would certainy not only always print `Hello World!` in your `C program` But it is almost all about print and scan, that's what the user sees. To begin with scanning from user. We need to understand how to `declare` a variable, `initialise` it or `give value` to it. Now let's begin
{% highlight ruby %}
int a;
char b;
float c;
{% endhighlight %}
<h3>Now what is int, char and float?</h3>
`int` is used for giving integer value to a variable, i.e in above program, you can give any integer value to a, i.e 1, 2 , 100, 23213,..... but you can not give any character value like 'a', 'c',... or any numeric value with decimals like 1.223, 123.213<br/>
`char` is used for giving any character value to a variable. i.e in above program you can give any single character value to b. like 1,2,3,....9 or 'a','b','c'.......'z' but not more than one charactr like 'bibek' or 'blog' or even 'is'.<br/>
`float` is used for giving numeric value with decimals to a variable. i.e in above program you can give any numeric value to c, like 1 2 23 4324.432 ..... but float does not take alphabetical or unique characters.<br>
Now lets give some value to our variables. Now there are three methods of giving value to a variable.
<h3>1. Initialise </h3>
{% highlight ruby %}
int a=20;
char b="a";
float c=4.53;
{% endhighlight %}
<h3>2.Define and Declare </h3>
{% highlight ruby %}
int a
char b;
float c;
a=20;
b="a";
c=4.53;
{% endhighlight %}
<h3> User defined</h3>
To understand how to give value to variable by user, we have to know about `scanf()` function.
{% highlight ruby %}
int a;
char b;
float c;
scanf("%d",&a);
scanf("%c",&b);
scanf("%f",&c);
{% endhighlight %}
here %d is for saying compiler that it is a integer.
after " " there is ,&a, this is for saying compiler where to save the value given by user<br>
%c is for char<br>
%f is for float <br>

| Variable type     | Initialiser     | |Bytes |
| :--------------- | :--------------- | |:----------|
| Integer       | %d       | |    2 or 4bytes|
| Character     | %c       | |      1byte|
| Float         | %f       | |   4 or 8 bytes|
|Long integer   | %ld      | |  double of integer|
|String         | %s       | | defined during declaration|
