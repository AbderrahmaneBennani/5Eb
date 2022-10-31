<h1>SETUP PROJECT</h1>

- install npm
- install npm package: "npm install -g express-generator"

<h1>SETUP WEBSERVER:</h1>

For following Commands terminal must be in folder .\nodeapp
 
- 'npm i' - installs all needed packages
- 'npm start' - starts Webserver (Accessable over localhost:3000)

<h3>HOW TO DOCKER BUILD:</h3>

    docker build -t 5eb-dev .

<h3>HOW TO DOCKER RUN:</h3>

    docker run -d -p 8000:3000 --name 5eb-dev 5eb-dev

<h3>HOW TO ENABLE AUTO START / RESTART:</h3>

    docker update --restart=always 5eb-dev