APIRest
Diseño de aplicaciones Web
Download the repository
git clone https://github.com/jestrade/diseno-aplicaciones-web.git
Enter into the directory
cd diseno-aplicaciones-web
Install the app
npm install
Create .env file ENV = development | production
ENV=
DEV_DATABASE_HOST=
DEV_DATABASE_NAME=
PROD_DATABASE_HOST=
PROD_DATABASE_NAME=
PROD_DATABASE_USER=
PROD_DATABASE_PASSWORD=
SERVER_PORT=
SERVER_HOST=
To run the app on production mode
npm start
To run the app on development mode 6.1 Install nodemon
npm i nodemon -g
6.2 Run

npm run dev
Libraries
https://www.npmjs.com/package/dotenv
https://www.npmjs.com/package/morgan
https://www.npmjs.com/package/path
https://www.npmjs.com/package/fs
https://www.npmjs.com/package/crypto-js
https://www.npmjs.com/package/jsonwebtoken