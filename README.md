# GunieaRun

2025 2학기 네트워크프로그래밍 수행평가

---

## 💡 프로젝트 소개

이 프로젝트는 네트워크 프로그래밍 수업의 수행평가를 위해 개발된 러닝 게임입니다.

- **주요 언어**: JavaScript(69.4%), CSS(13.8%), TypeScript(13.6%), HTML(2%), Dockerfile(1.2%)
- **구성**: 백엔드, 프론트엔드, 인게임 모듈로 분할되어 있으며, 다양한 웹 개발 기술을 활용합니다.

---

## 📁 폴더 구조

```
/
├── .env
├── .gitignore
├── settings.json
├── package.json
├── backend/
│   ├── api/
│   ├── routes/
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
├── frontend/
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── public.zip
│   ├── src/
│   ├── vite.config.js
│   └── webpack.config.cjs
├── guinea-run-frontend/
│   ├── .dockerignore
│   ├── .gitignore
│   ├── Dockerfile
│   ├── README.md
│   ├── app/
│   ├── package.json
│   ├── package-lock.json
│   ├── public/
│   ├── react-router.config.ts
│   ├── tsconfig.json
│   └── vite.config.ts
└── inGame/
    ├── assets/
    ├── index.html
    ├── main.js
    ├── object/
    └── scenes/
```

---

## 📦 주요 폴더 설명

- **backend**: 서버와 API, 라우팅, 서버 실행(`server.js`) 등 백엔드 로직 담당
- **frontend**: 클라이언트 UI, 번들러(vite/webpack) 구성과 `src` 소스
- **guinea-run-frontend**: 리액트 기반 프론트엔드로, Docker 배포 관련 파일(`Dockerfile`), 타입스크립트, 라우터 설정 등 포함
- **inGame**: 실제 게임실행 코드(`main.js`, `index.html`) 및 게임 오브젝트/씬 리소스 포함

---

## 🛠️ 실행 방법 (예시)

> 아래 실행 방법은 실제 구현에 따라 다를 수 있으니 `package.json` 혹은 각 폴더 내 문서를 참고해주세요.

```sh
# backend
cd backend
npm install
node server.js

# frontend
cd ../frontend
npm install
npm run dev

# guinea-run-frontend
cd ../guinea-run-frontend
npm install
npm run dev
```

---

## 📂 기타 파일

- `.env`, `settings.json`: 환경설정 및 개발 관련 설정 파일
- `package.json`, `package-lock.json`: 각 디렉토리의 Node.js 의존성 관리

---

## 🙌 기여 및 문의

수업 평가용 프로젝트로, 궁금한 점은 이슈로 남겨주세요.
