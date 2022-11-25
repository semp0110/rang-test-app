### `npm install`
패키지 설치 ./node_modules 디렉토리에 필요 패키지들을 다운로드
(해당 파일들은 app 배포시 필요없음)

### `npm start`
개발모드로 app 실행 (기본 URL : http://localhost:3000)

### `npm build`
프로젝트를 빌드하고 결과 파일을 만듬
(./build 디렉토리에 배포파일들이 생성됨...)


### 수정 업데이트 테스트
화면 내용을 수정해보고 싶으면 ./src/App.js 파일에서 `Hello world~` 텍스트 수정후 
npm build 하면 결과 파일들이 다시 생성됨