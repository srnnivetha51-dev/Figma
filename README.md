# Ex08 Event Registration Web Application
## Date:
24-12-2025
## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
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
      <img class="f" src="img/f-1-1.png" />
      <div class="text-wrapper">DEPARTMENT</div>
      <div class="div">REGISTER NO</div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-3">REGISTRATION</div>
      <div class="text-wrapper-4">GENDER</div>
      <div class="text-wrapper-5">MOBILE NUMBER</div>
      <div class="text-wrapper-6">EMAIL ID</div>
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

 .android-medium {
  background: linear-gradient(
    180deg,
    rgba(42, 3, 34, 1) 0%,
    rgba(227, 185, 218, 1) 0%,
    rgba(144, 10, 115, 1) 100%
  );
  width: 100%;
  min-width: 467px;
  min-height: 791px;
  position: relative;
}

.android-medium .f {
  position: absolute;
  top: 0;
  left: 0;
  width: 467px;
  height: 791px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 293px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 225px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 113px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle {
  position: absolute;
  top: 0;
  right: 0;
  width: 393px;
  height: 73px;
  background-color: #f98d8d;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 22px;
  left: 146px;
  width: 249px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 169px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 360px;
  left: 147px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 416px;
  left: 152px;
  width: 134px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
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
    <div class="android-medium">
      <div class="rectangle"></div>
      <div class="text-wrapper">CRAFT DAY EVENTS</div>
      <img class="f" src="img/f2-1.png" />
      <div class="div">ARTISPHERE</div>
      <div class="RANGE-ROOTS">RANGE&nbsp;&nbsp;&amp; ROOTS</div>
      <div class="CREATIVE-CANVAS">CREATIVE&nbsp;&nbsp;CANVAS</div>
      <div class="text-wrapper-2">HANDMADE CRAFTS</div>
      <div class="ellipse"></div>
      <div class="ellipse-2"></div>
      <div class="ellipse-3"></div>
      <div class="ellipse-4"></div>
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

android-medium {
  overflow: hidden;
  background: linear-gradient(
    180deg,
    rgba(42, 3, 34, 1) 0%,
    rgba(227, 185, 218, 1) 0%,
    rgba(144, 10, 115, 1) 100%
  );
  width: 100%;
  min-width: 467px;
  min-height: 791px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 9px;
  left: -44px;
  width: 433px;
  height: 98px;
  background-color: #edc4df;
  transform: rotate(0.01deg);
}

.android-medium .text-wrapper {
  position: absolute;
  top: 25px;
  left: 3px;
  width: 406px;
  font-family: "Jacques Francois Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .f {
  position: absolute;
  top: 516px;
  left: 0;
  width: 375px;
  height: 275px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .div {
  position: absolute;
  top: 477px;
  left: 133px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .RANGE-ROOTS {
  position: absolute;
  top: 381px;
  left: 126px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #171616;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .CREATIVE-CANVAS {
  position: absolute;
  top: 287px;
  left: 131px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 177px;
  left: 131px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .ellipse {
  top: 173px;
  left: 60px;
  width: 45px;
  height: 39px;
  background-color: #b4a8a5;
  border-radius: 22.5px / 19.5px;
  border-color: #171616;
  position: absolute;
  border: 1px solid;
}

.android-medium .ellipse-2 {
  top: 271px;
  left: 60px;
  width: 45px;
  height: 40px;
  background-color: #a99191;
  border-radius: 22.5px / 20px;
  border-color: #000000;
  position: absolute;
  border: 1px solid;
}

.android-medium .ellipse-3 {
  top: 370px;
  left: 58px;
  width: 47px;
  height: 41px;
  background-color: #bf9f9f;
  border-radius: 23.5px / 20.5px;
  border-color: #2e2828;
  position: absolute;
  border: 1px solid;
}

.android-medium .ellipse-4 {
  top: 470px;
  left: 60px;
  width: 46px;
  height: 44px;
  background-color: #cab6b6;
  border-radius: 23px / 22px;
  border-color: #292727;
  position: absolute;
  border: 1px solid;
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
    <div class="android-medium">
      <img class="f" src="img/f-1-1.png" />
      <div class="text-wrapper">DEPARTMENT</div>
      <div class="div">REGISTER NO</div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-3">REGISTRATION</div>
      <div class="text-wrapper-4">GENDER</div>
      <div class="text-wrapper-5">MOBILE NUMBER</div>
      <div class="text-wrapper-6">EMAIL ID</div>
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
.android-medium {
  background: linear-gradient(
    180deg,
    rgba(42, 3, 34, 1) 0%,
    rgba(227, 185, 218, 1) 0%,
    rgba(144, 10, 115, 1) 100%
  );
  width: 100%;
  min-width: 467px;
  min-height: 791px;
  position: relative;
}

.android-medium .f {
  position: absolute;
  top: 0;
  left: 0;
  width: 467px;
  height: 791px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 293px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 225px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 113px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle {
  position: absolute;
  top: 0;
  right: 0;
  width: 393px;
  height: 73px;
  background-color: #f98d8d;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 22px;
  left: 146px;
  width: 249px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 169px;
  left: 152px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 360px;
  left: 147px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 416px;
  left: 152px;
  width: 134px;
  font-family: "Luckiest Guy-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-24 094254.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
