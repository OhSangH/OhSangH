<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Oh%20Sanghyeon!&fontAlign=50&fontAlignY=40&color=gradient" />

  ### 백엔드 중심 풀스택 개발자 지망생
  
  🌱 **Spring Boot 기반 백엔드 설계/구현**과 **배포 자동화(CI/CD)** 경험을 쌓고 있습니다.  
  🔍 문제를 끝까지 파고들어 **원인 분석 → 해결 → 재발 방지**까지 만드는 걸 좋아합니다.  
  💡 REST API, 인증/인가(JWT·OAuth2), 데이터 동기화, Docker/Nginx 운영에 관심이 많습니다.
  <br/>
  
  <p>
    <a href="mailto:dhtkdgus126@naver.com">
      <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge" />
    </a>
    <a href="https://osh126.tistory.com/">
      <img src="https://img.shields.io/badge/Blog-20C997?style=for-the-badge&logo=velog&logoColor=white" />
    </a>
  </p>

  ## 💻 Tech Stack
  <p>
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
    <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
    <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
    <img src="https://img.shields.io/badge/JPA(Hibernate)-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
    <br>
    <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=fff"/>
    <br>
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
    <img src="https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white"/>
    <br>
    <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"/>
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
    <br>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
    <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
    <h2>🛠️ Tools & IDE</h4>
    <img src="https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=IntelliJ-IDEA&logoColor=white" />&nbsp
    <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=Visual-Studio-Code&logoColor=white" />
  </p>
</div>


## ✨ About Me

- 👨‍💻 **백엔드 중심 풀스택**을 목표로 (Spring Boot , React) 프로젝트를 꾸준히 개발 중입니다.
- 🧩 인증/인가(**JWT / OAuth2**), REST API 설계, DB 모델링, 성능/운영 이슈 해결을 좋아합니다.
- 🐞 에러를 단순 해결에서 끝내지 않고 **재현 → 로그/원인 파악 → 수정 → 회고 문서화**까지 합니다.
- ☁ **Docker + Nginx + GCP** 환경에서 배포/운영을 직접 구성하며, CI/CD로 반복 작업을 자동화하고 있습니다.
- 🤝 팀 프로젝트에서 **branch/PR/review/merge** 협업을 경험했고, merge conflict 해결을 통해 안정적 통합을 연습했습니다.

---

## 🛠 Projects

<details>
  <summary>🎫 OMIJOY (공연 탐색 · 티켓/공연 정보 플랫폼)</summary>
  <br/>

  > KOPIS(Open API) 기반 공연 데이터를 수집/가공하여, 공연 탐색·상세·공연장 지도·개인화 기능을 제공하는 플랫폼

- **기간**: 2025-10-29 ~ 2025-12-10
- **인원**: 5인 팀 프로젝트  
- **역할**: Backend 중심 Full-stack (API 설계/구현 + 배포/운영)
- **핵심 기능**
  - 공연 목록/필터/정렬, 상세 조회 및 외부 예매 링크 연결
  - 공연장 지도(카카오맵) 기반 주변 공연장 조회 + 공연 목록 모달
  - 즐겨찾기/플래그/마이페이지
  - JWT 로그인 + Google OAuth2 소셜 로그인 연동
  - (선택) 공연 데이터 동기화 배치 / 스케줄링
- **기술 스택**
  - FE: `React` `TypeScript` `Vite` `MUI` `TanStack Query`
  - BE: `Spring Boot` `Spring Security` `JPA(Hibernate)` `JWT` `OAuth2`
  - DB: `MariaDB`
  - Infra: `Docker` `Nginx` `GCP VM` `GitHub Actions`
- **Troubleshooting**
  - 502 Bad Gateway, CORS, 컨테이너 네트워크/포트 충돌, JPA 연관관계 직렬화 문제 등 운영 이슈를 해결하며 안정화
- 링크: [Repository](https://github.com/Team-OMIJA) · [Service](https://omijoy.kro.kr/)

</details>


---

## 📌 What I'm Working On

- ✅ Spring Security 인증/인가 흐름 정리 (JWT + OAuth2)
- ⏳ 성능 개선: N+1 / 인덱스 / 캐시(Redis) 확인

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=OhSangH&show_icons=true&theme=radical&hide_border=true" height="150" alt="GitHub Stats"/>
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=OhSangH&layout=compact&theme=radical&hide_border=true" height="150" alt="Top Languages"/>
</div>
