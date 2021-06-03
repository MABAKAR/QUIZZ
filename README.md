# QUIZZ 

![alt text](http:/Capture d’écran 2021-06-03 à 08.50.34![image](https://user-images.githubusercontent.com/73992960/120600499-2194f900-c449-11eb-8dc9-af7174440db1.png))
with several features

USER

```create play the quiz while not connected```

```create an account with email  confirmations```

```resend a confirmation email if you did not validate at the beginning``` 

```watch your history while being logged in```

```edit your profile with email confirmations if you change your email```

ADMIN

```CHANGE THE ROLE OF A USER```

```DEACTIVATE AND ACTIVE AN ACCOUNT```

```CREATE USER```

```CREATE QUIZZ```

# INSTALL

```git clone git@github.com:MABAKAR/QUIZZ.git```




NAVIGATE IN THE FOLDER

```cd quizz```

Install project dependencies


```composer install```



CHANGE THE .ENV WITH YOUR SQL IDENTIFIER AND YOUR MAILTRAP

DATABASE MIGRATIONS

```php bin/console d:d:c```
```php bin/console d:m:m```

IMPORT THE FILE quizz.sql with your phpMyAdmin

Launch Web application in localhost

```symfony serve -d ```
