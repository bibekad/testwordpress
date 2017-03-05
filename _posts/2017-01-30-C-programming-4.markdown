---
layout: post
title:  "C tutorial-4:Algebra"
date:   2017-01-30 09:23:17 +0530
categories: c-tutorial
permalink: /posts/c-tutorial-4
---
Now let's begin again. Now we are going to look towards algerbra like `+`,`-`,`*`,`/`. To start with lets initialize two variables 'a' and 'b'
{% highlight ruby %}
int a;
int b;
{% endhighlight %}
Or we can also use float
{% highlight ruby %}
float a;
float b;
{% endhighlight %}
The only problem that I feel from float is that it gives .00 even for normal integers.<br>
Now lets ask user for the value of 'a' and 'b'
{% highlight ruby %}
#=>For Int
scanf("%d %d",&a,&b);
#=>For Float
scanf("%f %f",&a,&b);
{% endhighlight %}
Now let us initialize outputs
{% highlight ruby %}
int sum,subs,mul,div;
{% endhighlight %}
Lets start Processing
{% highlight ruby %}
sum=a+b;
subs=a-b;
mul=a*b;
div=a/b;
{% endhighlight %}
Now let us print the outputs
{% highlight ruby %}
#=>For int
printf("%d\n",sum);
printf("%d\n",subs);
printf("%d\n",mul);
printf("%d"\n,div);
#=>For float
printf("%f\n",sum);
printf("%f\n",subs);
printf("%f\n",mul);
printf("%f"\n,div);
{% endhighlight %}
Lets see what do we get as a output considering inputs as a=20 and b=40
<blockquote>
20<br>
40<br>
#=>For int<br>
60<br>
-20<br>
800<br>
0<br>
#=>For float<br>
60.00<br>
-20.00<br>
800.00<br>
0.50<br>
</blockquote>
Some compiler might give garbage value to subs and div while using int<br>
Unlike our normal airthemetics there is a sign `%` used for arithmetic in `C programming`, let's see what it does
{% highlight ruby %}
int a=10;
int b=3;
int out;
out=a%b;
printf("%d",out);
{% endhighlight %}
Let's see its output<br>
Output:
<blockquote>
1
</blockquote>
Now how does this one come and what does `%` do?. Let's see if we divide 10 by 3 then `3*3=9` with remainder 1. This is what `%` does, it finds our remainder when a number is divided by another number.
