---
layout: post
title:  "Week Eleven"
date:   2016-11-6
categories: jekyll update
---

# 1. What did you do this past week?
We finished the second phase of the project.

# 2. What's in your way?
My group is having trouble fixing our splash page. Right now the images in the carousel are not able to be enlarged to full screen and our website doesn't look quite as professional. 

# 3. What will you do next week?
Fix our splash page in the final phase of the project (there is definitely something stupid that we are missing), add more features to our website if time allows (such as a like button for the open source projects, or ratings). Also start studying for the next SWE test by reviewing the materials we went over so far.

# My experience in the class:
This week we learned the difference between DTD (Document Type Definition) and XSD (XML Schema Definition). I actually got an interview question on XML but unfortunately I didn't know anything about XML back then. On Wednesday, we covered a third schema type -- the good old JSON. It's the prettiest and most intuitive schema format, in my opinion, but JSON lacks a pretty cool pointing system that XSD and DTD have. We are also introduced to some beginner SQL commands. On Friday, we went more in depth into the world of SQL and learned about subqueries and aggregate functions. I already knew SQL from Data Management class, but the review was definitely really helpful because it reminded me of the things I forgot. At the end of the class, I wondered if we can *not* use a subquery, and just use a simple join to achieve the same thing. In other words, how do we know when to use a subquery? (Because they take longer to run and having the most optimized performance is always preferred).

# Tip of the week:
To answer the question above, first read the second answer from this [Stack Overflow article](http://stackoverflow.com/questions/2577174/join-vs-sub-query) on the difference between joins and subqueries. Then read this [page](http://support.sas.com/documentation/cdl/en/sqlproc/69049/HTML/default/viewer.htm#n1dvk6nw2jgit3n1wp3xf9q3fkvv.htm) that explains when to use joins and subqueries. Basically, if you need to filter the table (retrieve a subset of the whole table) or if you just to know memebership (using not exists conditions), then you need to use a subquery. Otherwise, if both accomplish the same thing, then a join would be better because it's not only more readable/concise, but it's also faster in performance.