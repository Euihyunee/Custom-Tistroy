# Custom Tistory Skin — hELLO 기반

이 저장소는 [hELLO](https://pronist.tistory.com/5) 티스토리 스킨을 기반으로 제작된 **커스텀 티스토리 스킨**입니다.  
[티도리 프레임워크(Tidory)](https://github.com/pronist/tidory/wiki)를 사용하여 개발되었으며, 별도의 개발 환경 설정이 필요합니다.

---

## 시작하기

### 1. 저장소 클론

```bash
git clone https://github.com/Euihyunee/Custom-Tistroy.git
cd Custom-Tistroy
```

### 2. 패키지 설치

티도리 프레임워크는 **Node.js** 와 **Webpack** 기반입니다. [NPM](https://www.npmjs.com/)이 설치되어 있어야 합니다.

```bash
npm install
```

### 3. 환경 설정

프리뷰 서버 실행 전, `tidory.config.js` 를 설정해야 합니다.  
루트 디렉토리의 `tidory.config.example.js` 를 복사하여 `tidory.config.js` 로 이름을 변경한 뒤,  
[티도리 환경설정 가이드](https://github.com/pronist/tidory/wiki/Configuration)를 참고하여 아래 항목을 입력하세요.

| 항목         | 설명                         |
| ------------ | ---------------------------- |
| `ts_session` | 티스토리 로그인 세션 쿠키 값 |
| `url`        | 본인 티스토리 블로그 주소    |

### 4. 프리뷰 서버 실행

티스토리 치환자가 적용된 실제 스킨 모습을 로컬에서 미리 확인할 수 있습니다.

```bash
npm run preview
```

---

## 배포

`tidory.config.js` 에 `ts_session` 과 `url` 이 올바르게 설정되었다면 아래 명령어로 빌드 및 배포를 진행합니다.  
자세한 내용은 [티도리 빌드 및 배포 가이드](https://github.com/pronist/tidory/wiki/Deployment)를 참고하세요.

```bash
npm run production && npm run deploy
```

---

## 기반 스킨 정보

- **원본 스킨**: [hELLO](https://pronist.tistory.com/5) by [SangWoo Jeong](https://github.com/pronist)
- **프레임워크**: [Tidory](https://github.com/pronist/tidory)
- **원본 저작권**: Copyright 2020-2025. [SangWoo Jeong](https://github.com/pronist). All rights reserved.
