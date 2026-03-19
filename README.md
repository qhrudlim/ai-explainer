# AI Explainer

AI 개념을 쉽고 명확하게 설명하는 정적 웹사이트입니다.

## 🌐 라이브 사이트

[https://sangwoo108.github.io/ai-explainer](https://sangwoo108.github.io/ai-explainer)

## 📁 프로젝트 구조

```
ai-explainer/
├── index.html      # 메인 HTML 파일
├── style.css       # 스타일시트
├── script.js       # 자바스크립트
└── README.md       # 이 파일
```

## 🚀 시작하기

### 로컬에서 실행

1. 리포지토리 클론:
```bash
git clone https://github.com/sangwoo108/ai-explainer.git
cd ai-explainer
```

2. 로컬 서버 실행 (Python 3):
```bash
python -m http.server 8000
```

3. 브라우저에서 열기:
```
http://localhost:8000
```

또는 **Live Server** VS Code 확장을 사용하면 됩니다.

## 📝 파일 설명

- **index.html**: 웹사이트의 HTML 구조
  - 헤더 및 네비게이션
  - 히어로 섹션
  - 소개, 주제, 연락처 섹션
  
- **style.css**: 반응형 디자인
  - 모바일 친화적 레이아웃
  - 부드러운 애니메이션 효과
  - 다크/라이트 색상 변수 사용
  
- **script.js**: 상호작용 기능
  - 부드러운 스크롤 네비게이션
  - 스크롤 이벤트 처리
  - 교차 관찰자를 이용한 애니메이션

## 🔧 커스터마이징

### 색상 변경
`style.css`의 `:root` 섹션에서 색상 변수 수정:
```css
:root {
    --primary-color: #2563eb;      /* 주색상 */
    --secondary-color: #1e40af;    /* 보조색상 */
    --light-bg: #f3f4f6;           /* 배경색 */
    --dark-text: #1f2937;          /* 텍스트색 */
    --light-text: #6b7280;         /* 밝은 텍스트색 */
}
```

### 텍스트 수정
`index.html`에서 직접 내용 수정

## 📱 반응형 디자인

웹사이트는 다음 화면 크기에서 최적화됨:
- 📱 모바일: 480px 이하
- 📱 태블릿: 480px ~ 768px
- 💻 데스크톱: 768px 이상

## 📤 GitHub Pages 배포

### 자동으로 배포되는 방법:

1. **Repository Settings에서 설정**:
   - GitHub에서 리포지토리 열기
   - Settings → Pages
   - Source: `Deploy from a branch` 선택
   - Branch: `main` 또는 `master`, `/root` 폴더 선택
   - Save 클릭

2. **GitHub Actions 사용 (권장)**:
   - `.github/workflows/deploy.yml` 파일이 자동으로 배포를 처리합니다.
   - Push할 때마다 자동 배포됩니다.

3. **몇 분 후 확인**:
   - https://sangwoo108.github.io/ai-explainer 에서 사이트 확인 가능

## 🎨 기능

✅ 반응형 디자인  
✅ 부드러운 스크롤 애니메이션  
✅ 교차 관찰자를 이용한 요소 애니메이션  
✅ 모바일 친화적 네비게이션  
✅ 빠른 로딩 속도 (외부 의존성 없음)  

## 📄 라이센스

MIT License - 자유롭게 사용, 수정, 배포 가능합니다.

## 🤝 기여

개선 사항이나 버그를 발견하면 Issue를 등록하거나 PR을 보내주세요!

---

**만들어진 날짜**: 2026년 3월 19일
