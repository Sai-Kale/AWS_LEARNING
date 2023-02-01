# Elastic Container Service:

- ECS is a orchestrator service that runs our docker containers.
- deploy and LB traffic across multiple servers.
- Autoscaling to handle traffic and rolling out new changes to the application.


- ECS is a simple orchestrator unlike kubernetes which is more complex.

- ECS launch types:
    - EC2 : here we have to manage the underlying infrastructure.
    - Fargate: here the underlying infrastructure is maintained by the AWS.
- Cluster is a bunch of resources and ECS is responsible to run the containers on the cluster.
- Cluster has physical resources. 

- ECS vs Fargate:
    - Fargate is serverless architecture.
    - Fargate will create severs on demand.
    - Pay for what you use.
- ECS Task:
    - We dockerize an application into an image.
    - Upload the image to a resitry.
    - Now we have to define a task definition.
        - Blueprint the describes how containers should launch.
        - How much CPU/MEM
        - Images/Ports/Volumes
    - An instance of the task definition. A running container with the settins defined in the task definition.
- ECS Services:
    - A service ensures that a certain number of Tasks are running at all times.
    - Restart the containers that have exited/crashed.

- Load Balancers:
    - A LB is to route external traffic to your service.



## Working with ECS:

- 

