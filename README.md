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
   - 에러: `--source-map true` 적용인 안됨 
   - 해결방법: base/\_reset.scss 첫줄에 `/*# sourceMappingURL=styles.css.map */` 추가함 - `style.css.map`이라는 파일이 생김
