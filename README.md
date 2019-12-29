<html>
  <head> <!--홈페이지에 대한 정보-->
    <title>두드림퀵 홈페이지</title>
    <meta charset="utf-8"> <!--글씨 안 깨지도록-->
    <link href="style.css" rel="stylesheet" 
    type="text/css"/>
    <!--어떤 파일을 불러오는 것. type은 그게 무슨 파일인지를 소개.-->
    <meta name ="description" content="노인지하철택배">
    <!--이 웹사이트가 어떤 정보를 담고 있는지. 사이트 소개-->
  </head>
  <body>
    <!--텍스트 관련 태그들-->
    <h1>두드림퀵 하이</h1>
    <h2>두드림퀵 하이</h2>
    <!--h1부터 h6까지 있는데 이게 다 글씨 크기 관련된 것-->
    <b>굵은 글씨</b1>
    <i>기울은 글씨</i>
    <h1><b1><i>셋 다 되나? 오 되네</i></bi></h1>
    <p>문단(본문)</p>

    <!--링크 태그-->
    <a href="https://dodreamquick.com/policy/use">이용약관</a>
    <!--a href는 링크를 누르면 어디로 갈 것인지. 뒤에 오는 글자는 그걸 뭘로 네이밍할 것인지.-->
    <a href="https://dodreamquick.com/policy/personal_information" target="_blank">개인정보 처리 방침</a>
    <!--target은 창을 새로 띄워서 가라는 소리-->
    
    <!--테이블 태그-->
    <table border="1">
      <thead>
        <tr>
          <th>이름</th>
          <th>나이</th>
      </thead>
      <!--head는 테이블에 칼럼이 몇 개 있고 그 칼럼의 이름은 뭔지-->
      <tbody>
        <tr>
          <td>해민</td>
          <td>21살</td>
        </tr>
      </tbody>

    <!--목록 태그. ol은 ordered list(숫자대로 나열) ul은 unordered. 그냥 불렛포인트-->
    <ol> 
      <li>두드</li>
      <li>림퀵</li>
    </ol>
    <ul>
      <li>안녕</li>
      <li>잘가</li>

    <!--구역을 나누는 태그.div는 그냥 문서 여러 구역으로 나눌 때. -->
    <style>
    .top {
      background : #1A8F74;
      height : 100px;
    }
    .mid {
      background : #FFFFFF;
      height : 100px;
    }
    .bot {
      background : #1A8F74;
      height : 100px;
    }
    </style>
    <div class="top">두드림퀵 소개</div>
    <div class="mid">특별한 서비스 두드림퀵</div>
    <div class="bot">(주)두드림퀵 사업자 정보</div>
    <!--div는 한 줄 전체 공간을 차지 span은 자기 내용물만큼만 공간 차지-->
    <span class="like">질문</span>
    <div class="mid">주문 폼 <p></p>
    <!--인풋(유저한테 정보를 받아야 할 때) 태그-->
    물건 종류 <input type="text" /> <br>
    물건이 5kg 미만인가요? 예<input type="checkbox" /> <br> 
    물건이 케이크가 아닌가요? 예<input type="radio" /> <br> 
    색깔 <input type="color" /> <br> 
    <!--여러 문장-->
    추가요청사항 <textarea> </textarea>
    <!--드랍다운-->
    지역 <select name="name">
      <option value="강남">강남</option>
      <option value="강북">강북</option>
    </select>
    </div>
    <div class="mid">로그인
      <input type="email" placeholder="이메일" />
      <input type="password" placeholder="비밀번호" />
      <button type="submit">로그인</button>
    </div>
  </body>
</html>
