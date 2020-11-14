<pre>Report not walkthrough.


Level 0 > Level1
ssh bandit0@bandit.labs.overthewire.org -p 2220
Pwd: bandit0.
`Cat readme:`
`boJ9jbbUNNfktd78OOpsqOltutMc3MY1`

Level 1 > Level2
ssh bandit1@bandit.labs.overthewire.org -p 2220
pwd:boJ9jbbUNNfktd78OOpsqOltutMc3MY1
`ls `
`cat < -`
`CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9`

Level 2 > Level3
ssh bandit2@bandit.labs.overthewire.org -p 2220
Pwd: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

`ls`
`file file spaces\ in\ this\ filename`
`cat spaces\ in\ this\ filename`
`UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK`

Level 3 > Level4
ssh bandit3@bandit.labs.overthewire.org -p 2220
pwd:pIwrPrtPN36QITSp3EQaw936yaFoFgAB    


Level 5
`koReBOKuIDDepwhWk7jZC0RTdopnAYKh`

find -type f -size 1033c ! -executable
 

Level6:
`DXjZPULLxYr17uwoI01bNLQbtFemEgo7`

Level7:
`HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs`

Level7:
`cvX2JJa4CFALtqS87jk27qwqGhBM9plV`

Level8:
cat data.txt | sort | uniq -u
`UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR`

Level9:
strings data.txt | grep "="
`truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk`


Level10:
base64 -d data.txt
`IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR`

Level11:
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
`5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu`


Level12:
Walkthrough
`8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL`

Level13-14 to 15:
ssh -i sshkey.private bandit14@localhost

14:
nc localhost 30000
Put hte pwd :4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e

And get 15 pwd:
BfMYroe26WYalil77FoDi9qh59eK5xNr

Level15-16:
openssl s_client -connect localhost:30001
And put : BfMYroe26WYalil77FoDi9qh59eK5xNr

`cluFn7wTiGryunymYOu4RcffSxQluehd`


Level 16 to 17:
ssh bandit17@bandit.labs.overthewire.org -p 2220 -i key.txt

key :
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----


Level17-18:
diff passwords.new passwords.old
< kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
---
> w0Yfolrc5bwjS4qw5mq1nnQi6mF03bii


To 19:
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
`IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x`


To 20:
./bandit20-do cat /etc/bandit_pass/bandit20

`GbKksEFF4yrVs6il55v6gwY5aVje5f0j`

To 21:
As kanoyme ena listener 
echo "GbKksEFF4yrVs6il55v6gwY5aVje5f0j" | nc -l localhost -p 61337 &

Ps aux 

Na doyme an eigne

Meta pame sto programa kai patame:
./suconnect 61337


Pwd:    `gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr`

21 to 22:

ls -l | grep cronjob

cat cronjob_bandit22

cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

`Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI`



22 to 23:

`jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n`



23 to 24:
mkdir /tmp/paok

chmod 777 /tmp/paok

vi get.sh
    `cat /etc/bandit_pass/bandit24 > /tmp/paok/thepassword.txt`

chmod +x get.sh

cat /tmp/paok/thepassword.txt

`UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ`
24 to 25

  1 #!/bin/bash
  2 passwd="UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ"
  3 for a in {0..9}{0..9}{0..9}{0..9}
  4 do
  5             echo $passwd' '$a >> combinations.txt
  6 done

./ncbrute.sh

cat combinations.txt | nc localhost 30002 >> result.txt

cat result.txt

`uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG`



25-26:
ssh bandit26@localhost -i bandit26.sshkey

Resize to much
After saw more 50%
Press ‘v’
And shift ‘:’
:set shell=/bin/bash
:shell
bandit26@bandit:~$ cat /etc/bandit_pass/bandit26
5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z


26-27
./bandit27-do cat /etc/bandit_pass/bandit27

`3ba3118a22e93127a4ed485be72ef5ea`


27-28
mkdir /tmp/rep

cd /tmp/rep

git clone ssh://bandit27-git@localhost/home/bandit27-git/repo
Put the pwd :`3ba3118a22e93127a4ed485be72ef5ea`

Cd repo 
cat README
`The password to the next level is: 0ef186ac70e04ea33b4c1853d2526fa2`


28 to 29




Mkdir /tmp/gitrepo

Cd /tmp/gitrepo
git clone ssh://bandit28-git@localhost/home/bandit28-git/repo


cat README.md

git log

git log -p -1

`bbc96594b4e001778eee9975372716b2`



29-30:

Mkdir /tmp/reporttgit remote showt

git clone ssh://bandit29-git@localhost/home/bandit29-git/repo
Bbc96594b4e001778eee9975372716b2

git show-branch --all
git remote show
git remote show origin
Bbc96594b4e001778eee9975372716b2
git checkout dev


cat README.md
`5b90576bedb2cc04c86a9e924ce42faf`



30 to 31:

Mkdir /tmp/repo2
Cd /tmp/repo2
Git clone ssh://bandit30-git@localhost/home/bandit30-git/repo
5b90576bedb2cc04c86a9e924ce42faf


git branch -r

  origin/HEAD -> origin/master
  origin/master

git tag
    Secret
git show secret
`47e603bb428404d265f59c42920d81e5`


31-32:
mkdir /tmp/paokara

Cd /tmp/paokara

Git clone ssh://bandit31-git@localhost/home/bandit31-git/repo
47e603bb428404d265f59c42920d81e5

Cd repo

git branch
* master

echo "May I come in?" > key.txt

git add -f  key.txt

ls -al

git commit -m "paoakra arrwstia"

git push origin master
47e603bb428404d265f59c42920d81e5

remote: Well done! Here is the password for the next level:
remote: `56a9bf19c63d650ce78e6ec0354ee45e`


32-33:
To shell metatrepi kane entoli se kefalea. Gia na paroyme ksana to arxiko shell to kanoyme xrisimopiontas thn metavliti `$0`

>> $0

id 

uid=11033(bandit33) gid=11032(bandit32) groups=11032(bandit32)
cat /etc/bandit_pass/bandit33
`c9c3199ddf4121b10cf581a98d51caee`


Login as bendit33:

bandit33@bandit:~$ cat README.txt
Congratulations on solving the last level of this game!

At this moment, there are no more levels to play in this game. However, we are constantly working
on new levels and will most likely expand this game with more levels soon.
Keep an eye out for an announcement on our usual communication channels!
In the meantime, you could play some of our other wargames.

If you have an idea for an awesome new level, please let us know!
</pre>
