# DevOps Mentorship Program - Dzenan Behram


## Week 1
Koraci: 


```bash
$ ssh-keygen -t rsa #komanda za generisanje ssh privatnog i javnog kljuca 

$ cat .ssh/id_rsa.pub # ispis javnog kljuca na ekran
#Dodavanje javnog kljuca unutar github UI

$ mkdir dzenan-behram-devops-mentorship

$ cd dzenan-behram-devops-mentorship

$ git init

$ git commit --allow-empty -m "initial commit" 
#dozvoljavanje i pravljenje praznog commita

$ git branch #provjera brancha

$ git remote add origin git@github.com:dzenanbehram/
dzenan-behram-devops-mentorship.git #povezivanje sa 
udaljenim repozitorijem na GitHub

$  git push --set-upstream origin main #guranje izmjena na remote repozitorij


# provjera unutar GitHUb UI da li je inicijaliziran prazna main grana
# kreiranje development branch kroz GitHub UI
# Povratak na terminal

$ git pull #povlacenje izmjena sa remote repozitorija (development branch)

$ git checkout development #prebacivanje na development branch lokalno


#kreiranje gitignore i readme file kroz vscode

$ git add . #dodavanje kreiranih fileova

$ git commit -m"add .gitignore and readme files"

$ git push 

```
