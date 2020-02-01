### 배포 링크
https://mnist-33527.web.app/

### 프로젝트 설명
최근 AI 분야의 딥러닝 공부를 시작했다. 석사 과정 중에 딥러닝 수업을 들었지만 시간이 지나니 기억이 나지 않아 처음부터 다시 시작했다. 딥러닝을 처음 공부하면 코딩에서 Hello World 같은 존재가 바로 Mnist일 것이다. Mnist는 숫자 손글씨 데이터로 딥러닝 모델을 트레이닝하고 테스트하는 프로젝트이다. Mnist를 공부하다가 이를 웹앱으로 만들어서 웹상에서 손글씨를 이미지를 업로드하고 결과를 확인하면 재밌겠다는 생각이 들었다. 그래서 AI 숫자 판별 앱이라는 이름으로 Mnist 웹앱을 개발해보았다.

웹사이트는 3개의 페이지로 구성되어 있다.
홈 - AI 숫자 판별 앱의 소개이다.
가이드라인 - 판별 대상인 손글씨 이미지를 만드는 방법을 설명한다.
파일 업로드 - 파일을 업로드하여 AI가 판별한 결과를 확인한다.

### 개발 블로그 링크

https://jongbeom-dev.tistory.com/86?category=847760

## Available Scripts

이 프로젝트에서는 다음의 스크립트를 이용한다.

### `npm run dev`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `public` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `firebase deploy`

App is deployed to firebase server.
Url of the deployed app is [https://mnist-33527.web.app/](https://mnist-33527.web.app/)