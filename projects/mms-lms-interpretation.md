---
layout: project
title: "MMS vs LMS: 메시지 서비스 범위 불일치 해석"
category: "Legal Interpretation"
permalink: /projects/mms-lms-interpretation/
date: 2025-04-30
description: "개인정보 처리방침과 재위탁 계약서 간 메시지 전송 범위(SMS, LMS, MMS) 불일치에 대한 기술적·계약적 해석 및 권고안입니다."
tech: ["Compliance", "Contract Analysis", "Privacy Policy", "Messaging"]
---

## 📌 메시지 서비스 범위 불일치 쟁점 정리
본 리포트는 개인정보 처리방침과 실제 재위탁 계약 간의 메시지 전송 범위(SMS, MMS vs LMS) 차이로 인해 발생할 수 있는 컴플라이언스 이슈를 분석하고, 기술적 근거를 바탕으로 해결 방안을 제시합니다.

## 📜 Version History
<div class="changelog">
    <div class="changelog-item">
        <span class="changelog-version">v1.0</span>
        <span class="changelog-date">2025-04-30</span>
        <div class="changelog-content">
            <ul>
                <li>최초 작성: 메시지 서비스 범위 불일치에 대한 기술적·계약적 해석</li>
            </ul>
        </div>
    </div>
</div>

## 1. 쟁점 개요 (Issue Overview)
*   **상황**: 개인정보 처리방침에는 `SMS`, `MMS`만 명시되어 있으나, 실제 재위탁 계약서상에는 `LMS` 전송이 포함되어 있음.
*   **문제점**: 처리방침과 재위탁 계약 간의 명시 범위 불일치로 인한 법적 투명성 이슈 발생 가능성.
*   **핵심 질문**: "MMS 전송이 허용된다면, 기술적으로 하위 기능을 포함하는 LMS 전송도 허용된 것으로 해석 가능한가?"

## 2. 기술적 분석 (Technical Analysis)
MMS와 LMS의 구조적 관계를 분석한 결과입니다.

| 항목 | LMS (Long Message) | MMS (Multimedia Message) |
| :--- | :--- | :--- |
| **전송 방식** | 데이터망 (Data Traffic Channel) | 데이터망 (Data Traffic Channel) |
| **텍스트 용량** | 약 2,000byte | 약 2,000byte |
| **미디어 첨부** | 불가 | **가능** (이미지, 동영상 등) |
| **구조적 관계** | 텍스트 전송 전용 | **LMS + 멀티미디어 파일** 포함 형태 |

**[기술적 근거]**: MMS는 기술적으로 LMS의 텍스트 전송 기능을 온전히 포함하면서 멀티미디어 파일 첨부 기능이 추가된 상위 형식입니다. 따라서 **MMS 허용은 기술적으로 LMS 전송 능력을 포함**함을 의미합니다.

## 3. 계약적 해석 (Contract Interpretation)
*   **포괄적 해석**: 계약서 내 “MMS 전송 가능” 명시는 해당 메시징 인프라의 사용을 승인한 것으로, 하위 호환 기능인 LMS를 포괄하는 개념으로 해석 가능합니다.
*   **유사 사례**: "이메일 첨부파일 전송 허용" 승인이 본문 텍스트 전송에 대한 승인을 당연히 포함하는 것과 유사한 논리 구조를 가집니다.

## 4. 결론 및 권고안 (Conclusion)
*   **결론**: MMS 기능 명시를 통해 LMS 기능은 기술적으로 이미 포함된 것으로 간주할 수 있어 실질적인 법 위반으로 보기는 어려우나, 명확성을 위해 현행화가 필요합니다.
*   **권고안**: 
    1.  향후 처리방침 및 계약서 개정 시 **“SMS, LMS, MMS 포함”**으로 문구를 명확히 통합하여 명시할 것.
    2.  재위탁 계약 부속서에 메시지 전송 규격에 대한 정의를 추가하여 해석의 모호성을 제거할 것.

---
<div style="text-align: center; color: var(--text-muted); font-size: 0.9rem;">
    본 해석은 기술적 명세와 계약 원칙을 바탕으로 작성되었으며, 실제 심사 시 감독기관의 해석과 다를 수 있습니다.
</div>
