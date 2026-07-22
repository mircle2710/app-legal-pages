# app-legal-pages

도메인 없는 모바일 앱용 **개인정보처리방침 / 이용약관 / 지원** HTML 모음.  
GitHub Pages로 배포해 Play Console, App Store Connect, Google OAuth에 URL로 등록합니다.

## 배포 (최초 1회)

1. GitHub에 **public** 저장소 `app-legal-pages` 생성
2. 이 폴더 내용 push
3. **Settings → Pages → Build: Deploy from branch → main / root**
4. 몇 분 후 `https://<GITHUB_USERNAME>.github.io/app-legal-pages/...` 로 접속 확인

## Google OAuth

- **승인된 도메인**: `<GITHUB_USERNAME>.github.io`
- 앱 홈 / privacy / terms URL에 아래 주소 사용

## 앱별 URL (today-page)

| 용도 | URL |
|------|-----|
| 홈(지원) | `https://mircle2710.github.io/app-legal-pages/today-page/support.html` |
| 개인정보 | `https://mircle2710.github.io/app-legal-pages/today-page/privacy.html` |
| 이용약관 | `https://mircle2710.github.io/app-legal-pages/today-page/terms.html` |

## 앱별 URL (dongpo / 동포)

| 용도 | URL |
|------|-----|
| 고객 지원 | `https://mircle2710.github.io/app-legal-pages/dongpo/support.html` |
| 개인정보 | `https://mircle2710.github.io/app-legal-pages/dongpo/privacy.html` |
| 이용약관 | `https://mircle2710.github.io/app-legal-pages/dongpo/terms.html` |
| 계정 삭제 | `https://mircle2710.github.io/app-legal-pages/dongpo/delete-account.html` |

## 새 앱 추가

```
app-legal-pages/
  <app-slug>/
    privacy.html
    terms.html
    support.html
```

`_template/` 복사 후 앱 이름·이메일·기능 설명만 수정.

## 장점

- IP 주소 불가 → **github.io** 도메인으로 스토어·OAuth 통과
- HTTPS 무료
- 프로젝트마다 레포 복제 없이 **한 곳에서** 관리
- 앱 업데이트와 법적 문서 버전 분리 (git history)
