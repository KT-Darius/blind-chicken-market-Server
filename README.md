# 🐔 Blind Chicken Market Server

이 프로젝트는 **EC2 서버**에서 프론트엔드와 백엔드 레포지토리를 함께 배포하여  
웹 서비스를 운영하기 위한 서버 환경을 구성하는 예시입니다.

---

## 📦 프로젝트 구조
```
blind-chicken-market-Server/
├── 📁 frontend/ # 프론트엔드 레포지토리 (React, Vue 등)
├── 📁 backend/ # 백엔드 레포지토리 (Node.js, Express, NestJS 등)
└── 📄 README.md
```

---

## 🖥️ 서버 환경

| 항목 | 내용 |
|------|------|
| OS |  Amazon Linux 2023 |
| Web Server | Nginx |
| DB | PostgreSQL |
| 배포 대상 | AWS EC2 |
| 실행 방식 | PM2 or Docker (선택) |

---
