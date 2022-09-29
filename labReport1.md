Hello incoming CS15L students! Here is your cheat sheet for remote access (FOR WINDOWS)

First, instal vs code on your personal device by going to [Link] https://code.visualstudio.com/
Next, install OpenSSH in the apps section of settings through the optional features button
After, step up your CS account and password at [Link]https://sdacs.ucsd.edu/~icc/index.php
Next, try signing into the remote server using ssh cs15lfa22zz@ieng6.ucsd.edu on your terminal  (it may take a while for the password to work) 
You should see something that looks like this after logging in [Image] ..

Now you can start trying out some commands!
Some to start with are:
cd~
cd
ls -lat
ls -a

Once that works you can try copying files into your remote server. To see what files you currently have in your directory use the ls command
First change to your home directory using cd~
Next create your file and save it somewhere on your personal computer
After, use scp <file path> <where to copy to (cs15lfa22zz@ieng6.ucsd.edu:~/)>
Now you can log into the remote server and list the files. You should see the one you have just copied
  

Now you are ready to use SSH keys to make this login process easier!
 


