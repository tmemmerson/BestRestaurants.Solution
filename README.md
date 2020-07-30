**<h1 align = "center"> Cuisine Finder**

<h1 align="center">
  <img width="800" height="487" src="https://coding-assets.s3-us-west-2.amazonaws.com/img/best_restaurants.png">
</h1>


**<h3 align="center">Finding you the best restaurants by cuisine**

<br>

**<h2 align = "center">
  <a href="#install">Install</a> •
  <a href="#setup">Setup</a> •
  <a href="#protecting-your-data">Protecting Data</a> •
  <a href="#questions-and-concerns">Q's & C's</a> •
  <a href="#technologies-used">Technologies</a> •
  <a href="#known-bugs">Known Bugs</a> •  
  <a href="#contributors">Contributors</a> •
  <a href="#license">License</a>**

<br>
<h2 align = "center">

**ABOUT**

</p>

_Cuisine finder allows you to add favorite local restaurants and associated cuisine type. You can also search the database for other restaurants by their cuisine type. This app utilizes razor c# asp.net core mvc with entity framework using the CRUD naming convention._

<br>

## **INSTALL**

* Install [.NET version 3.1](https://dotnet.microsoft.com/download/dotnet-core/2.2) _SDK v2.2+_
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [MySql Workbench](https://www.mysql.com/products/workbench/)

<br>

## **SETUP**


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
cd BestRestaurants
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

#### Step 2: commit that .gitignore file (this prevents your sensitive information like your username or password being shown to others). **DO NOT PROCEED UNTIL YOU DO THIS!**


![appsettings](https://coding-assets.s3-us-west-2.amazonaws.com/img/app-settings.png)

![setup](https://coding-assets.s3-us-west-2.amazonaws.com/img/readme-image-3.jpg "Set up instructions")

<br>



_Recommended browser for everything in life. [Google Chrome](https://www.google.com/chrome/)_.




**Windows/Mac Users:** If modifying for personal use, dl Git [here](https://git-scm.com/downloads/) (v2.62.2)





In your preferred terminal window, navigate into PROJECTNAME.SOLUTIONS/PROJECTNAME using cd (i.e. cd desktop/PROJECTNAME.SOLUTIONS/PROJECTNAME) and open the project with your preferred code editor.

Run the following terminal command: $ dotnet restore
To initiate this program, run the command: $ dotnet run
To run the test suite included with this project, within the terminal navigate into PROJECTNAME.TESTS and run the following commands:
$ dotnet restore
$ dotnet test

<br>




## **QUESTIONS AND CONCERNS**

_Questions, comments and concerns can be directed to the author [Tristan Emmerson](tristan@stickerslug.com)

<br>

## **Technologies Used**

_**Written in:** [Visual Studio Code](https://code.visualstudio.com/)_

_**Image work:** [Adobe Photoshop](https://www.adobe.com/products/photoshop.html/)_

<br>


## **Known Bugs**

_**No Known Bugs:**7/28/2020_

<br>


## **Contributors**

#### By _**Tristan Emmerson, Kyle Hubbard, Taylor Phillips, & Megan Hepner**_

<br>

## **License**
![alt text][logo]

[logo]: https://img.shields.io/bower/l/bootstrap "MIT License"

Copyright (c) 2020 **_Tristan Emmerson, Stickerslug Inc._**