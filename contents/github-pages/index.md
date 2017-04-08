---
title: Free&Easy Hosting
author: azat
date: 2015-01-22 15:00
template: article.jade
---

Tech advice: if you need a simple website for your project, then use [GitHub pages](https://pages.github.com). It's free and better than cheap $4.99/mo hosting, which can be easily hacked, is slow and requires you to use cPanel.

Here's what you'll need to get your website up and running:

1. Create account on GitHub (do it once).
2. Create a new repository.
3. Send your developer a link to that repository, and a Twitter Bootstrap theme of your choice (Google it if you don't know where to get a beatiful theme).
4. Point your CNAME records in Godaddy, or whatever you're using, to GitHub IPs (192.30.252.153 and 192.30.252.154).
5. Merge pull request from you developer on GitHub.com.
6. Boom! You've got your website.

I use this technique for my 10+ websites, some of them quite fancy:

* <http://rpjs.co>
* <http://150x.co>
* <http://azat.co>
* <http://proexpressjs.com>
* <http://expressjsguide.com>
* <http://azat.co/blog>
* <http://nodeprogram.com>

There's no need for WordPress or PHP. GitHub Pages is free and it is faster than BlueHost.

The site must be static only without any PHP, Node.js or any other server-side logic. You can use [foxyform](http://www.foxyform.com) or [EmailMeForm](http://www.emailmeform.com) for contact forms, and [Gumroad](http://gumroad.com) for sales. For blogs, you can use [Wintersmith](http://wintersmith.io) or [Jekyll](http://jekyllrb.com).