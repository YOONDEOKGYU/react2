# 201930119 윤덕규

## 8월 28일 강의
### Next.js
* 리액트를 위해 만든 오픈소스 자바스크립트 웹 프레임워크
* 리액트에는 없는 다양한 기능 제공  
-> 서버 사이드 렌더링(SSR : Server Side Rendering)  
-> 정적 사이트 생성(SSG : Static Site Generation)  
-> 증분 정적 재생성(ISR : Incremental Static Regeneration)
* SSG는 미리 만들어 놓은 페이지를 서비스해서 속도는 빠르지만 수정 불가
* ISR은 이미 생성된 페이지를 일정 시간이 지난 후 다시 생성(최신 데이터로 업데이트)

### Next.js와 비슷한 프레임워크
* Gatsby  
-> 정적 웹 사이트를 만들 수 있는 프레임워크  
-> 정적 사이트 생성만 지원  
-> 클라이언트 사이드 렌더링만 지원

* Razzle  
-> 서버 사이드 렌더링이 가능한 자바스크립트 애플리케이션 개발 가능  
-> CRA와 유사하게 프로젝트를 구성할 수 있다는 장점(create-razzle-app)  
-> React, Preact, Reason-React, Angular 및 Vue와 함께 사용 가능

* Nuxt.js  
-> Vue를 사용한 웹 애플리케이션 개발에서 리액트의 Next.js에 해당하는 프레임워크  
-> Nuxt.js나 Next.js 모두 같은 목표를 갖지만 Nuxt.js는 더 많은 설정 필요

* Angular Universal  
-> 정적 사이트 생성과 서버 사이드 렌더링 지원  
-> Nuxt나 Next와는 달리 구글에서 만듬