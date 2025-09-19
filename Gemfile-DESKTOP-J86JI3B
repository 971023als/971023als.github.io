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

# Rack과 WEBrick 명시적 추가
gem "rack", "~> 3.1"                # Rack 추가
gem "webrick", "~> 1.9"             # WEBrick 추가

# Puma 서버 추가 (WEBrick 대체 가능)
gem "puma", "~> 5.6"

# CSV 관련 경고 해결
gem "csv", "~> 3.3.2"

# Sass 및 SCSS 관련 종속성 추가
gem "sassc-rails", "~> 2.1", platforms: [:mingw, :x64_mingw, :mswin, :jruby]

# 개발 환경 전용 도구
group :development do
  gem "base64", "~> 0.2.0"
end
