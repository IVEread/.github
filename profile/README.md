# 📚 IVEread  
### 내가 읽은 것, 우리가 읽은 것

IVEread는 **친구들과 함께하는 교환 독서 경험**을 중심으로  
독서 기록, 소셜 상호작용, AI 기반 독서 인사이트를 제공하는 모바일 앱입니다.
![IVEread Team Illustration](https://raw.githubusercontent.com/IVEread/IVEread-FE/main/iveread/assets/images/iveread-people-Photoroom1.png)

---

## 👥 Our Team

### 🧑🏻‍💻 신원영 (Wonyoung Shin)
- Dept. of Information System, Hanyang University  
- Frontend Developer  
- Email: pingu090@hanyang.ac.kr  
- GitHub: https://github.com/godten-cmd  

### 👩🏻‍💻 임유진 (Yoojin Lim)
- Dept. of Computer Science & Engineering, POSTECH  
- Backend Developer  
- Email: limyoojin@postech.ac.kr  
- GitHub: https://github.com/LYoooJ  

---

## 🔗 About Link

- **GitHub**: https://github.com/IVEread  
- **Figma**:  
  [https://embed.figma.com/design/Ph1ardey7Sjx7H59yM5Uur/madcamp-2026-app](https://www.figma.com/design/Ph1ardey7Sjx7H59yM5Uur/madcamp-2026-app?node-id=1-2&t=XKEB0mpd5nuMn1JF-0)  

---

## 🎥 iOS 시연 영상
(추후 영상 링크 첨부)

![IVEread Logo](https://raw.githubusercontent.com/IVEread/IVEread-FE/main/iveread/assets/images/iveread-logo.jpg)

---

## 📌 이런 분들에게 추천해요!

✔️ 친구들과 함께 교환 독서를 하고 싶은 분  
✔️ 독서 기록을 캘린더로 관리하고 싶은 분  
✔️ **AI 기반 독서 인사이트**를 얻고 싶은 분  

---

## 🧑‍💻 기술 스택

| Category | Technology | Description |
|--------|------------|-------------|
| Frontend | React Native | iOS 기반 모바일 앱 개발 |
| Backend | Node.js (Next.js) | REST API 서버 및 인증 로직 구현 |
| Database | PostgreSQL | 사용자, 독서 기록, 교환독서 데이터 관리 |
| AI | Gemini 2.5 Flash | 독서 기록 기반 AI 요약 및 인사이트 생성 |
| External API | Aladin Book Search API | 도서 검색 및 메타데이터 제공 |
| Dev Tools | VS Code | 개발 환경 |
| Version Control | GitHub | 소스 코드 관리 및 협업 |


---

## 🏗 시스템 아키텍처

![System Architecture](https://raw.githubusercontent.com/IVEread/IVEread-FE/main/iveread/assets/images/system-architecture.png)

(ERD 수정 후 추가 예정)

---

## 🔐 로그인 / 회원가입 / 비밀번호 재설정

- **백엔드 API와 연동된 사용자 인증 플로우 구현**
- 로그인, 회원가입, 비밀번호 재설정 기능 제공
- 이메일 기반 계정 관리
- 인증 성공/실패에 따른 UI 상태 처리

---

## 🏠 Tab 1. 홈 탭

### 📌 교환 독서 생성 및 검색
- 교환 독서 생성
  - 그룹 이름
  - 책 제목
  - 모집 인원
  - 시작일 / 목표일
  - 그룹 소개
- 교환 독서 검색
  - 그룹 이름 검색
  - 그룹 가입

### 📖 교환 독서 상세 페이지
- 교환 도서 정보 (알라딘 API 연동)
  - 지은이, 출판사, 책 표지
- 교환 독서 그룹 정보
  - 인원, 시작일, 목표일
- 출석 스탬프
  - 최근 2주 기록 조회
- 인상 깊었던 문장
  - 페이지 및 문장 작성
  - 답글 작성 / 수정 / 삭제
- 교환 독서 피드
  - 사진 및 글 업로드
  - 좋아요 및 댓글

### 📘 완독한 책
- 교환 독서 상세 페이지에서 **완독 처리**
- 진행 중 → 완독한 책으로 전환

---

## 📅 Tab 2. 캘린더 탭

### 📆 읽기 캘린더
- 기록한 독서 내용이 날짜별로 저장

### ✍️ 기록하기
- 교환 독서 중이거나 완독한 책에 대해
- 한 줄 코멘트 기록

### ❤️ 반응
- 독서 기록에 대한 반응 남기기
- 반응 수정 / 삭제 가능

### 📊 이번 달 기록
- 해당 월 기록한 날짜 수
- 참여한 교환 독서 수

### 👥 친구 캘린더
- 팔로잉 중인 친구의 캘린더 조회
- 친구 기록에도 반응 남기기 가능

---

## 👤 Tab 3. 프로필 탭

### 🙋 프로필
- 이모티콘 프로필 설정
- 진행 중 / 완독 / 친구 수 확인

### ✏️ 프로필 수정
- 닉네임 변경
- 비밀번호 변경

### 🤝 친구 관리
- 내 ID 복사
- 친구 추가 (ID 또는 이메일)
- 친구 삭제

### 📊 독서 인사이트 (AI)
- 독서 기록 기반 **AI 요약 리포트 제공**
- 독서 습관 분석
  - 연속 기록 일수
  - 주간 독서 빈도
- 완독 성과
  - 완독한 책
  - 완독률
- 활동 요약
  - 피드 기록 수
  - 인상 깊었던 문장 수

---

## 💬 느낀 점

### 🙆🏻‍♂️ 신원영
- 짧은 기간 동안 몰입 개발을 처음 경험했는데 힘들면서도 굉장히 재미있었습니다.
- 프론트엔드와 백엔드 간의 **소통이 얼마나 중요한지** 많이 느꼈습니다.

### 👺 임유진
- 백엔드 개발이 처음이라 쉽지 않았지만, 많은 것을 배울 수 있었습니다.
- 역시 프론트엔드와 백엔드의 소통이 핵심이라고 느꼈습니다.
