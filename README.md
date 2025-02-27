## 프로젝트 브랜치 안내

이 프로젝트는 다양한 설정과 기능을 실험하기 위해 여러 개의 브랜치로 구성되어 있습니다. 각 브랜치의 특징과 사용 방법은 아래와 같습니다:

1. **`eslint-airbnb` 브랜치**

   - **설명:** Airbnb의 ESLint 규칙을 적용한 브랜치입니다.
   - **사용 방법:**
     ```bash
     git checkout eslint-airbnb
     ```

2. **`eslint-biome` 브랜치**

   - **설명:** ESLint와 Prettier를 Biome으로 대체한 브랜치입니다.
   - **사용 방법:**
     ```bash
     git checkout eslint-biome
     ```

3. **`eslint-biome-tailwind-pretendard` 브랜치**
   - **설명:** Biome 설정에 Tailwind CSS 4.0과 Pretendard 폰트를 추가한 브랜치입니다.
   - **사용 방법:**
     ```bash
     git checkout eslint-biome-tailwind-pretendard
     ```

각 브랜치로 전환한 후, 프로젝트의 의존성을 설치하고 개발 서버를 실행하려면 다음 명령어를 사용하세요:

```bash
npm install
npm run dev
```
