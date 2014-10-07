---
layout: post
title:  "Static pages on Heroku"
date:   2014-10-07 15:08:00
tags: featured
image: /assets/article_images/2014-10-07-static-pages-on-heroku/article1.jpg
published: true
---

Lets get straight into it, I have been developing a static website for a client however this client isn't very technical so the best way to display my results to them is by handing them a link they click on and see the product.

How was I going to do this? by making Heroku accept my static pages. The easiest way to do this, I found was to simply create an index.php file that includes my html file.

{% highlight php %}
  <?php include_once("home.html"); ?>
{% endhighlight%}
