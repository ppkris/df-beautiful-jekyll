---
layout: post
title: Website Setup Diary
subtitle: Difficulties I met during setting up this website
cover-img: /assets/img/gustav-gullstrand.jpg
thumbnail-img: /assets/img/kiki-wang-TOc.jpg
share-img: /assets/img/path.jpg
permalink: /setup diary/
tags: [story]
---

# Achievement #1
I learned how to use GitHub.

# Achievement #2
I learned markdown syntax.

# Achievement #3
I met problem when adopting the theme "beautiful-jekyll" and spent almost 48 hours 
without any progress. I forked the theme on July 29th making changes on it for two straight nights until morning 
when I had to take 2 hours nap and began my MacLean Center summer intensive lectures at 8 am on the bed 
turning off the video and kept muted.  

I even started a new issue on GitHub which I become familiar with.
>#### Thank you Dean for this beautiful theme. I really like it.
>
>#### Yet, I encountered one problem when deploying the _site to my server after building.
>
>#### 1. It seems not rendering well.  
>#### 2. The permalink I set for "about", "blog" or "projects" does not work.
>#### http://www.diagnosticforest.com:200/
>#### Both of the problems do not exist when I deploy them on Github.
>#### https://ppkris.github.io/df-beautiful-jekyll/
>#### GitHub repo: https://github.com/ppkris/df-beautiful-jekyll
>
>#### I spent 2 whole days googling and trying to figure it out, but this place is my last resort.
>#### Anyone encounter the same problem? I really like the theme so I don't want to quit.
>#### Thank you so much.

The author replied immediately:
>#### I'm sorry it's going to be very very difficult for me to help you 
>#### debug a custom server set up, there's just too many variables at play 
>#### there. If I had a lot of time on my hands I would ask you to send me 
>#### credentials to your server to troubleshoot, but I'm working on about 
>#### a dozen open source projects at the moment (plus my actual work) so 
>#### I really don't have time to dedicate so much time for free help 
>#### unfortunately. If I were you I'd try to start again and take small 
>#### steps and see when exactly it stops working.

Actually I figured out the problem of improper rendering myself. It was because 
I did not clean my chrome and since the website runs very well on Safari, 
ipad, and iphone. I accidentally tried it on Safari and found there is no 
problem of rendering. So I my google key words turned from css jekyll to css 
chrome and found the answer on StackOverflow. I would thank the replier so 
much.  

Then Dean's advice really helped me and I think that is a generally correct 
pathway to fix any problem that you might feel frustrated and unclear about.  

I started over again, and cloned a brand new repo, trying to take every small step 
cautiously. In the end I do not know what fixed my permalink problem, at least that issue
is gone.  

But after deploying _site to my own server another issue raised that is I can not return 
to my main page by clicking title or avatar pic in branch pages since both of the links 
were pointing to their current folder but not the main page.  

By checking the last issue of permalink I learned that one can change `baseurl` in `_config.yml`. 
It seems this trick helps here though it can't fix my permalink problem. I just need to change 
the `baseurl` to `"../"` every time I want to build `_site`. But I have to keep `baseurl` to `""` 
when working locally, otherwise the links rendered in site would be in chaos.  

OK, these are my 3 days' summary of learning website front end development. At last I learned something 
pretty useful both technically and philosophically.  

Let's keep learning and now it's time to turn back to machine learning.



