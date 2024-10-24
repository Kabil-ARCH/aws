### VPC (Virtual Private Cloud):

- VPC is a network service helps in managing network traffic across our cloud infrastructure .
- It helps in making secure way of managing our network traffic with components like public and private subnets , route table , igw , NATgw , ACL , security groups .



### VPC : 

![[Pasted image 20241023102124.png]]

VPC makes the isolated network from the cloud and makes every services to communicate locally and over the internet through separate features .

#### subnets : 

subnets named public and private subnets can be created for a single vpc.
- private subnets can not accessed from internet and and compute services or other services can access their resources from internet through NAT gateway

*no inbound access only outbound access when using NAT gateway*

- public subnets can be accessed through internet by configuring igw (INTERNET GATEWAY).

*inbound and outbound access through igw*

> [!NOTE]
> INTERNET GATEWAY (igw):
> 
Allows two-way traffic between instances and the internet (both inbound and outbound).

> [!NOTE]
> NAT GATEWAY:
> 
 Only allows outbound traffic from private subnets to the internet (no inbound traffic).

#### ROUTE TABLE : 

- Route tables can direct traffic to the internet through an Internet Gateway, allowing public instances to send and receive traffic.

- Route tables can route traffic to your on-premises network via a VPN or Direct Connect, facilitating hybrid cloud architectures.





