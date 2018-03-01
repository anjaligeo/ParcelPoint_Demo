# ParcelPoint_Demo

1. Prepared development environment , used AWS EC2 instances. 
2. Used Jenkins offical Dockerised image from docker hub. 
3. Created Ansible playbook , 
    Created Role called "prepare" - installed the docker and started the docker daemon process. 
    Created Role called "jenkins" - Deployed the jenkins docker image, pointed  default 8080 port to 8081. 
4. Login to Jenkins as Administrator and created a free style project to checkout code from github. In this case I used the same project ParcelPoint_Demo. The build.xml is saved under ~/jenkins_build/ folder. 
