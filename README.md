# QR Color Studio

URL과 텍스트를 QR 코드로 만들고, QR 색상과 배경색을 선택해 PNG 또는 SVG로 저장하는 웹 도구입니다.

- QR 색상과 배경색 선택기, HEX 코드 입력
- 투명 배경 또는 단색 배경
- 512 / 1024 / 2048 px PNG 및 SVG 다운로드
- 한글·이모지 지원
- 브라우저에서만 QR 생성, 서버 및 외부 CDN 불필요

## 실행

`index.html`을 브라우저로 열면 바로 사용할 수 있습니다. 코드와 스타일, QR 라이브러리가 한 파일에 포함되어 있습니다.

## GitHub Pages 배포

1. 이 폴더의 파일을 저장소의 `main` 브랜치 루트에 올립니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Source → Deploy from a branch**를 선택합니다.
4. **Branch → main**, **Folder → / (root)**를 선택하고 저장합니다.
5. GitHub Pages의 배포가 완료되면 표시되는 사이트 URL을 엽니다.

무료 개인 계정에서는 공개 저장소를 사용합니다. 별도 패키지 설치나 빌드 과정은 필요하지 않습니다.

## 사용 시 참고

QR과 배경의 명도 차이를 충분히 유지하고 실제 사용할 배경과 크기에서 스캔을 확인하세요. 투명 배경에서는 배치할 이미지나 문서의 배경색이 QR 판독에 영향을 줍니다.

## QR 라이브러리

[Project Nayuki QR Code generator](https://www.nayuki.io/page/qr-code-generator-library)를 사용합니다. 라이브러리의 MIT 라이선스 및 저작권 표시는 `index.html` 안에 포함되어 있습니다.

GitHub Pages 설정: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
