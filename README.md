# springboot-docker-ecs
Run your Docker image on AWS ECS (Elastic Container Service)

### Required commands

- Build Docker Image.

		mvn spring-boot:build-image
   
- Run Docker Image.

		docker run --tty --publish 8080:8080 <image-name>
    
- Tag Docker Image

		docker tag <image-name> tag-name/<image-name>
    
- Push Docker Image to Docker Hub

		docker push tag-name/<image-name>
		
- Application Flow  

<img width="576" alt="11" src="https://user-images.githubusercontent.com/25712816/91267149-570d0780-e790-11ea-8497-806b30cbcfc2.PNG">

