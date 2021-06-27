# Front-End
Web Page
//HTML

<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie-edge">
    <meta name="robots" content="index">
    <meta name="robots" content="follow">
    <meta name="author" content="Narek Svazyan">
    <title>Armenia home electronics</title>
    <link rel="icon" href="img/home-electronics-logo.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="css/media.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
<body onload="startTime()">
    <header>
      <div id="div1"></div>
    <div class="icondiv">
    <a href="https://facebook.com" class="f"><i class="fa fa-facebook"></i></a>
     <a href="https://twitter.com" class="t"><i class="fa fa-twitter"></i></a>
     <a href="https://instagram.com" class="ins"><i class="fa fa-instagram"></i></a>
      </div>

      <section class="section_name"><h1>Armenia home electronics</h1></section>
           <nav class="dws-menu">
            <input type="checkbox" name="toggle" id="menu" class="toggleMenu">
            <label for="menu" class="toggleMenu"><i class="fa fa-bars"></i>Меню</label>
            <ul>
               <li><a href="#section-reg"><i class="fa fa-home"></i>Գլխավոր էջ</a></li>
               <li><a href="#"><i class="fa fa-shopping-cart"></i>Ապրանքներ</a>
                 <ul>
                   <li><a href="#">Մսաղացներ</a></li>
                   <li><a href="#">Միքսերներ</a>
                    <ul>
                      <li><a href="#">Միքսերներ</a></li>
                    </ul></li>
                   <li><a href="#">Մազերի արդուկներ</a></li>
                   <li><a href="#">Արդուկներ</a></li>
                 </ul>
                </li>
               <li><a href="#"><i class="fa fa-cogs"></i>Ծառայություններ</a></li>
               <li><a href="#"><i class="fa fa-th-list"></i>Նորություններ</a></li>
               <li><a href="#"><i class="fa fa-envelope-open"></i>Կապնվել մեզ հետ</a></li>
            </ul>
        </nav>

        <section class="hsection">
      <ul>

        <li><a href="#">sign up</a></li>
        <li><a href="#">sign in</a></li>
      </ul>



           <div class="carts">
            <span class="ss">Корзина</span>
            <span class="cart-s" id="cart-s">0</span>
        </div>
      </section>
      </header>
 <section class="section1">
   <img src="img/miqs.png">
   <h3>Միքսեր HAEGER</h3>
   <div  class="price-tn">
   <span id="price">500$</span>
 </div>
   <div class="sub-but">
   <input type="button" name="button" value="+" class="button1"  data-id="prod">
   <input type="button" name="button" value="-" class="button2"  data-id="prod">
     </div>
 </section>

  <section class="section1">
   <img src="img/img_0_316_144_0.jpg">
       <h3>Մսախաց BOSH</h3>
   <div  class="price-tn">
   <span id="price">500$</span>
 </div>
 <div class="sub-but">
   <input type="button" name="button1" value="+" class="button1" data-id="prod1">
   <input type="button" name="button1" value="-" class="button2" data-id="prod1">
 </div>
 </section>
  <section class="section1">
   <img src="img/img_x500_603e05cd6c4ed.jpg">
     <div  class="price-tn">
   <span id="price">500$</span>
 </div>
 <div class="sub-but">
   <input type="button" name="button2" value="+" class="button1" data-id="prod2">
   <input type="button" name="button2" value="-" class="button2" data-id="prod2">
 </div>
  </section>


  <!--<section class="section1">
   <img src="img/1538384652.jpg">
 </section>

 <section class="section1">
   <img src="img/12723137-1.jpg">
 </section>

 <section class="section1">
   <img src="img/EDENLARGEPNG.Png">
 </section>-->

    <script src="script.js"></script>
    <script type="text/javascript" src="script-cart.js"></script>

</body>
</html>

//CSS

*{
    margin: 0;
    padding: 0;
}
header{
    width: 16%;
    background-color:#08631B;
    height: 1000px;
    float: left;

}

#div1{
    height: 30px;
    font-size: 35px;
    margin-top: 10px;
    margin-left: 15px;
    color: white;
}

.hsection{
  width: 100%;
  height: 30px;
  float: left;
  margin-top: 50px;
  background-color:#08631B;
}
.hsection ul li{
    display: inline;
    margin-left: 20px;
}
.hsection a{
    text-decoration: none;
    color: white;
    text-align: justify;
    font-size: 18px;
    text-transform: uppercase;
}
.section_name {
    width: 100%;
    height: 80px;
    margin-top: 55px;
}
.section_name h1{
    color: white;
    padding-left: 10px;
    text-transform: uppercase;
    text-shadow:  0 0 10px #40ff00;
}

