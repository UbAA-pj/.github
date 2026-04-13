<div align="center">

<br>

```
 ____  _            _         ___
/ ___|| |_ _   _  __| |_   _  / _ \
\___ \| __| | | |/ _` | | | || | | |
 ___) | |_| |_| | (_| | |_| || |_| |
|____/ \__|\__,_|\__,_|\__, | \__\_\
                        |___/
```

# Study.Q

**강의 영상 중간에 AI 랜덤 퀴즈를 출제해 학습자의 집중도를 높이는 스마트 강의 플랫폼**

<br>

![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white)

![Python](https://img.shields.io/badge/Backend-Python-3776AB?style=flat-square&logo=python&logoColor=white)

![AI](https://img.shields.io/badge/AI-Clode%20Code-orange?style=flat-square)

<br>

</div>

## 📌 프로젝트 소개

**Study.Q**는 단순 강의 시청을 넘어, 영상 재생 중 **랜덤 타이밍에 퀴즈를 삽입**해 학습자가 실시간으로 이해도를 확인할 수 있는 서비스입니다.

수동적인 영상 소비에서 벗어나 능동적 학습 참여를 유도하고, 학습 완료율과 장기 기억 보존율을 향상시킵니다.

> 💡 **PainPint**: 20-25분의 긴 강의 동영상을 오랜 시간 집중하며 시청하기란 어렵다.

<br>

## 배포 링크

### 🚀 [Study.Q - 랜덤 퀴즈 스마트 강의 플랫폼](https://ubaa-pj.github.io/Study.Q-FE/auth/singup)

> [Study.Q Figma 링크](https://www.figma.com/design/xj8io2vlAtk6WOzbWUXwNl/Study.Q?node-id=0-1&t=EUTq0tXSwIwuEEpa-1)<br>
> [배포된 백엔드 서버 링크](https://gahyon.smilersa.com/study_q)


<br>

## ✨ 주요 기능

| 기능                  | 설명                                                                    |
| --------------------- | ----------------------------------------------------------------------- |
| ❓ **랜덤 퀴즈 삽입** | 영상 재생 중 무작위 타이밍에 퀴즈가 팝업되어 집중도 유지                |
| ✅ **즉각 피드백**    | 퀴즈 정답 여부와 해설을 즉시 확인, 이해도 점검                          |
| 📊 **학습 기록 관리** | 강사는 퀴즈 통계에서 퀴즈 정답률을, 학생은 오답 노트로 학습 기록을 확인 |

<br>

## 🏗️ 아키텍처

| | Study.Q-FE | Study.Q-BE |
|--|--|--|
| **기능** | 강의 플레이어 / 퀴즈 팝업 UI / 학습 대시보드 / 진도 트래킹 | 강의 관리 API / 퀴즈 로직 / 사용자 인증 / 학습 기록 저장 |
| **기술** | JavaScript · React | Python · FastAPI |

<br>

## 🗂️ 서비스 흐름

```
학습자 접속
    │
    ▼
강의 목록 조회 → 강의 선택 → 영상 재생 시작
                                    │
                               (랜덤 타이밍)
                                    │
                                    ▼
                             퀴즈 팝업 출제
                                    │
                    ┌───────────────┴───────────────┐
                    ▼                               ▼
                 정답 입력                       시간 초과
                    │                               │
                    ▼                               ▼
              즉각 피드백 제공              오답 처리 & 해설
                    │
                    ▼
             영상 재생 재개 → 학습 완료 → 결과 리포트
```

<br>

## 👥 팀 멤버

> UbAA-pj 팀이 함께 만들어가는 프로젝트입니다.

| <a href=https://github.com/><img src="https://avatars.githubusercontent.com/u/197880704?v=4" width=100px/><br/><sub><b>@Jiyang98</b></sub></a><br/> | <a href=https://github.com/><img src="https://avatars.githubusercontent.com/u/202045563?s=64&v=4" width=100px/><br/><sub><b>@kimgahyoun</b></sub></a><br/> | <a href=https://github.com/><img src="https://avatars.githubusercontent.com/u/162546405?v=4" width=100px/><br/><sub><b>@wnduddlekd</b></sub></a><br/> | <a href=https://github.com/><img src="https://avatars.githubusercontent.com/u/127817110?v=4" width=100px/><br/><sub><b>@kimbomin</b></sub></a><br/> |
| :-------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                       남지양                                                                        |                                                                           김가현                                                                           |                                                                        박주영                                                                         |                                                                       김보민                                                                        |

<br>

## 🧰 사용 스택

### FE

<div align=center>

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

### BE

<div align=center>

![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenAI Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

</div>

<br>

## 📄 Pages

| 페이지 | 파일 | 설명 |
|--------|------|------|
| 메인 | `MainPage.jsx` | 서비스 메인 화면 |
| 로그인 | `LoginPage.jsx` | 로그인 |
| 회원가입 | `SignUpPage.jsx` | 회원가입 |
| 강의 목록 | `CourseCatalogPage.jsx` | 전체 강의 카탈로그 |
| 강의 상세 | `CourseDetailPage.jsx` | 강의 상세 정보 |
| 강의 생성 | `CreateCoursePage.jsx` | 새 강의 등록 |
| 강의 수정 | `EditCoursePage.jsx` | 강의 편집 |
| 내 강의 | `MyCoursesPage.jsx` | 수강 중인 강의 목록 |
| 퀴즈 분석 | `QuizAnalyticsPage.jsx` | 퀴즈 결과 및 통계 |
| 오답 노트 | `MistakeNotesPage.jsx` | 틀린 문제 모아보기 |
