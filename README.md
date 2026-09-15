iniiozov@c2r1s6:~$ cd Dokumente/
iniiozov@c2r1s6:~/Dokumente$ mkdir reviews
iniiozov@c2r1s6:~/Dokumente$ cd reviews/
iniiozov@c2r1s6:~/Dokumente/reviews$ git clone git@github.com:42learners/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168.git
Klone nach 'Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168'...
The authenticity of host 'github.com (140.82.121.3)' can't be established.
ED25519 key fingerprint is: SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
Schwerwiegend: Konnte nicht vom Remote-Repository lesen.

Bitte stellen Sie sicher, dass die korrekten Zugriffsberechtigungen bestehen
und das Repository existiert.
iniiozov@c2r1s6:~/Dokumente/reviews$ cd
iniiozov@c2r1s6:~$ cd Dokumente/
iniiozov@c2r1s6:~/Dokumente$ cd ..
iniiozov@c2r1s6:~$ cd
iniiozov@c2r1s6:~$ ssh-keygen -t ed25519 -C "izmir.niiozov@learner.42.tech"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/iniiozov/.ssh/id_ed25519):
Enter passphrase for "/home/iniiozov/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/iniiozov/.ssh/id_ed25519
Your public key has been saved in /home/iniiozov/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:2Q/dBvHllzYQB+izYL7BcYtioACHTM/8f4R3DuzxKSw izmir.niiozov@learner.42.tech
The key's randomart image is:
+--[ED25519 256]--+
|oo          o+o..|
|o.=        . ooo.|
|.. +      . . .+o|
| .  ..  o* = o. o|
|  . ....S*B.= o  |
|   .  .o==*=..   |
|      .E.=o+.    |
|        o..      |
|                 |
+----[SHA256]-----+
iniiozov@c2r1s6:~$ cat /.ssh/id_ed25519.pub
cat: /.ssh/id_ed25519.pub: Datei oder Verzeichnis nicht gefunden
iniiozov@c2r1s6:~$ cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIFhGsSSmj1Vx4YqRP92L58wlifuo1tvfaNR4w/cZb6RL izmir.niiozov@learner.42.tech
iniiozov@c2r1s6:~$ cd
iniiozov@c2r1s6:~$ cd Dokumente/
iniiozov@c2r1s6:~/Dokumente$ ls
reviews
iniiozov@c2r1s6:~/Dokumente$ cd reviews/
iniiozov@c2r1s6:~/Dokumente/reviews$ ls
iniiozov@c2r1s6:~/Dokumente/reviews$ cd ..
iniiozov@c2r1s6:~/Dokumente$ cd reviews/
iniiozov@c2r1s6:~/Dokumente/reviews$ git clone git@github.com:42learners/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168.git
Klone nach 'Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 10 (delta 1), reused 10 (delta 1), pack-reused 0 (from 0)
Empfange Objekte: 100% (10/10), fertig.
Löse Unterschiede auf: 100% (1/1), fertig.
iniiozov@c2r1s6:~/Dokumente/reviews$ tree
.
└── Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168
    ├── ex0
    │   └── testShell00.tar
    ├── ex1
    │   └── ex1.tar
    ├── ex2
    │   └── midLS
    └── ex3
        └── "\?$*'MaRViN'*$?\"

6 directories, 4 files
iniiozov@c2r1s6:~/Dokumente/reviews$ cd ex0
bash: cd: ex0: Datei oder Verzeichnis nicht gefunden
iniiozov@c2r1s6:~/Dokumente/reviews$ cd Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$ cd ex0
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex0$ tar -xf testShell00.tar
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex0$ ll
insgesamt 16
-r--r-xr-x. 1 iniiozov iniiozov    40  1. Jun 23:42 testShell00
-rw-r--r--. 1 iniiozov iniiozov 10240 15. Sep 15:39 testShell00.tar
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex0$ cd ..
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$ cd ex1
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ ll
insgesamt 12
-rw-r--r--. 1 iniiozov iniiozov 10240 15. Sep 15:39 ex1.tar
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ tar -xf ex1.tar
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ ll
insgesamt 28
-rw-r--r--. 1 iniiozov iniiozov 10240 15. Sep 15:39 ex1.tar
drwx--xr-x. 2 iniiozov iniiozov     6  1. Jun 20:47 test0
-rwx--xr--. 1 iniiozov iniiozov     4  1. Jun 21:46 test1
dr-x---r--. 2 iniiozov iniiozov     6  1. Jun 22:45 test2
-r-----r--. 2 iniiozov iniiozov     1  1. Jun 23:44 test3
-rw-r----x. 1 iniiozov iniiozov     2  1. Jun 23:43 test4
-r-----r--. 2 iniiozov iniiozov     1  1. Jun 23:44 test5
lrwxrwxrwx. 1 iniiozov iniiozov     5  1. Jun 22:20 test6 -> test0
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ cd ..
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$ cd ex2
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex2$ ll
insgesamt 4
-rw-r--r--. 1 iniiozov iniiozov 12 15. Sep 15:39 midLS
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex2$ cat midLS
ls -t -p -m
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex2$ cd ..
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$ cd ex1
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ ls -t -p -m
ex1.tar, test3, test5, test4, test2/, test6, test1, test0/
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex1$ cd ..
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$ cd ex3
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex3$ ll
insgesamt 4
-rw-r--r--. 1 iniiozov iniiozov 2 15. Sep 15:39 '"\?$*'\''MaRViN'\''*$?\"'
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex3$ ls -lRa *MaRV* | cat -e
-rw-r--r--. 1 iniiozov iniiozov 2 15. Sep 15:39 "\?$*'MaRViN'*$?\"$
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex3$ cat \"\\\?\$\*\'MaRViN\'\*\$\?\\\"
42
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168/ex3$ cd ..
iniiozov@c2r1s6:~/Dokumente/reviews/Shell-Fundamentals-90cfc85c-ac0b-4814-be18-7fd5505f9168$
