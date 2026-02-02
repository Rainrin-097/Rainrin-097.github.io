---
layout: default
title: "Rin's Blog"
description: "欢迎来到我的技术博客"
---

<nav>
  <a href="{{ '/' | relative_url }}">首页</a> |
  <a href="{{ '/about/' | relative_url }}">关于我</a>
</nav>

# 欢迎来到我的技术博客

这里将分享我的编程学习历程和技术心得。

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y年%m月%d日" }}
    </li>
  {% endfor %}
</ul>

---

*感谢访问！记得常回来看更新哦~*
