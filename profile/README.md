# 📚 JPStudy
## 🚀 About Us
개인적인 일본어 학습 효율을 높이기 위해 만든 사이드 프로젝트입니다.
학습 과정에서 필요하다고 느낀 기능들을 웹 기반으로 구현하며 발전시키고 있습니다.

## 📂 Projects
- [**jpstudy-backend**](https://github.com/jpstudy-org/jpstudy-backend) - 서비스 메인 백엔드 API 서버
    - REST API 기반 서비스 주요 기능들을 제공합니다.
    - 데이터 수집 및 처리 로직도 포함된 메인 백엔드 서버입니다
- [**infra**](https://github.com/jpstudy-org/infra) - 서비스 배포 및 및 인프라 구성을 관리하는 저장소
    - 배포 자동화를 위한 구성이 설정되어 있습니다.
    - 중요한 변수는 sealed_secret으로 관리합니다.
- [**FrontEnd**](https://github.com/jpstudy-org) - 사용자, 관리자 페이지 서버
    - 완전히 AI로 제작되어, API를 제외한 나머지에 대한 안정성을 검증하지 못합니다.
    - 향후 재개발 대상이며, 현재는 백엔드 우선 순위가 높아 UX/UI 측면은 고려하지 않습니다.
    > ⚠️ 현재 프론트엔드 소스코드는 공유되지 않습니다.

## 🛠 Tech Stack
![System Architecture](./src/image.png)

- FrontEnd: React, Next.js
- BackEnd: Spring Boot
- Database: PostgreSQL, Redis, RabbitMQ
- Infra: On-Premise, K3S, Cloudflare Pages
- Development Tools: Swagger, Jenkins, ArgoCD, K6, Figma
- Monitoring: Grafana, Prometheus
- AI: FrontEnd(GPT-5, GPT-mini), Support(Gemini-3)

## 🤝 Contribution Guide
- 언제든지 편하게 `issue`에 의견을 올려주세요!
- 서비스 의견을 공유하는 것도 기여입니다
- 추가되거나 수정되어야하는 기능을 PR로 기여하실 수 있습니다

## 🗺 Roadmap
- [x] **1차 서비스 개발 완료**
    - 기간: 2025.09.21 ~ 2025.11.29
    - 내용: 백엔드 기본 기능 구축, MVP 수준 기능 완성

- [ ] **코드 품질 향상 (리팩토링 & 성능 개선)**
    - 기간: 2025.12.01 ~ 2025.12.31
    - 목표: 구조 최적화, 중복 제거, 쿼리 튜닝, 로깅 개선

- [ ] **데이터 활성화 단계**
    - 기간: 2026.01.01 ~
    - 목표: 사용자에게 제공할 유의미한 데이터를 확보하기 위해 크롤링·수집·정제 작업 진행

- [ ] **지속 로직 개발**
    - 기간: 2026.01.01 ~
    - 목표: 비즈니스 로직 보완, 안정화 작업

- [ ] **디자인 UX/UI 외주 -> 프론트엔드 개발**
    - 예정 시기: MAU 100 이상 확보 후 고려하며, 우선 순위가 낮음
    - 사유: 현재는 AI로 제작되어, 보안을 제외하곤 사용자 편의성이 확보되지 않음
    - 목표: 지속 가능하다 판단되는 시기에 프론트 개발 진행

## 📫 Contact
- 현재 운영 궤도에 오르지 않아 문의, 협업 제안은 받지 않습니다.
- 다만, 프로젝트 관련 버그 제보나 개선 의견은 Github Issue를 통해 남겨주실 수 있습니다.

## ✨ Other
- 성능 개선 관련 상세한 내용은 [블로그](https://devlog.jpstudy.org)에 정리되어 있습니다.