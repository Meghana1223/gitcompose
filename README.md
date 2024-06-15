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


