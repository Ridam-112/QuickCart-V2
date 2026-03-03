# QuickCart
Quick commerece webapp<br>
app
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
    <style> @import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone .ellipse {
  position: absolute;
  top: 600px;
  left: -150px;
  width: 350px;
  height: 350px;
  background-color: #e1f5fe;
  border-radius: 175px;
  filter: blur(7.5px);
}

.iphone .div {
  position: absolute;
  top: -50px;
  left: 200px;
  width: 272px;
  height: 284px;
  background-color: #f3e5f5;
  border-radius: 136px/142px;
  filter: blur(7.5px);
  opacity: 0.9;
}

.iphone .ellipse-2 {
  position: absolute;
  top: -100px;
  left: -100px;
  width: 300px;
  height: 300px;
  background-color: #e8f5e9;
  border-radius: 150px;
  filter: blur(7.5px);
  opacity: 0.77;
}

.iphone .v {
  position: absolute;
  top: 489px;
  left: 235px;
  width: 167px;
  height: 208px;
}

.iphone .ellipse-3 {
  position: absolute;
  top: 10px;
  left: calc(50% + 141px);
  width: 40px;
  height: 40px;
  background-color: #4991ef;
  border-radius: 20px;
  box-shadow: 0px 4px 4px #0000001a;
}

.iphone .img {
  position: absolute;
  top: 13px;
  left: 345px;
  width: 33px;
  height: 33px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 70px;
  left: 35px;
  width: 314px;
  height: 44px;
  background-color: #ffffff;
  border-radius: 24px;
  border: 1px solid;
  border-color: #eeeeee66;
  box-shadow: 0px 2px 4px #0000000d;
  opacity: 0.9;
}

