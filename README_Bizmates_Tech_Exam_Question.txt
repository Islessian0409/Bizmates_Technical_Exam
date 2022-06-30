Can you please explain in detail the work experience over the last three years. What kind of
technology, what kind of solution, what kind of difficulties did you face? What was the work
procedure you did?

In line with our procedures and operations, we used AWS in all of our projects. We find it easier to learn and to implement. From Manual provisioning, deployment, maintaining, monitoring, and updating. We have managed to automate that chaotic process into a smooth and stable process through CI/CD and several AWS services to minimize the operational overhead rendering us to have more time and flexibility to promote innovation.

For instance, from manual backend deployment that will take at least 10-15 minutes each iteration. We have used AWS CodePipeline to do automate the process and have experienced seamless deployment and smooth process providing our developer the ability to deploy their updates anytime and revert back to the previous state should there be any problem that we may encounter.

Going back to our chaotic days where we have to apply a front-end update. It will take us a lot of time to create a build and more time to deploy it depending on the internet speed for manual syncing to be invalidated in CloudFront afterwards.

The solution for this is we have managed to use CodePipeline as well and saved us a lot of time and effort. As I have noticed, there's a better approach in line with this approach. The use of Amplify where we only have to provide the code from the repository gave us a lot more flexibility as once the code is pushed into the repository, it will automatically deploy on its own without any interaction.

In addition, from our manual provisioning of infrastructure which is repetitive and tedious, we've utilized cloudformation to ensure that it will be reusable providing us more time and minimize the chance to commit a mistake.

Then, I've proposed the use of Serverless service in which upon initial setup of creating an API gateway and necessary configurations, all we have to do is to upload or write the code directly into the service and it will simply deploy itself.

No installation, less cost, minimal operational overhead, faster deployment, secured API's, has the ability to scale on its own and stop costing us money if the function is not used. This service provides us the best experience we had in terms of deploying our projects.

It is also part of my job to document everything step-by-step for our change management. Creating instructional materials for our clients and providing live training and collaboration so to speak.

All in all, manual work is tedious, prone to error, slow and requiring a lot of time has been eliminated as we've managed to use different cloud services for the issues we've encountered.

In addition, below are some of the difficulties I've experienced:

- I will be called on the spot regardless of time to deploy any updates for any project(s).
The solution for this is through continuous learning, the discovery of the services provided us a better approach in delivering our services

- Tracing the root cause of our mistake as the production environment's database was mistakenly pointed to the test environment. 
There is no problem in infrastructure as I've checked it thoroughly. And as my final resolve, I've checked the repository and saw that our developer accidentally pointed the endpoint to the incorrect environment. But instead of blaming, we've learned from our mistakes and took note of what went wrong. In order for the endpoint to be reverted on its appropriate environment, we've updated the code and a code review was then added and an approval of codepipeline deployment is implemented. By that time, it's a good thing that in every update or iteration of our project, It is my procedure to create an automated backup of the database instance itself as well as a manual creation of the database dump to be uploaded on S3.

- Manually teaching our client on how are they going to provision and maintain their resource(s)
A repetitive process, and once the momentum is lost, we have to repeat from the start. The solution I've made was to create a documentation with step-by-step process as well as necessary screenshots for our clients to follow along.

- Monitoring of servers and databases
Before, we are just manually monitoring our servers and databases by manually checking its utilization, network performance, CPU, memory, and everything there is that needs to be monitored.
We can't detect it in real-time if there's a problem in the infrastructure's performance unless reported. From there, we've learned to use CloudWatch Agent to monitor everything we need through custom logs and configured an alarm for us to be notified beforehand should the threshold is being breached.

- A low budget infrastructure.
It is given that the client wants their system to run 24/7 without an actual problem. But due to low budget, creating an scalable infrastructure is out of my hands. It can be done, but my hands are tied we will be the one to shoulder the cost as their budget is way too low to have a resource that is more suitable for its use case. What I did is provided them with detailed process monitoring report and made them realize that the current setup is not suitable for that level of traffic and load. Upon agreement, the creation of their system to scale up and down were implemented and those days are finally over.

In all honesty, there is a lot more. I am looking forward to talk about this in the next phase of my application.



