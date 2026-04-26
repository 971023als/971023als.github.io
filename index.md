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
        <div class="skill-tag">SBOM / Supply Chain</div>
        <div class="skill-tag">AI / LLM</div>
        <div class="skill-tag">Git / GitHub</div>
    </div>
</section>

<section id="projects">
    <h2>Featured Projects</h2>

    <!-- Search Bar -->
    <div class="search-container">
        <input type="text" id="project-search" placeholder="프로젝트 명칭, 키워드 검색 (예: ISMS-P, AWS, 가이드...)" aria-label="Search projects">
        <span class="search-icon">🔍</span>
    </div>

    <div class="filter-container">
        <button class="filter-btn active" data-filter="all">전체 보기</button>
        <button class="filter-btn" data-filter="automation">🛠️ Automation</button>
        <button class="filter-btn" data-filter="compliance">⚖️ Compliance</button>
        <button class="filter-btn" data-filter="isms">🛡️ ISMS-P</button>
        <button class="filter-btn" data-filter="research">🔍 Research</button>
    </div>

    <!-- 1. Automation & Tools -->
    <div class="project-category-section" data-category="automation">
        <h3>Security Automation & Tools</h3>
        <div class="projects-grid">
            <div class="project-card" data-category="automation">
                <span class="card-badge badge-automation">Tool</span>
                <div class="project-info">
                    <h3>Personal Data Flow Mapper</h3>
                    <p>서비스, DB, API 정보를 기반으로 개인정보 처리 흐름도와 위험 노드를 자동 생성하는 도구입니다.</p>
                    <ul class="project-points">
                        <li>Mermaid 기반 데이터 흐름도 자동 생성</li>
                        <li>국외이전, 수탁사, 외부제공 위험 노드 표시</li>
                    </ul>
                    <a href="/projects/personal-data-flow-mapper/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="automation">
                <span class="card-badge badge-automation">Tool</span>
                <div class="project-info">
                    <h3>AWS Privacy Baseline Scanner</h3>
                    <p>AWS 환경에서 개인정보 처리 시스템의 기본 보안 설정을 자동 점검하는 도구입니다.</p>
                    <ul class="project-points">
                        <li>S3 Public Access, 암호화, CloudTrail 점검</li>
                        <li>IAM 과다권한 및 MFA 적용 여부 확인</li>
                    </ul>
                    <a href="/projects/aws-privacy-security-baseline-scanner/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="automation">
                <span class="card-badge badge-automation">Tool</span>
                <div class="project-info">
                    <h3>FinOSS Risk Checker</h3>
                    <p>오픈소스 라이선스와 취약점을 분석하여 전자금융 납품검수 리스크를 점검하는 도구입니다.</p>
                    <ul class="project-points">
                        <li>package-lock.json, requirements.txt 등 분석</li>
                        <li>CVE, 라이선스, 고위험 오픈소스 식별</li>
                    </ul>
                    <a href="/projects/finoss-risk-checker/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="automation">
                <span class="card-badge badge-automation">Tool</span>
                <div class="project-info">
                    <h3>Privacy Internal Audit Automation</h3>
                    <p>내부관리계획 이행점검을 Excel 기반으로 자동화하고 준거성을 관리하는 시스템입니다.</p>
                    <ul class="project-points">
                        <li>연간 이행점검 이력 관리 및 대시보드 시각화</li>
                        <li>자동화 수식을 통한 입력 오류 방지 및 시간 단축</li>
                    </ul>
                    <a href="/projects/privacy-internal-audit-automation/" class="btn btn-small">View Details</a>
                </div>
            </div>
        </div>
    </div>

    <!-- 2. Compliance & SOPs -->
    <div class="project-category-section" data-category="compliance">
        <h3>Privacy Compliance & SOPs</h3>
        <div class="projects-grid">
            <div class="project-card" data-category="compliance">
                <span class="card-badge badge-compliance">SOP</span>
                <div class="project-info">
                    <h3>Privacy Management Archive</h3>
                    <p>개인정보 보호 가이드, 증적 관리 기록을 체계화한 업무 아카이브입니다.</p>
                    <ul class="project-points">
                        <li>개인정보 생명주기 및 흐름도 아카이빙</li>
                        <li>글로벌 규제 대응 및 최신 법령 해석 DB</li>
                    </ul>
                    <a href="/projects/privacy-management-archive/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="compliance">
                <span class="card-badge badge-compliance">SOP</span>
                <div class="project-info">
                    <h3>Privacy Ops Guide Database</h3>
                    <p>ISMS-P 인증 심사 및 상시 점검에 대응하기 위한 핵심 운영 업무 SOP 데이터베이스입니다.</p>
                    <ul class="project-points">
                        <li>접속기록 검토, 파기 보고 등 필수 점검 항목 가이드</li>
                        <li>체크리스트 및 보고서 템플릿 연계 지식 베이스</li>
                    </ul>
                    <a href="/projects/privacy-ops-guide-database/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="compliance">
                <span class="card-badge badge-compliance">Guide</span>
                <div class="project-info">
                    <h3>Integrated Privacy Handbook</h3>
                    <p>개정 개인정보 보호법(2025.07)의 전 프로세스를 아우르는 실무 통합 가이드라인입니다.</p>
                    <ul class="project-points">
                        <li>2025년 핵심 개정 사항 반영 (고지 방식 전환 등)</li>
                        <li>조문별 실무 체크포인트 및 Q&A 정리</li>
                    </ul>
                    <a href="/projects/integrated-privacy-processing-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="compliance">
                <span class="card-badge badge-compliance">Guide</span>
                <div class="project-info">
                    <h3>Privacy Outsourcing Governance</h3>
                    <p>수탁사 관리·감독 의무 이행을 위한 위·수탁 계약 관리 실무 가이드입니다. </p>
                    <ul class="project-points">
                        <li>수탁사 보안 역량 평가 및 계약 관리 생애주기</li>
                        <li>2025년 통합 안내서 최신 지침 반영</li>
                    </ul>
                    <a href="/projects/privacy-outsourcing-governance-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="compliance">
                <span class="card-badge badge-compliance">Guide</span>
                <div class="project-info">
                    <h3>Privacy Lifecycle Governance</h3>
                    <p>수집부터 파기까지 전 과정을 정의한 단계별 법적 준수 가이드입니다.</p>
                    <ul class="project-points">
                        <li>2025년 4월 최신 처리방침 지침 반영</li>
                        <li>데이터 흐름별 핵심 보안 요구사항 정립</li>
                    </ul>
                    <a href="/projects/privacy-lifecycle-governance-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
        </div>
    </div>

    <!-- 3. ISMS-P Governance & Certification -->
    <div class="project-category-section" data-category="isms">
        <h3>ISMS-P Governance & Certification</h3>
        <div class="projects-grid">
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Certification</span>
                <div class="project-info">
                    <h3>ISMS-P Certification Management</h3>
                    <p>ISMS-P 인증 기준에 따른 조직적 R&R 수립 및 증적 자료 관리 데이터베이스입니다.</p>
                    <ul class="project-points">
                        <li>102개 인증 항목별 부서 세부 역할 정의</li>
                        <li>심사 대응 지식 베이스 및 증적 관리 자동화</li>
                    </ul>
                    <a href="/projects/isms-p-certification-management/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Governance</span>
                <div class="project-info">
                    <h3>ISMS-P Management Commitment</h3>
                    <p>경영진의 참여를 보장하기 위한 보고 체계 및 실무 이행 증적 관리 프로젝트입니다.</p>
                    <ul class="project-points">
                        <li>정보보호위원회 운영 및 위험평가 보고 프로세스</li>
                        <li>경영진 보안 의사결정 거버넌스 설계</li>
                    </ul>
                    <a href="/projects/isms-p-management-commitment-governance/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Governance</span>
                <div class="project-info">
                    <h3>ISMS-P Security Organization</h3>
                    <p>3단계 보안 거버넌스(위원회-전담조직-협의체) 체계 구축 프로젝트입니다.</p>
                    <ul class="project-points">
                        <li>전담 조직 구성 및 부서별 보안 담당자 R&R</li>
                        <li>인사 발령 및 직무기술서(JD) 아카이빙</li>
                    </ul>
                    <a href="/projects/isms-p-security-organization-governance/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Governance</span>
                <div class="project-info">
                    <h3>ISMS-P Policy & Chief Officer</h3>
                    <p>정보보호 최고책임자 지정 및 보안 정책·지침 수립 거버넌스 가이드입니다.</p>
                    <ul class="project-points">
                        <li>CISO/CPO 지정 요건 및 법적 신고 절차</li>
                        <li>조직 내 보안 규정 제·개정 승인 프로세스</li>
                    </ul>
                    <a href="/projects/isms-p-policy-governance-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Asset</span>
                <div class="project-info">
                    <h3>ISMS-P Scope & Asset Identification</h3>
                    <p>인증 범위를 획정하고 보안 등급에 따른 자산 식별 및 관리 체계를 정립합니다.</p>
                    <ul class="project-points">
                        <li>핵심 서비스 흐름 기반의 범위 산정 로직</li>
                        <li>정보자산 분류 기준 및 등급 부여 가이드</li>
                    </ul>
                    <a href="/projects/isms-p-asset-identification-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="isms">
                <span class="card-badge badge-isms">Resource</span>
                <div class="project-info">
                    <h3>ISMS-P Resource Allocation</h3>
                    <p>보안 목표 달성을 위한 인적·물적 자원 할당 및 예산 관리 거버넌스입니다.</p>
                    <ul class="project-points">
                        <li>연간 보안 예산 수립 및 보안 교육 이수 관리</li>
                        <li>보안 전담 인력 및 직무별 적정성 검토</li>
                    </ul>
                    <a href="/projects/isms-p-resource-allocation-governance/" class="btn btn-small">View Details</a>
                </div>
            </div>
        </div>
    </div>

    <!-- 4. Security Research & Insights -->
    <div class="project-category-section" data-category="research">
        <h3>Security Research & Insights</h3>
        <div class="projects-grid">
            <div class="project-card" data-category="research">
                <span class="card-badge badge-research">Research</span>
                <div class="project-info">
                    <h3>AI Privacy Governance Framework</h3>
                    <p>생성형 AI 서비스 전 수명주기에 걸친 개인정보 보호 원칙과 거버넌스 구축 가이드입니다.</p>
                    <ul class="project-points">
                        <li>AI 수명주기 게이트별 필수 통제 항목 정의</li>
                        <li>프라이버시 레드팀 운영 및 결정 권리 보장 체계</li>
                    </ul>
                    <a href="/projects/ai-privacy-governance-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="research">
                <div class="project-info">
                    <h3>PISFAIR 2025 Technical Deep Dive</h3>
                    <p>AI 보안 프레임워크(LINNDUN) 및 비정형 데이터 가명처리 실무 분석 리포트입니다.</p>
                    <ul class="project-points">
                        <li>OWASP LLM Top 10 전략 분석</li>
                        <li>비정형 데이터(CT, 영상 등) 가명처리 사례</li>
                    </ul>
                    <a href="/projects/pisfair-2025-technical-deepdive/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="research">
                <div class="project-info">
                    <h3>Online Behavioral Privacy Guide</h3>
                    <p>쿠키, ADID 및 SDK를 통한 온라인 행태정보 수집 프로세스 가이드라인입니다.</p>
                    <ul class="project-points">
                        <li>웹·모바일 환경별 수집 메커니즘 분석</li>
                        <li>처리방침 내 고지 사항 및 거부 방법(Opt-out) 표준</li>
                    </ul>
                    <a href="/projects/online-behavioral-privacy-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="research">
                <div class="project-info">
                    <h3>Mobile App Access Permissions</h3>
                    <p>정보통신망법 및 OS 정책에 따른 앱 접근권한 고지 기준 실무 가이드입니다.</p>
                    <ul class="project-points">
                        <li>필수/선택 권한 구분 및 목적 고지 문구 설계</li>
                        <li>Android 런타임 및 iOS ATT 정책 대응</li>
                    </ul>
                    <a href="/projects/mobile-app-access-permissions-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
            <div class="project-card" data-category="research">
                <div class="project-info">
                    <h3>CCTV Privacy Compliance Guide</h3>
                    <p>고정형·이동형 영상정보처리기기 설치 기준 및 안전성 확보 조치 지침서입니다.</p>
                    <ul class="project-points">
                        <li>영상정보 보관·파기 주기 및 비식별 처리 기준</li>
                        <li>근로 공간 내 모니터링 노사 협의 프로세스</li>
                    </ul>
                    <a href="/projects/cctv-privacy-compliance-guide/" class="btn btn-small">View Details</a>
                </div>
            </div>
        </div>
    </div>
