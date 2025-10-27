# Ex09 Event Registration Web Application
## Date:16-10-2025

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

### Step 7:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
HOME PAGE

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
    <div class="iphone-pro-max">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="REGISTER"><div class="text-wrapper">REGISTER</div></div>
      <div class="div"></div>
      <div class="LOGIN">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LOGIN</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-08-at-13-29-02-1.png" />
      <div class="DESIGNED-BY-MUZAMMIL">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DESIGNED BY MUZAMMIL.T</div>
    </div>
  </body>
</html>

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

style.css

.iphone-pro-max {
  background-color: #f9f506;
  width: 100%;
  min-width: 653px;
  min-height: 1050px;
  position: relative;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 383px;
  left: 147px;
  width: 274px;
  height: 92px;
}

.iphone-pro-max .rectangle {
  top: 264px;
  height: 86px;
  background-color: #ff1616;
  position: absolute;
  left: 169px;
  width: 353px;
}

.iphone-pro-max .REGISTER {
  position: absolute;
  top: 286px;
  left: 252px;
  width: 342px;
  height: 56px;
  display: flex;
}

.iphone-pro-max .text-wrapper {
  margin-left: 3.42%;
  width: 342px;
  margin-right: -3.42%;
  flex: 1;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #111010;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  top: 383px;
  height: 83px;
  background-color: #fc0808;
  position: absolute;
  left: 169px;
  width: 353px;
}

.iphone-pro-max .LOGIN {
  position: absolute;
  top: 405px;
  left: 231px;
  width: 230px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #171515;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 521px;
  left: 15px;
  width: 623px;
  height: 415px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone-pro-max .DESIGNED-BY-muzammil {
  position: absolute;
  top: 969px;
  left: 61px;
  width: 546px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}



PAGE 2

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
    <div class="iphone">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">DESIGNED BY KARTHIK.A</div>
      <div class="div">THANK YOU.</div>
    </div>
  </body>
</html>

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

style.css

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 534px;
  min-height: 863px;
  position: relative;
}

.iphone .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 534px;
  height: 863px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 25px;
  left: 100px;
  width: 510px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #e71212;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .batminton {
  position: absolute;
  top: 97px;
  left: 100px;
  width: 355px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .span {
  font-family: "Inter-BlackItalic", Helvetica;
  font-style: italic;
}

.iphone .text-wrapper-2 {
  font-family: "Inter-BlackItalic", Helvetica;
  font-style: italic;
  font-size: 24px;
}

.iphone .volleyball {
  position: absolute;
  top: 137px;
  left: 100px;
  width: 261px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .baseketball {
  position: absolute;
  top: 176px;
  left: 100px;
  width: 245px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .cricket {
  position: absolute;
  top: 213px;
  left: 100px;
  width: 210px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .football {
  position: absolute;
  top: 253px;
  left: 100px;
  width: 232px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .element-m {
  position: absolute;
  top: 294px;
  left: 102px;
  width: 188px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .tennis {
  position: absolute;
  top: 335px;
  left: 102px;
  width: 261px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 802px;
  left: 123px;
  width: 374px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #f8f9f0;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}


PAGE 3


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
    <div class="iphone-pro-max">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">EVENT REGISTERATION FORM</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Register</div>
      <div class="rectangle-2"></div>
      <p class="full-name"><span class="span"> ✰</span> <span class="text-wrapper-3"> Full Name</span></p>
      <div class="rectangle-3"></div>
      <p class="gender">
        <span class="span">✰</span>
        <span class="text-wrapper-4">&nbsp;</span>
        <span class="text-wrapper-3">Gender</span>
      </p>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <p class="age"><span class="span">✰</span> <span class="text-wrapper-3"> Age</span></p>
      <p class="register-number"><span class="span">✰ </span> <span class="text-wrapper-3">Register Number</span></p>
      <div class="rectangle-6"></div>
      <p class="department"><span class="span">✰ </span> <span class="text-wrapper-3">Department</span></p>
      <div class="rectangle-7"></div>
      <p class="email-ID"><span class="span">✰ </span> <span class="text-wrapper-3">Email ID</span></p>
      <div class="rectangle-8"></div>
      <p class="mobile-number"><span class="span">✰ </span> <span class="text-wrapper-3">Mobile Number</span></p>
    </div>
  </body>
</html>


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

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 566px;
  min-height: 874px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 258px;
  left: 144px;
  width: 422px;
  height: 616px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 31px;
  left: 84px;
  width: 458px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #fbe015;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 460px;
  left: 60px;
  width: 206px;
  height: 56px;
  background-color: #da1010;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 476px;
  left: 118px;
  width: 89px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #1b1616;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 105px;
  left: 70px;
  width: 261px;
  height: 33px;
  background-color: #d9d9d9;
}

.iphone-pro-max .full-name {
  position: absolute;
  top: 97px;
  left: 70px;
  width: 434px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .span {
  font-family: "Inter-BlackItalic", Helvetica;
  font-style: italic;
}

.iphone-pro-max .text-wrapper-3 {
  font-family: "Inter-BlackItalic", Helvetica;
  font-style: italic;
  font-size: 20px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 153px;
  left: 70px;
  width: 261px;
  height: 40px;
  background-color: #d9d9d9;
}

.iphone-pro-max .gender {
  position: absolute;
  top: 144px;
  left: 74px;
  width: 276px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  font-family: "Inter-BlackItalic", Helvetica;
  font-style: italic;
  font-size: 24px;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 208px;
  left: 70px;
  width: 261px;
  height: 33px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 251px;
  left: 70px;
  width: 261px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-pro-max .age {
  position: absolute;
  top: 197px;
  left: 74px;
  width: 287px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .register-number {
  position: absolute;
  top: 251px;
  left: 74px;
  width: 287px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 298px;
  left: 74px;
  width: 257px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-pro-max .department {
  position: absolute;
  top: 298px;
  left: 74px;
  width: 394px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 343px;
  left: 74px;
  width: 257px;
  height: 33px;
  background-color: #d9d9d9;
}

.iphone-pro-max .email-ID {
  position: absolute;
  top: 339px;
  left: 74px;
  width: 239px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-8 {
  position: absolute;
  top: 389px;
  left: 74px;
  width: 257px;
  height: 31px;
  background-color: #d9d9d9;
}

.iphone-pro-max .mobile-number {
  position: absolute;
  top: 385px;
  left: 74px;
  width: 276px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}


PAGE 4

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
    <div class="iphone">
      <img class="rectangle" src="img/rectangle.png" />
      <div class="text-wrapper">DESIGNED BY KARTHIK.A</div>
      <div class="div">THANK YOU.</div>
    </div>
  </body>
</html>

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

style.css

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 562px;
  min-height: 854px;
  position: relative;
}

.iphone .rectangle {
  position: absolute;
  top: 526px;
  left: 0;
  width: 562px;
  height: 277px;
  aspect-ratio: 2.03;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 803px;
  left: 137px;
  width: 385px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 408px;
  left: 223px;
  width: 319px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ff1616;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-10-18 201456.png>)




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
