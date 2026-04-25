---
layout: project
title: "개인정보 내부관리계획 이행점검 자동화 및 연간 관리 시스템"
category: "Security Research"
permalink: /projects/privacy-internal-audit-automation/
date: 2025-12-05
description: "개인정보 보호법 제29조에 따른 법정 의무인 '내부관리계획 이행점검'을 체계화하고, Excel 기반의 자동화 체크리스트와 대시보드를 통해 연간 준거성을 관리하는 프로젝트입니다."
tech: ["GRC Automation", "Compliance Audit", "Excel Engineering", "VLOOKUP/IF", "Dashboard"]
---

## 📌 프로젝트 개요 (Overview)
개인정보 처리자는 내부관리계획이 실제로 이행되고 있는지 연 1회 이상 점검하고 결과를 보고해야 합니다. 본 프로젝트는 수작업으로 진행되던 이행점검 프로세스를 Excel 자동화 수식과 드롭다운 기능을 활용하여 고도화하였으며, 2020년부터 2026년까지의 연간 점검 이력을 체계적으로 관리하는 거버넌스 체계를 구축했습니다.

## 📜 Version History
<div class="changelog">
    <div class="changelog-item">
        <span class="changelog-version">v1.4</span>
        <span class="changelog-date">2025-12-05</span>
        <div class="changelog-content">
            <ul>
                <li>작성자: 이민형</li>
                <li>이행점검 현황 시각화를 위한 대시보드 링크 및 연동 체계 추가</li>
            </ul>
        </div>
    </div>
    <div class="changelog-item">
        <span class="changelog-version">v1.1</span>
        <span class="changelog-date">2025-04-25</span>
        <div class="changelog-content">
            <ul>
                <li>Excel 자동화 기능 개선: '판단기준' 선택 시 '이행여부' 자동 입력(IF/VLOOKUP) 및 입력 오류 방지 드롭다운 적용</li>
            </ul>
        </div>
    </div>
</div>

## ⚖️ 1. 법적 근거 및 점검 주기
*   **개인정보 보호법 제29조(안전조치의무)**: 개인정보 유출 방지를 위한 기술적·관리적 보호조치 이행.
*   **안전성 확보조치 기준 제4조**: 내부관리계획 수립 및 시행 의무.
*   **점검 주기**: 연 1회 이상 자체 점검 실시 및 결과 보고(내부관리계획 제6조, 제7조).

## 🛠️ 2. 기술적 구현: 체크리스트 자동화 (Excel Engineering)
반복적이고 실수가 잦은 수동 입력을 개선하기 위해 다음과 같은 자동화 로직을 적용했습니다.
*   **자동 판단 로직**: `IF` 및 `VLOOKUP` 함수를 사용하여 점검자가 특정 판단 기준을 선택하면 법적 이행 여부와 조치 필요성이 실시간으로 계산되도록 설계.
*   **데이터 무결성**: 데이터 유효성 검사(드롭다운 목록)를 적용하여 사용자 입력 오류를 원천 차단.
*   **조치 계획 연동**: 미이행 항목 발생 시 즉시 '조치 계획' 필드가 활성화되어 후속 관리가 누락되지 않도록 프로세스 통합.

## 📊 3. 연간 이행점검 아카이브 (2020 ~ 2026)
지속적인 준거성 확보를 위해 매년 점검 결과를 기록하고 대시보드로 관리합니다.
*   **2020~2024**: 초기 수립 및 안정화 단계의 점검 이력 보관.
*   **2025**: 자동화 툴이 적용된 고도화된 이행점검 실시 및 결과 보고.
*   **2026~2027**: 인공지능기본법 등 신규 법령 대응을 포함한 미래 점검 계획 수립.

## 🚀 기대 효과
*   **점검 시간 단축**: 자동화 수식 적용으로 점검 보고서 작성 시간 50% 이상 감소.
*   **데이터 신뢰도 향상**: 수동 입력에 의한 오류를 제거하여 감사 대응 시 신뢰할 수 있는 증적 자료 확보.
*   **거버넌스 강화**: 연간 이력을 한눈에 파악할 수 있는 대시보드를 통해 미이행 리스크를 조기에 발견하고 개선.

---
<div style="text-align: center; color: var(--text-muted); font-size: 0.9rem;">
    본 시스템은 개인정보 보호법의 안전성 확보조치 기준을 완벽하게 준수하도록 설계되었습니다.
</div>
