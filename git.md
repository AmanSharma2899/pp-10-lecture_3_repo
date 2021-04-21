# Upload code to github

## First time setup

* git config --global user.email "amansharma.2899@gmail.com"
* git config --global user.name "Aman Sharma"

## Do everytime when using git

* git init -> timeline created for that particular folder
* git add . -> add all files/folder within folder for tracking
* git commit -m "messege" -> create a state/timestamp within that timeline that we can access later, all commits are associated with 
                             an id and author name and email id
* git log -> list of all commits

## create a repo on github

* git remote add origin your **Repo Name**
* git branch -M main
* git push -u origin  main