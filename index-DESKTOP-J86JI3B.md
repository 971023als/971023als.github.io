---
layout: default
title: "홈"
---

# {{ site.title }}
{{ site.description }}

<p>안녕하세요! 이 블로그는 {{ site.title }}에서 다양한 정보와 이야기를 공유하기 위해 만들어졌습니다.</p>

<form action="/search" method="get" class="search-form">
    <input type="text" name="query" placeholder="Search posts..." aria-label="Search posts">
    <button type="submit">Search</button>
</form>

<section>
    <h2>Latest Posts</h2>
    <ul>
        {% for post in site.posts limit:5 %}
        <li>
            <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
            <p>{{ post.excerpt | truncate: 100 }}</p>
            <p><small>{{ post.date | date: "%Y-%m-%d" }}</small></p>
        </li>
        {% endfor %}
    </ul>
    <a href="/blog" class="button">View All Posts</a>
</section>

<a href="/about" class="button">About Me</a>
<a href="/categories" class="button">Explore Categories</a>

<img src="/assets/banner.jpg" alt="블로그 배너 이미지" class="homepage-banner">

<footer>
    <p>&copy; {{ "now" | date: "%Y" }} {{ site.title }}. All rights reserved.</p>
    <ul>
        <li><a href="/sitemap.xml">Sitemap</a></li>
        <li><a href="/privacy-policy">Privacy Policy</a></li>
    </ul>
    <div class="social-links">
        <a href="https://twitter.com/{{ site.author.twitter }}" target="_blank">Twitter</a>
        <a href="https://github.com/{{ site.author.github }}" target="_blank">GitHub</a>
    </div>
</footer>
