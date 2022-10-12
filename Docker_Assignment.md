1. docker ps -a

     It will show the list of containers
  
  
     ![docker1](https://user-images.githubusercontent.com/8469407/195258383-99c37fe9-4b5d-4597-ad30-dd0e294d8315.PNG)
     
  
2. docker pull hello-world

     This will pull the image from dockerhub
       
       
     ![docker2](https://user-images.githubusercontent.com/8469407/195259860-3811a20e-bc5d-43a7-ba85-5c7e4e475475.PNG)


3. docker run hello-world

     This will run the image locally
        
        
     ![docker3](https://user-images.githubusercontent.com/8469407/195260257-d5fc5958-ff91-4de7-8b4f-a9008727fa70.PNG)


4. docker images

     It will show the list images present in host machine
     
     
     ![docker4](https://user-images.githubusercontent.com/8469407/195261053-d6e83752-9380-4b63-8bc8-2647b1941118.PNG)

5. docker stop -t 15 container

     This will stop the specified container after specified time(15s)
     
     
     ![docker5](https://user-images.githubusercontent.com/8469407/195262253-aee908a6-8697-40ec-9734-577c72b4fee5.PNG)

6. docker inspect image

     This will provide low level info of the image in a key value pair format
     
     
     ![docker6](https://user-images.githubusercontent.com/8469407/195263108-48e38d75-519a-4191-86fe-d739da898ebd.PNG)

7. docker history image

     This will provide the history of an image
     
     
     ![docker7](https://user-images.githubusercontent.com/8469407/195263666-33ffef61-4b74-486a-b53b-764e81a119d7.PNG)

8. docker logs container

     This will provide logs of the specified container
     
     
     ![docker8](https://user-images.githubusercontent.com/8469407/195263990-56e6d4cd-ed8b-412d-8efa-ed4173f266a5.PNG)

