---
layout: page
title: Jaz
---
我叫陆诗钊，英文名Jaz，这是我新的个人网站，使用[Jekyll](https://github.com/mojombo/jekyll)搭建，搭载于[GitHub Pages](http://pages.github.com/)。

所有文章都使用[Markdown](http://daringfireball.net/projects/markdown/)标记语言撰写。

我相信探索和创造是一生中唯一不变的主旋律，而过程中转瞬即逝的灵感便是所必须记录的人生音符。

另外你们还在能在[微博](http://weibo.com/lushizhao)和[Github](https://github.com/jazdelu)上找到我。

<BR>
<BR>
<BR>


#### 最近发布的文章
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


