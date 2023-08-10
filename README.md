- 👋 Hi, I’m @bonzarbty13
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
bonzarbty13/bonzarbty13 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<!--Google Search-->
index.html

<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Google</title>
  <link rel="stylesheet" type="text/css" href="style.css" media="screen"/>
</head>

<body background="" width="900"></body>
<header>
    <nav>
      <ul id="nav_bar">
      <li class="nav-links" id="Gmail"></li>
        <a href="https://mail.google.com"> Gmail </a>
      <li class="nav-links"></li>
        <a href="https://sites.google.com/view/worldphotoworkshop/home"> Images </a>
        <li id="Sign_in"></li>
        <a href="https://myaccount.google.com"> Sign in </a>
      </ul>
      </nav>
  </header>
  <!-- Google IMG -->
  <div class="Google">
  <a href="" id="Google_logo"> <img src="https://www.google.com/logos/doodles/2015/googles-new-logo-5078286822539264.3-hp2x.gif" alt="wait image is loading"
  
  </a>
  </div>
  <!-- FORM SEARCH -->
  
  <div class="form">
  <form id="frmsearch" method="GET"></form>
  <input type="text" id="txtsearch" placeholder="type for search"/>
  </div>
  <!-- BUTTONS -->
  <div class="buttons">
  <input type="Submit" value="Google Search" id="google_search">
  <input type="Submit" value="I'm feeling lucky" id="im_feeling_lucky"><br><br>
    <a href="https://en.wikipedia.org/wiki/Boro_people.html">Bodo</a><br>
 <a href="https://en.wikipedia.org/wiki/Assamese_language.html">Assamese</a><br>
 <a href="https://en.wikipedia.org/wiki/English_language.html">English</a><br>
  </div>
  
  <script type="text/javascript"> document.getElementById('frmSearch').onsubmit = function() { window.location = 'https://www.google.com/search?q=' + document.getElementById(' txtSearch').value;return false;} </script>
  <!-- FOOTER -->
  
<footer>
  <ul class="footer-left">
  <li>
    <a href="https://ads.google.com">Advertising</a>
  </li>
    <li>
    <a href="">Business</a>
  </li>
    <li>
      <a href="">About us</a>
    </li>
  </ul>
  
  <ul class="footer-right">
    <li>
      <a href="">Privacy</a>
    </li>
    <li>
      <a href="">Terms</a>
    </li>
    <li>
      <a href="">setting</a>
    </li>
  </ul>
  
</footer>
</body>

</html>


<!--Google Search-->
Style.css

body{
  margin: 0;
  padding: 0;
  font-family: 'Robot' , sans-serif;
}
header{
  width: 100%;
  
}
ul{
  list-style: none;
  
}
#nav_bar{
  float: right;
}
#nav_bar li{
  display: inline-block;
  padding: 6px;
}
#nav_bar #sign_in{
  background: #4887ef;
  margin-right: 25px;
  padding: 7px 15px;
  border-radius: 3px;
  font-weight: bold;
  
}
a{
  text-decoration: none;
  color: inherit;
}
li.nav-links a:hover{
  text-decoration: underline;
  
}
#Sign_in:hover{
  box-shadow: 1px 1px 5px #999;
}
#Sign_in{
  color: #fff;
}

.google #google_logo{
  text-align: center;
  display: block;
  margin: 0 auto;
  clear: both;
  padding-top: 112px;
  padding-bottom: 20px;
}
.form{
  text-align: center;
}
#textsearch{
  width: 250px;
  line-height: 32px;
  padding: 20px 10px;
}
.form #textsearch{
  padding: 0 8px;
}
#textsearch:hover{
  border-color: #e4e4e4;
  padding-top: 0;
}
.buttons{
  text-align: center;
  padding-top: 30px;
  margin-bottom: 300px;
}
footer{
  background: #f2f2f2;
  border-top: solid 2px #e4e4e4;
  position: fixed;
  bottom: 0;
  padding-bottom: 0;
  width: 100%;
}
footer ul li{
  display: inline;
  color: #666666;
  font-size: 14px;
  padding: 13px;
  
}
footer ul{
  float: left;
  padding: 1px;
 
}
footer ul a:hover{
  text-decoration: underline;
}
.footer-right{
  float: right;
}
