# Image Classifier REST API
### This is a sample code to use docker container, Tensorflow inception3 model, Mongodb & flask REST api for image classification

You need to install docker ce & docker compose and then run the followings:


```
sudo docker-compose build
sudo docker-compose up -d
```
### Using postman to call API
1- Register a user:
### 
![](https://github.com/amir-rafieian/image_classifier_docker_rest_api/blob/master/register.PNG)

2 - And then call the api with an image to receive response:
### 
![](https://github.com/amir-rafieian/image_classifier_docker_rest_api/blob/master/classify.PNG)