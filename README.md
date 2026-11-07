# 🛡️ SK쉴더스 루키즈 35기 — 실습 기록

> **클라우드 기반 스마트 융합보안 과정** · 2026.09.16 ~ 2027.03.23 (960H)
> 수업에서 실습한 코드·설정·정리 노트를 과목별로 모아 둔 저장소입니다.

## 📚 과목별 목차

| # | 과목 | 기간 | 핵심 키워드 | 폴더 |
|---|---|---|---|---|
| 1 | 🐍 파이썬 | 09.21 ~ 10.02 | 자료형 · 제어문 · 함수/파일 · 정규식/API · OOP · Flask | [`python/`](python/) |
| 2 | ⚡ 네트워크 보안 | 10.06 ~ 10.19 | OSI · VLAN · ACL · NAT · VPN · LAN 보안 | [`network/`](network/) |
| 3 | 🍏 애플리케이션 보안 | 10.21 ~ 10.29 | OWASP Top 10 · Burp Suite · XSS · SQLi · 파일 취약점 | [`web-security/`](web-security/) |
| 4 | ☁️ 클라우드 보안 | 11.02 ~ 진행 중 | EC2 · VPC · S3 · IAM · ELB · RDS | [`cloud/`](cloud/) |

## 🗂 폴더 구조

```
sk-shieldus-rookies/
├── python/         # 보안 자동화 스크립트 (보안 감사 자동화 엔진 Ver.1 → Ver.2 …)
├── network/        # Cisco 설정, ACL/NAT/VPN 실습 config
├── web-security/   # 취약점 실습 정리, 시큐어 코딩 예시
├── cloud/          # AWS 실습 기록, IAM 정책 JSON
└── docs/           # 회고, 발표 자료, 참고 링크
```

## ⚖️ 주의

이 저장소의 공격·취약점 관련 내용은 **수업용 실습 환경(VM)에서만** 수행한 것입니다.
허가받지 않은 대상에 대한 스캔·공격은 불법입니다.

- 실습 코드에 API 키·비밀번호 등 자격증명은 포함하지 않습니다 (`.env` + `.gitignore`).
