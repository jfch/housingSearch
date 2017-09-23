# Anti-Fraud Housing Search Web Application

## How to run the web app:

1.aws login, 2 servers with MongoDB installed

2.server login key file

3.log in server-1 and run: [worspace/testing-8.8-release]$ forever start server.js

3.log in server-2 and run: [worspace/project-295-gener]$ forever start bin/www 

4.visit the site: http://52.11.239.50:3000/app
-web pages works

5.change config file with updated dbserver ip: "awsApiUrl": "http://34.211.36.173:3100"
rerun: forever restart server.js
-all microservices worked

### note:
forever list: check running services
local: \Users\MyPC\git\housingSearch