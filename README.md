# ProjectTwo edit to read me

Create repo on github
include readme
check git ignore for node modules
check travis ci integration

basic servrer up and running

touch server.js
npm init -y
install packages
npm install expresss sequelize mysql2
copy paste server.js boiler plate
test server by running npm run start

Integrate Sequelize
1. Run the following command: sequelize init: config & sequelize init: models
2. Modify the config.json development object with your database and credentials
3. Create matching db using MySQL workbench
4. Save the create script to db/schema.sql
5. Enable sequelize portions of server.js
6. Test the server with sequelize by running npm run start


## Integrate Handlebars

** NOTE: As of Jan. 2020, there was a conflict in handlebars and express-handlebars.  The following configuration is necesssary to avoid this settings conflict. **

1. ```npm install express-handlebars@3.1.0```
2. ```npm install handlebars@4.5.3```
3. Uncomment handlebars portions of server.js
4. Create the folder structure for handlebars
a. views folder
b. views/index.handlebars
c. views/layouts folder
d. views/layouts/main.handlebars
5. Add html boilerplate to main.handlebars
6. Add ```{{{body}}}``` to main.handlebars
7. Text by running ```npm run start```

### Housekeeping
1. Create a dev script so I can run ```npm run deve```: in package.json
2. Add my .eslintrc.json and .eslintignore files
3. run ```npm install eslint@4.19.1```
4. Create a scrip to run eslint: ```npm
