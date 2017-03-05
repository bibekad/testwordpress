---
layout: post
title: "Starting Jekyll"
date: 2017-03-02 00:00:00 +0530
categories: internet
permalink: /posts/starting-jekyll
---
I have finally transfered my [blog](/) to Jekyll, for someone like me, who likes things free rather than paid, Using Jekyll to make my blog has been blessing. As you can see I am using a free web domain [dot tk](http://dot.tk) made using website [freenom](http://freenom.com), making a stable website has always been a trouble. There are many free hosting sites like [000webhost](http://000webhost.com) or [1freehosting](http://1freehosting.com) but they are not upto mark. For free there is not much to complain, but my website had its server crashed like __4 times in every 10 times__. People also asked me, why did not I use websites like [blogspot](http://blogspot.com) or [wix](http://wix.com) to run my blog. Yes, while using blogspot or wix or yola or such other websites the blog never crashed. And I used it much time ago, but there was some other problem, like, while using blogspt to make my blog, I found it very hard to edit the layouts and ther was not much freedom to choose how my blog looks like. The only template that I ever liked in blogspot was dynamic template, but choosing dynamic template made the website slower. Now coming to drag and drop design websites like wix or yola, there was always a limit till which I could use the facilities provided by them, as long as I wanted to do something, it was out of services provided to free account, and yes the website did not crash, but was almost always slow. Then I tried the __Go Site__ provided by freenom, that was a lot hard than wix or yola, or weebly. Yes I liked weebly, but it was almost not free, to give a website to my domain was not free, but I could use free subdomain provided by weebly which was actually good. Now lets talk about Go site, free - yes, fast - yes, good user interference - no. Now, my website is as stable as any other paid websites. This is due to hosting my website using [github](http://github.com). Language used is jekyll. What I got using jekyll was freedom, the freedom to make my own layout, the freedom to edit anything I want using pre-loaded templates. Even writing content became fun. It was like I am the godfather of my website. But there are limitations of using Jekyll too. For me, as I got my domain from __Freenom__, there was no C-panel. Using __000webhost__ and __1freehosting__, I used to get free Cpanel, but since now I am not using any hosting site, I do not have any free C-panel. Setting up jekyll is not that hard, if you are using linux, or mac, but for windows, it is. You can also visit [Github Pages](http://pages.github.com) to see how is github setup in windows.Then you can visit a website [Milanaryal.com](https://milanaryal.com/jekyll-on-windows/) I found it usefull for windows users, to set up jekyll. But in linux it is very easy, you just have to open terminal, run a couple of commands and you are done, simple is that.
{% highlight ruby %}
gem install jekyll bundler #--> To install jekyll
#--> Now open directory where you want to save your blog
jekyll new blog
{% endhighlight %}
After running above two codes, you will have a folder named blog on you terminal opened directory. Then you can open the folder.
{% highlight ruby %}
jekyll serve --incremental 
#-->//OR
jekyll serve
{% endhighlight %}
Now you can make a blog out of it, and host it in github.
