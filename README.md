# azure-devops
This a repo for azure devops

# Before we start

1 - Create ssh-keys in Azure Cloud Shell 

ssh-keygen -t rsa
cat /home/odl_user/.ssh/id_rsa.pub

Then we add keys-pairs to our repo 

2 - git clone git@github.com:khalil117/azure-devops.git
3 - git status to see modified file 
4 - git add * to add all modified file
5 - git commit -m "adding a change to the README"

# if this was the first commit , we need to run additioanal commands 

 a - git config --global user.email "you@example.com"
 b-  git config --global user.name "Your Name"