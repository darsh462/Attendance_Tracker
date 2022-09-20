# Attendance_Tracker - The Ultimate Installing Guide


## Prerequisites

1.Node.jS:
<https://nodejs.org/dist/v14.17.0/node-v14.17.0-x64.msi>

2.Mongodb Community Server:
<https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-4.4.6-signed.msi>

You can check the version by typing “mongod —version” on your terminal.
While installing choose to install mongodb compass, else install it seperately.

3.Mongodb Compass:
<https://downloads.mongodb.com/compass/mongodb-compass-1.26.1-win32-x64.msi>

4.Database tools:
<https://fastdl.mongodb.org/tools/db/mongodb-database-tools-windows-x86_64-100.3.1.msi>

5.python has to be installed, along with pip.

## Installation

1.Download the Repo and extract it to the convinient location on your Computer`


2.Install NPM packages
-> You should be in root directory of ur project.

```sh
   npm install       
```

3.Install Python packages

```sh
   cd Py-Scrpits
   pip install -r requirements.txt
```

4.Create a empty folder namely 'db' in root of our project.
-> change path name aacoording to ur PC.



5.Extract dump.rar file.
-> You have to change path.



OR
You can also import files using mongo compass GUI, for that files will be in " db.rar "  Just Import json files.

## Execution of project

1.Start the express server from the root directory.

```sh
   npm start
```

2.Start the flask server from Py-scripts directory.

```sh
   python app.py
```

3.Start the mongo server
-> change path to ur path.



## Compass Connection

1.After Installing MongoDB Compass, paste this in the adress bar of compass.



For Local connection

```sh
   mongodb://127.0.0.1:27017 
```

## Usefull Commands

1.This wiil dump all the database files, i mean schema, to the directory where you are.

```sh
   mongodump
```

2.Restore the database from imported schema.



## Heroku Setup

To download project from heroku, and you need to create an account.

1.Install heroku CLIfrom: <https:/>/devcenter.heroku.com/articles/heroku-command-line>

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

```sh
   heroku login
```

2.Clone the repository
Use Git to clone attendance_tracker source code to your local machine.



3.Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.


