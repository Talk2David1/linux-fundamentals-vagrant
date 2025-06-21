# linux-fundamentals-vagrant
![image (1)](https://github.com/user-attachments/assets/fba96104-0f06-4818-87ec-d2d48c081bf9)
Used the terminal window within VS Code to Initialize Vagrant to use an Ubuntu/Jammy64 virtual machine.
Vagrant up is used for bringing up a Vagrant-managed virtual machine. It's using VirtualBox as the provider and It successfully downloaded and added the ubuntu/jammy64 box (version 20241002.0.0).
![image (2)](https://github.com/user-attachments/assets/1667db6f-1ec1-4e87-bc6e-4c5cc875eee4)
vagrant ssh command was run and there was a successful SSH connection to the server

![image (3)](https://github.com/user-attachments/assets/664fb402-9f49-4f83-ad68-f2407f50a213)
Created a folder called projects and created another folder called devops inside the projects folder

![image (5)](https://github.com/user-attachments/assets/814b4878-c6c8-42dc-a242-717b2cfdaf57)
drwxr-xr-x for projects: This indicates projects is a directory (d). The permissions are rwx (read, write, execute) for the owner (vagrant), rx (read, execute) for the group (vagrant), and rx (read, execute) for others.
chmod 744 projects command changes the permissions of the projects directory to have rwxr--r-- permissions.
chmod 777 projects command changes projects directory to have rwxrwxrwx permissions, meaning everyone has full read, write, and execute access.

![image (6)](https://github.com/user-attachments/assets/7feed44c-d47d-45f5-b827-5004562e9f78)
The command sudo apt install nginx downloads and installs the Nginx web server software on the Linux system where the command is executed, using administrative privileges.

![image](https://github.com/user-attachments/assets/c3dec953-b21a-4edd-8804-da98a6ce91d1)
The Vagrant Ubuntu VM successfully connected to and received responses from Google's servers, demonstrating active network connectivity and providing measurements of the connection's latency. The connection appears stable with no packet loss.
