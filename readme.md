#WELCOME TO BACHHOACHANGSEN

#This is prototype project replicate partial functions of youtube for training purposes.

#Please skim through a few of these instruction before using to avoid unwanted errors and malfunction.

#INSTALLATION
- npm install : Run for the first time cloned project or after pull branches with major changes.

#SETUP DATABASE
- Check database info in process.env to match with your local database.
- If you have just clone this project fresh
+ Run "npm run init_database" to create database and folow
- If you already have this database
+ Command "npx sequelize-cli db:migrate" or "npm run init_table" to create database tables.
+ Then use "npx sequelize-cli db:seed:all" or "npm run init_data" to seed all dummies data.

#RUN
- npm start : Run project with nodemon


I- installing rasa
>conda deactivate
>conda create -n rasaenv
>conda activate rasaenv
>conda install ujson
>conda install tensorflow
>pip install rasa
>rasa init
(install in current directory)

>conda info --envs

II- to communicate with rasa in cmd
>rasa shell

II- running rasa end points:
(rasaenv) E:\Automation\Bots\PersonalBot\Rasa>rasa run --cors "*" --enable-api

(rasaenv) E:\Automation\Bots\PersonalBot\Rasa>rasa run actions
