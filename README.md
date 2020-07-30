**<h1 align = "center"> Cuisine Finder**

<h1 align="center">
  <img width="800" height="487" src="https://coding-assets.s3-us-west-2.amazonaws.com/img/best_restaurants.png">
</h1>


**<h3 align="center">Finding you the best restaurants by cuisine**

<br>

**<h2 align = "center">
  <a href="#✅requirements">Requirements</a> •
  <a href="#🚀setup">Setup</a> •
  <a href="#protecting-your-data">Protecting Data</a> •
  <a href="#📫 questions-and-concerns">Q's & C's</a> •
  <a href="#technologies-used">Technologies</a> •
  <a href="#known-bugs">Known Bugs</a> •  
  <a href="#❤️contributors">Contributors</a> •
  <a href="#📘 license">License</a>**

<br>
<h2 align = "center">

**ABOUT**

</p>

_Cuisine finder allows you to add favorite local restaurants and associated cuisine type. You can also search the database for other restaurants by their cuisine type. This app utilizes razor c# asp.net core mvc with entity framework using the CRUD naming convention._


## **✅REQUIREMENTS**

* Install [Git v2.62.2+](https://git-scm.com/downloads/)
* Install [.NET version 3.1 SDK v2.2+](https://dotnet.microsoft.com/download/dotnet-core/2.2)
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [MySql Workbench](https://www.mysql.com/products/workbench/)


## **🚀SETUP**


copy this url to clone this project to your local system:
```html
https://github.com/tmemmerson/BestRestaurants.git
```

<br>

Once copied, select "Clone Repository" from within VSCode & paste the copied link as shown in the image below.

![cloning](https://coding-assets.s3-us-west-2.amazonaws.com/img/clone-github2.gif "Cloning from Github within VSCode")

<br>

With the project open to the root directory, navigate to the production directory with the following command in your terminal.
```js 
cd ProjectName
```

Then, install the necessary packages with the following command
```js 
dotnet restore 
```

Finally, you can start the program with this command.
```js 
dotnet run 
```

![cloning](https://coding-assets.s3-us-west-2.amazonaws.com/img/dotnet-readme.gif "How to clone repo")


## **PROTECTING YOUR DATA**

#### **Step 1: From within VSCode in the root project directory, we will create a .gitignore file**

**On Mac**
```js 
touch .gitignore 
```

**On PC**
```js 
ni .gitignore 
```

#### Step 2: commit that .gitignore file (this prevents your sensitive information from being shown to others). **DO NOT PROCEED UNTIL YOU DO!**

![setup](https://coding-assets.s3-us-west-2.amazonaws.com/img/entity-readme-image.png "Set up instructions")

#### Step 3: **To commit your .gitignore file enter the following commands**
```js
git add .gitignore
git commit -m "protect data"
```

#### Step 4: **Then, you need to update your username and password in the appsettings.json file.**

_by default these are set to user:root and an empty password. if you are unsure, refer to the settings for your MySqlWorkbench._

![appsettings](https://coding-assets.s3-us-west-2.amazonaws.com/img/app-settings.png)

<br>

## **📫 QUESTIONS AND CONCERNS**

_Questions, comments and concerns can be directed to the author [Tristan Emmerson](tristan@stickerslug.com)_

<br>

## **Technologies Used**

_**Written in:** [Visual Studio Code](https://code.visualstudio.com/)_

_**Image work:** [Adobe Photoshop](https://www.adobe.com/products/photoshop.html/)_

<br>


## **Known Bugs**

_**No Known Bugs:**7/30/2020_

<br>


## **❤️Contributors**

#### By _**Tristan Emmerson, Kyle Hubbard, Taylor Phillips, & Megan Hepner**_

<br>

## **📘 License**
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2020 **_Tristan Emmerson, Stickerslug Inc._**

