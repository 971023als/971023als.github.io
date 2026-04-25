# 971023als.github.io

## 개요
이 저장소는 개인 GitHub Pages를 사용하여 생성된 블로그 및 포트폴리오 웹사이트입니다. Jekyll을 기반으로 구성되었으며, 사용자 맞춤형 스타일 및 콘텐츠를 제공합니다.

---

## 디렉토리 구조

### 주요 폴더 및 파일

- **`_git`**: Git 저장소의 메타데이터가 저장되는 폴더입니다.
- **`_jekyll-cache`**: Jekyll의 빌드 캐시 파일을 포함하며, 빌드 성능을 향상시킵니다.
- **`_layouts`**: 페이지 레이아웃 템플릿을 저장합니다.
- **`_pages`**: 개별 페이지 파일들이 저장된 폴더입니다.
- **`_posts`**: 블로그 게시물 파일을 저장합니다.
- **`_sass`**: Sass 스타일 파일들이 저장되어 있습니다.
- **`_site`**: Jekyll 빌드 결과물이 생성되는 폴더입니다.

### 구성 파일

- **`.gitignore`**: Git 추적에서 제외할 파일/폴더 목록.
- **`_config.yml`**: Jekyll 사이트의 설정 파일.
- **`about.markdown`**: 'About' 페이지 내용.
- **`index.md`**: 메인 페이지 콘텐츠.
- **`style.css`**: 사이트의 사용자 정의 CSS 스타일 파일.

---

## 설치 및 실행

### 로컬 환경에서 실행하기
1. **Jekyll 설치**:
   ```bash
   gem install jekyll bundler
   ```

2. **필수 Gem 설치**:
   ```bash
   bundle install
   ```

3. **로컬 서버 실행**:
   ```bash
   bundle exec jekyll serve
   ```
   - 기본적으로 [http://localhost:4000](http://localhost:4000)에서 실행됩니다.

---

## 주요 파일 설명

### `index.md`
- 웹사이트의 메인 페이지를 정의하는 Markdown 파일입니다.

### `about.markdown`
- 사이트의 'About' 섹션을 정의합니다.

### `style.css`
- 사용자 정의 스타일을 적용하기 위한 CSS 파일입니다.

### `_config.yml`
- 사이트의 제목, URL, 테마, 플러그인 등을 설정합니다.

---

## 기여 방법
1. 저장소를 포크합니다.
2. 새 브랜치를 만듭니다:
   ```bash
   git checkout -b feature-branch
   ```
3. 변경 사항을 커밋합니다:
   ```bash
   git commit -m "Add feature"
   ```
4. 푸시 후 Pull Request를 생성합니다:
   ```bash
   git push origin feature-branch
   ```

---

## 라이선스
이 프로젝트는 공개되지 않은 개인 프로젝트입니다. 별도의 허가 없이 사용하지 마십시오.
