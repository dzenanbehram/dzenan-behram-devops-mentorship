# DevOps Mentorship Program - Dzenan Behram


## Week 2
Koraci: 


```bash
$ cd dzenan-behram-devops-mentorship 

$ git branch #provjera brancha

$ git checkout week-2-bandit-labs #lociranje na novi branch

$ mkdir week-2 #kreiranje direktorija week-2

$cd week-2 #lociranje unutar direktorija

$ code . #pokretanje vscode unutar dir

#wargame koraci

#level 0-10

$ ssh bandit0@bandit.labs.overthewire.org -p 2220 #koristimo ssh komandu po portu 2220 kako bi se spojili na server

$ ls #koristimo komandu ls kako bi dobili listu svih fajlova koji se tu nalaze

$ cat readme #ispij file readme na ekranu

#nakon izvrsenog kopiranja lozinke, pokretanje novog spajanja putem ssh
$ ssh bandit1@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ cat < - 

$ ssh bandit2@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls #nakon koristenja komande ls prikazuje nam se file koji ima razmake u imenu

cat spaces\ in\ this\ filename #koristimo kako bi dobili ispis lozinke za naredni nivo, radi lakseg pisanja mozete ukucati spaces i koristiti tipku tab

$ ssh bandit3@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls 

$ cd inhere

$ ls -lah #pregled fileova

$ cat .hiden #ispis filea

$ ssh bandit4@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ cd inhere #lociranje unutar dir

$ cat < -file07 #ispis pronadjenog filea

$ ssh bandit5@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ cd inhere #lociranje unutar

$ find . -type f -size 1033c -name "[[:print:]]*" ! -executable #pretrazivanje file uz pomoc datih karakteristika 

$ cat ./.file2 #ispis sifre

$ ssh bandit6@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ find / -user bandit7 -group bandit6 -size 33c -type f 2>/dev/null #pretrazivanje uz pomoc date specificne velicine file

$ cat /var/lib/dpkg/info/bandit7.password #ispis file na ekranu

$ ssh bandit7@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ grep millionth data.txt #ispis linija koji imaju podudarnost trazenu

$ ssh bandit8@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ sort data.txt | uniq -c | grep '^ *1 ' #uz pomoc opisa pretrazicati file koji se pojavljuje samo jednom

$ ssh bandit9@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ trings data.txt | grep -E "=+" #

$ ssh bandit10@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka

$ ls

$ cat data.txt | base64 -d #podaci su spaseni u fileu koji je kodiran u bazi 64 

$ ssh bandit11@bandit.labs.overthewire.org -p 2220 #uspjesno spojeno na novi nivo koristenjem lozinke iz prethodnog koraka