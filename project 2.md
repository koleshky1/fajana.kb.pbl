# Step 0
## Spin up a new EC2 instance with the following details:
### Project 2
### Unbuntu 22.0
### and others
## Connect Git to AWS by applying the key pair
![AWS to Git connect](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/da4cfd77-9b1f-4b66-9f65-23c16852bf52)
# Step 1 
## STEP 1 – INSTALLING THE NGINX WEB SERVER
### First update the Service package with the Sudo Apt command
![sudo apt update](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b93c7a14-8449-4da2-968e-a1c06fac1af2)
### Install the Nginx server
![Nginx 1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3844dbf9-574b-4b5d-b39b-0cfc461bacd4)
![Nginx 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3e204f07-266f-4253-acdc-7532e76935f8)
### Verify Nginx is active using the SystemCtl command
![Nginx active](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dae8f93e-9694-450f-81fe-dd7bba33517a)
### Open TCP port 80 to allow Web access
![allow HTTp access](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a24e365f-def3-41b5-809f-3b8961602eac)
### Accessing the server locally from the Ubuntu shell using the Curl command
![local host](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/5efe0810-daaf-4f84-8257-28c91bc9a4c1)
![local host1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/af2518c5-729c-4038-855f-0a56743b7714)
### Testing the Nginx functionality on the Google browser using the public IP
![Testing on browser](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a7a4d45f-5c87-46ce-ae32-63f20935336c)
### Public IP retrieval
![retrieval](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dcf4fd5f-efb3-40a9-bd73-b8b62331d985)

# Step 2 MySQL Server installation
### MySQL is a relational database where we store and retrieve the data in the LEMP stack solution.
### The Sudo-apt install command is used to upgrade to root user to be able to install the MySQL database
## Installation of Database
![DB1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1f9b3cd6-6928-46e4-97d5-aa2d2800f271)
![DB2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/bce11e47-bdde-4a0e-af84-ba1a4c91f16e)
## Login to the MySQL console using the Sudo MySQL command
![mysql console](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f8846486-4881-4692-bdab-e8b8dcb07b5d)
## To Secure MySQL Server using the Script that comes with the package and Exit the MySQL database
![secure script and exit](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/fc73d6ce-6e48-4cc2-8bf7-ee79db20298f)
## Run the interactive Secure installation and validate the password
![Secure instalation access](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/d2c744c5-069b-4adc-8046-3ffbdb8de504)
![Validation Success](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f24da398-bc1b-4328-8b1b-fe0c550284b9)
## To Relogin to MySQL console
![Relogin](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7b2d03b5-e2d0-4c8f-9d42-e5cf36d9c119)

# STEP 3 
## INSTALLING PHP
### Two packages will be installed simultaneously:
#### 1. PhP fpm that tells Nginx to pass the request to the Php for processing
#### 2. PHP-MySQL that allows PHP to communicate with MySQL
![Php installation 1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2f3021bc-a461-4035-89db-77f86bc6f060)
![Php installation 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/420aa185-de0f-4cd4-bd02-9dec7abaf068)
# Step 4
## CONFIGURING NGINX TO USE PHP PROCESSOR
### Create a projectLEMP file




