--Followed https://www.youtube.com/watch?v=Hl7diL7SFw8&list=PLpPqplz6dKxUaZ630TY1BFIo5nP-_x-nL&index=2&ab_channel=PedroTech
youtube tutorial

1) Create two folders call client & server

2) open terminal - 
npm init

3) Framework for create Rest API for NodeJs 
npm install express

4) Package cors & mysql
npm install cors mysql2

5) to run 
node index.js

6) Instll NodeMon Package (this restarts the server after saving)
npm install nodemon
add  "start": "nodemon index.js" under "Scripts in package.json

7) after installing nodemon to run the app 
npm start

8) install sequlize and cli
npm install -g sequelize sequelize-cli
npx sequelize init (run this from inside the server which created models, config and seeders folders)
if the packages not getting added into package.json file try "npm install sequelize-cli" and "npm install sequelize"

9) Create a table/model under "models" folder, when npm start is called this will create a table in mysql server.
Before that change the /server/config/config.json file with root username and password for the mysql server.

10)




