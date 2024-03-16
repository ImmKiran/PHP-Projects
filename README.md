### Form control 

## Overview
This is a web application project  i have developed for the assignment task which was given by GKB Labs. This web application that allows users to input data, validate it, store it in a database, retrieve it, and display it in a table format.. The application is built using Bootstrap, PHP and JavaScript 

***Front-End:*** 
  - Bootstrap
  - Javascript 
  
***Backend:***
  - MySQL

  ## How to Run the web Application
  1. Install a Local Server Environment: Before you can run PHP projects, you need a server environment on your local machine such as XAMPP.
  2. Set Up Your Database like mySQL
  3. Create Your Project Directory: Organize your project files within a directory. For example, create a folder named my_project in the server's web root directory.
  4. Access Your Project in a Web Browser: Once your server is running, you can access your PHP project through a web browser. Open your browser and type http://localhost/my_project/ in the address bar.

  # User input Form

  In this program user have to enter his/her details in the form box such as-:

             Name (text input)
             Email (email input)
             Age (Positive number input)
             Date of Birth (date input)


 # Brief Explanation

 1. First I created a Form by using Bootstrap

 2. After that I went to localhost/PHPMyAdmin and created a new database named "contacts". Now in that database, I have created a new table named "Contactus". Now in that table, I have create the following columns: sno (Serial No), name, email, Age and DOB.

 3. // Connecting to the Database
      $servername = "localhost";
      $username = "root";
      $password = "";
      $database = "contacts";

 4. I have created a connection using MySQLi and we need to insert the SQL query there
         "INSERT INTO `contactus` (`name`, `email`, `age`, `dob`) VALUES ('$name', '$email', '$age', '$DOB)";

 5. Data Retrieval:
I have created another PHP page that retrieves the data from the database  which was submitted by the user and displays it in a tabular format (HTML table).

## Contributor
- Kiran kumar sahu
