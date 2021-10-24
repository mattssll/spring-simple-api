## To build the docker image:
<i>docker build -t bootdocker:1 . </i>

## To run the application in a container
docker run -d --name bootdocker -p 8080:8080 bootdocker:1

## Available endpoint
/greeting > "Hello, World!"
/greeting?name=Ed > "Hello, Ed!"