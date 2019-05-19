# PAF-Group-Project
SellNBye is an e-commerce system, which provides a platform for the registered sellers to advertise their products and registered buyers to order and purchase them.

- Shopping cart
- Catalogue
- Search
- Checkout
- Administration
- REST API


Get the code:
-------------------
Clone the repository:
     
	 $ git clone https://github.com/IshanAK/PAF-Group-Project.git
	 
To build the application:
-------------------	
From the command line with Maven installed:

	$ cd shopizer
	$ mvn clean install
if Maven is not installed, use maven wrapper
       
	$ mvmw clean install
	

Run the application from Tomcat 
-------------------
copy sm-shop/target/ROOT.war to tomcat or any other application server deployment dir

Increase heap space to 1024 m

### Heap space configuration in Tomcat:


If you are using Tomcat, edit catalina.bat for windows users or catalina.sh for linux / Mac users

	in Windows
	set JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 
	
	in Linux / Mac
	export JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 

Run the application from Spring boot 
-------------------

       $ cd sm-shop
       $ mvn spring-boot:run
if Maven is not installed, use maven wrapper
       
	   $ mvmw spring-boot:run

Run the application from Spring boot in eclipse
-------------------

Right click on com.salesmanager.shop.application.ShopApplication

run as Java Application

### Access the application:
-------------------

Access the deployed web application at: http://localhost:8080/

Acces the admin section at: http://localhost:8080/admin

username : admin

password : password

The instructions above will let you run the application with default settings and configurations.
Please read the instructions on how to connect to MySQL, configure an email server and configure other subsystems


### Group Details:
-------------------

Group ID	Student ID 		 Name

403-G8		IT17083638 – I.A. Kandamby
			IT17118514 – S. Niluxshan
			IT17085786 – Mannakkara D.N.
			IT17063388 – Ranaweera R.C.
			IT17083314 – H.M. Yasas Rusiru