.dws-menu ul,
.dws-menu ol{
    list-style: none;
}
.dws-menu > ul{
    float: left;
    margin-top: 70px;
    animation: animate 5s linear infinite;
    box-shadow: 0 0 40px #40ff00;
}
.dws-menu > ul li a{
    height: 25px;
    display: block;
    background-color: #08631B;
    padding: 15px 30px 15px 40px;
    padding-top: 20px;
    font-size: 14px;
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    transition: all 0.3s ease;
    box-shadow: 1px 5px 10px -5px #40ff00;
}
/*@keyframes animate{
    0%{
        color: #0e3742;
        box-shadow: none;
    }
    100%{
        color: #fff;
        box-shadow:  0 0 10px #40ff00,
         0 0 20px #40ff00,
         0 0 40px #40ff00,
         0 0 80px #40ff00,
         0 0 120px #40ff00;
    }
}*/
.dws-menu > ul li{
    position: relative;
}
.dws-menu > ul li > a i.fa{
    position: absolute;
    top: 20px;
    left: 12px;
    font-size: 18px;
}

.dws-menu li a:hover{
    background-color: #00cc00;
    color: #ffffff;
    box-shadow: 1px 5px 10px -5px block;
    transition: all 0.3s ease;
}

/*Sub menu*/
.dws-menu li ul{
    position: absolute;
    min-width: 164px;
    display: none;
    left: 100%;
    top: 0;
}
.dws-menu li > ul li{
    border: 1px solid #c7c8ca;
}
.dws-menu li > ul li a{
    padding: 10px;
    text-transform: none;
    background-color:#08631B;
}
.dws-menu li > ul li ul{
    position: absolute;
    left: 100%;
    top: 0;
}
.dws-menu li:hover > ul{
    display: block;
}



.carts{
    width: 100%;
    height: 50px;
    margin-top: 25px;
}

.carts .ss {
    position: relative;
    padding-left: 19px;
    transition: background-color 0.3s;
    color: white;
    padding-top: 15px;
}

.cart.active:hover {
    cursor: pointer;
    background: rgba(93, 113, 221, 0.1);
    transition: background-color 0.3s;
}


.cart-s {
    position: absolute;
    transform: translateY(-50%);
    background-color: #de707b;
    border-radius: 100%;
    padding: 2px;
    color: #fff;
    font-size: 12px;
    min-height: 16px;
    min-width: 16px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
}








.section1 {
    width: 13%;
    height: 350px;
    float: left;
    margin-top: 30px;
    margin-left: 10%;
    background-color: gray;
}
.section1 img{
    width: 100%;
    height: 200px;
}
.section1 h3{
    text-align: center;
    color: white;
    padding-top: 10px;
}
.price-tn{
    color: white;
    margin-top: 10px;
    text-align: center;
}
.price-tn span{
    font-size: 25px;
}
.button1 {
    width: 50%;
    height: 20px;
    background-color: green;
    border: none;
    margin-left: 25%;
}
.button2 {
    width: 50%;
    height: 20px;
    margin-top: 5px;
    background-color: sienna;
    border: none;
    margin-left: 25%;
}

.button1:hover{
    background-color: darkgreen;
}
.button2:hover{
    background-color: darkgreen;
}

.f{
    padding-right: 10px;
    padding-left: 10px;
    padding-top: 5px;
    padding-bottom: 5px;
    border-radius: 30px;
    position: absolute;
    margin-top: 150px;
    margin-left: 90px;
    background-color: green;
}
.f:hover{
    background-color: grey;
}
.t{
    padding-right: 8px;
    padding-left: 8px;
    padding-top: 5px;
    padding-bottom: 5px;
    border-radius: 30px;
    position: absolute;
    margin-top: 150px;
    margin-left: 50px;
    background-color: green;
}
.t:hover{
    background-color: grey;
}
.ins{
    padding-right: 8px;
    padding-left: 8px;
    padding-top: 5px;
    padding-bottom: 5px;
    border-radius: 30px;
    position: absolute;
    margin-top: 150px;
    margin-left: 10px;
    background-color: green;
}
.ins:hover{
    background-color: grey;
}
.icondiv{
    margin-left: 30px;
}

//JavaScript

function startTime() {
  var today = new Date();
  var h = today.getHours();
  var m = today.getMinutes();
  var s = today.getSeconds();
  // add a zero in front of numbers<10
  m = checkTime(m);
  s = checkTime(s);
  document.getElementById("div1").innerHTML = h + ":" + m + ":" + s;
  var t = setTimeout(function(){ startTime() }, 500);
}

function checkTime(i) {
  if (i < 10) {
    i = "0" + i;
  }
  return i;
}

