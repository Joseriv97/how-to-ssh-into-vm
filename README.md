Step 1. # how-to-ssh-into-vm
Step 2. how to ssh into vm: for beginners 
Step 3. verify port 22 is open on vm and verify by using netstat -natp
Step 4.this will show which ports are open
Step 5. then you will enter the following commands
Step 6. sudo systemctl status ssh.service
Step 7. type your password when prompted
Step 8. sudo systemctl start ssh.service
Step 9. insert again to doublecheck your ports
Step 10. then type q to exit 
Step 11. netstat -natp
Step 12. ifconfig to get your ip address
Step 13. then go to command prompt
Step 14. insert ssh usernam@ipaddress then password when prompted
