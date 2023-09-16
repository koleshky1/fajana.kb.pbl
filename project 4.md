# Step 0
- Spin up a new EC2 instance with the following details:
-  Project 2
-  Unbuntu 22.0
-  and others
-  Connect Git to AWS by applying the key pair
![AWS to Git connect](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/da4cfd77-9b1f-4b66-9f65-23c16852bf52)

# Step 1 
-  STEP 1 – INSTALLING THE NGINX WEB SERVER
-  First update the Service package with the Sudo Apt command
![sudo apt update](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b93c7a14-8449-4da2-968e-a1c06fac1af2)
- install the Nginx server
![Nginx 1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3844dbf9-574b-4b5d-b39b-0cfc461bacd4)
![Nginx 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3e204f07-266f-4253-acdc-7532e76935f8)
- Verify Nginx is active using the SystemCtl command
![Nginx active](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dae8f93e-9694-450f-81fe-dd7bba33517a)
-  Open TCP port 80 to allow Web access
![allow HTTp access](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a24e365f-def3-41b5-809f-3b8961602eac)
-  Accessing the server locally from the Ubuntu shell using the Curl command
![local host](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/5efe0810-daaf-4f84-8257-28c91bc9a4c1)
![local host1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/af2518c5-729c-4038-855f-0a56743b7714)
-  Testing the Nginx functionality on the Google browser using the public IP
![Testing on browser](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a7a4d45f-5c87-46ce-ae32-63f20935336c)
-  Public IP retrieval
![retrieval](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dcf4fd5f-efb3-40a9-bd73-b8b62331d985)

# Step 2 MySQL Server installation
### MySQL is a relational database where we store and retrieve the data in the LEMP stack solution.
### The Sudo-apt install command is used to upgrade to root user to be able to install the MySQL database
-  Installation of Database
![DB1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1f9b3cd6-6928-46e4-97d5-aa2d2800f271)
![DB2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/bce11e47-bdde-4a0e-af84-ba1a4c91f16e)
-  Login to the MySQL console using the Sudo MySQL command
![mysql console](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f8846486-4881-4692-bdab-e8b8dcb07b5d)
-  To Secure MySQL Server using the Script that comes with the package and Exit the MySQL database
![secure script and exit](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/fc73d6ce-6e48-4cc2-8bf7-ee79db20298f)
-  Run the interactive Secure installation and validate the password
![Secure instalation access](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/d2c744c5-069b-4adc-8046-3ffbdb8de504)
![Validation Success](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f24da398-bc1b-4328-8b1b-fe0c550284b9)
-  To Relogin to MySQL console
![Relogin](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7b2d03b5-e2d0-4c8f-9d42-e5cf36d9c119)

# STEP 3 
## INSTALLING PHP
-  Two packages will be installed simultaneously:
-   1. PhP fpm that tells Nginx to pass the request to the Php for processing
-   2. PHP-MySQL that allows PHP to communicate with MySQL
![Php installation 1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2f3021bc-a461-4035-89db-77f86bc6f060)
![Php installation 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/420aa185-de0f-4cd4-bd02-9dec7abaf068)

# Step 4
## CONFIGURING NGINX TO USE PHP PROCESSOR
- Create the root web directory for your_domain and assign ownership 
![Create directory](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c9171073-8a27-4419-825b-de57c4734d53)
-  Open a new configuration file in Nginx’s sites-available directory
![open config](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/9b2c107b-ebd2-4bb8-a040-142ba5dbd69a)
-  Activate your configuration by linking to the config file from Nginx’s sites
-  Test the configuration
![test config](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7450e923-1223-4a18-b1df-a4eefbf93ea5)
-  Disable the default Nginx host and reload Nginx to apply the change
![Disable and reload](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/6b56c674-1532-4edb-b4b2-bf49bfad5365)
-  Create an Index.html file to test the Server block works and go to the browser to open the URL
![create file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/be64d776-fbf3-44a3-92fd-eec8bb5faf39)
![echo hello](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f1052944-1d0d-4a25-953d-6bcc7ea376cb)
![DNS name](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8d454bd9-4308-4cf4-beb9-f7946427e218)

# Step 5
## TESTING PHP WITH NGINX
-  Create a PHP test file using the Nano text editor
![php test page Ip](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/0f4756bf-11de-49d6-a2f7-da7423bdbc45)
![php test page DNS](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8c47c32f-b3cd-45bf-aeba-b2d93c89ed33)
-  To Remove page
![remove test page](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/80df937b-7a44-41d7-886d-aed1edad6990)
# STEP 6 
## RETRIEVING DATA FROM MYSQL DATABASE WITH PHP 
-  Connect to MySQL console
-  To create a new Database
-  Create User for Example database and exit
-  Check to see if you can login into the database with the new password
![creating new database](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/02917350-5973-4f83-9b31-85a0104df57b)
### Show Database
![Show database](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a815cdee-89aa-45db-84df-386b6e07d8be)
-  Create a todo_list test table
-  Insert a few rows of content in the test table
-  Display data output
![To do items](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/63cde55d-bb3c-466a-884a-86d64e2f1ba2)
-  Create a PHP script that will connect to MySQL
![nano php to MySQl command](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/9147f88a-9e0e-435e-a411-22798bafce48)
![nano php to MySQl connection](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a5d83680-be5c-45d1-ab6f-e581b6c946b8)
-  Access on Web browser
![to do list DNS output](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7b907241-9f13-4c8f-9ca7-568eae632c97)
![to do list ip output](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/299385fc-6708-4d2b-8b4d-b067f4d2fda2)


##### Project 4 completion Fajana Kolade









