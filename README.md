# gitcompose
gitcompose

### 1. Create repository :- 
-Remote repository steps :-

-Create repository >> new repository > name > description > public > add a README file > create repository 

-Delete the repository 
Settings >scroll down and delete the repository .

 - After creating the repository, repository files clone to the local system from the github using the below cmd .
- git clone code ur             --------->    
  git clone https://github.com/Meghana1223/Googleworkspace-project.git

- ls              >>>  cd repository name/  >> ls -la             {change directory to repository }

 -When we clone the remote to local we identify the file like .git

 -Download the visual studio code > create a file > select the path in the local system. > execute the code in vs files .

#https://docs.docker.com/compose/gettingstarted/   [take the reference for code for creating files on vs ]

 # Add  
Add cmd is used for adding files from the workspace to stage state 

- Git add filename 

 - If we want to add file one by one we can use git add filename filename  

or 

 - If we want to add all the files from workspace to stage state cmd is git add .

# Commit : 
- saved the files into the database with message 
- Cmd: git commit -m “message which you want to describe ”

#Git status 

- Push the file from local system to remote system [github]
git push origin master [branch name :- master/main]

- When we push the files from local to remote, the prompt will ase the Username and password.

# Generate token key

- Click on profile > Settings > developers settings > personal access token > token classic > copy the key 

- Github UN :-xxx
- Github key:- XXXX

- Use the key whenever you push the files  to a remote repository.
- Don't use the password, in the place of the password use the key.
- When we login to a github account use username & password.
- When we use the command line interface git bash , connect to the terminal using the key .[key based authentication ] connect to a remote system .

# Parallel working
Develop 1 :- windows which we use the git bash

Developer2 system for join to the project :-

- Create the ec2 
- Connect to mobaxterm 
- Install the git in the mobaxterm 
- In dev2 system we need to install the git & configure the git settings 
- Install the git in linux system :- sudo yum install git -y

- Before we do that git configuration we should need to specify. [Username & email]

- git config --global --list [ To check the username and email ID ]

 - To specify the user name :-  git config --global user.name “scorptors2”

- To specify the email :- git config --global user.email “scorptors2@gmail.com”
git config --global --list 

ll

Pwd  :- user location 

- Git clone https://github.com/Meghana1223/gitcompose.git

- ll >>> git compose repository

cd repositoryname/    {gitcompose}

ls or ls -lrth

============================

Develop1 system git bash 

git pull origin main   >> in git bash

In dev1 system is doing some changes in the readme.md file 

git push origin main 

Everything is done, modifications are changed in the files.


# 2,{parallel working}

Mobaxturm 
While doing the dev1 parlelly dev2 also doing the development in his instance system

vi dockerfile 

Adding content to the dockerfile in the dev2 system using vi editor [same files in the dev2 and dev2]


 Same as modifying the data in the readme.md file also in the linux interface

vi readme.md >>> Save the file :wq

Dev2 is ready to push the files to repository

- Git push origin main 

Github Username :- Meghana1223

Password : use token key       

# day:4[time:- 37:00]  

keyname :- name>>  dev-2 ec2instance 


==================================================
Modificatins done in this file for develop branch 
=====================================================
changs develop branch to dev to dev 







