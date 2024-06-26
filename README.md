# CC_AWS
### Amazon Web Services 

Cloud Computing : 
on demand avaliability of IT resources over the internet on basis of pay as per use 

AWS : 
Comprehansive cloud computing paltform which provides over a 200 plus cloud computing services provided by Amazon 

Well in types we have in delivery model 
1] Cloud-based deployment 
2] on-Prim deployment 
3] Hybrid deployment 

### Amazon EC2
Elistic Cloud Compute 
- Virtual server provided by AWS

- <br/> <hr/>

### Amazon EC2 Auto Scaling
- Amazon EC2 Auto Scaling enables you to automatically add or remove Amazon EC2 instances in response to changing application demand. By automatically scaling your instances in and out as needed, you can maintain a greater sense of application availability.

- Within Amazon EC2 Auto Scaling, you can use two approaches: dynamic scaling and predictive scaling.

* Dynamic scaling responds to changing demand. 
* Predictive scaling automatically schedules the right number of Amazon EC2 instances based on predicted demand.

- <br/> <hr/>

### Directing Traffic with Elastic Load Balancing

 
![image](https://github.com/cnnarayanchavan/CC_AWS/assets/113028954/5fb189ec-477b-4672-8381-cf7aac0b1b0f)



- Now the load balancer is the appliction that takes in requests and route them to the instances to be processed
- so Basically ELB is the Regional Construct as it runs at regon level and distribute triffic effectively to the instances

- <br/> <hr/>

- ### Messaging and Queuing in AWS
- Simple and in basic term we are going to have a buffer (temporary storage area) to hold data which is being transferred between two locations

- So the concept of <h3>Messaging and  Queuing</h3> in AWS is :
  * Basically placing a messages into a buffer is nothing but the M&Q
  * Where it helps applications to communicate with each other in the EC2 environment
 
  </br> </hr>

  Ok so here if the applications are directlt communicate with each other so it says as it is a TIGHTLY COUPLED APPLICATION
  where we have risk for failaure because one component fails it'll afftect another working component too
  <h5>here's example:</h5> 
  ![Screenshot 2024-06-26 133817](https://github.com/cnnarayanchavan/CC_AWS/assets/113028954/16d0053a-e6ca-4cc5-a369-7a573d399abc)




</br> </hr> 


  So here we have the more reliable architecture which is loosly coupled architecture where one component faliure won't cause cascading faliure as they are isolated from ach other 
  where, fo communication they uses message queue 
  <h5>here's example:</h5> 
  ![Screenshot 2024-06-26 134309](https://github.com/cnnarayanchavan/CC_AWS/assets/113028954/18bd3334-46ae-4976-88e0-c1232c65e220)

  
</br> </hr> 

### SQS & SNS (Simple Queue Service and Simple Notification Service)
* For decoupled applications and microservices, Amazon SQS enables you to send, store, and retrieve messages between components.

* Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers. This is similar to the coffee shop; the cashier provides coffee orders to the barista who makes the drinks.

* </br> </hr>
  ## AWS Lambda
  * Serverless computing facilaties
  * no more need to provisioning the underlying infra. and other management
  * all are taken care by vendor
 
  * ![Screenshot 2024-06-26 171230](https://github.com/cnnarayanchavan/CC_AWS/assets/113028954/29f5dd46-61e9-42af-8e36-b4281c5790f6)
 
  </br> </hr>

  ## AWS Container Orchestration Tools
  * so here if you do not wnat the coMplete serverless computing of your domain and still wnat the provision of your server with efficiency and portability you could use AWS's
    1] Amazon Elastic Container Services (Amazon ECS)

    2] Amazon Elastics Kubernetes Services (Amazon EKS)

    * where the container in this case is the docker container
    * where Docker is the widely used containerization application, where the container is the package of your code in which we package up our application and dependencies and the configuration tha required to run the application.
    * these container runs on top of EC2 instences
   
      ## AWS Fargate
    Serverless compute for EKS and ECS ( If you don't want to manage both of these services ) {"*i don't understand wyh you even bother just make every single thing automatic*"}
    
    
  