</section>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const filterBtns = document.querySelectorAll('.filter-btn');
    const sections = document.querySelectorAll('.project-category-section');
    const cards = document.querySelectorAll('.project-card');

    filterBtns.forEach(btn => {
        btn.addEventListener('click', () => {
            const filter = btn.getAttribute('data-filter');

            // Update button state
            filterBtns.forEach(b => b.classList.remove('active'));
            btn.classList.add('active');

            if (filter === 'all') {
                sections.forEach(s => s.classList.remove('hidden'));
                cards.forEach(c => c.classList.remove('hidden'));
            } else {
                sections.forEach(s => {
                    if (s.getAttribute('data-category') === filter) {
                        s.classList.remove('hidden');
                        // Show all cards in visible section
                        s.querySelectorAll('.project-card').forEach(c => c.classList.remove('hidden'));
                    } else {
                        s.classList.add('hidden');
                    }
                });
            }
        });
    });
});
</script>

<section id="research">
    <h2>Research &amp; Resources</h2>
    <div class="research-card">
        <span class="research-badge">Current Thesis Preparation</span>
        <h3>SBOM 기반의 공급망 보안 및 컴플라이언스 자동화 연구</h3>
        <p>
            오픈소스 소프트웨어의 비중이 높아짐에 따라 SBOM(Software Bill of Materials)을 활용한 가시성 확보와 취약점 관리의 중요성이 커지고 있습니다. 
            현재 SBOM 데이터 추출, 표준(SPDX, CycloneDX) 분석, 그리고 이를 활용한 보안 통제 자동화 방안에 관한 논문을 준비 중입니다.
        </p>
        
        <div class="research-links">
            <a href="#" class="resource-item">
                <span>📑 SBOM 자료 모음집 (준비 중)</span>
            </a>
            <a href="#" class="resource-item">
                <span>🔍 공급망 보안 가이드라인 분석</span>
            </a>
            <a href="#" class="resource-item">
                <span>🏗️ 자동화 도구 연동 아키텍처</span>
            </a>
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
