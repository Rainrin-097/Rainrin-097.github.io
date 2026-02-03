---
layout: default
title: "Rin's Blog"
description: "欢迎来到我的博客"
---

<nav>
  <a href="{{ '/' | relative_url }}">首页</a> |
  <a href="{{ '/about/' | relative_url }}">关于我</a>
</nav>

# 欢迎来到我的生活博客

这里将分享我的学习历程和技术心得，还有最近的一些生活和思考

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y年%m月%d日" }}
    </li>
  {% endfor %}
</ul>

---

- *去往遗痕 明日消损 值此栖处 四方情深*

*感谢访问！*
