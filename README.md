# Vibe Coding Project

이 프로젝트는 HTML, CSS, JavaScript로 구성된 정적 웹 애플리케이션입니다.

## 배포 가이드

이 프로젝트는 정적 파일(HTML, CSS, JS)로만 이루어져 있으므로, 다양한 정적 웹 호스팅 서비스를 통해 매우 쉽게 배포할 수 있습니다.

### 1. GitHub Pages를 이용한 배포 (추천)
가장 간단하고 무료로 사용할 수 있는 방법입니다.
1. GitHub 저장소(https://github.com/neorion9-lab/0613_test)로 이동합니다.
2. 저장소의 **Settings** 탭을 클릭합니다.
3. 좌측 메뉴에서 **Pages**를 선택합니다.
4. "Build and deployment" 섹션의 **Source**를 "Deploy from a branch"로 설정합니다.
5. **Branch**를 `master`로 선택하고, 폴더는 `/(root)`로 지정한 뒤 **Save**를 누릅니다.
6. 1~2분 정도 기다린 후, 상단에 나타나는 URL(예: `https://neorion9-lab.github.io/0613_test/`)로 접속하여 배포된 사이트를 확인합니다.

### 2. Vercel을 이용한 배포
1. [Vercel](https://vercel.com/)에 회원가입/로그인합니다.
2. 대시보드에서 **Add New... > Project**를 클릭합니다.
3. GitHub 계정을 연동하고 `0613_test` 저장소를 `Import`합니다.
4. 별도의 설정(Build Command 등) 없이 기본값 그대로 **Deploy** 버튼을 클릭합니다.
5. 배포가 완료되면 제공되는 고유 URL을 통해 접속합니다.

### 3. Netlify를 이용한 배포
1. [Netlify](https://www.netlify.com/)에 회원가입/로그인합니다.
2. 대시보드에서 **Add new site > Import an existing project**를 클릭합니다.
3. GitHub를 선택하고 `0613_test` 저장소를 연결합니다.
4. 기본 설정 그대로 두고 **Deploy site**를 클릭합니다.
5. 배포가 완료되면 부여된 URL을 통해 사이트를 확인할 수 있습니다.

## 로컬 실행 방법
1. 프로젝트를 클론하거나 다운로드합니다.
2. VS Code 등의 에디터에서 프로젝트 폴더를 엽니다.
3. `index.html` 파일을 브라우저로 직접 열거나, **Live Server** 익스텐션을 사용하여 실행합니다.
