# ⚡️ 리액트 스타터 팩 (Biome + React 19 + Tailwind 4)

**TailwindCSS 4.0, ShadCN UI, Biome (ESLint & Prettier 대체)** 를 포함한 최신 **React 19 + TypeScript** 스타터 팩으로, **Vite**를 사용하여 빠른 개발 환경을 제공합니다.

## 🚀 기술 스택

이 프로젝트는 다음과 같은 도구와 기술을 포함합니다:

- **React** `19.0.0`
- **TypeScript** `5.7.2`
- **Vite** `6.2.0`
- **Tailwind CSS** `4.0.9`
- **ShadCN UI (Tailwind 4.0 대응 수정 버전)**
- **Biome (ESLint & Prettier 대체) `1.9.4`**
- **Class Variance Authority (CVA)** `0.7.1`
- **Lucide Icons** `0.476.0`
- **Tailwind Merge** `3.0.2`
- **Radix UI Slot** `1.1.2`

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
├── biome.json                   # Biome 설정 파일 (ESLint + Prettier 대체)
├── index.html                   # 메인 HTML 파일
├── components                   # shadcn/ui 설정 파일
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

2. **2번 브랜치 (eslint-biome)로 전환:**
   ```bash
   git checkout eslint-biome
   ```

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

## ✨ eslint-airbnb 브랜치와의 차이점

- **ESLint + Prettier → Biome으로 대체** (빠르고 통합된 린트 및 포맷팅)
- **React 18 → React 19로 업그레이드**
- **Tailwind 3 → Tailwind 4 적용**
- **ShadCN UI → Tailwind 4 대응 버전으로 수정**
- **의존성 최신화 및 최적화**

---

## 🧩 코드 품질 및 포맷팅 (Biome 적용)

이 프로젝트는 Biome을 사용하여 린팅 및 코드 포맷팅을 수행합니다.

### 코드 검사

코드 이슈를 확인하려면 다음 명령어를 실행하세요:

```bash
npm run lint
```

린팅 및 포맷팅을 자동으로 적용하려면:

```bash
npm run format
```

---

## 🌟 스타일링 (TailwindCSS 4.0 + Pretendard)

이 프로젝트는 **TailwindCSS 4.0**을 사용한 유틸리티 우선 스타일링과 한국어 타이포그래피를 위한 **Pretendard** 폰트를 구성했습니다.

### 커스텀 폰트 설정

`src/styles/global.css` 파일에서 Pretendard 폰트를 CDN을 통해 가져옵니다:

```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/Pretendard/dist/web/static/pretendard.css');

@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 📜 Biome 설정

- **ESLint + Prettier 기능을 Biome으로 통합**
- **Biome 설정 파일: `biome.json`**
- **저장 시 자동 코드 포맷팅 적용**

---

## 🔧 사용 가능한 스크립트

| 명령어             | 설명                               |
|--------------------|------------------------------------|
| `npm run dev`      | 개발 서버 시작                     |
| `npm run build`    | 프로덕션 빌드                      |
| `npm run preview`  | 프로덕션 빌드 로컬 미리보기        |
| `npm run lint`     | Biome을 사용한 코드 품질 검사     |
| `npm run format`   | Biome을 사용한 코드 포맷팅 적용  |

---

## 💁 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다. 자유롭게 사용하고 수정하실 수 있습니다.

