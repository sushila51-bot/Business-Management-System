#Installation :
Clone the repository : $ git clone https://github.com/SuhasKamate/Business_Management_Project.git

Import the project inside STS/Eclipse :

Open STS/Eclipse > file > import > maven > existing project > browse > finish .
Make sure you are in the Business_Management_Project directory.

#packageExplorer

4.Configure the database connection is application.properties (check the Database section for more information).

5.Run the project (by running main method is BusinessProjectApplication.java) OR right clink on the project > Run As > Spring Boot App.

6.Open http://localhost:2330/home in any browser.

7.Now your tables will be created in the databse.

You have to add one admin data manually to login as admin, So add one admin data.
Database :
MySQL can be used as the database for this project. The database connection can be configured in the application.properties file, with the appropriate values for the following properties:

#spring.datasource.name=[Your Database Name]
#spring.datasource.url=jdbc:mysql://localhost:3306/[Your Database Name]
#spring.datasource.password=[Your password]
#spring.datasource.username=[Your username]
#spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
#spring.jpa.hibernate.ddl-auto=update
#server.port=2330[Optional]
