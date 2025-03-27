---
layout: default
title: 홈
---

# 최신 글

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

환영합니다. 이 블로그는 금융권 프리랜서 개발자의 쿠버네티스 기반 CI/CD 구축기입니다.
