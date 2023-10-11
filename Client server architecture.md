# Client Server Architecture MySQL DBMS Project
# Steps:
1. Set up two instances.
-  Spin up two instances with the names MySQL server and MySQL Client
2. Connect your Git Bash terminal to the MySQL Server.
![connect Git bash terminal to AWS platform](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/78c8416c-fbc9-4105-b83c-8840ebb10f05)
3. Update with Sudo apt update.
![sudo apt update](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/5152dc31-4259-4a8c-b8d2-05cd60e2edaf)
4. MySQL Server software Installation.
-  Install the MySQL Server software.
![server install1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/66b03911-0ac6-4188-82e6-bf5bd83b2c63)
![server install2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/5f5aa661-1baa-484f-95c5-7ebbf477f6e3)
- Reconnection to the Server after rectifying my Windows System Errors.
![reconnection due to error](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/36376be4-651e-40ee-8174-619b15e97128)
- Start the MySQL Server with the enable command and check the status.
![enable and check status](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/787b3286-6e63-4dd3-8811-d2e9726be0b9)
5. Connect, update, and install the MySQL Client through the Visual Studio code.
-  SSH On git bash terminal in visual studio code to connect to the MySQL Client.
![ssh1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/42f63659-1f09-409a-bc9a-18c5491ca812)
![ssh2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4a9938ba-9b8d-4ddd-bb4c-37c7821ae1a5)
-  Update client sudo apt.
![client sudo update](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/029888de-0868-4878-96a8-5cc9f29cfe9d)
-  Install the MySQL Client software.
![client install1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3e487e23-84a4-438b-a4cb-2edce0426758)
![client install2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1c89ff81-e3f0-4df8-a179-1478cd6d7f8f)
- Check the status of MySQL Client.
 ![client status](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2841cf9f-33f8-4104-925c-d04f551c6591)
6. Edit the Server Inbound rules.
-  On the MySQL Server security Group open port 3306 MySQL/Aurora and restrict access to only the client IP address.
![edit server inbound rule](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/acd7a018-4e37-4b58-82c8-0da4b6f1624b)
7. Configure MySQL Server to allow connection from remote hosts.
![pre binding command](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/53cb98ae-ee61-4e61-8a6d-b10601c843eb)
![previous bind address](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c497ca12-a23f-4a1c-8ac9-7d1fd038d6fd)
![post bind address](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/0a8ef35d-0561-4634-9809-1e918c5c9332)
8. Create MySQL Server Database
-  Run MySQL secure installation
![MySQL secure installation](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7d874bf7-333f-42d1-b747-b2297777ce25)
![MySQL secure installation1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/81105b2c-1ff2-46e6-ab5d-53113347576b)
-  Log in to MySQL.
![log in to mysql](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2338ad44-dbee-4fc4-bf93-bf8ae0f472f9)
-  Create MySQL User.
![create my SQL user](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/29204d81-bf7f-4074-af4f-c4a0c7ebdb2e)
-  Create My SQL database.
![create MySQL database](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/45539a27-006a-46be-a417-91c636b31f12)
-  Grant access to the database.
![grant mysql databse privileges](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/37d576a2-2f59-48d4-9ca7-e0aea41abaff)
-  Flush the database.
![Flush privliges on mysql](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1bf53c66-415a-46b2-a65a-2a3e3c489a2e)
-  Exit MySQL.
![exit mySQl](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b7ec4aea-215c-4efd-bebf-4eb20d32d8dc)
9. Connect to the MySQL Server Database from the MySQL Client using the MySQL utility without doing SSH.
![client to server connection1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f7f6a27d-87be-47a0-ab84-aa57d665ffe7)
![client to server connection2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a29278b2-f0db-45c6-a432-350e80fe1746)
10. Show the database.
![shown database](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7f4fd521-21ba-43ac-bda2-b8d45f6f948b)







