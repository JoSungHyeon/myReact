*** React Start ***

Node,js 기반의 자바 라이브러리

React 사용이유
1. 컴포넌트 기반의 UI 라이브러리이므로
중복코드를 컴포넌트화 시켜 개발 가능함
2. 명령형 프로그래밍(절차를 하나하나 다 나열 해야함)
선언형 프로그래밍(그냥 목적을 바로 말함)
= 선형 프로그맹 방식의 UI 라이브러리임
3. 가상돔을 사용하므\로 랜더가 필요 없음

npx create-react-app reactexam1
-- 한번만 사용하는 리액트 프로젝트 생성

npm create vite@latest
-- vite를 사용한 리액트 프로젝트 생성
framework = react
variant = javascript
로 생성

확장프로그램 eslint <-- 설치

eslintrc.cjs 파일의
rules 에 아래 스크립트 추가
"no-unused-vars":"off" = 실제 사용하지 않는 변수가 있을때 오류로 알려줌(혼란스러울 수도 있으니 OFF)
"react/prop-types":"off" = 나중에 안정적으로 돌리게끔 해주는것(실습땐 OFF)

다음엔 실습해야지!!!