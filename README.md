# devhitu.github.io

## 깃에 리액트 작업물 올리기
1. 작업
2. 작업후 `npm run build`
3. build 폴더 안에 안에 있는 내용 내 깃.io repository에 드래그해서 올리기

---
1. [내계정].io 레포지토리 생성, 브랜치 main 설정
2. [작업물 레포지토리] 생성, 브랜치 main 설정
3. [작업물 레포지토리]에 복제해서 내 로컬 vs환경에 설치
4. 복제한 폴더에 리액트 작업물 복붙
5. "homepage": "https://[내계정]..github.io/portfolio/" json추가


6. build 파일 생성, build 파일을 커밋
7. https://[내계정].github.io/[작업물 레포지토리]/ 확인
npx serve -s build
npm install -g serve
serve -s build
npm run build



참고자료: https://codingapple.com/unit/react-build-deploy-github-pages/
- 주의
서브디렉토리 설정: "homepage" 설정에 올바른 서브디렉토리 경로를 지정했는지 다시 한 번 확인하세요. "homepage" 설정에는 마지막 슬래시 '/'가 포함되어야 하므로 "https://[내계정].github.io/portfolio/"로 설정되어야 합니다.

```
다음 build 생성시, 여러 번 npm run build를 실행하는 경우, 매번 새로운 빌드 파일이 생성됩니다. 즉, 이전에 생성된 파일은 더 이상 존재하지 않으며 새로운 파일로 대체됩니다.

따라서 빌드를 실행할 때마다 변경된 소스 코드에 따라 새로운 빌드 파일이 생성되므로, 이전에 생성된 파일이 덮어씌워집니다.

```
---
## 작업 참고할때는
1. npm start로 local에서 확인

