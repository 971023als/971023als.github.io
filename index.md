---
layout: default
title: "Home"
---

<div class="hero">
    <h1>이민형</h1>
    <p>
        개인정보보호, 클라우드 보안, AI 기반 보안 자동화를 연구하고 구현하는 보안 실무자입니다.
    </p>
    <div class="hero-btns">
        <a href="#projects" class="btn">View Projects</a>
        <a href="/about/" class="btn btn-outline">About Me</a>
    </div>
</div>

<section id="skills">
    <h2>Skills &amp; Technologies</h2>
    <div class="skills-grid">
        <div class="skill-tag">Python</div>
        <div class="skill-tag">Flask</div>
        <div class="skill-tag">JavaScript</div>
        <div class="skill-tag">AWS Security</div>
        <div class="skill-tag">ISMS-P</div>
        <div class="skill-tag">Privacy Compliance</div>
        <div class="skill-tag">Security Automation</div>
        <div class="skill-tag">AI / LLM</div>
        <div class="skill-tag">Git / GitHub</div>
    </div>
</section>

<section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects-grid">

        <div class="project-card">
            <div class="project-info">
                <h3>Personal Data Flow Mapper</h3>
                <p>
                    서비스, DB, API, 수탁사, 외부 제공처 정보를 기반으로 개인정보 처리 흐름도와 위험 노드를 자동 생성하는 도구입니다.
                </p>
                <ul class="project-points">
                    <li>개인정보 수집·저장·이용·제공 흐름 구조화</li>
                    <li>Mermaid 기반 데이터 흐름도 자동 생성</li>
                    <li>국외이전, 수탁사, 외부제공 위험 노드 표시</li>
                </ul>
                <a href="/projects/personal-data-flow-mapper/" class="btn btn-small">View Details</a>
            </div>
        </div>

        <div class="project-card">
            <div class="project-info">
                <h3>AWS Privacy Security Baseline Scanner</h3>
                <p>
                    AWS 환경에서 개인정보 처리 시스템의 기본 보안 설정을 자동 점검하고 ISMS-P, ISO 통제항목과 연결하는 보안 점검 도구입니다.
                </p>
                <ul class="project-points">
                    <li>S3 Public Access, 암호화, CloudTrail 점검</li>
                    <li>IAM 과다권한 및 MFA 적용 여부 확인</li>
                    <li>점검 결과 JSON 및 HTML 리포트 생성</li>
                </ul>
                <a href="/projects/aws-privacy-security-baseline-scanner/" class="btn btn-small">View Details</a>
            </div>
        </div>

        <div class="project-card">
            <div class="project-info">
                <h3>FinOSS Risk Checker</h3>
                <p>
                    외주개발 산출물의 오픈소스 라이선스와 취약점을 함께 분석하여 전자금융 납품검수 리스크를 점검하는 도구입니다.
                </p>
                <ul class="project-points">
                    <li>package-lock.json, requirements.txt, pom.xml 분석</li>
                    <li>CVE, 라이선스, 고위험 오픈소스 식별</li>
                    <li>전자금융 업무 영향도 기반 우선순위 산정</li>
                </ul>
                <a href="/projects/finoss-risk-checker/" class="btn btn-small">View Details</a>
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
        <a href="/blog/" class="btn btn-muted">See All Posts</a>
    </div>
</section>
