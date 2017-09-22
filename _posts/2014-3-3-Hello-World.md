---
layout: post
title: You're up and running!

It is that time of year again! The McDonald's Monopoly Contest is back, and this time around
you don't want to settle for a free apple pie or a pack of small fries; you are
determined to collect every last token and win big. Fortunately, you are as curious (or as hungry) as you are determined,
so you ask yourself: *"How many times will I have to make a purchase at McDonald's to collect
**each token** exactly one time."* This question can be solved by understanding
the **Coupon Collector Problem**.

The general idea here is that as we increase the amount of unique "coupons" ($n$) we are looking for,
the amount of times we have to *try* to obtain the coupon increases. Furthermore, the chance of getting each
coupon is the same. For example, if we are looking for $40$ unique coupons ($n=40$) we can see that, on average, it will take
$172$ tries to obtain each one.

Let's say you are looking for $50$ unique coupons ($n=50$). In the beginning, you are very likely to draw
a unique coupon; however, if you have $49$ coupons and you are looking
for the $50^{th}$ coupon, *it will take you on average of $n$ tries to draw the last coupon.*
In other words, to draw the $50^{th}$ coupon, you will need to draw an average of $50$ more times.

In this blog post, we covered the general principles of the **Coupon Collector Problem**.
There are many variations and special cases that were not discussed, but if you are interested in
reading more about this topic, a good place to start would be [here](https://probabilityandstats.wordpress.com/tag/coupon-collector-problem/).

---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
