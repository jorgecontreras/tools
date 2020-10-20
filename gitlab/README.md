# Gitlab installation in Mac OS 

1. Install VirtualBox
2. Install Vagrant
3. Execute vagrant up (from same folder where Vagrantfile lives)
4. Log into the box: vagrant ssh
5. sudo apt-get update
6. sudo apt-get install -y curl openssh-server ca-certificates 
7. curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
8. sudo EXTERNAL_URL="http://192.168.50.10" apt-get install gitlab-ce
9. open http://192.168.50.10
10. Done!
