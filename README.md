# Create React App 파해치기

Create React App으로 만들어진 결과물을 알아보기위한 프로젝트입니다.

> 해당 프로젝트는 `TypeScript`가 포함된 템플릿을 기본 프로젝트로 사용했습니다.

## 프로젝트 만들기

`TypeScript`가 포함된 템플릿으로 `create-react-app`을 실행하여 `my-app`이라는 프로젝트를 만듭니다.

```
$ npx create-react-app my-app --template typescript
```

기존의 프로젝트는 `react-scripts`라는 라이브러리에 대부분의 설정이 숨겨져있습니다.

```
  "scripts": {
    ...
    "build": "react-scripts build",
    ...
  },
```

이를 해당 커맨드로 풀어서 볼 수 있습니다.

```
$ npm run eject
```
