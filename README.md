# ALX-Udacity-Cloud_developer_Nanodegree-program
All projects during Udacity-cloud_developer_nanodegree program

**PROJECT 1**   
### Deploy static webiste to AWS    
I deployed a static website to AWS using S3, CloudFront, and IAM.

**PROJECT 2**   
### Image-filter_Udagram    
Deployed an image filtering app (Udagram) using AWS elastic beanstalk.
Udagram is a simple cloud application that allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

**PROJECT 3**   
### Refactor-monolith-to-microservices  
- Refactored a monolith application to microservices
- Set up each microservice to be run in its own Docker container
- Set up a Travis CI pipeline to push images to DockerHub
- Deployed the DockerHub images to the Kubernetes cluster

**PROJECT 4**   
### Develop-and-deploy-serverless-app   
- Implemented the following functions:
    Auth: a custom authorizer for API Gateway that is added to all other functions.
    GetTodos:Returns all TODOS for a current user
    CreateTodo: Creates a new TODO item for the current user
    UpdateTODO: update a TODO item created by a current user.
    DeleteTODO: deletes a TODO item created by a current user.
    GenerateUploadUrl: returns a pre-signed URL that can be used to upload an attachment file for a TODO item.
- Deployed the application using serverless framework
- Auth0 is implemented into the application
- AWS X-RAY distributed tracing is implemented
- Functions contain logging