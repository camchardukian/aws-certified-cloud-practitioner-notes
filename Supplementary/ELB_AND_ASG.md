# Elastic Load Balancing (ELB) and Auto Scaling Groups (ASG)

_Scalability_ means that an application/system can handle greater loads by adapting.

_Vertical scaling_ is very common for non-distributed systems such as databases.

_Horizontal scaling_ is more popular with modern web applications.

In the context of AWS, _high availability_ refers to running the same application across multi availability zones.

## ELB

Load balancers are servers that forward internet traffic to multiple servers (such as EC2 instances) downstream.

Load balancers allow us to spread a load across multiple downstream instances while still only exposing a single point of access (DNS) to our application.

An ELB is a managed load balancer.

_Application Load Balancers_ (Layer 7) are for HTTP/HTTPs only.

_Network Load Balancers_(Layer 4) offer ultra-high performance and allow for TCP.

## ASG

Auto Scaling Groups help us realize cost savings by helping us to run our servers at optimal capacity.

Other advantages of ASGs are that they can:

- Scale out (add EC2 instances) to match an increased load
- Scale in (remove EC2 instances) to match a decreased load
- Ensure we have a minimum and maximum number of machines running
- Automatically register new instances to a load balancer
- Replace unhealthy instances
