## Install Docker on Ubuntu  
    
    sudo apt update
    sudo apt upgrade
    sudo apt install docker.io
    
## Download source code
    
    sudo apt install git net-tools
    git clone https://github.com/Greenhat1998/OnlineJudgeDeploy
   
## Login as root and setup OJ
    
    sudo passwd root
    su -
    cd /home/{your_user}/OnlineJudge
    apt install docker-compose
    docker-compose up -d
    
# DONE!!!
