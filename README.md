# HODU-landing

고양이 호두 랜딩페이지.
귀여운 고양이 호두를 알아보는 랜딩페이지.

## 1. 목표와 기능

---

### 1.1 목표

- 기간 안에 페이지 완성하기
- HTML, CSS 만을 이용한 호두 랜딩페이지 만들기
- 시멘틱 마크업, 접근성, SEO, CSS 네이밍 방법론 고려하기
- 여러가지 화면에서도 문제 없는 반응형으로 작업하기

### 1.2 기능

특수한 기능은 없으나 고려해야 할 부분을 정리

1. HTML
   - 시맨틱 마크업 준수
   - 접근성 고려
   - SEO 고려
2. CSS
   - 반응형 제작
   - CSS 네이밍 방법론 고려

### 1.3 팀 구성

개인 프로젝트로 1인 개발.

## 2. 개발 환경 및 배포 URL

---

### 2.1 개발 환경

- VSCode

### 2.2 배포 URL

- https://jieunheo.github.io/HODU-landing/

## 3. 요구사항 명세와 기능 명세

---

1. 피그마를 참고하여 페이지 구현을 합니다.
2. 시멘틱 마크업, 반응형 웹, 접근성, SEO, CSS 네이밍 방법론 등을 고려해서 작업해주세요.
3. 모바일 화면도 고려하여 페이지 구현을 합니다.
4. 스크롤시 헤더가 고정되게 합니다.
5. 구독하기 모달창의 경우 퍼블리싱 해주신 후 화면에서 보이지 않게 숨김처리 해주시고 발표할 때 노출로 전환해서 보여주세요.
6. 자바스크립트로 추후 구현할 리스트
   1. 스크롤 탑 버튼
      1. 스크롤 탑 버튼은 스크롤시 나타납니다.
      2. 스크롤 탑 버튼은 푸터 아래로 내려가지 않습니다.
      3. 스크롤 탑 버튼을 누르면 스크롤이 최상단으로 올라갑니다. (단, 부드럽게 올라가야 합니다.)
   2. 구독하기 모달창
      1. 이메일을 입력하고 `Subscribe` 버튼을 클릭하면 모달창이 나타납니다.
      2. 이메일 유효성 검사를 진행해야 합니다. (값이 들어가지 않거나 이메일 형식이 유효하지 않으면 alert 창으로 경고 문구가 떠야합니다.)
      3. 이메일이 잘 입력되었다면 모달창이 뜹니다. 이때 모달창의 `OK! I love HODU` 버튼을 클릭하면 form이 제출되고 모달창이 닫힙니다.

[피그마 참고](https://www.figma.com/design/rbi8px4O2GrnXN4gK0ZaLv/WENIV_FE_%EC%8B%A4%EC%8A%B5-%EC%98%88%EC%A0%9C?node-id=49-1791&p=f&t=2VCDDzw7QxWKjnpz-0)

## 4. 프로젝트 구조와 개발 일정

---

### 4.1 프로젝트 구조

```
HODU-landing
├─ images
│  ├─ arrow-left.svg
│  ├─ arrow-right.svg
│  ├─ blog.svg
│  ├─ box-cat.png
│  ├─ cat-subscribe.png
│  ├─ facebook.svg
│  ├─ img_1.jpg
│  ├─ img_2.jpg
│  ├─ img_3.jpg
│  ├─ img_4.jpg
│  ├─ img_5.jpg
│  ├─ instagram.svg
│  ├─ logo.png
│  ├─ logo.svg
│  ├─ mail.svg
│  ├─ menu.svg
│  ├─ modal-bg-img.png
│  ├─ readme
│  │  ├─ desktop.png
│  │  └─ mobile.png
│  ├─ top-btn.svg
│  └─ youtube.svg
├─ index.html
├─ README.md
└─ styles
   ├─ reset.css
   └─ style.css
```

### 4.2 개발 일정

25.08.08(금) ~ 25.08.12(화), 평일 기준 총 3일

## 5. 화면

---

### 5.1 pc 화면

![desktop](./images/readme/desktop.png)

### 5.2 mobile 화면

![mobile](./images/readme/mobile.png)

## 6. 메인 기능

---

- 시멘틱 태그 사용 (header, main, footer, h1, h2, ...)
- flex 사용
- input 태그에 텍스트 필수 입력 체크 (required)
- 팝업 (JavaScript 없이 팝업 위치만 스타일링)
- CSS 방법론 - BEM 방식으로 진행
- 헤더 상단 고정, to top 버튼 우측 하단 고정
- 가상요소와 backgroung-image 사용
- 반응형 웹 테스트 (pc/mobile 2단계)
  - 모바일 퍼스트 형식으로 진행
  - pc 화면에서 배경색 확장
  - 모바일 메뉴 햄버거 형식
  - 모바일에서만 footer nav 출력

## 7. 에러와 에러 해결

---

### 7.1

### 7.2

### 7.3

## 8. 개발하며 느낀점

---
