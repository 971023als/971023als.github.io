---
layout: project
title: "Personal Data Flow Mapper"
category: "Privacy Automation"
permalink: /projects/personal-data-flow-mapper/
date: 2026-04-25
description: "서비스, DB, API 정보를 기반으로 개인정보 처리 흐름도와 위험 노드를 자동 생성하는 도구입니다."
tech: ["Python", "Mermaid.js", "Flask", "JSON"]
github: "https://github.com/971023als/personal-data-flow-mapper"
---

## 📌 Project Overview
본 프로젝트는 기업의 개인정보 처리 현황을 가시화하고, 복잡한 데이터 흐름 속에서 발생할 수 있는 보안 리스크를 사전에 식별하기 위해 개발되었습니다. 
수동으로 작성하던 개인정보 처리 흐름도를 자동화하여 데이터 정합성을 높이고 관리 부담을 줄이는 것이 핵심입니다.

## 🚀 Key Features
*   **Data Structure Analysis**: API 명세 및 DB 스키마 정보를 분석하여 개인정보 수집·저장·이용·제공 흐름을 구조화합니다.
*   **Automatic Visualization**: Mermaid.js를 활용하여 동적인 데이터 흐름도(Data Flow Diagram)를 실시간으로 생성합니다.
*   **Risk Node Identification**: 국외 이전, 수탁사 제공, 외부 제3자 제공 등 법적 규제 준수가 필요한 위험 구간을 시각적으로 강조합니다.
*   **Compliance Mapping**: 생성된 흐름도를 ISMS-P 등 주요 보안 인증의 통제 항목과 매핑하여 증적 자료로 활용 가능하게 합니다.

## 🛠 Tech Stack & Implementation
*   **Core**: Python을 활용한 데이터 파싱 및 로직 구현
*   **Interface**: Flask 기반의 웹 대시보드 제공
*   **Visualization**: Mermaid-CLI를 연동한 다이어그램 렌더링
*   **Data Format**: 표준화된 JSON 형식을 통한 외부 시스템 확장성 확보

## 📈 Expected Impact
*   개인정보 처리 흐름도 현행화 작업 시간 **80% 단축**
*   수동 작업 시 발생할 수 있는 데이터 누락 및 오류 원천 차단
*   보안 감사 및 인증 심사 시 신속한 증적 대응 가능
