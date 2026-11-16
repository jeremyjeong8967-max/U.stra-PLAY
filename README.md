# U.stra PLAY 브라우저 데모 (GitHub Pages)

## 페이지 주소
- 메인: `https://jeremyjeong8967-max.github.io/U.stra-PLAY-Admin/`
- 관리자: `https://jeremyjeong8967-max.github.io/U.stra-PLAY-Admin/admin/`
- 직원용 게임: `https://jeremyjeong8967-max.github.io/U.stra-PLAY-Admin/games/`

## GitHub 업로드 구조
`index.html`, `admin/`, `games/`를 저장소 최상위에 업로드하세요. GitHub Pages 설정은 `main` 브랜치, `/(root)`입니다.

## 테스트 범위 및 제한
- 이 패키지는 브라우저에서 화면과 링크를 확인하기 위한 정적 데모입니다.
- 관리자와 직원 화면은 동일한 GitHub Pages 출처(origin)를 사용하므로 같은 브라우저 프로필 안에서는 localStorage를 공유할 수 있습니다.
- 다른 사람의 기기·브라우저와 데이터가 자동 동기화되지는 않습니다. 서버·공용 데이터베이스·로그인 기능은 포함하지 않습니다.
- 관리자에서 생성하는 직원용 이벤트 링크는 `/games/` 경로로 이동하도록 조정했습니다.
- 이벤트 데이터는 URL 해시에 포함되는 데모 방식입니다. 실제 개인정보나 실제 경품 운영에는 사용하지 마세요.
- GitHub 저장소가 Public이면 소스 파일도 공개됩니다.

## 원본 보존
기존 파일은 저장소 루트의 `U.stra PLAY-Admin.html`, `U.stra PLAY-Games.html`로 보존했습니다. 실제 Pages 진입 파일은 `admin/index.html`, `games/index.html`입니다.
