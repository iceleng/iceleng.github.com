---
layout: post
title:  这是我的第一个github page post，好的开始！
categories: [test, sample]
---

2014年10月26日，通过jekyll now，开始github上的blog之旅！

小猫今天说了很有趣的话，他对ella说，你给我生个孩子吧，哈哈哈。

{% for category in site.categories %}
<h2>{{ category | first }}</h2>
</span>{{ category | last | size }}</span>
<ul class="arc-list">
    {% for post in category.last %}
        <li>{{ post.date | date:"%d/%m/%Y"}}<a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
{% endfor %}
