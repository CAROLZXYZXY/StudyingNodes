### Run Docker Environment
> sudo docker pull zxycarol/ubuntu-14:openie-backend   
> sudo docker run -it zxycarol/ubuntu-14:openie-backend /bin/bash   
> cd /home/xinyi   
**Please be careful when running with root user access**  


### How to Configure the Docker Environment  
> sudo docker pull ubuntu:trusty  
> sudo docker run -it ubuntu:trusty /bin/bash  

+ Install jdk 7
> sudo apt-get install software-properties-common  
> sudo add-apt-repository ppa:openjdk-r/ppa  
> sudo apt-get update  
> sudo apt-get install openjdk-7-jdk

+ Install scala 2.9  
> apt-get install scala  

+ Install Sbt  
Please follow https://github.com/paulp/sbt-extras  

+ Compilation   
Please follow https://github.com/sbt/sbt-assembly/issues/331  
