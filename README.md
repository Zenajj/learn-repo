# Commands
## clone
Bring repo that is on github (or smth else) to folder on your pc
## add
track your files and changes in Git
primer: 'git add .' --- dodamo vse datoteke (untracked and modified)
## commit
save your files in Git (localy, če hočemo dati na guthub moramo dati še push)
primer: 'git commit -m "message content" -m "description"' -m pomeni message in doda sporocilo zakaj smo commital
## push
upload Git commits to remote repo like Github
primer: 'git push origin master'
## pull
download changes from remote repo to your local machine
## status
shows updated / created files, but were not commited

## creating new ssh key
ssh-keygen -t rsa -b 4096 - C "my.email@gmail.com" 