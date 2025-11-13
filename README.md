# Ex09 Event Registration Web Application
## Date:13-11-2025

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
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="screenshot" src="img/screenshot-2025-11-09-211904-1.png" />
      <div class="text-wrapper">Sports Day</div>
      <div class="div">Login</div>
      <div class="text-wrapper-2">Register</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-17-at-23-23-55-ce1b14eb-1.png" />
      <img class="img" src="img/screenshot-2025-11-09-213029-1.png" />
    </div>
  </body>
</html>
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
.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 917px;
  aspect-ratio: 0.9;
  object-fit: cover;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 112px;
  left: 51px;
  font-family: "Island Moments-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 473px;
  left: 43px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 596px;
  left: 43px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 82px;
  aspect-ratio: 5.35;
  object-fit: cover;
}

.android-compact .img {
  position: absolute;
  top: 248px;
  left: 43px;
  width: 326px;
  height: 164px;
  aspect-ratio: 1.99;
  object-fit: cover;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="screenshot" src="img/screenshot-2025-11-09-211904-2.png" />
      <div class="text-wrapper">sports day events</div>
      <div class="div">cricket</div>
      <div class="text-wrapper-2">batminton</div>
      <div class="text-wrapper-3">volley ball</div>
      <div class="text-wrapper-4">foot ball</div>
      <div class="text-wrapper-5">kho-kho</div>
      <div class="text-wrapper-6">chess</div>
      <div class="text-wrapper-7">carrom</div>
    </div>
  </body>
</html>
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
.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 917px;
  aspect-ratio: 0.9;
  object-fit: cover;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 79px;
  left: 49px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .div {
  position: absolute;
  top: 230px;
  left: 71px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 319px;
  left: 73px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 407px;
  left: 84px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 503px;
  left: 80px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 605px;
  left: 84px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 696px;
  left: 88px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-7 {
  position: absolute;
  top: 796px;
  left: 93px;
  font-family: "Josefin Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}



<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="screenshot" src="img/screenshot-2025-11-09-211904-3.png" />
      <div class="thank-you">Thank<br />&nbsp;&nbsp;&nbsp;&nbsp;you</div>
      <div class="by-sports-club-SEC">by <br />Sports club<br />SEC</div>
    </div>
  </body>
</html>
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
.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 412px;
  height: 917px;
  aspect-ratio: 0.9;
  object-fit: cover;
}

.android-compact .thank-you {
  position: absolute;
  top: 227px;
  left: 94px;
  font-family: "Kapakana-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .by-sports-club-SEC {
  position: absolute;
  top: 675px;
  left: 166px;
  font-family: "Kaushan Script-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}


## OUTPUT:
![alt text](<Screenshot 2025-11-09 213413.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
