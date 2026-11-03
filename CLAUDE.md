# Pixel Stack — 작업 규칙

## 프로젝트
- 빌드 없는 단일 파일 게임: 모든 코드는 `index.html` 하나에 있음.
- 내부 해상도 180×320 캔버스 픽셀아트. 외부 리소스는 Google Fonts(Press Start 2P)뿐.

## 배포 (항상 바로 배포)
- 배포: GitHub Pages가 `main` 브랜치 루트를 자동 배포 → https://euntaeglee.github.io/pixel-stack/
- 변경을 마치면 묻지 말고 바로 배포한다:
  1. 작업 브랜치에 커밋하고 푸시
  2. 같은 커밋을 `main`에도 푸시 (`git push origin HEAD:main`, fast-forward만; main이 앞서 있으면 먼저 rebase)
  3. 세션에서 미리보기 Artifact를 만들었다면 같이 갱신
- 배포 전에 헤드리스 브라우저(Playwright)로 페이지를 열어 콘솔 에러가 없는지 확인한다.
- 사용자에게는 한국어로 답한다.
