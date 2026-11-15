# Security-Analyst-Intro
Dashboard, Firewall Block, Escalating.

# TryHackMe - A Day In the Life of a Junior Security Analyst

## 1. 실습 개요
* **주제:** SIEM 대시보드 알람 분석 및 의심스러운 IP 추적
* **목표:** 크리티컬(Critical) 보안 경고를 식별하고 비정상적인 SSH 로그인 시도 분석

## 2. 주요 분석 내용
* **탐지된 위협:** 2026년 11월 15일 21:20에 수신된 Critical 등급 알람
* **공격자 IP:** `221.181.185.159` (포트 22를 통한 무차별 대입 및 성공적인 SSH 로그인 시도 탐지)
* **조치 사항:** IP Hunter 탭을 이용해 해당 악성 IP의 통신 기록 확인 완료

## 3. 실습 화면 캡처
![SIEM Dashboard](./siem-alert.png)