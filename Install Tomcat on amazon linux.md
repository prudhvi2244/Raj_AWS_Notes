# Install Tomcat on Amazon Linux

	* >sudo su -
	* >cd /opt

	* >wget https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.78/bin/apache-tomcat-8.5.78.tar.gz

	* >tar -xvzf /opt/apache-tomcat-8.5.78.tar.gz

	* >mv apache-tomcat-8.5.78 tomcat
 
	* >cd tomcat/

	* >cd bin/

	* >./startup.sh

	* >./shutdown.sh

	* >cd webapps/manager/META-INF

* modify context.xml and comment <Valve> tag

	* >cd conf/

* modify tomcat-users.xml file with role as "manager-gui"

