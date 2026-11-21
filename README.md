# MarkStudio 홈페이지 게시 안내

이 폴더에는 웹사이트 게시에 필요한 파일만 들어 있습니다. MarkStudio 프로그램 전체 폴더나 `Google API OAuth`, `google_oauth_client.json`, 개인 문서, 작업 상태, 빌드 및 설치 파일은 이 공개 저장소에 올리지 마세요.

## GitHub Pages에 게시

1. GitHub 사용자 `kormo09`에서 `MarkStudio`라는 **Public** 저장소를 만듭니다. 웹사이트를 게시하는 데 라이선스 선택은 필수가 아닙니다.
2. 이 폴더의 **내용물**(`index.html`, `privacy.html`, `terms.html`, `style.css`, `assets` 폴더)을 저장소 최상위에 업로드하고 커밋합니다. 이 안내 파일도 함께 두어도 됩니다.
3. 저장소의 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**, `main`, `/(root)`를 선택하고 저장합니다.
4. 배포가 완료되면 다음 주소를 브라우저에서 직접 확인합니다. 저장소 이름의 대소문자를 정확히 유지하세요.

- 홈페이지: https://kormo09.github.io/MarkStudio/
- 개인정보처리방침: https://kormo09.github.io/MarkStudio/privacy.html
- 서비스 약관: https://kormo09.github.io/MarkStudio/terms.html

위 주소는 GitHub Pages가 배포된 뒤 예상되는 URL입니다. 실제 생성·배포는 아직 이루어지지 않았습니다. `kormo09.github.io` 사용자 사이트나 사용자 지정 도메인을 사용하는 경우 URL은 달라집니다.

## Google OAuth 검토 전에

- Google Cloud 인증 플랫폼의 앱 이름, 연락처 이메일과 이 홈페이지의 운영 정보를 일치시킵니다. 개인정보처리방침과 약관의 내용이 실제 앱·운영 방식에 맞는지 확인한 뒤 공개합니다.
- Google Cloud 프로젝트의 소유자 또는 편집자 계정으로 Search Console에서 사이트 소유권을 확인하고, Google이 해당 홈페이지 도메인을 OAuth 검증에 인정하는지 확인합니다. GitHub Pages의 공유 도메인 구조 때문에 검증이 받아들여지는지는 실제 확인이 필요하며, 필요하면 소유한 사용자 지정 도메인을 연결합니다. Search Console에서 제공하는 HTML 확인 태그 또는 파일이 있다면 지시된 위치에 그대로 추가하세요.
- 현재 앱은 광범위한 Google Drive 권한(`drive`)을 요청합니다. Google 정책에서 요구하는 앱 내부의 데이터 접근·사용 안내와 동의, 권한의 필요성 및 제한된 권한에 대한 검증 요건을 별도로 확인해야 합니다. 이 웹페이지를 올리는 것만으로 검증이나 승인이 보장되지 않습니다.
- 현재 작업 상태와 PDF 그림 캐시는 사용자 PC에 남을 수 있습니다. 배포 전에 개인정보 보호, 로컬 파일 보안, 삭제 및 관련 법령과 정책을 검토하세요.
- 공식 안내: https://developers.google.com/identity/protocols/oauth2/production-readiness/brand-verification
