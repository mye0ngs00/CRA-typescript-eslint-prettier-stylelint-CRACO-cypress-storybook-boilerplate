자주 사용하는 기술 스택을 정리하여 보일러 플레이트를 만들었다. 백엔드는 TDD가 중요하지만, 프론트엔드는 CDD BDD 위주로 가는 게 다방면에서 좋다고 생각하기 때문에 이렇게만 사용한다.
### spec
1. CRA(Creat-React-App)
- SPA 구조와 생산성   
2. Typescript
  - 안정적인 개발   
3. eslint
- 정적 분석과 코딩 컨벤션   
4. prettier
- 코드 스타일과 코딩 컨벤션   
5. stylelint
- 스타일 시트의 정적 분석과 코딩 컨벤션   
6. CRACO(+alias)
- eject없이 webpack, babel 설정
- path의 depth가 깊어짐에 따라 발생하는 가독성 향상   
7. cypress
- e2e scenario test   
8. storybook
- 컴포넌트 설계 및 디자인 시스템  

### how to use this
`$ git clone https://github.com/mye0ngs00/CRA-typescript-eslint-prettier-stylelint-CRACO-cypress-storybook-boilerplate.git`

`$ cd CRA-typescript-eslint-prettier-stylelint-CRACO-cypress-storybook-boilerplate.git`

`$ yarn install`

추가로 jest, jest-dom은 craco설정을 따로 해줘야 한다.