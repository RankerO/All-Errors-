# {"code":"PROTOCOL_ENQUEUE_AFTER_FATAL_ERROR","fatal":false}

### This type of error due to mysql package 

1. Uninstall the mysql package from the application using npm uninstall mysql command.

2. Install mysql2 using npm install mysql2 command.
Change below code:
From

3. const mysql = require('mysql')

To:

4. const mysql = require('mysql2')

Now start your application using npm start command and check the database connection.
