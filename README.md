# ledger-app
Docker project integrates different parts of application into a local development environment.

Application has 3 parts: Web, Api and Database.

Web is a frontend project built with React.

Api is a backend project built with Go.

Database is Mongodb.

Using Nginx as a reverse proxy, connects with Web and Api.

### First run *"yarn build"* in ledger-api and *"yarn build:copy"* in ledger-admin to copy project outputs

### into ledger-app, then run "docker-compose up -d" to build the docker image and container. 

### Finally you can open browser and input *http://localhost:8001* to view the application.