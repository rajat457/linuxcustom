# linuxcustom

**Scenario** There is a customer who came to you with a problem to have a custom linux
command for his operations. Your task is to understand the problem and create a linux
command via bash script as per the instructions.

Command name - internsctl

Command version - v0.1.0

Step 1: Set Up Your Bash Script
Create a new file named internsctl and make it executable:

![image](https://github.com/rajat457/linuxcustom/assets/91472404/2e4a6c3b-c9a8-40b7-8d27-8162f782865f)

Step 2: Open the Script in a Text Editor
Open the **internsctl** file in a text editor of your choice. You can use nano, vim, or any other text editor you are comfortable with:
nano internsctl

Step 3: Write the Initial Structure
Inside the internsctl file, write the initial structure and shebang

Step 4: Implement Section A - Manual, Help, and Version
Continue building the script by implementing Section A - Manual, Help, and Version. Add the necessary functions and content inside the existing script structure.

Step 5: Implement Section B - CPU and Memory Commands
Extend the script to include Section B commands for CPU and memory. Implement the functions get_cpu_info and get_memory_info with the appropriate code to retrieve and display the information.

Step 6: Implement Section B - User Commands
Add the functions create_user, list_users, and list_sudo_users to handle user-related commands.

Step 7: Implement Section B - File Commands
Add the function get_file_info to handle file-related commands. Implement the necessary code to retrieve and display file information.

Step 8: Handle Command Line Arguments
Modify the existing case statement to handle various command line arguments. Update it to support the structure and options specified in the scenario.

Step 9: Test the Script
Test your script with various commands to ensure it behaves as expected. You can use sample inputs and check if the outputs match the expected format.

**./internsctl --help**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/37a852d6-21ab-44f0-b4d0-ef2a20a7db69)

**./internsctl --version**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/383127c2-6936-4fdb-93e1-bafa93389fe7)

**./internsctl cpu getinfo**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/0a0ce1a5-89b1-4967-893f-d500d640f82a)

**./internsctl memory getinfo**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/074aa5f1-4f6b-4827-99fc-cf37e5a7961f)

**./internsctl user create <username>**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/b56b3d07-2da6-454b-ba46-11007a2bd3ab)

**./internsctl user list**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/c257e23e-e3ff-43d2-9ba0-1799edc595ce)

**./internsctl user list --sudo-only**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/76703fdd-1f20-445b-b1b1-04cae0c13a38)

**./internsctl file getinfo <file-name>**

![image](https://github.com/rajat457/linuxcustom/assets/91472404/2bc717ab-0fea-4187-ba50-1204087bf602)
