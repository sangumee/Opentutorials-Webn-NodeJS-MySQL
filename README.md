# Opentutorials-Webn-NodeJS-MySQL ![](https://img.shields.io/badge/Code%20Statue-Open-brightgreen.svg)
This repository is code written during the course of the NodeJS-MySQL class provided by Opentutorials.
You can access the class with this [Link](https://opentutorials.org/course/3347).
This program is developed with NodeJs and MySQL. A Simple CRUD(reate, read, update, and delete) App.

# Installation
You can download with this [link](https://github.com/sangumee/Opentutorials-Webn-NodeJS-MySQL/archive/master.zip) If you already installed the Visual Studio Code or Github Program, You can access it directly with these programs.

The first thing to do is to install the packages using NPM.
Next, rename the file /lib/db_bak.js to db.js, open the file, and enter the server information. This is because the original db.js file is defined in .gitignore to prevent server information from being uploaded to Github.

In package.json supervisor is installed so you can start this project with this commend.

If you want to use supervisor function use this commend.

`supervisor main.js`

If you want to use just normal version of node use this commend.

`node main.js`

Basic settings of internet port is 3000. But you can change it in main.js last line.

`app.listen(3000);`

After finished the all settings. You can access with this url in your browser.

`localhost:3000` or `127.0.0.1:3000`

# Contact
If you have some questions or issues about this repository please contact me with the [Issue](https://github.com/sangumee/Opentutorials-Webn-NodeJS-MySQL/issues) section.

# License
This project is released under the [MIT License](https://choosealicense.com/licenses/mit/). If you think there is a problem with this license, please file an issue through the Issue section.
