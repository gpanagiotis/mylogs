# mylogs
 Experimentation with log tracking system to DataBase for unsuccessful login

1. configure the file config/db.php and set the crendentials of the database
2. go to project folder and run this in terminal to create the log table into database `yii migrate --migrationPath=@yii/log/migrations/`
3. try to login using wrong credentials and go to table log of the database (like phpmyadmin) and run the query `select * from log where category = 'mylogs'` 
