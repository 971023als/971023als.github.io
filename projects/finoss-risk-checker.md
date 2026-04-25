---
layout: project
title: "FinOSS Risk Checker"
category: "Supply Chain Security"
permalink: /projects/finoss-risk-checker/
date: 2026-04-23
description: "외주개발 산출물의 오픈소스 라이선스와 취약점을 분석하여 전자금융 납품검수 리스크를 점검하는 도구입니다."
tech: ["Python", "CVE-Search", "OSV API", "SQLite"]
github: "https://github.com/971023als/finoss-risk-checker"
---

## 📌 Project Overview
금융권의 외주 개발 비중이 높아지면서 공급망 보안(Supply Chain Security)이 핵심 과제로 부상했습니다. 
본 프로젝트는 외주 업체로부터 납품받는 소프트웨어에 포함된 오픈소스 라이선스 위반 및 알려진 취약점(CVE)을 검수 단계에서 자동으로 식별합니다.

## 🚀 Key Features
*   **Dependency Analysis**: `package-lock.json`, `requirements.txt` 등 패키지 관리 파일을 분석하여 전체 종속성을 파악합니다.
*   **Vulnerability Mapping**: OSV, NVD 등 공신력 있는 취약점 데이터베이스와 연동하여 실시간 리스크를 탐지합니다.
*   **License Compliance**: Copyleft 라이선스(GPL 등) 포함 여부를 확인하여 법적 분쟁 소지를 사전에 차단합니다.
*   **Financial Context Priority**: 전자금융 업무의 중요도에 따라 취약점 패치 우선순위를 자동으로 권고합니다.

## 🛠 Tech Stack & Implementation
*   **Engine**: Python 기반의 정적 분석 엔진
*   **Database**: 로컬 SQLite 및 외부 취약점 API(OSV) 연동
*   **Report**: 취약점 점수(CVSS)와 금융 보안 가이드를 포함한 PDF 보고서 생성

## 📈 Expected Impact
*   외주 산출물 보안 검토 프로세스의 표준화
*   오픈소스 라이선스 위반으로 인한 법적·재무적 리스크 방지
*   공급망 보안 강화를 통한 전자금융 안정성 확보
