---
layout: post
title:  "C tutorial-3:Print variable"
date:   2017-01-29 09:23:17 +0530
categories: c-tutorial
permalink: /posts/c-tutorial-3
---
Do you remember using `printf` variable and `scanf` variable. If you do that's what we need now.
{% highlight ruby %}
int a=10;
char b="a";
float c=1.213;
{% endhighlight %}
If you remember the initialiser for `int` is `%d`, char is `%c` and float is `%d` to print,
{% highlight ruby %}
printf("%d %c %f",a,b,c);
{% endhighlight %}
here we do not need & infront of variable because & is used only while a value is to be stored from user i.e during `scanf`<br>
Output:
<blockquote>
10 a 1.213
</blockquote>
Now if you want them to print in different lines you can always use `/n`
{% highlight ruby %}
printf("%d /n %c /n %f /n");
{% endhighlight %}
Now the output will be<br/>
Output:
<blockquote>
10<br>
a<br>
1.213<br>
</blockquote>
You can also write `printf` itself on different lines but it will be of no work until you give `\n` on each `printf`
{% highlight ruby %}
printf("%d\n",a);
printf("%c\n",b);
printf("%c\n",c);
{% endhighlight %}
The output will have no change<br>
Output:
<blockquote>
10<br>
a<br>
1.213<br>
</blockquote>
