# reference.html
<!DOCTYPE html>

<html>

  <head>

    <title>근로신청안내</title>

    <meta charset="utf-8">

    <meta name="author" content="조">

    <meta name="description" content="">

    <meta name="keywords" content="시간표">

    <link type="text/css" rel="stylesheet" href="css/recommend.css">

    <link href="https://fonts.googleapis.com/css?family=Do+Hyeon" rel="stylesheet">

    <script src="js/recommend.js">

    </script>

  </head>

  <body>

    <div class="menubar">

      <ul>

        <li><a href="main.html">홈</a></li>

        <li><a href="recommend.html"></a></li>

        <li><a href="region.html"></a></li>

        <li><a href="#"></a></li>

      </ul>

    </div>

    <div class="submenu">

      <ul>

        <li id="recommend_head"></li>

        <li onclick="season_click()"><a href="#"></a></li>

        <li onclick="price_click()"><a href="#"></a></li>

        <li onclick="food_click()"><a href="#"></a></li>

      </ul>

    </div>

    <div id="content_season">

      <h3>계절 선택</h3>

      <p>계절을 선택하고 찾기를 누르면 계절에 따른 시간표.</p>

      <form>

        <input type="radio" name="season" value="1" checked> 봄

        <input type="radio" name="season" value="2">여름

        <input type="radio" name="season" value="3">가을

        <input type="radio" name="season" value="4">겨울

        &nbsp;

        <input type="button" class="season_button" value="찾기">

      </form>

    </div>

    <div id="content_price">

      <h3>가격대별 선택</h3>

      <p>근로소득</p>

      <form>

        <input type="radio" name="price" value="1" checked> 원 이하

        <input type="radio" name="price" value="2"> 원 ~ 원

        <input type="radio" name="price" value="3">원 ~ 원

        <input type="radio" name="price" value="4">  이상

        &nbsp;

        <input type="button" class="price_button" value="찾기">

      </form>

    </div>

    <div id="content_food">

      <h3></h3>

      <p>.</p>

      <form>

        <input type="radio" name="food" value="1" checked> 

        <input type="radio" name="food" value="2"> 

        <input type="radio" name="food" value="3">

        &nbsp;

        <input type="button" class="food_button" value="찾기">

      </form>

    </div>

  </body>

</html>

