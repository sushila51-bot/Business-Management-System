# **#Installation**

Clone the repository:  
[https://github.com/sushila51-bot/Business_Management_Project.git](https://github.com/sushila51-bot/Business_Management_Project.git)

Import the project inside STS/Eclipse:  

Open STS/Eclipse > File > Import > Maven > Existing Project > Browse > Finish.  
Make sure you are in the `Business_Management_Project` directory.

---

# **#packageExplorer**

Configure the database connection in `application.properties` (check the Database section for more information).

Run the project (by running the main method in `BusinessProjectApplication.java`) OR right-click on the project → Run As → Spring Boot App.

Open [http://localhost:2330/home](http://localhost:2330/home) in any browser.

Now your tables will be created in the database.  

You have to add one admin record manually to login as admin. Database: MySQL can be used for this project.  
The database connection can be configured in the `application.properties` file with the following properties:

