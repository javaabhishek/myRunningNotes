Before anything: 
====================
Steps to setup git on your local. (Windows)

1. Create account on github. (https://github.com/)
2. Download gitbash https://git-scm.com/download/win
3. Create any repository directly on github (From github website)
4. Now first start ssh agent on windows (follow : https://stackoverflow.com/questions/18683092/how-to-run-ssh-add-on-windows)
5. Open git bash in the folder where you want to clone the repository
6. run below command
7. git config --global --unset core.excludesfile
8. git config --global --unset user.name
9. git config --global --unset user.email
10. git config --global user.name "{YOUR_GIT_USER_NAME}"
11. git config --global user.email "{YOUR_GIT_EMAIL_ADDRESS}"
12. Type *ssh-keygen* command, It will prompt some questions but just press enter.
13. After performing step 12, you will see id_rsa and id_rsa.pub in C:\Users\{user_name}\.ssh path
14. Now Open powershell (Run As Adminstrator) and execute *Get-Content ~/.ssh/id_rsa.pub | Set-Clipboard* command.
15. Step 14 command will copy the ssh key from id_rsa.pub (.pub means public key) to clip board.
16. Go to github UI
17. Navigate to Settings > SSH and GPG Keys
18. Click on new Key in SSH key section
19. copy the step 15 key (or content)
20. Now you are ready to perform any kind of operation from your local computer to github repo. 

==================================
About this repository
----------------------------
Adding my study and R&D notes here in the form of ms word/PDF format which may helpfull to others
