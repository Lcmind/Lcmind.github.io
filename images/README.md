# 🖼️ 이미지 교체 안내

현재 포트폴리오는 **placeholder 이미지**를 사용하고 있습니다.
본인의 실제 사진과 프로젝트 스크린샷으로 교체하세요!

## 📝 이미지 교체 방법

### 방법 1: 로컬 이미지 사용 (권장)
이 폴더(`images/`)에 아래 이미지 파일들을 저장하고, `index.html`에서 URL을 변경하세요:

**필요한 이미지:**
- `profile.jpg` - 프로필 사진 (400x400px 정사각형)
- `project1.jpg` - E-Commerce 플랫폼 (800x450px)
- `project2.jpg` - 실시간 채팅 앱 (800x450px)
- `project3.jpg` - 날씨 대시보드 (800x450px)
- `project4.jpg` - 블로그 플랫폼 (800x450px)
- `project5.jpg` - AI 이미지 생성기 (800x450px)
- `project6.jpg` - 프로젝트 관리 시스템 (800x450px)

**index.html 수정 예시:**
```html
<!-- 현재 (placeholder) -->
<img src="https://via.placeholder.com/400x400/..." alt="이창민 프로필">

<!-- 변경 후 (로컬 이미지) -->
<img src="images/profile.jpg" alt="이창민 프로필">
```

### 방법 2: 온라인 이미지 URL 사용
- GitHub에 이미지를 업로드하고 raw URL 사용
- Imgur, Cloudinary 등의 이미지 호스팅 서비스 사용
- 본인의 서버에 업로드 후 URL 사용

## 💡 이미지 팁

### 프로필 사진
- ✅ 밝은 배경, 정면 얼굴
- ✅ 정사각형 비율 (1:1)
- ✅ 고화질 (최소 400x400px)
- ❌ 너무 어두운 사진
- ❌ 전신 사진 (얼굴이 작게 보임)

### 프로젝트 스크린샷
- ✅ 프로젝트의 메인 화면
- ✅ 주요 기능이 잘 보이는 화면
- ✅ 가로 비율 16:9 (800x450px)
- ❌ 에러 화면이나 로딩 화면
- ❌ 텍스트가 너무 작아서 안 보이는 화면

### 파일 크기
- 프로필: 100KB ~ 500KB
- 프로젝트: 500KB ~ 1MB
- 너무 크면 로딩이 느려집니다!

## 🎨 이미지 압축 도구
- [TinyPNG](https://tinypng.com/) - 무료 이미지 압축
- [Squoosh](https://squoosh.app/) - 구글 이미지 압축 도구

## 📸 무료 프로필/프로젝트 이미지
실제 프로젝트가 없다면 임시로 사용할 수 있는 사이트:
- [Unsplash](https://unsplash.com/) - 무료 고품질 이미지
- [UI8 Mockups](https://ui8.net/category/mockups) - 프로젝트 목업

