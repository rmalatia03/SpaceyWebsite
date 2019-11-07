# SpaceyWebsite

Steps to pull from master to local files and then push to personal repo:


Create a fork of the repository in your own by clicking fork in the top right

Open your code editor/terminal and navigate to where you want to place the new project (cd "path")

git clone https://github.com/(your github account)/SpaceyWebsite.git

enjoy

git remote add upstream https://github.com/SpaceyDevs/SpaceyWebsite.git
git fetch upstream

git checkout master

git merge upstream/master

git add .

git commit

git remote add myrepo https://github.com/(your github account)/SpaceyWebsite.git

git push myrepo master (upstream and myrepo are essentially variable names so if they are saved to the wrong repo you can try 
using a different name. I am Unaware of how to reset those at this time)

initial setup of project in visual studio code

https://gist.github.com/jedmao/5053440
