---
layout: default
title: JKSR's website
---

# haha

#### test

this is a [test post](https://jksr.github.io/posts/mytest/test)

{% for cate in site.categories %}

***

{% for posts in cate %}
{% for post in posts %}

# {{ cate }}

## [{{ post.title }}]( http://jksr.github.io{{ post.url }} )

#### ![img](http://jksr.github.io/images/post_images/{{ post.date | date: "%Y-%m-%d"}}/highlight.png)

{% endfor %}
{% endfor %}
{% endfor %}

