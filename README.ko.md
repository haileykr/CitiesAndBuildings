# Cities And Buildings
건축가, 건축공학자, 그리고 모든 빌딩 팬들을 위한 웹 앱. &#127751; &#127747; 

[citiesandbuildings.herokuapp.com](https://citiesandbuildings.herokuapp.com)

Read in  [English](https://github.com/haileykr/CitiesAndBuildings/blob/master/README.md)


![home](./public/imgs/CAB_image.png)

![index](./public/imgs/CAB_ind.png)

## Functionalities
1. 세계 각지의 빌딩들을 탐험해보세요!
- 관심 있는 빌딩에 대한 정보를 알아보세요.
- 여러분이 알고 있는 재밌는 정보도 추가해보세요.
`
2. 당신의 빌딩을 추가하기 위해 멤버가 되어보세요!
- 회원가입 후에는, 관심있는 빌딩을 추가할수도, 수정 및 삭제할수도 있어요.

3. 다양한 검색어로 빌딩을 검색해보세요!
- 빌딩 이름, *(추가 예정)*높이, 건축가, 그리고 건축공학자 이름으로 빌딩을 검색해보세요.

## Tech Stack
![tech_stack](./public/imgs/CAB_tech_stack.png)

#### Front-end
- HTML, CSS, 그리고 JavaScript (EJS)로 개발되었습니다.
- 더 많은 스타일링과 반응형 디자인 구현을 위해 CSS 프레임워크인 Bootstrap이 사용됐습니다.

#### Back-end
- RESTful 라우팅을 구현했습니다.
- Express 웹 프레임워크가 서버 구현에 사용되었습니다.
- 프론트엔드, 백엔드 모두 자바스크립트로 구현하기 위해 Node.js에 기반한 Express를 선택했습니다.
- MongoDB를
  * Node.js와 Express와의 호환성
  * NoSQL 데이터베이스 사용 연습 목적
  을 바탕으로 선택했습니다.
- 기타 라이브러리
  * _EJS_: 자바스크립트 사용 기반 템플릿 엔진
  * _Axios_: 프로미스 바탕의 HTTP 리퀘스트 관리
  * _express-session_: 세션 도입
  * _passport_: Authentication (인증)과 Authorization (인가) 관리
  * _Mongoose_와_JOI_: 데이터 스키마 관리를 통한 데이터 유효성 검증
  * _express-mongo-sanitize_: Express의 내장 미들웨어 / 클래스와 더불어 Mongo Injection (데이터베이스 삽입 공격) 방지 
  * _sanitize-html_: JOI와 더불어 XSS(Cross-Site Scripting) 공격 방지
  * _helmet_: 보안 강화를 위해 헤더 설정
  * _flash_: 알림 메시지 커스터마이제이션
  * _cloudinary_: 이미지 업로드와 수정 및 관리
  * _multer_: multipart form 데이터 관리
  * _mapbox_: 빌딩의 geolocation을 바탕으로 지도에 위치 표시

#### Deployment
- _heroku_ 에 배포하였습니다.
- PaaS (Platform as a Service)를 제공하여 비교적 사용이 쉬운 Heroku를 처음 만든 프로젝트의 배포 플랫폼으로 결정하였습니다.