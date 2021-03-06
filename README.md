
## 1. 프로젝트 소개

- 주제 : 땅콩스쿨 메인화면 클론
- 기간 : 22.02.14 ~ 22.02.16



## 2. 배포 링크

https://lucid-yonath-e29dc7.netlify.app/


## 3. 팀원 소개

<table>

  <tr align="center">
    <td><a href="https://github.com/Yena-Yun">윤예나</a></td>
    <td><a href="https://github.com/minjuice1">박민주</a></td>
  </tr>

  <tr align="center">
    <td><img src="https://avatars.githubusercontent.com/u/68722179?v=4" width="150px"/></td>
    <td><img src="https://avatars.githubusercontent.com/u/82799961?v=4" width="150px"/></td>
  </tr>
</table>


## 4. 구현 기능

⚜ 박민주
* ReadingBook, DiaryBook, Books, Bookmarks, Download, Footer UI 구현 및 반응형 적용
* Books 컴포넌트에서 react-slick으로 인피니트 슬라이드 기능 구현
* main 컴포넌트에서 mouse animation 적용
* 모든 컴포넌트에 aos로 fade-up 적용
* floatingButton 구현
  
⚜ 윤예나
* 프로젝트 초반 세팅 (Typescript, Prettier, eslint, Cypress)
* globalStyles 설정 및 사이트 실제 폰트 적용 (Noto Sans KR)
* Header, Main, Intro, Video, Checks, ReviewSlide UI 구현 및 반응형 적용
* ReviewSlide 컴포넌트에서 react-slick으로 슬라이드 기능 구현
* 화면 스크롤 시 Header 컴포넌트에 트랜지션 CSS 적용

## 5. 기술 스택
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![styled-components](https://img.shields.io/badge/styled-components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white) 


## 6. 디렉토리 구조

```bash
.
├── components              # 프로젝트 구성 컴포넌트
│   ├── Books
│       ├── BookList.tsx
│       ├── Books.tsx
│       └── BooksCarousel.tsx
│   ├──  ReviewSlide
│       ├── ReviewCarousel.tsx
│       ├── ReviewList.tsx
│       ├── ReviewThumbnail.tsx
│       ├── ReviewThumbCarousel.tsx
│       └── ReviewSlide.tsx
│   ├── Bookmarks.tsx
│   ├── Checks.tsx
│   ├── DiaryBook.tsx
│   ├── Download.tsx
│   ├── Footer.tsx
│   ├── Header.tsx
│   ├── Intro.tsx
│   ├── Main.tsx
│   ├── ReadingBook.tsx
│   └── Video.tsx
├── cypress               # e2e Test
├── pages
│   ├──  _app.tsx         # css, 레이아웃 구성
│   ├──  _document.tsx
│   └──  index.tsx        # 프로젝트 구성 페이지
├── public                # images, gif, mp4
│       ├── images
│       ├── movies
├── styles                # 글로벌 css 적용
│   ├── global-styles.ts
│   ├── global.css
│   └── theme.ts
└── utils
```


## 7. 설치 및 실행 방법
클론 후 yarn install

    ```bash
      yarn dev
    ```


## 8. 커밋 컨벤션

깃모지를 사용하여 이모티콘만 보고 커밋의 목적이나 의도를 쉽게 식별할 수 있도록 하였습니다.

| 깃모지 | 사용 예시 |
| --- | --- |
| :sparkles: | 기능 구현 |
| :lipstick: | CSS 스타일링 |
| :wrench: | utils 함수나 types 추가 |
| :fire: | 파일 삭제 |
| :wastebasket: | 코드 삭제 |
| 🚚 | 디렉토리 또는 파일 이동 |
| :package: | 패키지 설치 |
| ♻️ | 리팩토링 |
| 📝 | Readme 수정 |
| 🐛 | 버그 수정 |
