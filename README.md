# jun — 자기소개 페이지

프로젝트 목록 없이 자기소개와 생각을 담은 반응형 정적 웹사이트입니다. HTML과 CSS만 사용하므로 빌드나 패키지 설치가 필요하지 않습니다.

## 내용 수정

- `index.html`: 이름, 소개 문구, 태도 소개, 페이지 제목과 설명
- `style.css`: 색상, 글꼴, 화면 배치

소개와 태도 문구는 예시입니다. 공개하기 전에 본인에게 맞게 수정하세요. GitHub 사용자명은 아직 확인되지 않아 계정 링크를 넣지 않았습니다. Google Fonts를 불러오며, 연결되지 않을 때는 시스템 글꼴로 표시됩니다.

## GitHub Pages 배포

1. GitHub에 저장소를 만듭니다. 사용자 사이트 주소를 원하면 실제 GitHub 사용자명을 사용한 `<사용자명>.github.io`로 이름을 지정합니다. `jun`이라는 표시 이름과 GitHub 계정명은 별개입니다.
2. 이 폴더의 `index.html`, `style.css`, `.nojekyll`을 저장소의 루트에 올립니다.
3. 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
4. **main** 브랜치와 **/(root)** 폴더를 선택하고 **Save**를 누릅니다. 다른 브랜치를 사용했다면 해당 브랜치를 선택합니다.
5. Pages 설정에 표시되는 공개 주소를 확인합니다. 일반 저장소는 `https://<사용자명>.github.io/<저장소명>/`으로 열립니다.

모든 로컬 경로를 상대 경로로 작성하여 사용자 사이트와 저장소 하위 경로 모두 지원합니다.

공식 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
