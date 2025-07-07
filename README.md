# 다시 스탠드 문서 센터

다시 스탠드 서비스의 법적 문서들을 호스팅하는 GitHub Pages 사이트입니다.

## 📋 포함된 문서

- **개인정보처리방침** (`privacy-policy-dasi-stand.html`)
- **서비스 이용약관** (`약관.html`)

## 🌐 사이트 접속

GitHub Pages를 통해 호스팅되는 사이트는 다음 URL에서 확인할 수 있습니다:
- `https://[YOUR_USERNAME].github.io/docs_hosting/`

## 🚀 배포 방법

1. GitHub 저장소의 Settings → Pages 섹션으로 이동
2. Source를 "GitHub Actions"로 선택
3. main/master 브랜치에 푸시하면 자동으로 배포됩니다

## 📁 파일 구조

```
docs_hosting/
├── index.html                           # 메인 페이지
├── privacy-policy-dasi-stand.html       # 개인정보처리방침
├── 약관.html                           # 서비스 이용약관
├── .nojekyll                           # Jekyll 처리 건너뛰기
├── .github/
│   └── workflows/
│       └── deploy.yml                  # GitHub Actions 워크플로우
└── README.md                           # 프로젝트 설명
```

## 🔧 수정 방법

문서를 수정하려면:
1. 해당 HTML 파일을 직접 편집
2. 변경사항을 커밋하고 푸시
3. GitHub Actions가 자동으로 사이트를 업데이트

## 📝 라이선스

이 프로젝트는 패션 개발자들의 소유입니다.
