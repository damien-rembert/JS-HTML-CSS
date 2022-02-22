# MongoDB

Use environment variables with dotenv and put sensitive data in `.env` file in project top folder.
Use `.gitignore` to ensure `.env` is not sent to the repo

# set-up
```bash
 mkdir projectName
 cd mongoDB
 npm init -y
 mkdir src
 touch src/app.js
 mkdir src/db
 touch src/db/connection.js
 touch src/db/connection.test.js
 npm i mongodb yargs dotenv
```
