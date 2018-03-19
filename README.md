# nodejs-file-upload-with-mongodb
Programmer Blog: https://programmerblog.net/


Source code for article on Nodejs uplaod file using mongodb with multer package.

You can read detailed tutorial on our blog: https://programmerblog.net/nodejs-file-upload-tutorial/

Install MongoDB 

    First you need to install MongoDB on your system, Please visit MonogoDB site and download it.

    Create a MongoDB database After MongoDB installation. Create a data/db directory - In windows c:/data/db

    On command prompt, open MongoDB -> bin folder and run

      > mongod

    Open another command prompt and open bin folder and type

      > mongo

    Mongo shell is running, type

      > use dbphotogallery

    Current databse will be changed to to dbphotogallery.

Install NodeJS 
 
     Please visit NodeJS site and download installer, Install on your system, It also install NPM or Node Package Manager

     Generate NodeJs, Express application using Express command line tool to generate an application skeleton.

     express --view=pug nodejs-file-upload


Install required dependencies

           cd  nodejs-file-upload && npm install
           
           npm install -g nodemon --save
           
           npm install --save multer
           
           npm i --save mongoose
           
Add a folder to upload files

         Open the public folder and add a new folder called files in it. This folder is used to save user uploaded files.

Create a Model using mongoose 

         A Photo Schema is created in a Models folder using Mongoose

Create a Form in pug template engine 

         Create a form and photo gallery using materialize framework
         
Fecth records from MongoDB and display in photo gallery

Upload file to server and add file path and caption to MongoDB collection


Reade More at : https://programmerblog.net/nodejs-file-upload-tutorial/

