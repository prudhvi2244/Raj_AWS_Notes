# How to Install Java 11/8 on Amazon Linux
* The OpenJDK 8 is available under default yum repositories and OpenJDK 11 is available under Amazon Linux 2 extras repositories. You can simply install Java 11 or Java 8 on the Amazon Linux system using the following commands.
	* sudo amazon-linux-extras install java-openjdk11
	* sudo yum install java-1.8.0-openjdk

* Check Active Java Version
	* java -version

* Switch Java Version
  * Use alternatives command-line utility to switch active Java version on your Amazon Linux system. Run below command from the command line and select the appropriate Java version to make it default.
  	* alternatives --config java

