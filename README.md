# Typechain

Learning Typescript by making a Blockchain with it


## Errors
- [X] tsc :command not found => npx tsc
- [X] compilerOptions "target"을 ES5 , ES6이런 식으로 바꾸라고 함

## Comments
- typed 언어 : 변수와 데이터의 종류를 설정 해야 함
  - 코드를 읽을 때 뭐가 일어날 지 예상 가능
    - 맞게 하고 있는지 아닌지 알려 줌

- TSC Watch : tsconfig.jason, package.json에서 설정 한 것에 따라 무언가를 바꿀 때마다 설정 한 곳이 바뀐다.
- interface를 js에 넣고 싶을 때 => class를 사용
  - 속성(string, number, bollean)과 속성들이 가지고 있는 권한(public, private)을 설정
  - public, private : js에서는 신경을 안씀
    - private : class 내부에서만 접근 가능
- typescript import 과정
  - import *(everything) as Crypto form "crypto-js";
