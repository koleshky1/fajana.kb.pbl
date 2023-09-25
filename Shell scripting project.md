32# Shell Scripting Auxilliary Project
# steps
1. Variables: variables can store different data types or values such as strings, numbers, and arrays. The operator = is used to assign values  to variables while the values are output using the variable name, $ alongside the echo command.
   
![variable](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/198e6135-e1ee-4f06-a072-bb298cb15d85)

2. Control Flow: Bash as an interface has provision for control flow statements like if -else, while loops, case statements, and for loops that control the steps of task execution in scripts. This helps in decision-making and others. Example:
-  Using the if-else statement to execute the script based on certain conditions ( check if a number is positive, negative, or zero).
![ctrl flow1](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f8afb3e7-c52d-45a4-b200-8f5f67f8c704)
![ctrl flow 2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b533334b-d121-47cd-b246-5687705d391d)
![ctrl flow3](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/5729b1c0-9d44-4c7f-9e70-271fbbc93392)
- Iterating through a list using a for loop: This control flow statement keeps increasing the number from 0 to 5. When it equals 5 the script stops the execution of the task.
![iterative steps](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/7c9fd274-4274-422e-be46-0c9f2e39992f)

3. Command Substitution: this allows the user to capture the output of a command and use it within the script. The backtick and the $() syntax can be used for command substitution.
- backtick use:
-  error: Git bash does not recognize the command.
-   the error is used to the absence of $ sign utilization and bash does not actually recognize the command but gives the needed output.
  ![error on backtick](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/f5d5fd19-4eca-4c79-be45-738bf9c4f227)
- Syntax use:
![syntax](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/b445be8c-6857-4813-9d44-e1dc1879b6f6)

- Other variants:
-  inclusion of hours, minutes, and seconds.
![variant2](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/38377dd8-040d-4d53-810f-7f97d9280e98) 
-  Calendar date:
![calendar date](https://github.com/koleshky1/fajana.kb.pbl/assets/44333161/8d30eea5-5085-4f29-ab37-f9a0ccb6c35c)
4. Input and output: bash has a provision for executing input and output.
-  The output can be displayed on the screen using the echo command.
-  can redirect input and output; operator > ( pass output to a file) and operator < (pass input from a file)
-   Grep command | pipes the output of a command as the input of another




