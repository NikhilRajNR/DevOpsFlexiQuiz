# DevOpsFlexiQuiz
## DevOps Engineer Test

### DevOps Test Senerio :
The goal of this assignment is to find out how you, as a DevOps Engineer handles a scenario with the constrains and vagueness of the real world. We expect you to make a variety of assumptions given the information you have, and to clearly document them in the README.   
You’ve been tasked to create a deployment strategy for a microservices based application. The kind of applications that we deal with at Ormae are primarily backend heavy and vastly distributed in nature and we prefer Kubernetes to run apps in production. Below are the components that will be there in an application
1. User Interface
2. API Gateway
3. Authentication
4. API
5. Public Endpoints
6. Internal APIs
7. OAuthorization Server
8. Long Running Workers/Jobs (~30mins)
9. Queues (Like RabbitMQ, Bull, etc)
10. Database   
11. Redis      

### Objective -
1. Chalk out a Git repository structure in terms of helping in reaching maximum efficiency in terms of ease of development and collaborating.   
2. Lay down a plan for CI/CD. As there will be tests pertaining to each microservice, how do you plan to run them in tandem in the deployment pipeline.   
3. Prepare a deployment strategy that can be adapted for **Staging, UAT and Production**. Note that staging setup needs to be less in terms of operating cost.   
4. Prepare a plan to see logs in all the above three environments.   
5. Prepare a plan to add alerts and monitoring across all of the mentioned components.      
### Extra Points -   
1. Able to come up with a plan which can be scaled to 100K users in a cost optimized way.   
2. Able to come up with strategies that are cloud agnostic.
