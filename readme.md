##Prerequisites

  - Linux Systeme or WSL, i use ubuntu 24.04
  - Git
  
##Step 1: Install Docker and Docker Compose.

  ``shell
  sudo apt update
  sudo apt install docker.io -y
  sudo apt install docker-compose -y``

##Setp 2: Pull this project

``shell
  git clone https://github.com/tchindebebruno/odoo-with-docker.git
  cd odoo-with-docker/
  ``

##Step 3: Build & Run
  ``shell
  docker compose -d 
  ``
##Step 4: Access to odoo and configure it

  ``shell
  http://localhost:8069/
  ``
