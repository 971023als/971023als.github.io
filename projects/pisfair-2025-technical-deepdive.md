---
layout: project
title: "PISFAIR 2025: 기술적 심층 분석 및 프라이버시 보호 전략"
category: "Security Research"
permalink: /projects/pisfair-2025-technical-deepdive/
date: 2025-05-28
description: "PISFAIR 2025에서 다루어진 AI 보안 프레임워크(LINNDUN, OWASP), 차세대 인증 표준(X.1280), 비정형 데이터 가명처리 사례 및 MCP 보안 위협을 심층 분석한 기술 리포트입니다."
tech: ["LINNDUN", "OWASP LLM", "X.1280", "Pseudonymization", "Zero Trust", "MCP"]
---

## 📌 리포트 개요 (Overview)
본 리포트는 PISFAIR 2025의 기술 세션들을 중심으로 AI 시대의 고도화된 위협에 대응하기 위한 실무적 기술 전략을 다룹니다. 단순한 정책을 넘어 설계 단계의 보안(PbD), 비정형 데이터 처리 기법, 그리고 제로트러스트 기반의 계정 및 데이터 보호 기술을 상세히 분석합니다.

## 📜 Version History
<div class="changelog">
    <div class="changelog-item">
        <span class="changelog-version">v1.0</span>
        <span class="changelog-date">2025-05-28</span>
        <div class="changelog-content">
            <ul>
                <li>최초 작성: AI 보안 전략, 차세대 인증 표준 및 비정형 데이터 처리 기술 심층 분석</li>
            </ul>
        </div>
    </div>
</div>

## 🤖 1. AI 시대의 이중 보안 전략
기술사들이 제시하는 AI 보안은 'AI를 위한 보호'와 'AI를 통한 보호'의 조화입니다.
*   **Protection Privacy for AI**: LINNDUN 위협 모델링, OWASP LLM Top 10 적용, PbD 기반의 설계 단계 보안 내재화.
*   **AI for Protection Privacy**: AI 기반 처리방침 자동 진단, SIEM/SOAR 연계 위협 분석 자동화, Security Copilot 활용.

## 🔐 2. 차세대 인증 및 계정 탈취 방어 (X.1280)
기존의 인밴드(In-band) 인증의 한계를 극복하기 위한 **대역외(Out-of-band) 인증** 기술이 핵심입니다.
*   **ITU-T X.1280**: 인증 책임을 서비스 제공자로 전환하고, 피싱/파밍/중간자 공격을 차단하는 표준 기술.
*   **Passwordless**: 스마트폰 생체인증과 푸시를 결합하여 보안성과 편의성을 동시에 확보.

## 📁 3. 비정형 데이터 가명처리 및 활용 (KISA)
영상, 음성, 의료 데이터 등 비정형 데이터의 안전한 학습을 위한 실무 사례입니다.
| 데이터 유형 | 처리 방식 (Case Study) |
| :--- | :--- |
| **흉부 CT 사진** | 폐쇄형 클라우드 분석 환경 운영 (가명처리 없이 활용) |
| **구강 촬영 사진** | 충치 부위 외 블러링 및 메타데이터 삭제 |
| **도로 차량 사진** | 번호판/얼굴 블러링 및 AI 식별 수준 조정 |
| **음성 상담 파일** | STT 변환 후 텍스트 치환/삭제 및 전수검사 |

## 🛡️ 4. MCP 보안 위협 및 데이터 유출 방지
AI 기반 업무 환경의 새로운 인터페이스인 **MCP(Model Context Protocol)** 위협 분석입니다.
*   **유출 경로**: 로컬/외부 MCP 서버를 통한 데이터 접근 및 API Call 기반의 비인가 외부 전송.
*   **대응 전략**: 인라인 DLP를 통한 경로 통제, 제로트러스트 기반 RBAC 적용, 실시간 탐지 및 격리.

## ⚖️ 5. 분쟁 조정 및 침해 예방 전략
*   **침해 추세**: 개인정보 유출(210건) 및 열람/삭제 요구 불응(148건)이 주요 비중 차지.
*   **예방 가이드**: 최소 수집 원칙 준수, 정기 교육, 내부 민원 처리 체계 및 패턴 분석 시스템 구축.

---
<div style="text-align: center; color: var(--text-muted); font-size: 0.9rem;">
    본 리포트는 PISFAIR 2025 기술 세션의 전문가 강연 및 배포 자료를 바탕으로 재구성되었습니다.
</div>
