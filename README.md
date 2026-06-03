# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
PAGE---1
index.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bg" src="img/bg-1.png" />
      <div class="rectangle"></div>
      <img class="sec-logo" src="img/sec-logo-1.png" />
      <img class="secc" src="img/secc-1.png" />
      <div class="rounded-rectangle"></div>
      <div class="text-wrapper">E-SPORTS DAY EVENT</div>
      <div class="div">REGISTER</div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="DESIGNED-BY">
        DESIGNED BY YAZHINI<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(25017581)
      </div>
    </div>
  </body>
</html>

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 1106px;
  position: relative;
}

.android-medium .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 1106px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 624px;
  left: 174px;
  width: 360px;
  height: 88px;
  background-color: #18aa33;
  border-radius: 10px;
}

.android-medium .sec-logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 142px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .secc {
  position: absolute;
  top: 142px;
  left: 264px;
  width: 172px;
  height: 172px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .rounded-rectangle {
  position: absolute;
  top: 502px;
  left: 174px;
  width: 360px;
  height: 88px;
  background-color: #18aa33;
  border-radius: 10px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 369px;
  left: 152px;
  width: 461px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #15ffe3;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 644px;
  left: calc(50.00% - 92px);
  width: 355px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #9b1111;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 518px;
  left: 288px;
  width: 380px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #991717;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .DESIGNED-BY {
  position: absolute;
  top: 998px;
  left: 112px;
  width: 553px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
```
PAGE---2
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bg" src="img/bg-2.png" />
      <div class="text-wrapper">E-SPORTS DAY EVENT</div>
      <img class="polygon" src="img/polygon-1.svg" />
      <img class="polygon" src="img/polygon-2.svg" />
      <img class="img" src="img/polygon-3.svg" />
      <img class="polygon-2" src="img/polygon-4.svg" />
      <img class="polygon-3" src="img/polygon-5.svg" />
      <img class="polygon-4" src="img/polygon-6.svg" />
      <div class="div">FREE FIRE</div>
      <div class="text-wrapper-2">PUBG</div>
      <div class="text-wrapper-3">AMONG US</div>
      <div class="text-wrapper-4">CALL OF DUTY</div>
      <div class="text-wrapper-5">FORTNITE</div>
      <div class="DESIGNED-BY">
        DESIGNED BY YAZHINI<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(25017581)
      </div>
    </div>
  </body>
</html>

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 1106px;
  position: relative;
}

.android-medium .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 1106px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 85px;
  left: 117px;
  width: 465px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #2d49b7;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .polygon {
  position: absolute;
  top: 311px;
  left: 106px;
  width: 40px;
  height: 38px;
}

.android-medium .img {
  top: 739px;
  left: 106px;
  position: absolute;
  width: 40px;
  height: 38px;
}

.android-medium .polygon-2 {
  top: 627px;
  left: 109px;
  position: absolute;
  width: 40px;
  height: 38px;
}

.android-medium .polygon-3 {
  top: 515px;
  left: 106px;
  position: absolute;
  width: 40px;
  height: 38px;
}

.android-medium .polygon-4 {
  top: 413px;
  left: 106px;
  position: absolute;
  width: 40px;
  height: 38px;
}

.android-medium .div {
  position: absolute;
  top: 302px;
  left: 179px;
  width: 403px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f2094f;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 410px;
  left: 179px;
  width: 309px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f1070b;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 514px;
  left: 179px;
  width: 320px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #fc0b0f;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 627px;
  left: 176px;
  width: 346px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f11216;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 736px;
  left: 176px;
  width: 387px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ef090d;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .DESIGNED-BY {
  position: absolute;
  top: 998px;
  left: 112px;
  width: 553px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
```
PAGE---3
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bg" src="img/bg-3.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <img class="img" src="img/rectangle-8.svg" />
      <div class="rectangle-4"></div>
      <div class="NAME">NAME:</div>
      <div class="text-wrapper">REG.NO:</div>
      <div class="text-wrapper-2">BRANCH:</div>
      <div class="text-wrapper-3">MOBILE:</div>
      <div class="text-wrapper-4">EMAIL:</div>
      <div class="DEVICE-TYPE">
        DEVICE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;TYPE:
      </div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-5">GIVE THE DETAILS</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">REGISTER</div>
      <div class="DESIGNED-BY">
        DESIGNED BY YAZHINI<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(25017581)
      </div>
    </div>
  </body>
</html>

style.css

.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 700px;
  min-height: 1106px;
  position: relative;
}

.android-medium .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 1106px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 219px;
  left: 195px;
  width: 416px;
  height: 68px;
  background-color: #d9d9d9;
}

.android-medium .div {
  position: absolute;
  top: 321px;
  left: 195px;
  width: 416px;
  height: 70px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 737px;
  left: 195px;
  width: 413px;
  height: 70px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 633px;
  left: 195px;
  width: 416px;
  height: 70px;
  background-color: #d9d9d9;
}

.android-medium .img {
  position: absolute;
  top: 529px;
  left: 192px;
  width: 416px;
  height: 70px;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 425px;
  left: 195px;
  width: 416px;
  height: 70px;
  background-color: #d9d9d9;
}

.android-medium .NAME {
  position: absolute;
  top: 234px;
  left: 59px;
  width: 163px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 341px;
  left: 39px;
  width: 157px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 438px;
  left: 32px;
  width: 172px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 553px;
  left: 39px;
  width: 165px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #262222;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 649px;
  left: 59px;
  width: 192px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #201d1d;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .DEVICE-TYPE {
  position: absolute;
  top: 737px;
  left: 39px;
  width: 191px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #201b1b;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 52px;
  left: 85px;
  width: 526px;
  height: 87px;
  background-color: #ef1111;
  border-radius: 20px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 80px;
  left: 192px;
  width: 556px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 904px;
  left: 196px;
  width: 321px;
  height: 70px;
  background-color: #18aa33;
  border-radius: 40px;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 915px;
  left: 271px;
  width: 429px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #841313;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .DESIGNED-BY {
  position: absolute;
  top: 998px;
  left: 112px;
  width: 553px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
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
```
## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
