<div align="center">
  
<img width="3392" height="1248" alt="CozyStay 배사" src="https://github.com/user-attachments/assets/93629af0-dc1f-4ecc-98bc-863c2c40f57a" />

  <br/>
  <br/>

  # CozyStay
  > **누구나 호스트가 되고 게스트가 될 수 있는 글로벌 숙박 공유 플랫폼** <br/>
  > 지도 기반의 숙소 탐색부터 간편 결제, 호스트와의 실시간 채팅까지 원활한 숙박 경험을 제공합니다.

  <br/>

  ![React](https://img.shields.io/badge/React-19.1.1-61DAFB?style=flat-square&logo=react&logoColor=black)
  ![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=flat-square&logo=typescript&logoColor=white)
  ![Vite](https://img.shields.io/badge/Vite-7.1.7-646CFF?style=flat-square&logo=vite&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4.11-6DB33F?style=flat-square&logo=springboot&logoColor=white)

</div>

<br/>

## Core Features (핵심 기능)

- **지도 기반 숙소 탐색** : 카카오맵 API를 활용하여 원하는 지역의 숙소 위치를 직관적으로 탐색하고 다양한 조건으로 필터링할 수 있습니다.
- **간편한 예약 및 결제** : **토스페이먼츠(Toss Payments)** 연동을 통해 숙박 날짜 선택부터 결제까지 빠르고 안전한 원스톱 예약 시스템을 제공합니다.
- **손쉬운 호스팅 시스템** : 직관적인 인터페이스(단계별 입력 폼)를 통해 누구나 쉽게 자신의 숙소를 등록하고 관리할 수 있는 호스트 전용 페이지를 제공합니다.
- **실시간 1:1 채팅** : 웹소켓(STOMP) 통신을 이용하여 게스트와 호스트가 예약 및 숙소 관련 문의를 실시간으로 소통할 수 있습니다.

<br/>

## Tech Stack (기술 스택)

### Frontend
- **Framework:** React 19, Vite
- **Language:** TypeScript
- **Styling:** Styled-components
- **State Management:** Zustand
- **Network:** Axios, SockJS, STOMP

### Backend (예시)
- **Framework:** Spring Boot 3.x, Spring Data JPA
- **Language:** Java 17
- **Database:** MySQL 8.0

### Infrastructure & DevOps
- **Cloud:** AWS (EC2, RDS, S3) / Docker
- **CI/CD:** GitHub Actions

<br/>

## 🔗 External APIs

CozyStay는 사용자에게 최적의 경험을 제공하기 위해 아래의 외부 데이터 및 서비스를 연동합니다.
- [Kakao Map API](https://developers.kakao.com/) - 지도 기반 숙소 위치 시각화 및 호스트 주소 검색
- [Toss Payments API](https://docs.tosspayments.com/) - 안전하고 편리한 신용카드 및 간편 결제 처리

<br/>

## Team Members (팀원 소개)

| 포지션 | 이름 | GitHub | 역할 및 담당 업무 |
|:---:|:---:|:---:|---|
| **Frontend** | 팀원1 | [@github_id](https://github.com/) | 홈 화면, 검색 및 지도 뷰 구현 |
| **Frontend** | 팀원2 | [@github_id](https://github.com/) | 예약 및 결제 시스템, 상세 페이지 연동 |
| **Backend** | 팀원3 | [@github_id](https://github.com/) | 인증/인가, 숙소 검색 API, 채팅 웹소켓 구현 |
| **Backend** | 팀원4 | [@github_id](https://github.com/) | 예약/결제 API 연동, 마이페이지/리뷰 기능 구현 |

<br/>

## 📁 Repository Structure

우리 팀은 프론트엔드와 백엔드를 각각 독립된 레포지토리로 관리합니다.
- [**CozyStay_backend**](https://github.com/CozyStay/CozyStay_backend) : Spring Boot 기반의 백엔드 API 서버
- [**CozyStay_frontend**](https://github.com/CozyStay/CozyStay_frontend) : React 기반의 프론트엔드 웹 화면
