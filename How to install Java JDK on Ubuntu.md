# How to install Java JDK on Ubuntu
* We can use sudo apt search openjdk to find all available OpenJDK in the default repository
	* sudo apt search openjdk
* If we want to install Java 8.
	* sudo apt install openjdk-8-jdk
* If we want to install Java 11.
	* sudo apt install openjdk-11-jdk
* Where is JDK installed?
	* The apt install the Java JDK at this path /usr/lib/jvm.

* We can use java -version to verify if Java JDK is installed correctly.
	* java -version
	* sudo update-alternatives --config java

