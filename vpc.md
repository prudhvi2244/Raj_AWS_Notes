# VPC ( Virtual Private Cloud )

* VPC is a virtual network dedicated to our AWS Account.It is logically isolated from other virtual
  networks in the AWS Cloud.
* We can launch our AWS Resources, such as Amazon EC2 instances into our VPC.
* We can configure our vpc by modifying its IP address range, create subnets, and configure route 
  tables, network gateways and security settings

# What is a subnet?

* A subnet is a range of IP Address in your VPC.
* We can launch AWS resources into a specified subnet.

# Public Subnet

* If a subnet's traffic is routed to an internet gateway, the subnet is known as a public subnet.
* Use public subnet for the resources that must be connected to the internet.


# Private Subnet

* Use private subnet for the resources that will not be connected to the internet.


* To Protect AWS Resources in each subnet, you can use multiple layers of security including
  security groups and network access control lists (ACL)

* When we create a VPC, we must specify a range of IPv4 addresses for the VPC in the form of a
  CIDR ( Classless Inter-Domain Routing ) block; for example, 10.0.0.0/16. This is the primary CIDR
  block for our VPC.


* In a particular AWS Region we can have 5 VPC
* Within Particula VPC we can create 200 subnets
* We can have 5 IP address CIDR Block (1 primary and 4 Secodary) assigned to VPC
* VPC spans all the availability zones in the region.
* After creating a VPC, you can add one or more subnets in each availability zone.
* Each subnet must reside entirely within one Availability Zone and cannot span zones.
* Availability Zone is nothing but AWS Data Center

* internet gateway enables communication over the internet
* Virtual Private Network (VPN) connection enables communication with your corporate network.
* NAT ( Network Address Translation ) Gateway is a highly available AWS managed service that makes it easy to connect to the
  Internet from instances within a private subnet in an Amazon Virtual Private Cloud (Amazon VPC).







