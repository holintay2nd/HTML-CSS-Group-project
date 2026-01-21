1. 메인(index)페이지를 만드는 개발자가 header와 footer 부분의 html/css를 책임진다.
2. 로그인과 회원가입 등의 부분은 header와 footer의 html/css를 사용하지 않는다.
3. header와 footer를 사용하여 다른 page를 개발하시는 분들은 index.html의 html을 clone(복사)하고, css/index 아래의 header와 footer를 링크한다.
(예를들어 parchase 파일에서 header와 footer를 쓸 때 html부분을 복사하고 <link rel="stylesheet" href="./css/index/header.css">
    <link rel="stylesheet" href="./css/index/footer.css"> head태그 안에 정의한다.
4. 부트스트랩은 최신의 버전을 쓰기 때문에 각자의 부트스트랩 사이트에서 제공되는 최신 버전을 지향한다. (cdn버전 사용필수)
5. 모든 페이지 이동은 index.html의 a 태그를 통해서만 이루어진다.
   (직접 URL 입력, 임의 링크 금지) 예: <a href="parchase.html">구매 페이지</a>
