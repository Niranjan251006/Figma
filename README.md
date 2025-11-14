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
HTML
```
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-max-1-1">
<img src="images/img-1-2.png" class="img-1-2" alt="img-1" />
<div class="rectangle-3-3"></div>
<div class="rectangle-2-4"></div>
<p class="text-5"><span class="text-rgb-227-144-84">SIGN UP</span></p>
<p class="text-6"><span class="text-rgb-227-144-84">LOGIN 
</span></p>
<img src="images/logo-1-7.png" class="logo-1-7" alt="logo-1" />
</div>

</body>
</html>

FRAME 2


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-1-1">
<img src="images/img-1-2.png" class="img-1-2" alt="img-1" />
<img src="images/logo-1-3.png" class="logo-1-3" alt="logo-1" />
<div class="rectangle-1-4"></div>
<p class="text-5"><span class="text-rgb-254-183-158">TECHNICAL EVENTS
COMPUTER SCIENCE DEPT.</span></p>
<p class="text-6"><span class="text-white">CodeStorm
RoboRumble
DataVerse
HackNexus
SmartCity Sprint
TechTopia
ByteVerse
Algowar
DevVana
ElectroSpark
Quantum Quest
Cyber Yodha
Hack-o-Heist
DesignDerby
PitchPerfect
     
</span></p>
</div>

</body>
</html>

FRAME 3


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-pro-1-1">
<img src="images/img-1-2.png" class="img-1-2" alt="img-1" />
<img src="images/logo-1-3.png" class="logo-1-3" alt="logo-1" />
<div class="rectangle-1-4"></div>
<p class="text-5"><span class="text-rgb-254-183-158">REGISTER NOW
</span></p>
<div class="rectangle-2-6"></div>
<div class="rectangle-7"></div>
<div class="rectangle-4-8"></div>
<div class="rectangle-5-9"></div>
<div class="rectangle-6-10"></div>
<div class="rectangle-11"></div>
<p class="text-12"><span class="text-rgb-254-183-158">Name</span></p>
<p class="text-13"><span class="text-rgb-254-183-158">Department</span></p>
<p class="text-14"><span class="text-rgb-254-183-158">College Name
</span></p>
<p class="text-15"><span class="text-rgb-254-183-158">Session
</span></p>
<p class="text-16"><span class="text-rgb-254-183-158">Event Name</span></p>
<p class="text-17"><span class="text-rgb-7-37-66">Register
</span></p>
</div>

</body>
</html>


```
CSS
```

/* Add font files for Istok Web */
@font-face {
  font-family: 'Istok Web';
  src: url('fonts/istok-web.woff2') format('woff2'),
       url('fonts/istok-web.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-istok-web: 'Istok Web', sans-serif;
  --text-rgb-227-144-84: rgba(227, 144, 84, 1);
}

.text-rgb-227-144-84 {
  color: var(--text-rgb-227-144-84);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.img-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-3-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(20, 18, 35, 1);
}

.rectangle-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(20, 18, 35, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-227-144-84);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-227-144-84);
}

.logo-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.iphone-16-pro-max-1-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-max-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-max-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(20, 18, 35, 1);
}

FRAME 2


/* Add font files for Istok Web */
@font-face {
  font-family: 'Istok Web';
  src: url('fonts/istok-web.woff2') format('woff2'),
       url('fonts/istok-web.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-istok-web: 'Istok Web', sans-serif;
  --text-rgb-254-183-158: rgba(254, 183, 158, 1);
  --text-white: rgba(255, 255, 255, 1);
}

.text-rgb-254-183-158 {
  color: var(--text-rgb-254-183-158);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.img-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.logo-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-1-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(7, 37, 66, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-16-1-1 {
@media (max-width: 1440px) {
  .iphone-16-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

FRAME 3


/* Add font files for Istok Web */
@font-face {
  font-family: 'Istok Web';
  src: url('fonts/istok-web.woff2') format('woff2'),
       url('fonts/istok-web.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-istok-web: 'Istok Web', sans-serif;
  --text-rgb-254-183-158: rgba(254, 183, 158, 1);
  --text-rgb-7-37-66: rgba(7, 37, 66, 1);
}

.text-rgb-254-183-158 {
  color: var(--text-rgb-254-183-158);
}

.text-rgb-7-37-66 {
  color: var(--text-rgb-7-37-66);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.img-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.logo-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-1-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(7, 37, 66, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.rectangle-2-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-4-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-5-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-6-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.rectangle-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 183, 158, 1);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-254-183-158);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-istok-web);
  font-weight: 700;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-7-37-66);
}

.iphone-16-pro-1-1 {
@media (max-width: 1440px) {
  .iphone-16-pro-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-pro-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
## OUTPUT:
<img width="483" height="852" alt="image" src="https://github.com/user-attachments/assets/9e3658fa-0b8f-41f0-8c9a-1582584fbc8e" />
<img width="630" height="908" alt="image" src="https://github.com/user-attachments/assets/ac8f0097-9472-45ef-8cf3-e973a06c727b" />
<img width="523" height="863" alt="image" src="https://github.com/user-attachments/assets/502c790c-a2eb-4e92-a370-c8e548a60427" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
