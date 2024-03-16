## 요구사항
메인 화면 index.html에서 시맨틱태그가 적절히 활용되었는지 확인바랍니다.

### 기본

- [x] 랜딩 페이지의 url path는 루트(‘/’)로 설정합니다.
- [x] title은 “판다마켓”로 설정합니다.
- [x] 화면의 너비가 1920px 이상이면 하늘색 배경색은 너비를 꽉 채우도록 채워지고, 내부 요소들의 위치는 고정되고, 여백만 커지도록 합니다.
- [x] 화면의 너비가 1920px 보다 작아질 때, “판다마켓” 로고의 왼쪽 여백 200px“로그인" 버튼의 오른쪽 여백 200px이 유지되고, 화면의 너비가 작아질수록 두 요소간 거리가 가까워지도록 설정합니다.
- [x] 클릭으로 기능이 동작해야 하는 경우, 사용자가 클릭할 수 있는 요소임을 알 수 있도록 CSS 속성 cursor: pointer 로 설정합니다.
- [x] “판다마켓” 클릭 시 루트 페이지(‘/’)로 이동합니다.
- [x] '로그인'버튼 클릭 시 로그인 페이지(‘/login’)로 이동합니다 (빈 페이지)
- [x] “구경하러가기”버튼 클릭 시(’/items’)로 이동합니다.(빈 페이지)
- [x] “Privacy Policy”, “FAQ”는 클릭 시 각각 Privacy 페이지(‘/privacy’), FAQ 페이지(‘/faq’)로 이동합니다.(모두 빈 페이지)
- [x] 페이스북, 트위터, 유튜브, 인스타그램 아이콘을 클릭 시 각각의 홈페이지로 새로운 창이 열리면서 이동합니다.

### 심화

- [x] palette에 있는 color값들을 css 변수로 등록하고 사용해 주세요.
- [ ] 비밀번호 input 요소 위에 비밀번호를 확인할 수 있는 아이콘을 추가해 주세요.


## 주요 변경사항

- 메인 화면 작업했습니다.

## 스크린샷

![image](이미지url)

## 멘토에게

- [css 질문] 폰트사이즈 반응형 작업할 때 html, body에 font-size:100%를 적용하고 @media (max-width:767px) { html, body: font-size: 90%; } 이렇게는 잘 안하나요?
- 메인과 서브페이지 헤더 및 푸터 내용이 같을 때 어떤 방식으로 작업하면 좋을까요?
- 셀프 코드 리뷰를 통해 질문 이어가겠습니다.