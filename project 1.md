# WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS
# Step 1
##  Connection to AWS successful
![when connecting to Aws platform](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/81eb29fa-92bb-45d3-92d9-a2604e307b59)
## Test of hostname
![hostname brought back ip address](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/29c26d0d-deb7-42d0-aefe-cbcd99910757)
## Update a list of packages in the package manager
![update](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8a56fce6-7a84-454e-af0c-c5f2e3da0255)
## Upgrading the List
![upgrade](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7f651bed-428f-4bd4-8f2f-19f2c78a90b1)
# Step 2
## INSTALLING APACHE AND UPDATING THE FIREWALL
![installing apachea](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c3d1c1a9-b668-45c7-acb8-11e4c845d8c5)
![installing apacheb](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dbe25977-a544-4ba7-86c1-e04d627a6f1e)
![installing apachec](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/39214544-3b41-4021-9ea1-a83085b09103)
## To check if Apache2 is running and active
![Apache active](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/d4a465ad-7dc7-4f52-b2bd-b730b42923f9)
## To allow port 80 for HTTP
![open port 80](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/cdd1d311-4120-498a-bdd1-79acac9fe959)
### The Curl command renders  Apache page in HTML and CSS code (DNS name)
![aapache http and css code](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c8c11ad3-1409-48b7-a228-5819e243d1fa)
![curl continued](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/54dd6351-e12c-4146-9052-c9116aa2e6af)
### using the Ip address for the same Purpose
![using the Ip address for the same![using the Ip address for the same Purpose](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/6a7ace81-ba75-49d5-8923-d615446536fe)
 Purpose](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4a911b67-53ef-4496-bacf-effe365b7af5)
 ### Testing the Apache Web Server for response to Internet requests
 ### Opening the Google web browser and  attempting to use the public URL to display the Apache homepage
 ### First retrieve the IP using the Curl command
 ![Ip retrieval](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/0d0bb315-171b-4512-93cb-1c79800865bc)
 ### Pasting IP in a Web browser and check the functionality.
![Apache homepage](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/23c8ccf3-a032-4636-b4af-a9ff32259f31)
 # Step 3
 ## Install MySQL Database
 ### Use the apt command to get and install the MySQL software
 ![Installation MySQl](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/507fbabe-e439-4a3a-8996-1993370a6a34)

 ## To log in to the MySQL console
 ![MySQLconsole](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/ad0946da-290c-4f7c-a14e-de2e904c89ee)
 ## To exit 
 ![exit MySQL](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/40d141ab-a987-42ae-b214-88da3c0a3ba9)
 ## My SQL security validation steps.
 ![My SQL query](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c7f67e53-f2c2-48e4-8b00-fcec93140478)
 ## Password validation
 ![Validation of the password](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/0d951c8b-961a-4bda-8a14-5bc6fea43dcc)

![MySQL Validation success](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4d115cec-f291-48f3-a790-5dc4835472d4)
## To test if login to the console is possible
![to test Login](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b9a897b2-9134-4488-a7d0-a87c0493d746)
## Exiting MySQL
![image](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/760786ae-ca68-4eac-a449-399a079b7084)
# Step 4
## To Install PHP
### Three installations will be done together:
#### 1. Actual PHP installation.
#### 2. PHP-MySQL code to allow PHP to communicate with MySQL.
#### 3. A library that allows Apache to handle PHP files.
### Errors are shown while trying to install the three above
![Errpg1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/6ef71e60-f96b-444b-bc89-98c1f42e2101)
![Errpg2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c4445919-3deb-40fe-8a97-a384c3dda576)
### Errors rectification by updating Ubuntu using the apt-get update command
![error correction](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/783e2f29-a09c-4a73-b64e-a376fb186444)
### Installing the three packages
![Installing the three PHP packages](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1f1291df-aed1-4b93-8833-305fc05b42b0)
### PHP version confirmation
![PHP version](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/215b4abf-ebea-438b-a25a-261d3fee86c6)
# Step 5
## CREATING A VIRTUAL HOST FOR YOUR WEBSITE USING APACHE
### Create a directory Projectlamp
![steps to creating file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/9ded239e-903d-4e7e-a547-261aab04094e)
![save modified file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/490f0ce8-1b2f-41ea-b78d-b97cfe232e3c)
### To see if the file is available
![file availabilty](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/39f98de6-4939-401f-9a6c-259be665b38b)
### To enable the new Virtual host
![To enable the new VH](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8d3dc111-cfb5-4bc7-bb99-10b9c7ee1590)
### To disable the Apache default website
![disable default site](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2f46f1ee-6dad-4509-b85d-a72e181abd30)
### Removal of Syntax errors in Configuration
![Syntax error Rem](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b7e9500e-6231-4896-89ee-22a01bef1aab)
### Apache Reload 
### Create Index.html file in projectlamp
![Hello lamp](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/ed85ec6f-0709-4fac-8a3e-f365c16c1e31)
#### Accessing through the public DNS
![public DNS](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c68303e0-77a3-476b-b19b-7263a4e5c53c)
# Step 6
## ENABLE PHP ON THE WEBSITE
Changing the website display hierarchy index.php as the first website.
![changing to index php as default](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/634a3da8-4e4f-4164-8ed0-656a2b8346e5)
### Reload Apache
![Reload Apache](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a1afca06-57fb-43ec-87ea-10b5957512c4)
## To create a PHP test file
![php test file command](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/fc3ffca4-e07f-4c40-96e9-85b0f64b4f34)
![php test file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4d788be9-b3f0-45a2-8737-a972bf33308d)
## PHP page display
![new ip address due to instance stopped](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c37c115b-2f40-47a8-925e-014004f996af)
![New DNS](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f523911d-eab6-4e4d-8abd-a7e10695926c)
## PHP page removal
![PHP page removal](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/984729d3-9146-4f65-b5de-0dce85fb2c6a)
![PHP last page display](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4f9df85b-a872-492e-9dde-1c6b80492d89)






