# ⚡️ 리액트 스타터 팩

**TailwindCSS, ShadCN UI, ESLint (Airbnb), Prettier**, 그리고 **Pretendard 폰트**를 포함한 최신 **React + TypeScript** 스타터 팩으로, **Vite**를 사용하여 빠른 개발 환경을 제공합니다.

## 🚀 기술 스택

이 프로젝트는 다음과 같은 도구와 기술을 포함합니다:

- **React** `18.3.1`
- **TypeScript** `5.5.4`
- **Vite** `6.0.5`
- **Tailwind CSS** `3.4.17`
- **ShadCN UI** (Radix UI 기반 컴포넌트)
- **ESLint (Airbnb + TypeScript)** `8.54.0`
- **Prettier** `10.0.1`
- **Pretendard 폰트**
- **Class Variance Authority (CVA)** `0.7.1`
- **Lucide 아이콘** `0.473.0`
- **React 훅 & 접근성** (ESLint 규칙 포함)

---

## 💂️ 프로젝트 구조

```
react-starter/
├── public/                     # 정적 자산 (favicon, 이미지 등)
├── src/                         
│   ├── components/              # 재사용 가능한 UI 컴포넌트
│   ├── layouts/                 # 레이아웃 컴포넌트
│   ├── pages/                   # 페이지 컴포넌트 (홈, 소개 등)
│   ├── routes/                  # 라우트 정의
│   ├── styles/                  # 전역 스타일
│   ├── utils/                   # 유틸리티 함수
│   ├── main.tsx                 # 애플리케이션 진입점
│   └── vite-env.d.ts            # TypeScript 환경 설정
│
├── .eslintrc.json               # ESLint 설정 (Airbnb + TypeScript)
├── .prettierrc                  # Prettier 포맷팅 규칙
├── index.html                   # 메인 HTML 파일
├── tailwind.config.js           # Tailwind CSS 설정
├── tsconfig.json                # TypeScript 설정
├── vite.config.ts               # Vite 설정
└── package.json                 # 프로젝트 의존성 및 스크립트
```

---

## 🛠️ 설치 및 설정

1. **레포지토리 클론:**
   ```bash
   git clone https://github.com/your-repo/react-starter.git
   cd react-starter
   ```

2. **원하는 브랜치로 전환:**
   ```bash
   git checkout [브랜치명]
   ```

   사용 가능한 브랜치:
   - `eslint-airbnb`: Airbnb의 ESLint 규칙을 적용한 브랜치입니다.
   - `eslint-biome`: ESLint와 Prettier를 Biome으로 대체한 브랜치입니다.
   - `eslint-biome-tailwind-pretendard`: Biome 설정에 Tailwind CSS 4.0과 Pretendard 폰트를 추가한 브랜치입니다.

3. **의존성 설치:**
   ```bash
   npm install
   ```

4. **개발 서버 시작:**
   ```bash
   npm run dev
   ```

5. **프로덕션 빌드:**
   ```bash
   npm run build
   ```

6. **프로덕션 빌드 로컬 미리보기:**
   ```bash
   npm run preview
   ```

---

## ✨ 특징

- **Vite를 통한 빠른 개발** 🏎️
- **Airbnb ESLint + Prettier 포맷팅** 🪑
- **사전 구성된 Tailwind CSS** 💨
- **ShadCN UI를 활용한 아토믹 디자인** 🎨
- **Pretendard 폰트 적용** 📝
- **프로덕션 준비 완료된 코드 구조** 🏷️
- **핫 모듈 교체(HMR)** 🔥
- **정적 자산 관리 (Public 디렉토리)** 📂

---

## 🧩 코드 품질 및 포맷팅

이 프로젝트는 코드 일관성을 위해 **ESLint (Airbnb)**와 **Prettier**를 사용합니다.

### 린팅

코드 이슈를 확인하려면 다음 명령어를 실행하세요:

```bash
npm run lint
```

린팅 이슈를 자동으로 수정하려면:

```bash
npm run lint:fix
```

---

## 🌟 스타일링 (TailwindCSS + Pretendard)

이 프로젝트는 **TailwindCSS**를 사용한 유틸리티 우선 스타일링과 한국어 타이포그래피를 위한 **Pretendard** 폰트를 구성했습니다.

### 커스텀 폰트 설정

`src/styles/global.css` 파일에서 Pretendard 폰트를 CDN을 통해 가져옵니다:

```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/Pretendard/dist/web/static/pretendard.css');

@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 📜 ESLint & Prettier 설정

- **ESLint 규칙:** Airbnb + TypeScript + Prettier
- **Prettier 설정:** `.prettierrc`
- **스타일 가이드 적용:** 저장 시 일관된 포맷팅

---

## 💁 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 자유롭게 사용하고 수정하실 수 있습니다.

