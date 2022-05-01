# Amazon EC2 (Elastic Compute Cloud)


# Why AWS EC2?

* Why not buy our own stack of servers and work independently? Suppose we are a developer ans want to
  work independently. We buy some servers, we estimated the capacity and the compting power may be
  sufficent. Now, we have to look after the updating of security patches everyday, we have to 
  troubleshoot any problems which might occur at a back-end level in the servers and so on. These are
  all extra chores that we will be doing or maybe we will hire someone else to do these things for us.

* But if we buy an EC2 instance , we do not have to worry about any of these things as it will all be
  managed by Amazon; we just have to focus on our application. That too, at a fraction of a cost that
  we were incurring earlier. Isn't that interesting.

* It is difficult to predict how much computing power one might require for an application which we 
  might have just launched. There can be two scenarios: we may over-estimate the requirement and buy
  stack of servers which may not be of any use or we may under-estimate the usage, which will lead to
  the crashing of our application.

# What is AWS EC2

* Amazon Elastic Compute Cloud, EC2 is a web service from Amazon that provides re-sizable compute 
  services in the cloud.

# How are they re-sizable?

* They are re-sizable because you can quickly scale up or scale down the number of server instances
  you are using if your computing requirement changes.

# What is an instance?

* An Instance is a virtual machine server for running applications on Amazon's EC2. It can also
  be treated like a tiny part of a larger computer, a tiny part which has its own hard drive, network
  connection, OS but it is actually all virtual. We can have multiple "tiny" computers on a physical
  machine, and all these tiny machines are called instances.

# Difference between a service and an Instance?
* EC2 is a service along with other Amazon Web Services like S3 etc.
* When we use EC2 or any other service, we use it through an instance.

# Let us understand the types of EC2 Computing Instances:
* Computing is a very broad term; the nature of our task decides what kind of computing we need.
  Therefore, AWS EC2 offers 5 types of instances which are as follows:
    
	* General Instances

     	    * For applications that require a balance of performance and cost.
	      E.g. email responding systems, where we need a prompt response as well as
	           that it should be cost effective,since it doesn't require much processing.

	* Compute Instances
	
	    # For applications that require a lot of processing from the CPU.
	      E.g. Analysis of data from a stream of data, like Twitter stream.

