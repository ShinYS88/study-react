# study-react
리액트 개인 스터디  
예제 학습을 통한 문법 익히기  

# 정리 노트


## 1. 리액트 시작

### 작업 환경
```
OS : MacOS
Tool : VS Code

React (v16.12.0)

nvm (v0.33.2)
node.js LTS (v12.14.1)
brew (v2.2.2)
yarn (v1.21.1)
```

## 2. JSX

#### ./src/App.js
``` 
 - js,css,html JSX에서 렌더링
 - if문 대신 조건부 테스트
 - 인라인 스타일링
 - class(className) 사용
```



## 3. 컴포넌트

#### ./src/App2.js
#### ./src/component

### 3-1. 클래스형 컴포넌트와 함수형 컴포넌트 / 어느 상황에서 함수형 컴포넌트를?

#### 함수형 컴포넌트의 장점  
```
- 클래스형 컴포넌트보다 선언하기 편하다.  
- 클래스형 컴포넌트보다 메모리 자원 사용이 적다.
```

#### 함수형 컴포넌트의 단점
```
- state와 라이프사이클 API의 사용이 불가능하다.(리액트 v16.8 이후 Hooks라는 기능이 도입되면서 해결)
``` 
    
### 3-2. 클래스형 컴포넌트 state 사용하기
#### ./src/component/6.ClassComponentState.js
```
- constructor 메서드를 활용한 state 초기 값 설정
- 생성자를 사용하지 않고 state 초기 값 설정하기
```

    
