# This project is to document the deployment of a Todolist App on an AWS EC2 Instance. 


This is a basic aws project where I put both frontend(React) and backend (Node js) on one EC2 instance.

### 1) First Step Create and EC2 INSTANCE ON AWS
![image](https://github.com/leoimewore/DevopsRepo/assets/95531716/6acea7cc-0794-4298-903e-ed1f1ec22519)

### 2) Connect to the Ubuntu Linux Server via SSH and the pem key

![image](https://github.com/leoimewore/DevopsRepo/assets/95531716/404f2460-49ff-454b-a5f7-5ab20da2de9b)

![image](https://github.com/leoimewore/DevopsRepo/assets/95531716/9d7428e8-d5c2-4f2e-8dec-b8c58c295e89)


### 3) Update the apt package manager

sudo apt-get update

create a folder to hold all the files:

mkdir Todo

### 4) Install the package manager for node js, so we can install dependencies

sudo apt-get install -y nodejs

Check if node and npm are installed 

npm --version
node --version