.iphone .element {
  position: absolute;
  top: 86px;
  left: 53px;
  width: 12px;
  height: 12px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 84px;
  left: calc(50% - 81px);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .group {
  position: absolute;
  top: 124px;
  left: 16px;
  width: 370px;
  height: 60px;
  display: flex;
  gap: 8px;
}

.iphone .rectangle-2 {
  width: 118px;
  height: 60px;
  background-color: #ffffffe6;
  border-radius: 12px;
  border: 1px solid;
  border-color: #eeeeee;
  box-shadow: 0px 2px 4px #0000000d;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 160px;
  left: 186px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 142px;
  left: 171px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .group-2 {
  position: absolute;
  top: 142px;
  left: 35px;
  width: 76px;
  height: 33px;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 18px;
  left: 14px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 0;
  left: 19px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .element-2 {
  top: 22px;
  left: 0;
  position: absolute;
  width: 8px;
  height: 8px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone .element-3 {
  top: 164px;
  left: 175px;
  position: absolute;
  width: 8px;
  height: 8px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone .rectangle-3 {
  position: absolute;
  top: 200px;
  left: 16px;
  width: 229px;
  height: 175px;
  border-radius: 24px;
  background: linear-gradient(180deg, rgba(46, 125, 50, 0.4) 0%, rgba(129, 199, 132, 0.9) 100%);
}

.iphone .ellipse-4 {
  position: absolute;
  top: 210px;
  left: 29px;
  width: 30px;
  height: 30px;
  background-color: #ffffff;
  border-radius: 15px;
}

.iphone .istockphoto {
  position: absolute;
  top: 208px;
  left: 27px;
  width: 33px;
  height: 33px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 254px;
  left: 63px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .veg-fruit {
  position: absolute;
  top: 280px;
  left: 86px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #ffffff;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .group-3 {
  position: absolute;
  top: 311px;
  left: 53px;
  width: 156px;
  height: 23px;
}

.iphone .rectangle-4 {
  position: absolute;
  top: 0;
  left: 0;
  width: 143px;
  height: 23px;
  background-color: #caffd8;
  border-radius: 14px;
}

.iphone .text-wrapper-7 {
  position: absolute;
  top: 2px;
  left: 14px;
  width: 140px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #008106;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-5 {
  position: absolute;
  top: 392px;
  left: 16px;
  width: 179px;
  height: 84px;
  border-radius: 12px;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(243, 229, 245, 1) 0%, rgba(225, 190, 231, 1) 100%);
  opacity: 0.9;
}

.iphone .text-wrapper-8 {
  position: absolute;
  top: 412px;
  left: 80px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .apparel-style {
  position: absolute;
  top: 435px;
  left: 80px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-9 {
  top: 407px;
  left: 28px;
  width: 50px;
  font-size: 48px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-6 {
  position: absolute;
  top: 392px;
  left: 207px;
  width: 189px;
  height: 84px;
  border-radius: 12px;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(252, 228, 236, 1) 0%, rgba(248, 187, 208, 1) 100%);
  opacity: 0.9;
}

.iphone .text-wrapper-10 {
  position: absolute;
  top: 413px;
  left: 268px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-7 {
  position: absolute;
  top: 200px;
  left: 257px;
  width: 139px;
  height: 83px;
  border-radius: 12px;
  border: 1px solid;
  border-color: #ffd7be;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(255, 245, 240, 1) 0%, rgba(255, 224, 209, 1) 100%);
  opacity: 0.9;
}

.iphone .rectangle-8 {
  position: absolute;
  top: 292px;
  left: 257px;
  width: 139px;
  height: 83px;
  border-radius: 12px;
  border: 1px solid;
  border-color: #d1dfff;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(240, 244, 255, 1) 0%, rgba(230, 238, 255, 1) 100%);
  opacity: 0.9;
}

.iphone .PHARMACY-medicines {
  position: absolute;
  top: 318px;
  left: 278px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .span {
  font-weight: 700;
}

.iphone .text-wrapper-11 {
  font-family: "Inter-Regular", Helvetica;
  font-size: 10px;
}

.iphone .text-wrapper-12 {
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  font-size: 10px;
}

.iphone .rectangle-9 {
  position: absolute;
  top: 488px;
  left: 16px;
  width: 179px;
  height: 84px;
  border-radius: 12px;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(236, 239, 241, 1) 0%, rgba(239, 216, 220, 1) 100%);
  opacity: 0.9;
}

.iphone .rectangle-10 {
  position: absolute;
  top: 488px;
  left: 207px;
  width: 189px;
  height: 84px;
  border-radius: 12px;
  box-shadow: 0px 1px 2px #0000000d;
  backdrop-filter: blur(6px) brightness(100%);
  -webkit-backdrop-filter: blur(6px) brightness(100%);
  background: linear-gradient(180deg, rgba(224, 242, 241, 1) 0%, rgba(178, 223, 219, 1) 100%);
  opacity: 0.9;
}

.iphone .RESTAURANTS-food {
  position: absolute;
  top: 226px;
  left: 268px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-13 {
  font-weight: 500;
}

.iphone .text-wrapper-14 {
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
}

.iphone .text-wrapper-15 {
  font-weight: 500;
  font-size: 10px;
}

.iphone .text-wrapper-16 {
  top: 408px;
  left: 215px;
  width: 50px;
  font-size: 48px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-17 {
  top: 500px;
  left: 220px;
  width: 50px;
  font-size: 48px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .beauty-care {
  position: absolute;
  top: 435px;
  left: 268px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-18 {
  position: absolute;
  top: 511px;
  left: 278px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .group-4 {
  position: absolute;
  top: 503px;
  left: 28px;
  width: 136px;
  height: 60px;
}

.iphone .text-wrapper-19 {
  top: 0;
  left: 0;
  width: 50px;
  font-size: 48px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-20 {
  position: absolute;
  top: 0;
  left: 52px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .electronics {
  position: absolute;
  top: 20px;
  left: 52px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .home-decor-comfort {
  position: absolute;
  top: 530px;
  left: 278px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-21 {
  position: absolute;
  top: 590px;
  left: 16px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-11 {
  position: absolute;
  top: 628px;
  left: 16px;
  width: 112px;
  height: 135px;
  background-color: #d9d9d9;
}

.iphone .rectangle-12 {
  position: absolute;
  top: 629px;
  left: 149px;
  width: 112px;
  height: 135px;
  background-color: #d9d9d9;
}

.iphone .rectangle-13 {
  position: absolute;
  top: 629px;
  left: 283px;
  width: 112px;
  height: 135px;
  background-color: #d9d9d9;
}

.iphone .view-all {
  position: absolute;
  top: 593px;
  left: 331px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #6a6a6a;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .location-on {
  position: absolute;
  top: 20px;
  left: 16px;
  width: 24px;
  height: 24px;
  aspect-ratio: 1;
}

.iphone .home-chattrapally {
  position: absolute;
  top: 23px;
  left: 44px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-22 {
  font-weight: 800;
}

.iphone .text-wrapper-23 {
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
}

.iphone .text-wrapper-24 {
  top: 22px;
  left: 260px;
  width: 17px;
  transform: rotate(90deg);
  font-size: 20px;
  position: absolute;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .group-5 {
  position: absolute;
  top: 142px;
  left: 294px;
  width: 68px;
  height: 33px;
}

.iphone .text-wrapper-25 {
  position: absolute;
  top: 18px;
  left: 12px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-26 {
  position: absolute;
  top: 0;
  left: 1px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .element-4 {
  top: 21px;
  left: 0;
  position: absolute;
  width: 8px;
  height: 8px;
  aspect-ratio: 1;
  object-fit: cover;
}

</style>
  </head>
  <body>
    <div class="iphone">
      <div class="ellipse"></div>
      <div class="div"></div>
      <div class="ellipse-2"></div>
      <img class="v" src="img/v.svg" />
      <div class="ellipse-3"></div>
      <img class="img" src="img/11cdc1fd54af631ed5282f7605dfbc7e-1.png" />
      <div class="rectangle"></div>
      <img class="element" src="img/2989907-1.png" />
      <p class="text-wrapper">search for groceries , food...</p>
      <div class="group">
        <div class="rectangle-2"></div>
        <div class="rectangle-2"></div>
        <div class="rectangle-2"></div>
      </div>
      <div class="text-wrapper-2">2 hrs</div>
      <div class="text-wrapper-3">🚀Express</div>
      <div class="group-2">
        <div class="text-wrapper-4">10-20mint</div>
        <div class="text-wrapper-5">⚡Flash</div>
        <img class="element-2" src="img/109613-1.png" />
      </div>
      <img class="element-3" src="img/109613-2.png" />
      <div class="rectangle-3"></div>
      <div class="ellipse-4"></div>
      <img class="istockphoto" src="img/istockphoto-1389823033-612x612-removebg-preview-removebg-preview-1.png" />
      <div class="text-wrapper-6">KRISHAK DIRECT</div>
      <div class="veg-fruit">🥬 Veg&nbsp;&nbsp;&amp; Fruit</div>
      <div class="group-3">
        <div class="rectangle-4"></div>
        <div class="text-wrapper-7">Fresh From Farmers</div>
      </div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-8">GARMENTS</div>
      <div class="apparel-style">Apparel &amp; style</div>
      <div class="text-wrapper-9">👗</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-10">COSMETICS</div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <p class="PHARMACY-medicines">
        <span class="span">💊PHARMACY<br /></span>
        <span class="text-wrapper-11">&nbsp;&nbsp;</span>
        <span class="text-wrapper-12"> medicines &amp;  &nbsp;&nbsp; wellness</span>
      </p>
      <div class="rectangle-9"></div>
      <div class="rectangle-10"></div>
      <p class="RESTAURANTS-food">
        <span class="text-wrapper-13">🍔</span>
        <span class="text-wrapper-14">RESTAURANTS<br /></span>
        <span class="text-wrapper-15">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🍕 Food &amp; Deals</span>
      </p>
      <div class="text-wrapper-16">💄</div>
      <div class="text-wrapper-17">🛋️</div>
      <div class="beauty-care">Beauty &amp; Care</div>
      <div class="text-wrapper-18">FURNITURE</div>
      <div class="group-4">
        <div class="text-wrapper-19">📱</div>
        <div class="text-wrapper-20">GADGETS</div>
        <div class="electronics">Electronics &amp; <br />accessories</div>
      </div>
      <div class="home-decor-comfort">Home Decor &amp; <br />Comfort</div>
      <div class="text-wrapper-21">TRENDING DEALS</div>
      <div class="rectangle-11"></div>
      <div class="rectangle-12"></div>
      <div class="rectangle-13"></div>
      <div class="view-all">view all&nbsp;&nbsp;&gt;</div>
      <img class="location-on" src="img/location-on.svg" />
      <p class="home-chattrapally">
        <span class="text-wrapper-22">Home - </span> <span class="text-wrapper-23">Chattrapally Club, Blg...</span>
      </p>
      <div class="text-wrapper-24">&gt;</div>
      <div class="group-5">
        <div class="text-wrapper-25">2-3days</div>
        <div class="text-wrapper-26">🚚standard</div>
        <img class="element-4" src="img/109613-3.png" />
      </div>
      <img class="v" src="img/image.svg" />
    </div>
  </body>
</html>

