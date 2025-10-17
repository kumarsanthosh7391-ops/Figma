# Ex09 Event Registration Web Application
## Date:17/10/2025

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
```
Home Page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="first" src="img/first-1.png" />
      <img class="logo" src="img/logo-2.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">login</div>
      <div class="div"></div>
      <div class="text-wrapper-2">register</div>
    </div>
  </body>
</html>
//globals.css
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
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .first {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 841px;
  aspect-ratio: 1.79;
  object-fit: cover;
}

.iphone-pro .logo {
  position: absolute;
  top: 48px;
  left: 32px;
  width: 338px;
  height: 77px;
  aspect-ratio: 4.39;
  object-fit: cover;
}

.iphone-pro .rectangle {
  top: 368px;
  height: 69px;
  position: absolute;
  left: 80px;
  width: 226px;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 369px;
  left: calc(50.00% - 71px);
  width: 126px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  top: 515px;
  height: 71px;
  background-color: #d9d9d9;
  position: absolute;
  left: 80px;
  width: 226px;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 525px;
  left: 110px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}
event page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="second" src="img/second-1.png" />
      <div class="cricket-volleyball">
        cricket<br /><br />volleyball<br /><br />basketball<br /><br />football<br /><br />handball
      </div>
      <img class="logo" src="img/logo-1.png" />
    </div>
  </body>
</html>
//globals.css
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
.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .second {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.iphone-pro .cricket-volleyball {
  position: absolute;
  top: 178px;
  left: 61px;
  width: 482px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #288a82;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .logo {
  position: absolute;
  top: 45px;
  left: 23px;
  width: 338px;
  height: 77px;
  aspect-ratio: 4.39;
  object-fit: cover;
}
 details page 
 <!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="third" src="img/third-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">name</div>
      <div class="div"></div>
      <div class="text-wrapper-2">registerno</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">gender</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">emai.id</div>
    </div>
  </body>
</html>
//global.css
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
.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 204px;
  left: -785px;
  width: 189px;
  height: 47px;
}

.iphone-pro .third {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 1.6;
  object-fit: cover;
}

.iphone-pro .logo {
  position: absolute;
  top: 43px;
  left: 25px;
  width: 338px;
  height: 77px;
  aspect-ratio: 4.39;
  object-fit: cover;
}

.iphone-pro .rectangle {
  top: 204px;
  left: 99px;
  width: 189px;
  height: 57px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 206px;
  left: calc(50.00% - 69px);
  width: 138px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  top: 316px;
  left: 83px;
  width: 236px;
  height: 74px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 316px;
  left: 99px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-2 {
  top: 445px;
  left: 113px;
  width: 180px;
  height: 55px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 445px;
  left: 113px;
  width: 155px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-3 {
  top: 573px;
  left: 117px;
  width: 189px;
  height: 51px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 565px;
  left: 125px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
final page 
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="fourth" src="img/fourth-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <div class="text-wrapper">ThankYou!!</div>
    </div>
  </body>
</html>
 //globals.css
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
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .fourth {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 2;
  object-fit: cover;
}

.iphone-pro .logo {
  position: absolute;
  top: 40px;
  left: 24px;
  width: 338px;
  height: 77px;
  aspect-ratio: 4.39;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 388px;
  left: 59px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}



```
## OUTPUT:
![alt text](<Screenshot 2025-10-18 015143.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
