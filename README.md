# over-the-wire
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat read me
exit
ssh bandit1@bandit.labs.overthewire.org -p 2220
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
ls
cat ./-
exit
ssh bandit2@bandit.labs.overthewire.org -p 2220
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
ls
cat "spaces in filename"
exit
ssh bandit3@bandit.labs.overthewire.org -p 2220
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
ls
cd inhere
ls -al
cat .hidden
exit
ssh bandit4@bandit.labs.overthewire.org -p 2220
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
ls
cd inhere
ls -al
file ./-file*
cat ./-file07
exit 
ssh bandit5@bandit.labs.overthewire.org -p 2220
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
ls
cd inhere
ls -al
find . -size 1033c
cd maybehere07
ls
ls -al
cat ./.file2
exit
ssh bandit6@bandit.labs.overthewire.org -p 2220
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
ls -al
find / -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
exit
ssh bandit7@bandit.labs.overthewire.org -p 2220
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
ls
cat data.txt
grep millionth data.txt
exit
ssh bandit8@bandit.labs.overthewire.org -p 2220
cvX2JJa4CFALtqS87jk27qwqGhBM9plV
ls
cat data.txt
sort data.txt | uniqu -u
exit
ssh bandit9@bandit.labs.overthewire.org -p 2220
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
ls
cat data.txt
strings data.txt
strings data.txt | grep "=="
exit
ssh bandit10@bandit.labs.overthewire.org -p 2220
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
ls
cat data.txt
base64 -d data.txt
exit
ssh bandit11@bandit.labs.overthewire.org -p 2220
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
ls
cat data.txt
cat data.txt| tr [a-z] [n-za-m] |tr [A-Z] [N-ZA-M]
exit 
ssh bandit12@bandit.labs.overthewire.org -p 2220
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
