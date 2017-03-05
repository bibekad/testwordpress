---
layout: post
title:  "C tutorial-1:Printf"
date:   2017-01-27 07:19:17 +0530
categories: c-tutorial
header: C tutorial-1:Printf
permalink: /posts/c-tutorial-1
---
The first thnig that anyone will learn on Btech CSE is `C programming`. To start what is `c programming`. It is just a subject oriented language. Anyone would wonder why do we need `C language` when we already have object oriented programming languages like `c++`.
But in reality we do need `C programming language` because each and every language that comes futher is further extention of C language.(Atleast that's what our teacher said to make us believe that C is important). Now what do we need to start learning `C programming`. We need an operating system. any operating system. `Windows` or `Linux` or `Mac` or any other. And you will need an editing software. Like while I was using `windows`, I used `Dev C++`, some of my friends used `Code Blocks`.You can visit their official website, download and install. Easy as that. For `linux` you can use any editor just like `gedit`, or `leafpad`, I personally like to use `Atom`. to download atom just go to <a href="http://atom.io">Atom</a> website and download it and install it using your terminal.
I have never used mac so I've no idea what works for `mac`, but you can always `google`.
Now what would be the first thing to do in `C programming`. Like every other tutorial you might have read or watched, I'm also going to print hello world.
You have to keep in mind about the header, `#include<stdio.h>`is the header file of all `C programs`
The content is written in `int main()` or `main()` or `void main()` depending upon compiler. All content are written inside  curly brackets of `int main(){}`
{% highlight ruby %}
#include<stdio.h>
int main()
{
printf("Hello World!");
}
{% endhighlight %}
`printf` is a keyword, I called it print function just to remember, The thing you have to remember is
that C programming is case sensitive unlike html, almost all keywords are in lowecase. so `Printf` and `printf` are completely different in terms of `C programming`.The above code will give the below output.<br>
Output:
<blockquote>
Hello World!
</blockquote>
Now what you have to understand is except for `%` and `\` annything that you will write between " and " of your printf  will be printed as such in your output.
Now the question that I forgot to tell is how to get the output. To get the output in `Devc++` or other windows software, You can click `compile and run in tab compile` for `linux` to get output you have to open `terminal` in same file location where your program is saved and type following.
{% highlight ruby %}
# g++ filename.cpp
for compiling your program.
then a new file named a.out will be formed
# ./a.out
then you will see the output in terminal itself
{% endhighlight %}
Now let's see what happens when we use keyword `printf` two times in a row.
{% highlight ruby %}
#include<stdio.h>
int main()
{
printf("Hello World!");
printf("Hello World!");
}
{% endhighlight %}
Output:
<blockquote>
Hello World!Hello World!
</blockquote>
The output is not what you expected, or is it? We expected two `Hello World!`s to come in two different lines but what we forgot is to tell the compiler to break line just like `<br>` that we use to break line in html, in C we have `\n` now where to keep it in `printf`
{% highlight ruby %}
#include<stdio.h>
int main()
{
printf("Hello World!\n");
printf("Hello World!");
}
{% endhighlight %}
Now do you remember that except for `%` and `\` elements everything except for it gets printed as it is. So the output will be<br>
Output:
<blockquote>
Hello World!<br>
Hello World!
</blockquote>
For linux I recommend to use `\n` on both `printf` statements to get the terminal initials a line below when our program ends.
