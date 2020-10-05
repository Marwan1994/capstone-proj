# capstone-proj
 udacity capstone project
 steps:
 Create ubuntu t3.micro
 ssh into newly created instance
 sudo apt-get update && sudo apt-get upgrade
 sudo apt-get install default-jdk 
 wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'
sudo apt-get update
sudo apt-get install jenkins
