<h1>SETUP WEBSERVER:</h1>

1. Use Command 'npm start' in nodeapp folder

<h3>HOW TO DOCKER BUILD:</h3>

    docker build -t wows-webserver .

<h3>HOW TO DOCKER RUN:</h3>

    docker run -d -p 8000:3000 --name 5eb-dev 5eb-dev

<h3>HOW TO ENABLE AUTO START / RESTART:</h3>

    docker update --restart=always 5eb-dev