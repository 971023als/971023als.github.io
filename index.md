---
layout: default
title: "Home"
---

<div class="hero">
    <h1>이민형</h1>
    <p>사용자 중심의 웹 환경을 설계하고 AI 기술을 탐구하는 개발자입니다.</p>
    <div class="hero-btns">
        <a href="#projects" class="btn">View Projects</a>
        <a href="/about" class="btn" style="background: transparent; color: var(--primary-color); border: 1px solid var(--primary-color);">About Me</a>
    </div>
</div>

<section id="skills">
    <h2>Skills & Technologies</h2>
    <div class="skills-grid">
        <div class="skill-tag">JavaScript</div>
        <div class="skill-tag">React</div>
        <div class="skill-tag">Python</div>
        <div class="skill-tag">Node.js</div>
        <div class="skill-tag">Git / GitHub</div>
        <div class="skill-tag">AI / LLM</div>
    </div>
</section>

<section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects-grid">
        <div class="project-card">
            <div class="project-info">
                <h3>Portfolio Website</h3>
                <p>Jekyll과 GitHub Pages를 활용한 개인 브랜딩 포트폴리오 구축.</p>
                <a href="#" class="btn" style="padding: 0.5rem 1rem; font-size: 0.875rem;">View Details</a>
            </div>
        </div>
        <div class="project-card">
            <div class="project-info">
                <h3>AI Blogging Assistant</h3>
                <p>AI를 활용하여 콘텐츠 생성을 자동화하는 워크플로우 연구.</p>
                <a href="#" class="btn" style="padding: 0.5rem 1rem; font-size: 0.875rem;">View Details</a>
            </div>
        </div>
    </div>
</section>

<section id="blog">
    <h2>Latest Insights</h2>
    <ul class="post-list">
        {% for post in site.posts limit:3 %}
        <li class="post-item">
            <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
            <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
            <p><small>{{ post.date | date: "%Y-%m-%d" }}</small></p>
        </li>
        {% endfor %}
    </ul>
    <div style="text-align: center; margin-top: 2rem;">
        <a href="/blog" class="btn" style="background: var(--text-muted);">See All Posts</a>
    </div>
</section>
