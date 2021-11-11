21년 10월 27일

1. 개발 환경 설정

- [x] figma 설치 (vs는 이미 설치되어있음)
- [x] git rep 설정
- [x] node-sass 설치
- [x] npm script 업데이트
- [x] prettier & SCSS lint 설정

2. Asset 준비

- [x] HTML Document 셋업 & Webfont 적용
- [x] 이미지 파일 업로드
- [x] icon svg를 icon-font로 바꾸기
      svg를 태그 자체로 사용하면 할 수 있는게 많아진다.
- [x] favicon 설정
- [x] reset.css vs nomalize.css 차이 알고 적용
- [x] custome reset 적용
- [x] npm script --source-map 적용하기(개발자 도구가 scss 파일에 접근함)
  - [x] 에러: `--source-map true` 적용인 안됨
  - [x] 해결방법: base/\_reset.scss 첫줄에 `/*# sourceMappingURL=styles.css.map */` 추가함 - `style.css.map`이라는 파일이 생김

3. Sass 100% 활용하기: 변수 Variable

- [x] Sass를 배우는 우리의 자세
  - 작은 것부터 하나하나 만들어가자
- [x] $ - 디자인을 코드로 옮기는 첫 걸음
  - 변수를 선언하는 법:`$one: 1;`를 써야함,
  - 알파벳, 언더바, 대쉬, 숫자 사용가능
  - 숫자로 시작하면 안된다!
  - css에서 사용하는 모든 속성값을 사용할 수 있다.
  - css속성값을 문자열로 넣으면 안된다
  - scope도 가능
- [x] 색상 팔레트
- [x] 타이포그래피
- [ ] 그리드 시스템
- [ ] 그리드 시스템 분석 훈련
- [ ] 반응형 그리드 시스템 설계1
- [ ] 반응형 그리드 시스템 설계2
- [ ] 반응형 그리드 시스템 설계3
