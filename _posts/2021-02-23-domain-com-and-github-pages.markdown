---
layout: post
title:  "Building personal website in 20 mins on personal domain using github pages"
date:   2021-03-23 22:24:16 +0100
categories: jekyll update
---

I have been thinking since a while to start a new portfolio. My **last portfolio** looked like this at the end of its journey:

![image](/static/images/old_portfolio.png)
______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

It was also built using `Jekyll`, but was very lengthy to update because of some customization I did in it. After some procrastination, I decided to use a minimal `Jekyll` theme to reinvent my site.

Some requisites which I already had in mind:

1. Get my [own domain](#Getting my own domain).
2. Setup an email on my domain.
3. New site should be hosted via **github pages**.
4. Github provided URL should point to my domain.

This all took me 20 minutes in total, thanks to Jekyll theme (`open_source == love`) and at the end, I did also write my first blog post :)


# Getting my own domain
I used [domain.com](domain.com) to get a domain name ([tiwariayush.com](https://tiwariayush.com) in my case). Honestly, it was quite straightforward process to get domain name. Lucky for me, I got it for a very good discount (7 euros first year and then 9 euros/yr for the next years).

# Setting up email on my domain
Again, this was taken care of by [domain.com](domain.com). There is a very nice documentation on [how to add DNS records](https://www.domain.com/help/article/dns-management-how-to-update-dns-records). For email sending, you need to add a `SMTP` record.

If needed you can also check their doc on adding up an [email client](https://www.domain.com/help/article/email-client-setup) which was very useful to me.

# Host site on github pages
This could be read from my [first blog post](https://tiwariayush.com/jekyll/update/2021/03/22/welcome-to-jekyll.html)

# Point Github to your domain
You need to use `CNAME` file to point your github page to your domain name.

***************

All 4 done, push the changes to your github repository and you can go to your domain name URL to verify if the updates are well in place !

Voila ! You have your **blog + portfolio in 20 minutes ! Congrats !**
