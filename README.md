# 유럽 출시 타임라인

GitHub Pages로 배포할 수 있도록 구성한 정적 웹사이트입니다.

## 포함 파일
- `index.html`: 웹사이트 전체 코드(HTML, CSS, JavaScript 포함)

## GitHub Pages 배포 방법
1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 폴더의 `index.html`과 `README.md`를 저장소 최상위(root)에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 선택하고 **Save**를 누릅니다.
6. 배포가 완료되면 Settings → Pages에 표시되는 사이트 주소를 엽니다.

## 참고
- Google Fonts와 html2canvas 라이브러리를 CDN에서 불러오므로 일부 기능은 인터넷 연결이 필요합니다.
- 현재 버전의 입력 내용은 브라우저 메모리에서만 유지됩니다. 페이지를 새로고침하면 직접 추가·수정한 태스크가 초기화될 수 있습니다.
