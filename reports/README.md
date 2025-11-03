# 📄 프로젝트 리포트/문서 폴더

이 폴더에 프로젝트 관련 리포트, 문서, 발표자료를 저장하세요!

## 📁 파일 추가 방법

각 프로젝트마다 리포트 파일을 이 폴더에 저장하고, 파일명을 맞춰주세요:

```
reports/
├── project1-report.pdf    # 프로젝트 1 리포트
├── project2-report.pdf    # 프로젝트 2 리포트
├── project3-report.pdf    # 프로젝트 3 리포트
├── project4-report.pdf    # 프로젝트 4 리포트
├── project5-report.pdf    # 프로젝트 5 리포트
└── project6-report.pdf    # 프로젝트 6 리포트
```

## 📝 지원되는 파일 형식

- **PDF** (권장) - `project1-report.pdf`
- **Word 문서** - `project1-report.docx`
- **PPT 발표자료** - `project1-presentation.pptx`
- **텍스트 문서** - `project1-doc.txt`

## 💡 리포트에 포함하면 좋은 내용

### 1. 프로젝트 개요
- 프로젝트 목적 및 배경
- 개발 기간
- 팀 구성 (있다면)

### 2. 기술 스택
- 사용한 기술 및 이유
- 개발 환경

### 3. 주요 기능
- 핵심 기능 설명
- 스크린샷 포함

### 4. 나의 역할
- 담당한 부분 (백엔드, 프론트엔드 등)
- 구현한 기능
- 기여도 (%)

### 5. 구현 과정
- 아키텍처 설계
- 주요 알고리즘
- 문제 해결 과정

### 6. 결과 및 성과
- 완성도
- 배운 점
- 개선 사항

### 7. 링크
- GitHub 저장소
- 데모 사이트
- API 문서

## 🔧 파일명 변경 방법

만약 다른 파일명을 사용하고 싶다면, `index.html`에서 경로를 수정하세요:

```html
<!-- 현재 -->
<a href="reports/project1-report.pdf" target="_blank" class="btn-report">📄 리포트</a>

<!-- 변경 후 -->
<a href="reports/my-ecommerce-document.pdf" target="_blank" class="btn-report">📄 리포트</a>
```

## 🌐 온라인 문서 사용

Google Drive, Notion 등의 온라인 문서를 사용할 수도 있습니다:

```html
<!-- Google Drive 예시 -->
<a href="https://drive.google.com/file/d/YOUR_FILE_ID/view" target="_blank" class="btn-report">📄 리포트</a>

<!-- Notion 예시 -->
<a href="https://notion.so/your-page" target="_blank" class="btn-report">📄 문서</a>

<!-- GitHub Wiki 예시 -->
<a href="https://github.com/username/repo/wiki" target="_blank" class="btn-report">📄 문서</a>
```

## ⚠️ 주의사항

1. **파일 크기**: PDF는 10MB 이하 권장
2. **보안**: 민감한 정보(API 키, 비밀번호 등)는 제거하세요
3. **가독성**: 폰트 크기는 최소 11pt 이상
4. **이미지**: 고화질 스크린샷 사용

## 📊 리포트 템플릿 추천

- [Canva](https://www.canva.com/templates/) - 무료 리포트 템플릿
- [Google Docs 템플릿](https://docs.google.com/templates) - 프로젝트 문서 템플릿
- LaTeX - 전문적인 기술 문서 작성

## 💡 리포트가 없다면?

리포트를 준비하지 못했다면, 해당 프로젝트의 리포트 버튼을 제거하거나 GitHub README로 연결하세요:

```html
<!-- 리포트 버튼 제거 -->
<div class="project-links">
    <a href="#" target="_blank" class="btn-demo">🚀 데모 보기</a>
    <a href="#" target="_blank" class="btn-code">🔗 GitHub</a>
    <!-- 리포트 버튼 삭제 -->
</div>

<!-- 또는 GitHub README로 연결 -->
<a href="https://github.com/username/repo#readme" target="_blank" class="btn-report">📄 README</a>
```

---

**리포트를 작성하면 더 전문적인 포트폴리오가 됩니다!** 📈

