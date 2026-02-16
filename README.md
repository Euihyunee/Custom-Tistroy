# Custom Tistory Skin (Based on hELLO)

이 프로젝트는 [hELLO 스킨](https://github.com/pronist/hello)을 기반으로 **SEO 최적화**, **AI 가독성**, **개발자 편의 기능**을 추가한 커스텀 스킨입니다.

## 주요 기능 (Features)

### 1. SEO & AI 최적화
- **향상된 SEO**: JSON-LD 구조화 데이터(TechArticle, Breadcrumb) 및 SNS 메타 태그 자동 생성.
- **AI Readability**: 게시글 상단에 AI 에이전트(LLM)가 읽기 쉬운 'Hidden Summary Block' 자동 삽입.
- **Semantic HTML**: 웹 표준을 준수하는 시멘틱 태그 구조 강화.

### 2. 개발자 도구 (Developer Experience)
- **Code Highlighting**: 라인 넘버 표시 및 향상된 가독성 테마 적용.
- **Mermaid.js**: 코드 블록(`mermaid`)을 다이어그램으로 자동 변환.
- **LaTeX Math**: 수식 렌더링 지원 (예정).

### 3. 사용자 설정
- 티스토리 스킨 편집 화면에서 'AI 최적화' 및 'SEO 강화' 기능을 켜고 끌 수 있습니다.

## 설치 및 빌드 (Installation & Build)

### 1. 준비 사항
- Node.js 설치 필요

### 2. 설치
```bash
git clone https://github.com/Euihyunee/Custom-Tistroy.git
cd Custom-Tistroy
npm install
```

### 3. 빌드
```bash
npm run build
```
빌드가 완료되면 `dist/` 폴더에 생성된 파일(`skin.html`, `style.css`, `index.xml`, `images/*`)을 티스토리 스킨 관리 페이지에 업로드하세요.

자세한 내용은 [.antigravity/manual.md](./.antigravity/manual.md)를 참고하세요.

## 라이선스 (License)
이 프로젝트는 원본 [hELLO 스킨](https://github.com/pronist/hello)의 라이선스를 준수하며, 커스텀된 부분에 대해서는 [Euihyunee](https://github.com/Euihyunee)에게 권리가 있습니다.
