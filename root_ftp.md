sudo passwd root<br />
 
sudo gedit /etc/ssh/sshd_config<br />
 
Remove the (#) comment from this line: PermitRootLogin without-password<br />
directly under it add this: PermitRootLogin yes<br />

Now restart SSH: sudo service ssh restart<br />

ref: http://askubuntu.com/questions/618098/want-to-enable-root-direct-login-to-telnet-ssh-ftp <br />
