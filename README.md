# Building image

Add path `.build` containing `rundeck.war`

Build image  `docker build -t rundeck/tsuru .`

Create container `docker run --name rundeck-container -p 8888:8888 rundeck/tsuru`
