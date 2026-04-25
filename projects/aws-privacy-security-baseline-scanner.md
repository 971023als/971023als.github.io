---
layout: project
title: "AWS Privacy Security Baseline Scanner"
category: "Cloud Security"
permalink: /projects/aws-privacy-security-baseline-scanner/
date: 2026-04-24
description: "AWS 환경에서 개인정보 처리 시스템의 기본 보안 설정을 자동 점검하고 ISMS-P 통제항목과 연결하는 도구입니다."
tech: ["Boto3", "AWS SDK", "Python", "JSON"]
github: "https://github.com/971023als/aws-privacy-scanner"
---

## 📌 Project Overview
클라우드 환경으로의 전환이 가속화됨에 따라 S3 버킷 노출, 암호화 미적용 등 설정 오류로 인한 개인정보 유출 사고가 빈번해지고 있습니다. 
본 도구는 AWS 인프라의 개인정보 보호 설정을 자동으로 스캔하고, 국내 보안 인증 표준(ISMS-P)에 따른 가이드를 제공합니다.

## 🚀 Key Features
*   **Infrastructure Scanning**: S3, RDS, IAM, CloudTrail 등 주요 AWS 서비스의 보안 설정을 전수 조사합니다.
*   **Privacy-Specific Audit**: 단순 보안 설정을 넘어 '개인정보' 관점에서의 암호화(KMS), 접근 통제 정책을 중점 점검합니다.
*   **Compliance Alignment**: 점검 결과를 ISMS-P(개인정보보호 관리체계)의 구체적인 통제 항목과 매핑하여 결과 보고서를 생성합니다.
*   **Drift Detection**: 정기적인 스캔을 통해 초기 설정된 보안 베이스라인에서 벗어난 변경 사항을 탐지합니다.

## 🛠 Tech Stack & Implementation
*   **Scanner**: AWS Boto3 SDK를 활용한 자원 정보 수집
*   **Analysis Logic**: 사전에 정의된 YAML 기반 보안 베이스라인 정책과 비교
*   **Reporting**: JSON 형식의 로우 데이터 및 요약된 HTML 리포트 출력

## 📈 Expected Impact
*   클라우드 개인정보 유출 리스크의 선제적 방어
*   보안 담당자의 수동 점검 리소스를 자동화로 전환
*   ISMS-P 인증 유지 관리 비용 절감
