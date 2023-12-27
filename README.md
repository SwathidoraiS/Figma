# Ex09 Event Registration Web Application
## Date:27.12.2023

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

<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
    <img style="width: 365.69px; height: 55px; left: -3px; top: 17px; position: absolute" src="https://via.placeholder.com/366x55" />
    <img style="width: 148.21px; height: 150px; left: 106px; top: 107px; position: absolute" src="https://via.placeholder.com/148x150" />
    <div style="width: 212px; height: 38px; left: 71px; top: 273px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">HACKATHONS’23</div>
    <div style="width: 141px; height: 48px; left: 113px; top: 338px; position: absolute; background: #CD2EA1; backdrop-filter: blur(4px)"></div>
    <div style="width: 126px; height: 27px; left: 119px; top: 349px; position: absolute; text-align: center; color: white; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">REGISTER</div>
    <div style="width: 141px; height: 45px; left: 113px; top: 398px; position: absolute; background: #D92591; backdrop-filter: blur(4px)"></div>
    <div style="width: 127px; height: 34px; left: 118px; top: 406px; position: absolute; text-align: center; color: white; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">LOGIN</div>
</div>

// HACKATHONS’23
color: black;
 font-size: 24px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// REGISTER
color: white;
 font-size: 24px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// LOGIN
color: white;
 font-size: 24px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word

Page 2

<div style="width: 100%; height: 100%; padding-top: 74px; padding-bottom: 192px; padding-left: 67px; padding-right: 56px; background-image: url(https://via.placeholder.com/360x640); flex-direction: column; justify-content: flex-start; align-items: center; display: inline-flex">
    <div style="width: 237px; height: 374px; text-align: center"><span style="color: black; font-size: 24px; font-family: Inter; font-weight: 900; word-wrap: break-word">Hackathon Events<br/></span><span style="color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word"><br/>Automation in Industry<br/><br/>Machine Learning<br/><br/>Quantum Computing<br/><br/>Cloud Computing<br/><br/>Enterprenuership Program<br/><br/>Game Development<br/></span></div>
</div>

// Hackathon Events<br/>
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 900;
 word-wrap: break-word
---
// <br/>Automation in Industry<br/><br/>Machine Learning<br/><br/>Quantum Computing<br/><br/>Cloud Computing<br/><br/>Enterprenuership Program<br/><br/>Game Development<br/>
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 600;
 word-wrap: break-word

 Page 3

<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
    <div style="width: 281.29px; height: 14.95px; left: 29.85px; top: 32.26px; position: absolute; background: #E50A0A"></div>
    <div style="width: 208px; height: 40px; left: 37px; top: 77px; position: absolute; background: #0F0505"></div>
    <div style="width: 209px; height: 39px; left: 36px; top: 78px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">  Name</div>
    <div style="width: 207px; height: 39px; left: 38px; top: 132px; position: absolute; background: rgba(16.77, 15.75, 15.75, 0.93)"></div>
    <div style="width: 205px; height: 37px; left: 40px; top: 189px; position: absolute; background: black"></div>
    <div style="width: 204px; height: 39px; left: 41px; top: 245px; position: absolute; background: black"></div>
    <div style="width: 204px; height: 39px; left: 41px; top: 307px; position: absolute; background: black"></div>
    <div style="width: 204px; height: 39px; left: 41px; top: 364px; position: absolute; background: black"></div>
    <div style="width: 201px; height: 27px; left: 41px; top: 372px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Choose Events</div>
    <div style="width: 194px; height: 31px; left: 48px; top: 315px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Phone Number</div>
    <div style="width: 197px; height: 38px; left: 48px; top: 252px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">E-mail</div>
    <div style="width: 198px; height: 34px; left: 48px; top: 195px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Department</div>
    <div style="width: 201px; height: 36px; left: 41px; top: 138px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 700; word-wrap: break-word">Register Number</div>
    <div style="width: 140px; height: 46px; left: 102px; top: 441px; position: absolute">
        <div style="width: 140px; height: 46px; left: 0px; top: 0px; position: absolute; background: #23C5CF; backdrop-filter: blur(4px)"></div>
        <div style="width: 129px; height: 44px; left: 25px; top: 9px; position: absolute; color: #FBF8F8; font-size: 24px; font-family: Inter; font-weight: 700; word-wrap: break-word">SUBMIT</div>
    </div>
</div>

 //   Name
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// Choose Events
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// Phone Number
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// E-mail
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// Department
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// Register Number
color: white;
 font-size: 20px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// SUBMIT
color: #FBF8F8;
 font-size: 24px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word

Page 4

<div style="width: 100%; height: 100%; padding-left: 56px; padding-right: 56px; padding-top: 138px; padding-bottom: 138px; background-image: url(https://via.placeholder.com/360x640); flex-direction: column; justify-content: flex-start; align-items: flex-start; display: inline-flex">
    <div style="width: 236px; height: 111px; color: black; font-size: 36px; font-family: Inter; font-weight: 700; word-wrap: break-word">THANK YOU</div>
    <div style="width: 299px; height: 158px; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 700; word-wrap: break-word">Thank you for your registration. Your participation is greatly<br/>appreciated.Looking forward to seeing you there!</div>
</div>

// THANK YOU
color: black;
 font-size: 36px;
 font-family: Inter;
 font-weight: 700;
 word-wrap: break-word
---
// Thank you for your registration. Your participation is greatly<br/>appreciated.Looking forward to seeing you there!
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 700;
 word-wrap: break-word
```
## OUTPUT:
![Alt text](<Screenshot (66).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
