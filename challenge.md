# Challenge: Security Detective

## Question 1
Answer: I am logged in as user areebahabib. My home folder is /home/areebahabib.
Commands: whoami, pwd

## Question 2
Answer: The server's hostname is ubuntu. It runs Ubuntu 24.04.3 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has around 2.0Gi (or 4.0Gi depending on VM settings) of RAM, and the free disk space can be viewed under the Avail column of the root filesystem.
Commands: free -h, df -h /

## Question 4
Answer: Users that can log in with /bin/bash are listed by filtering /etc/passwd for bash (e.g., root, areebahabib).
Commands: grep "bash" /etc/passwd

## Question 5
Answer: The number of running processes right now is obtained by counting lines in ps aux.
Commands: ps aux | wc -l

## Question 6
Answer: The creation and deletion timestamps for lab5user are recorded in the security authentication log.
Commands: sudo grep lab5user /var/log/auth.log
