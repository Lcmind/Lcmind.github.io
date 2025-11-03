# 🚀 이창민 포트폴리오

풀스택 개발자 이창민의 개인 포트폴리오 웹사이트입니다.

## ✨ 주요 기능

- 🌓 **다크모드/라이트모드** - 우측 상단 버튼으로 전환
- 🎨 **현대적인 디자인** - 글래스모피즘, 그라데이션 효과
- ⚡ **부드러운 애니메이션** - 스크롤 애니메이션, 타이핑 효과
- 📱 **완벽한 반응형** - 모바일, 태블릿, 데스크탑 지원
- 🎯 **프로젝트 상세보기** - 기획 동기, 본인의 역할, 주요 기능
- 🖼️ **이미지 지원** - 프로필 사진과 프로젝트 스크린샷

## 📁 프로젝트 구조

```
potforlio/
├── index.html          # 메인 HTML 파일
├── css/
│   └── style.css      # 스타일시트 (다크모드, 애니메이션 등)
├── js/
│   └── script.js      # JavaScript (타이핑 효과, 인터랙션)
├── images/
│   └── README.md      # 이미지 교체 안내
└── README.md          # 이 파일
```

## 🎯 커스터마이징 가이드

### 1️⃣ 개인 정보 수정

`index.html` 파일을 열어서 다음 내용을 수정하세요:

**이름 변경:**
```html
<!-- 23번째 줄 -->
<h2 class="name-title">풀스택 개발자 <span class="highlight-name">이창민</span>입니다</h2>
```

**소개 문구 변경:**
```html
<!-- 27번째 줄 -->
<p class="hero-description">열정적으로 개발하며 성장하는 개발자입니다</p>
```

**연락처 수정:**
```html
<!-- 399-407번째 줄 -->
<a href="mailto:your.email@gmail.com" class="contact-btn">
<a href="https://github.com/yourusername" target="_blank" class="contact-btn">
<a href="https://linkedin.com/in/yourusername" target="_blank" class="contact-btn">
```

### 2️⃣ 프로젝트 수정

각 프로젝트 카드의 내용을 본인의 실제 프로젝트로 변경하세요:

- **프로젝트 제목** (`<h3>`)
- **프로젝트 타입** (`<span class="project-type">`)
- **요약** (`.summary`)
- **기획 동기** (💡 섹션)
- **나의 역할** (🎯 섹션)
- **주요 기능** (✨ 섹션)
- **사용 기술 아이콘**
- **데모/GitHub 링크**

### 3️⃣ 기술 스택 수정

`index.html`의 기술 스택 섹션에서 본인이 사용하는 기술로 변경:

```html
<!-- 44-66번째 줄 -->
<img src="https://skillicons.dev/icons?i=기술이름" alt="기술이름" title="기술이름">
```

**사용 가능한 기술 아이콘:**
- 프론트엔드: `html`, `css`, `js`, `react`, `vue`, `angular`, `svelte`
- 백엔드: `java`, `spring`, `nodejs`, `python`, `django`, `php`, `go`
- 데이터베이스: `mysql`, `mongodb`, `postgres`, `redis`, `firebase`
- 도구: `git`, `docker`, `aws`, `vercel`, `figma`, `vscode`

전체 목록: https://skillicons.dev

### 4️⃣ 이미지 교체

**방법 1: 로컬 이미지 사용**
1. `images/` 폴더에 이미지 저장
2. `index.html`에서 URL 변경:
   ```html
   <!-- 변경 전 -->
   <img src="https://via.placeholder.com/400x400/..." alt="...">
   
   <!-- 변경 후 -->
   <img src="images/profile.jpg" alt="...">
   ```

**방법 2: 온라인 이미지 URL 사용**
- 이미 호스팅된 이미지의 URL을 직접 사용

자세한 내용은 `images/README.md` 참고

### 5️⃣ 타이핑 애니메이션 수정

`js/script.js` 파일에서 타이핑 문구 변경:

```javascript
// 21-27번째 줄
const roles = [
    '풀스택 개발자입니다 💻',
    '백엔드 개발자입니다 ⚙️',
    // 원하는 문구 추가
];
```

## 🎨 색상 테마 변경

`css/style.css`의 CSS Variables 수정:

```css
:root {
    --primary-color: #6366f1;      /* 메인 색상 */
    --secondary-color: #8b5cf6;    /* 보조 색상 */
    --accent-color: #ec4899;       /* 강조 색상 */
    /* ... */
}
```

## 🚀 배포하기

### GitHub Pages
1. GitHub 저장소 생성
2. 코드 푸시
3. Settings > Pages > Source를 `main` 브랜치로 설정

### Vercel
1. [Vercel](https://vercel.com) 로그인
2. 프로젝트 import
3. 자동 배포 완료

### Netlify
1. [Netlify](https://netlify.com) 로그인
2. Drag & Drop으로 폴더 업로드
3. 배포 완료

## 💡 동료와 함께한 프로젝트는?

포트폴리오는 **본인의 기여도**를 강조하는 것이 중요합니다:

✅ **좋은 예:**
```
🎯 나의 역할
• 전체 시스템 설계 및 아키텍처 구성
• RESTful API 설계 및 백엔드 개발 (80%)
• 결제 시스템 연동 (토스페이먼츠)
```

❌ **나쁜 예:**
```
팀원 A, B, C와 함께 작업했습니다.
```

## 📞 문의

포트폴리오 관련 질문이나 문의사항이 있으시면 언제든지 연락주세요!

- 📧 Email: changmin.lee@example.com
- 💻 GitHub: [github.com/changmin-lee](https://github.com/changmin-lee)

---

**Made with ❤️ by 이창민**

