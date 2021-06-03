# QUIZZ 

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

Install project dependencies


```composer install```


NAVIGATE IN THE FOLDER

```cd quizz```

CHANGE THE .ENV WITH YOUR SQL IDENTIFIER AND YOUR MAILTRAP

DATABASE MIGRATIONS

```php bin/console d:d:c```
```php bin/console d:m:m```

IMPORT THE FILE quizz.sql with your phpMyAdmin

Launch Web application in localhost

```symfony serve -d ```
