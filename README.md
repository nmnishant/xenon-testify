# Xenon Project - Testify | Exam Proctoring Web App
## Submission for Xenon Stack ✨
![Wild (3)](https://user-images.githubusercontent.com/94772345/170864660-33e11ca6-e9c9-4f0f-b201-12e48301f084.jpg)


### 📹 Problem statement (as given)
Develop a browser-based application to demonstrate a theme, I choosed college theme

## 	💻 Interfaces

### **→** Landing Page
Seamless landing page with Login/SignUp Button.

<img src="https://user-images.githubusercontent.com/94772345/170834750-34150030-09fb-4213-a1de-0c5babddcf39.jpg" height="300">

### **→** Contact Us
Contact us with just a click.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/74682951/200981023-ab9471a5-f547-47f6-8874-ead73a3c7a6f.gif)

### **→** Student DashBoard
- Student Can Join Exam by clicking on **`Join Exam`** with the Exam Code provided by their teacher.’
- Students can see their Previous Exams in the Dashboard.
- After the Exam, Student can check their Results.

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/74682951/200978523-8b771e35-50d1-47c4-9091-842c844d4f5d.gif)

### **→** Examination Page
- There will be Question Panel.
- **`Next`** Button to goto the next Question.
- **`Submit Test`** Button to Submit the test.

<img src="https://user-images.githubusercontent.com/74682951/200978618-90d5e212-0811-4512-accb-b4153692c370.png" height="300">
<br>

### **→** Teacher DashBoard
   #### Teacher can :-
- Create the exam by **`Create Exam`** and get the exam code which can be shared to the students.
- Check students performance or students perform any Prohibited and UFM during the exam.
- Check the Ongoing, Past Exam Student Performance and can also **schedule** exams.

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/74682951/200978760-57052235-0413-49b4-b080-c7fb5bc187a5.gif)


## ⚙️ Tech Stack: 

- **Nodejs**
- **Express.js**
-  **MongoDB, Mongoose.js**
-  **Tensorflow object detection API**
- **HTML, CSS**
- **JavaScript**
- **Other third party services**


## 🧰 Features:


- **Multiple Face Detection**
- **Tab Switching**
- **Face Not Visible**
- **Mobile Phone Detection**
- **Book Or Any Prohibited Object Detection**
- **Disable Right Click and Modifier Keys.**

### What Happens If someone:-

-  Donot enable their camera ❔

- Tries to switch tabs during the test ❔

-  Face not Visible ❔

-  Uses Phone ❔

- Tries to cheat with someone in the room ❔

- Use Book Or Any Prohibited Object ❔

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/74682951/200978806-0211a315-d4bf-4114-b45e-ce4746031fc2.gif)


## ⏱️ Timeline
## Step 1

🏴 **Design phase**

Thought about the design idea and implemented it. My first Prototype was a simple application.

🏴 **Basic built by exploring technologies**

Learned about Nodejs, Express.js all the stuff explored more technologies.

🏴 **Setup server**

Setup server using Nodejs



## Step 2
🏴 **Front End Design**

Created Client-Side Pages Using HTML, and CSS. Started with Requirement Specifications for the application.

🏴 **Logic implementation**

Faked API data and wrote logic according to it for the client-side using JavaScript.

🏴 **Third party services**

Searched and used third party services like “Sweet Alert v2”, “Axios”, 
“CSVToJson”



## Step 3

🏴 **Created Data Base**

Thought of all the schemas that would be used and created database for the same using MongoDB and integrated it to the NodeJS using Mongoose

🏴 **Created API’s**

Created all the API’s using “Express” needed for the web app and served the pages using PUG



## Step 4

🏴 **Updated client-side logic**

Updated JavaScript logic to use actual API data instead of fake one

🏴 **Testing and Bug fixing**

Tested all the functionalities for different different senarios

Bugs : 
- Receiving 404 JSON data instead of 404 HTML page on visiting not-defined route. (Fixed)
- Server was performing operations on Date according to UTC timezone instead of IST. (Fixed)

🏴 **Deployment**

Deployed the web app to “heroku” and the link for the application.

**https://xenon-testify.herokuapp.com/**


## 🚩Points to remember while testing the app

1. Allow **permission** for camera
2. In case any **problem**, **REFRESH** the window. 
3. Make sure the **URL** is starting with https.
4. While **scheduling a test** make sure the start and end date follow a logical sequence or else it’ll show an error. 

## 🚩Installation/Environment Setup

1. **Clone App**
- Make a new folder and open the terminal there.
- Write the following command and press enter.

`https://github.com/nmnishant/xenon-testify.git`

2. **Set Environment Variables**
- Uncomment `dotenv.config({path : './config.env'});` in app.js
- Create file `config.env` with Environment Variables


3. **Install node packages** 
- Write the following command and press enter to download all required node modules.

     `npm install`

4. Run `node app.js` in terminal

5. The app is now running at **http://localhost:8000/**

## 🚩Important Links

<a href="https://drive.google.com/file/d/1oEyhCth7JLkRY-rsDICd8zK4p_1FNPdG/view?usp=sharing">Download Question Demo File</a>

<a href="https://documenter.getpostman.com/view/19469722/2s8YekQuYu">API Documentation</a>
