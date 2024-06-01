BE-master branch readme

1. news.html에서 검색창에 키워드를 검색하면, 해당 관련된 네이버 오픈 뉴스 api를 통해 기사 정보를 반환하는 기능을 구현하려 했음. 이하는 작동 순서를 기술함.
2. News.html과 spring을 연결함
3. News.html에서 검색 키워드를 넣으면 spring으로 연결됨.
4. 이때, news.html에서 spring에서 호출 받은 api 값을 json으로 웹에 출력하게 함. 이때 서버에서 요청되는 동안 잘못된 값이 들어가지 않도록 옵셔널체이닝 연산자를 사용함.
5. spring에서 fetch link 값을  GetMapping에 연동함.
6. 이하 NewsApiController, NewsService, NewsClient, NewsResponseDto 를 통해 오픈 api 값을 NewsResponsDto 객체로 반환하려 했음.
7. 다만 이 과정에서 실행시킬 때, 500 Internal Sever error가 발생함. 원인을 해결하려 했으나 시간 내에 찾기 실패함.


BE
1. SNS 연동을 통한 로그인 서비스를 구현 시도를 함.
2. 시간 부족으로 해당 내 오류를 찾지 못하여 실패함,

----------------------------------------

 FE
1. 수월한 spring 연동을 위해 html로 메인 페이지 및 news.html을 작성함.
