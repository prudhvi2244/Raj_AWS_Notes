# How to Install Apache Web Server on Amazon Linux 2

* Linux 2: Linux 2 is a very very popular linux AMI provided by AWS itself and also free tier eligible.
* Apache Web Server: Apache web server is one of the most used web server when it comes to serving web content online. It is open source and easy to setup.
* Update latest package available on the system

	* sudo yum update -y

* Install Apache Web Server
	
	* sudo yum install -y httpd.x86_64


* Start Apache Server
	
	* sudo systemctl start httpd.service

* Configure Apache to run on system boot

	* sudo systemctl enable httpd.service

* Change Security Group of instance to allow port 80 and 443

	* Let’s allow web traffic on port 80 and 443(Internet traffic for http and https)

* Restarts Apache Web server
	
	* sudo systemctl restart httpd.service

* Stop Apache Web Server

	* sudo systemctl stop httpd.service

* Prevent Apache from loading on system boot

	* sudo systemctl disable httpd.service

* 
