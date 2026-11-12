PIZZARIA - VS Code 프로젝트

1. pizzaria-vscode 폴더를 VS Code에서 엽니다.
2. index.html을 열고 Live Server로 실행합니다. (Live Server가 없다면 확장 프로그램에서 설치)
3. 상단 메뉴에서 홈 / 메뉴 / 가게 소개 / 오시는 길 / 예약·문의를 이동할 수 있습니다.

폴더 구성
- index.html, menu.html, about.html, location.html, contact.html : 5개 페이지
- css/common.css : 공통 색상, 글꼴, 헤더, 내비게이션, 버튼, 카드, 푸터
- css/home.css, menu.css, about.css, location.css, contact.css : 페이지별 디자인
- images/ : 직접 저장한 이미지 파일을 넣는 폴더

과제 조건 관련
- HTML과 CSS만 사용했습니다. JavaScript와 script 태그는 없습니다.
- 모바일 메뉴는 checkbox + CSS로 펼쳐지는 방식입니다.
- 커스텀 피자는 CSS :has() 선택자로 도우/토핑 미리보기를 구현했습니다.
- CSS만으로는 선택된 토핑 가격을 합산하거나 결제/예약 내용을 서버로 전송할 수 없습니다. 따라서 합계 계산 및 실제 결제/접수는 시연용 안내로 표시했습니다.
- 지점, 주소, 전화번호, 브랜드 창설 연도, 영업시간, 메뉴 가격은 과제용 가상 예시입니다. 실제 정보처럼 제출하지 말고 필요하면 수정하세요.
- 사진은 Unsplash의 원격 이미지 주소를 사용했습니다. 오프라인 발표라면 이미지 파일을 내려받아 images 폴더에 저장한 뒤 HTML의 src를 images/파일명.jpg로 바꾸세요.
