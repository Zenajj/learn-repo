# Commands

## init

doda folder iz katerega smo pognali ukaz kot gitfolder
primer: 'git init'   
ČE želimo dodati ta repozitorij na github, naredimo na github nov repo z istim imenom, nato poženemo ukaz: 'git@github.com:Zenajj/demo-repo.git'

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
primer: 'git push origin main'

## pull

download changes from remote repo to your local machine

## status

shows updated / created files, but were not commited

## branch

nam pove na katerem branchu smo in pokaže vse branche

## checkout

z tem ukazom spremenimo na katerem branchu smo  
primer 'git chekout main' gremo nazaj na main branch
da naredimo nov branch uporabimo -b    
primer: 'git checkout -b feature-readme' z -b naredimo nov branch z imenom "feature-readme"

## merge

združi current branch z main branchom

## diff

prikaže razlike med dvema branchema

## creating new ssh key

ssh-keygen -t rsa -b 4096 - C "my.email@gmail.com" 