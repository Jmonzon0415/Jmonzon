---
layout: post
title:  "Hit The Ground Running "
date:   2016-01-10 14:34:52 -0500
categories: jekyll update
---
First week of onsite in the books! The first few days of version control and terminal commands were a refreshing review and then we dove right into ruby. It was great to be in a room of people with a common goal and great instructors. The best part was seeing everyones different approach to solve one problem. It really showed how many ways there are to attack the logic. 

This week really exposed my weakness in changing my approach to a problem. Every time we were given a challenge I found myself locked on one idea of how to solve it. I would go down a rabbit hole of research with out testing and waste valuable time. I need to change my process to a more open approach.   A prime example of this was on the credit card exercise. We needed to take account number and replace all the digits except the last four with “ *’”. I had in my mind to make an array and approached the problem like that, without considering I can use the string indices like this: 

{% highlight ruby %}
def display_secure_account_num
    last_four = @account_num[-4..-1]
    num_stars = @account_num.length - 4
    p "*" * num_stars + last_four
 
  end 
{% endhighlight %}

I wasted a lot time trying my approach and it was eye opening to look at the clock and realized 90 minutes have passed. This is the biggest thing I took away from this week.

Overall I am really excited to dive into Rails this next week and to see it all come together! 


