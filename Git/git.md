1. config  
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"

2. ssh-key   
ssh-keygen -t rsa -C "your_email@example.com"
add content in ~/.ssh/id_rsa.pub to github

3. git command  

git pull origin master  
git pull --rebase origin master  
git push origin master  
git push origin master -f  
git remote -v  
git remote add \<name\> \<address\>  
git rebase -i \<commit id\>  
git rebase  
