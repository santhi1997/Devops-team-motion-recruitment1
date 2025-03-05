**create a Jenkins in the aws

1) Open instance in the platform
2) Connect to the instance
3) Use the following commands for installing the Jenkins:
* sudo wget -O /etc/yum.repos.d/jenkins.repo \
& https://pkg.jenkins.io/r edhat-stable/jenkins.repo
* sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
* sudo yum upgrade
4) Add required dependencies for the jenkins package
5) sudo yum install fontconfig java-17-openjdk
6) sudo yum install jenkins
7) sudo systemctl daemon-reload.
8) run This Command in your Instances:
9) To start the Jenkkins use Following commands:
* sudo systemctl enable jenkins
* sudo systemctl start jenkins
* sudo systemctl status jenkins
10) Run The Command to start and check the Virtual Machine(VM)
11) Change inbound Allow the code 8080 for the accesing of jenkins
12) Use your ip address with 8080 to open jenkins
13) create your own jenkin profile using your details.
14) finally jenkins is setuped in your instance
