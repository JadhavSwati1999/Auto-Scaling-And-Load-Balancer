# Auto-Scaling-And-Load-Balancer
# Create Auto-scaling &amp; Application load balancer.


### What is Auto-Scaling ?

### AWS Auto Scaling **monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost**. Using AWS Auto Scaling, it's easy to setup application scaling for multiple resources across multiple services in minutes.

What is Load-Balancer?

- A load balancer **serves as the single point of contact for clients**. The load balancer distributes incoming application traffic across multiple targets, such as EC2 instances, in multiple Availability Zones. This increases the availability of your application.
- AWS Elastic Load Balancing supports three types of load balancers: **Application Load Balancers, Network Load Balancers, and Classic Load Balancers**.

### Steps to create a Load Balancer and Auto-Scaling

- Create three instances as instance1, instance2, instance3 .


- Create three targets



- Register the targets


- Create a application load balancer.



- Assign a name for load balancer.


- Attach the security group and the target group

- This is the summary of the load balancer



- When we hit the DNS of the load balancer request it again we can  see that the load is rerouted to a different machine.


### Create an Auto Scaling Group

- To create auto-scaling we need a template.
- Create a template.


- Launch a template.


- Create a auto-scaling group.


- Attach an existing load balancer to the auto-scaling group.



- The auto-scaling group is created  with desired capacity -2, minimum capacity -1,maximum capacity-2


- Due to this if we terminate an instance new instances are created.