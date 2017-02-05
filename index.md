---
layout: default
title: JKSR's website
---

# haha

#### test

this is a [test post](https://jksr.github.io/posts/mytest/test)

{% for post in site.posts %}

## [{{ post.title }}]( http://jksr.github.io{{ post.url }} )

#### {{post.category}}

#### {{ post.date | date: "%Y-%m-%d" }}

#### ![img](http://jksr.github.io/images/post_images/{{ post.date | date: "%Y-%m-%d"}}/highlight.png)

----

{% endfor %}


