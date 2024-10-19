docker
docker --version
id
docker ps -a
sudo gpasswd -a ubuntu docker
su - ubuntu
exit
docker images
sudo apt update && sudo apt install -y docker.io curl
hostname -i
mkdir nodeexporter
cd nodeexporter/
wget https://github.com/prometheus/node_exporter/releases/download/v1.8.2/node_exporter-1.8.2.linux-amd64.tar.gz
ls
tar xvzf node_exporter-1.8.2.linux-amd64.tar.gz
cd node_exporter-1.8.2.linux-amd64/
sudo apt install net-tools
./node_exporter --web.listen-address 172.31.10.0:8080
ping 3.128.31.136
apache2 -version
cd ~/.ssh
cat authorized_keys
sudo apt install nginx
nginx -version
ps
sudo service nginx status
top
top|grep nginx
cd /var/
cd www/html/
vi index.nginx-debian.html
curl ifconfig.me
man man
env
which mkdir
which rm
echo $PATH
echo $PS1
chsh
git
pwd
mkdir git-for-devops
cd git-for-devops/
vim hello-doston.txt
git init
git status
rm hello-doston.txt
touch nibba.txt nibbi.txt
git add nibbi.txt
git add nibba.txt
git rm --cached nibba.txt
git commit nibba.txt nibbi.txt
git commit -m "first commit" nibba.txt nibbi.txt
git restore nibbi.txt
rm nibba.txt
git restore nibba.txt
vi nibba.txt
git log
git branch
git checkout -b dev
git checkout master
git checkout dev
git log --oneline
touch nibbu.txt
git add nibbu.txt
git commit -m "added changes in nibbu" nibbu.txt
git config --global user.name "rkantbiv"
git config --global user.email "rkantbiv@gmail.com"
git commit -m "nibbu status update" nibbu.txt
git head
history
