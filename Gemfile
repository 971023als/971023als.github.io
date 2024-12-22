source "https://rubygems.org"

# Jekyll 및 테마 설정
gem "jekyll", "~> 4.3.4"            # Jekyll 코어
gem "minima", "~> 2.5"              # 기본 테마

# Jekyll 플러그인
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"      # RSS 피드 생성
  gem "jekyll-seo-tag", "~> 2.8"    # SEO 메타 태그 생성
  gem "jekyll-sitemap", "~> 1.4"    # 사이트맵 생성
end

# Windows 및 JRuby 플랫폼별 종속성
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"       # 시간대 정보 관리
  gem "tzinfo-data"                 # Windows 플랫폼 시간대 데이터
end

# Windows 전용 파일 변경 감지 도구
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby 전용 HTTP 파서
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# 경고 해결 및 추가 패키지
gem "csv", "~> 3.3.2"               # CSV 파일 처리
gem "base64", "~> 0.2.0"            # Base64 인코딩/디코딩

# 개발 환경 전용 도구
group :development do
  gem "jekyll-admin", "~> 0.11"     # Jekyll 관리 인터페이스
end

gem "webrick", "~> 1.9"
