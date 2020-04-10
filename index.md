<!DOCTYPE html>
<html>
<head>

	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<meta name="Author" content="">
	<meta name="Keywords" content="contrabass 콘트라베이스 더블베이스 한국아마추어콘트라베이스협회">
	<meta name="Description" content="이 페이지는 한국아마추어콘트라베이스협회 홈페이지입니다. ">
<title>AmaCB</title>

<link rel=" shortcut icon" href="./image/clef.ico">
<link rel="icon" href="./image/clef.ico">


<link rel="stylesheet" href="styler01.css">
<link rel="stylesheet" href="fontstyle.css">
<style>
body, html {
  height: 100%;
  font-family: "Inconsolata", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
  background-image: url("./image/mainimage.jpg");
  min-height: 75%;
}

.menu {
  display: none;
}
</style>
</head>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">PEOPLE</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Enjoy your life with Contrabass</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white" style="font-size:30px">한국아마추어콘트라베이스협회<br>
    Korea Amateur Contrabass Association</span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white">Only those who have played the contrabass know the charm</span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT THE ASSOCIATION</span></h5>
    <p>2016년 여기저기서 알음알음 베이스를 해오던 사람들이 우연히 함께 공연을 했습니다. 이렇게 많은 아마추어 클래식 콘트라베이시스트들을 만나보지 못했던 그들은 너무나 즐거웠습니다. 그 여운을 잊지못하고, 그들은 협회를 조성하게 되었습니다. 지금까지 협회원들은 각자의 뮤직라이프를 즐기고 있습니다. </p>
    <p>한국아마추어콘트라베이스협회는 콘트라베이스로 1회 이상 공연을 한 모두에게 열려있습니다. </p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>Dr.A한테 한마디 해달라고 했는데 아직 답이 없습니다. </i></p>
      <p>협회장 : Dr.A </p>
    </div>
    <img src="./image/instru.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
    <p><strong>Available Seasons:</strong> whenever they are free from their occupation</p>
    <!--<p><strong>Address:</strong> 15 Adr street, 5015, NY</p>-->
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">PEOPLE</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Eat');" id="myLink">
        <div class="w3-col s6 tablink">Members</div> <br>
      </a>
		<p>각 멤버의 이름을 누르면 개인페이지를 볼 수 있습니다.</p> <br>
      <!--
      <a href="javascript:void(0)" onclick="openMenu(event, 'Drinks');">
        <div class="w3-col s6 tablink">Drink</div>
      </a>
      -->

    </div>

    <div id="Eat" class="w3-container menu w3-padding-48 w3-card">
      <h5><a href="https://earlgreybutter.github.io/" title="W3.CSS" target="_blank" class="w3-hover-text-green">earlgreybutter</a></h5>
      <p class="w3-text-grey">이 페이지를 만든 애. 여기서 제일 귀여운 애.<br>백앤드 개발자로 취직하고 싶어여. 취직시켜주세여.</p><br>
    
      <h5>ㅇㅈ</h5>
      <p class="w3-text-grey">이 페이지를 만들고 있는 사람이 한번도 뵙지 못해서 할말이 없습니다. </p><br>
    
      <h5>ㅈㅁ</h5>
      <p class="w3-text-grey">1박2일 출연자</p><br>
    
      <h5>ㅅㅇ</h5>
      <p class="w3-text-grey">공돌-기계를 잘안다고 한다</p><br>
    
      <h5>ㅈㅇ</h5>
      <p class="w3-text-grey">태국어 마스터, 태국어 관련 각종 행사 경험 풍부</p>
      
      <h5>Ginny</h5>
      <p class="w3-text-grey">알라딘의 친구</p>
      
      <h5><a href="https://www.youtube.com/channel/UCHEN870Kz7p8Bn4ss8wJICQ" title="W3.CSS" target="_blank" class="w3-hover-text-green">이주한</a></h5>
      <p class="w3-text-grey">친구가 없어서 집에서 자가격리 겸 작업 가능한 시대가 부르는 뮤지션...!(+콘이 방망이 휘두르는 이모티콘)<br></p>
      
      <h5>Dr.A</h5>
      <p class="w3-text-grey">지휘가능</p>
      <h5>ㅇㅈ2</h5>
      <p class="w3-text-grey">법잘알</p>
      <h5>ㅇㄴ</h5>
      <p class="w3-text-grey">중국어 네이티브</p>
    </div>
<!--
    <div id="Drinks" class="w3-container menu w3-padding-48 w3-card">
      <h5>Coffee</h5>
      <p class="w3-text-grey">Regular coffee 2.50</p><br>
    
      <h5>Chocolato</h5>
      <p class="w3-text-grey">Chocolate espresso with milk 4.50</p><br>
    
      <h5>Corretto</h5>
      <p class="w3-text-grey">Whiskey and coffee 5.00</p><br>
    
      <h5>Iced tea</h5>
      <p class="w3-text-grey">Hot tea, except not hot 3.00</p><br>
    
      <h5>Soda</h5>
      <p class="w3-text-grey">Coke, Sprite, Fanta, etc. 2.50</p>
    </div>  
    -->
    <img src="./image/dongdong.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us in Korea.</p>
    <img src="./image/instru.jpg" class="w3-image" style="width:100%">
    <p><span class="w3-tag">모두들 반가워요!</span> 여기저기 다니면서 공연하는 것을 상당히 즐기며 모든 협회원들은 객원 경험이 풍부합니다.</p>
    <!--
    <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2017-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-black" type="submit">DO NOT SEND MESSAGE</button></p>
      -->
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
  <p>Powered by <a href="https://earlgreybutter.github.io/" title="W3.CSS" target="_blank" class="w3-hover-text-green">earlgreybutter</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
