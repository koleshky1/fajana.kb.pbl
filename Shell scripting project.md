32# Shell Scripting Auxilliary Project
# steps
1. Variables: variables can store different data types or values such as strings, numbers, and arrays. The operator = is used to assign values  to variables while the values are output using the variable name, $ alongside the echo command.
![hello john](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/6311f9ad-6642-4057-ae11-6f6090a9cd37)
2. Control Flow: Bash as an interface has provision for control flow statements like if -else, while loops, case statements, and for loops that control the steps of task execution in scripts. This helps in decision-making and others. Example:
-  Using the if-else statement to execute the script based on certain conditions ( check if a number is positive, negative, or zero).
![positive](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a235d73f-a290-442c-8915-39a6d36bd3cc)
![negative](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/3c3356dc-76e6-47fb-b369-51e9a9f1b1df)
![zero](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/4247efeb-093c-4576-8d38-033f5334f3f1)
- Iterating through a list using a for loop: This control flow statement keeps increasing the number from 0 to 5. When it equals 5 the script stops the execution of the task.
![iterative](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f01ec5cf-c799-44ce-99cf-d928c694f172)
3. Command Substitution: this allows the user to capture the output of a command and use it within the script. The backtick and the $() syntax can be used for command substitution.
- backtick use:
![backtick](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/42aa4966-1b00-451c-a542-9e6dc113d059)
- Syntax use:
![syntax](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a6772bb0-a830-40d1-85f4-6f3a8bcab7a6)
- Other variants:
-  inclusion of hours, minutes, and seconds.
![inclusion of date and time](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/cb685900-0b1b-44ad-994d-7e741da5aadb)
-  Abbreviated form of the afore-mentioned where F represents date and T represents time ( hours, minutes and seconds:
![abbreviation ](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/fef1b8b9-23dd-49bd-988a-b7ad16ab34fa)
4. Input and output: bash has a provision for executing input and output.
-  The output can be displayed on the screen using the echo command.
![accept input](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8294597c-c6ee-4d9d-ab61-90b0b725ec8d) 
-  an redirect input and output; operator > ( pass output to a file) and operator < (pass input from a file)
-   Grep command | pipes the output of a command as the input of another
5. Functions allow users to group related commands together; it allows for code to be modularized and more reusable.
![function](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/e86116dd-41ab-40a0-8d99-ecbf612d25f3)
6. First shell-scripting:
- Creating a directory
![create a directory](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/75da311d-dac8-43d5-a4b1-6f492c478f08)  
- creating a file called user-input.sh
![create file user-input](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/c54d9df0-3ccc-4fb8-8246-35c0685689d0)
- paste the block code inside the file
[user-input](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/644b6b03-dad0-48b4-b37b-1d2d406a2b27)
7. Directory manipulation and Navigation:
- The script will do the following:
-   display the current directory
-   create a new directory "my_directory"
-   change to the directory
-   create two files in the directory
-   move back one level up
-   remove the directory  "my_directory" and its contents
-   finally, it will list files in the current directory
-     create a navigation file
![navigation file creation](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/50ea54b5-df86-4e74-81b8-ed4f131f49d1)
-     paste the code block
![opening file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/976abd8f-aa74-4a21-883e-06ce1d343c54)
-     run the command chmod +x file name to make an executable file
![exectable file](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/95322585-f4ab-4ce8-a8cd-888cf88ee6fa)
-     Run the script
![navigation 1 done](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8413160a-aa9f-439b-9ba7-9b569bd0e4ee)
![navigation 2 done](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/530e74f7-94d9-4cf1-9ae9-98b73eaab82c)
8. File Operations and Sorting:
- The script will do the following:
-     create three files
-     display the files in their current order
-     sort them alphabetically
-     save the sorted files in sorted_files.txt
-     display the sorted files
-     remove the original files
-     rename the sorted file to sorted_files_sorted_alphabetically.txt
-     finally, it will display the contents of the final sorted file
-       create a sorting file
![sorting file created](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/1479c742-4158-4e2c-9954-94e9183851a9)
-       open the file and paste the block of code
![block of code](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/de580813-c64b-4461-9276-3c15c111dd2a)
-       Make file executable by running the chmod command
![sorting executable](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/95dee64b-e6a1-47cb-84c9-b6b0ae377f31)
-       run the script
![sscript1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/ed8ebfea-6a76-499a-ba63-d2a5775cf8c6)
![sscript2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/473feeba-59a8-46da-b588-bc031cfca3c9)
![sscript3](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/84488bc3-00bb-427f-a1b2-ec38a0584692)
9. Working with numbers and calculations.
The script defines two variables and performs various calculations on the variables like addition, subtraction, and more.
-       create a calculations file
![calc file creation](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/0079f228-cba0-4a90-9918-5e68cda0618b)
-       Make file executable
![calc executable](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/63e8cf64-f337-4e8e-8021-f5cefc72601f)
-       Run the script  
![calc script 1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/58cc7819-3d99-461e-a767-861c6fa626f5)
![calc script 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/2632aab6-0563-4585-a6cd-751124006276)
10. This script defines source and backup directories, creates a backup directory timestamp, and others.
-       Create a backup file
![backup file creation](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/e557fcd4-6c53-47c0-a39b-1086ab059ecb)
-       Copy the block of code![block of code for backup](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a1fe39fc-f262-423e-b684-bcf3efaa124d)
![block of code for backup](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/a1fe39fc-f262-423e-b684-bcf3efaa124d)
-       Make the file executable using the chmod command
![backup executable](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/dbbdb5fb-05b5-4bea-92ff-0f7f37ea5554)
-       Run script
![backup done](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/d1855819-1457-42c0-a86d-0fc989752123)
