---
layout: default
title: JKSR's website
---

# haha

#### test

this is a [test post](https://jksr.github.io/posts/mytest/test)

{% for cate in site.categories %}

***

# {{ cate | first }}

haha

{% for posts in cate %}
{% for post in posts %}

{% if post.title != nil %}
### [{{ post.title }}]( http://jksr.github.io{{ post.url }} )
#### ![img](http://jksr.github.io/images/post_images/{{ post.date | date: "%Y-%m-%d"}}/highlight.png)
{% endif %}

{% endfor %}
{% endfor %}

{% endfor %}

[for further develop]( https://help.shopify.com/themes/liquid/filters/string-filters#slice )
