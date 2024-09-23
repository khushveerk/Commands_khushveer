# Commands_khushveer

# CONTENTS -
 
  i) USING EC2 IN AWS
  
  ii) USING CONTAINER IN VM and adding         nginx server by Docker
  
  iii) USING MINIKUBE

# 1. using EC2 in aws:- 


First open aws search EC2 then Launch Instance and there select keypair in putty or pem then download it

--By using pem file for linux

ssh -i /path/to/your/pemfile.pem ec2-user@your-ec2-public-ip

--By using putty

after that Launch it and run putty and paste public id on HOST NAME and open that downloaded key pair for putty in SSH then Auth then Credentials and open there

after that run it and write username as ubuntu as selected os and then type following commands:-

sudo apt update

sudo apt install apache2

--to install a web server on ip then

sudo su

for convert $ into # for getting admin role then

cd /var/www/html/
then

ls
for list of html file in it

then copy that html file name and write

rm index.html
rm means remove command

vi index.html
this will open a notepad like and write html code there like (vi is editor) -



then press ctrl+c then shift+colon then write wq and enter

now copy your public ip and paste it on browser you will see the texts written by you (by using html above)
