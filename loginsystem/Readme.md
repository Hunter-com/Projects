Create a login page having user name and password. On clicking submit, a welcome
message should be displayed if the user is already registered (i.e.name is present in the
database) otherwise error message should be displayed. 


// Firstly create a database with name and table name "loginsystem" in phpmyadmin and the table structure will be like this 
Name		      Type			       Constraints
sno		      int(11)		    	       primary key / AUTO_INCREMENT
username	      varchar(25)		       unique
password	      varchar(255)		
dt		      current_timestamp()	

// Create a folder name loginsystem and place signup.php, login.php, welcome.php, logout.php then create a subfolder name partials and place _nav.php and _dbconnect.php files up there