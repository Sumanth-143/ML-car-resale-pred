# ML-car-resale-pred
Creating a ML model for predicting the resale of the car using the dataset that was provided by the KAGGLE website.
1. git clone the project into local.
2. go into project directory
3. create a Dockerfile 
4. do docker build -t summu6699/mlmodel:v1 .
5. docker images ...
6. docker run -p 5000:5000 summu6699/mlmodel:v1 -> runs the app on localhost:5000
7. stop this running container (docker stop containerid)
8. After stopping the container , push the image to docker hub( docker push summu6699/mlmodel:v1)
9. Now you can remove the image from your local as it is uploaded in hub ,if you want to run this application , download the image from hub and run it.
