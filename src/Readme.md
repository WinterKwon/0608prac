## build 및 deploy 연습용

npx create-react-app@latest . → 최초1회

`create-react-app prac`

`cd prac`

`npm start` → 작동확인

`npm run build` 

`git 작업` 후 (저장소 연동 후 push까지) 

github settings의 pages 주소를 package.json에 `“homepage”항목 추가`

`npm run build`

`npx gh-pages -d build`
