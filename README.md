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
bandit12@bandit:~$ mkdir /tmp/nyx77
bandit12@bandit:~$ cp data.txt /tmp/nyx.tmp
bandit12@bandit:~$ cp data.txx /tmp/nyx77
cp: cannot stat 'data.txx': No such file or directory
bandit12@bandit:~$ cp data.txt /tmp/nyx77
bandit12@bandit:~$ cd /ymp/nyx77
-bash: cd: /ymp/nyx77: No such file or directory
bandit12@bandit:~$ cd /tmp/nyx77
bandit12@bandit:/tmp/nyx77$ ls
data.txt
bandit12@bandit:/tmp/nyx77$ xxd -r data.txt > data
bandit12@bandit:/tmp/nyx77$ ls
data  data.txt
bandit12@bandit:/tmp/nyx77$ file data
data: gzip compressed data, was "data2.bin", last modified: Thu May  7 18:14:30 2020, max compression, from Unix
bandit12@bandit:/tmp/nyx77$ man gzip
bandit12@bandit:/tmp/nyx77$ mv data file.emily
bandit12@bandit:/tmp/nyx77$ ls
data.txt  file.emily
bandit12@bandit:/tmp/nyx77$ file file
file: cannot open `file' (No such file or directory)
bandit12@bandit:/tmp/nyx77$ mv data file.gz
mv: cannot stat 'data': No such file or directory
bandit12@bandit:/tmp/nyx77$ rmv file.emily
-bash: rmv: command not found
bandit12@bandit:/tmp/nyx77$ rm file.emily
bandit12@bandit:/tmp/nyx77$ mv data file.gz
mv: cannot stat 'data': No such file or directory
bandit12@bandit:/tmp/nyx77$ la
-bash: la: command not found
bandit12@bandit:/tmp/nyx77$ ls
data.txt
bandit12@bandit:/tmp/nyx77$ xxd -r data.txt > data
bandit12@bandit:/tmp/nyx77$ ls
data  data.txt
bandit12@bandit:/tmp/nyx77$ file data
data: gzip compressed data, was "data2.bin", last modified: Thu May  7 18:14:30 2020, max compression, from Unix
bandit12@bandit:/tmp/nyx77$ mv data file.gz
bandit12@bandit:/tmp/nyx77$ ls
data.txt  file.gz
bandit12@bandit:/tmp/nyx77$ gzip -d file.gz
bandit12@bandit:/tmp/nyx77$ ls
data.txt  file
bandit12@bandit:/tmp/nyx77$ file file
file: bzip2 compressed data, block size = 900k
bandit12@bandit:/tmp/nyx77$ mv file file.bz2
bandit12@bandit:/tmp/nyx77$ bzip2 -d file.bz2
bandit12@bandit:/tmp/nyx77$ ls
data.txt  file
bandit12@bandit:/tmp/nyx77$ file file
file: gzip compressed data, was "data4.bin", last modified: Thu May  7 18:14:30 2020, max compression, from Unix
bandit12@bandit:/tmp/nyx77$ mv file file.gz
bandit12@bandit:/tmp/nyx77$ gzip -d file.gz
bandit12@bandit:/tmp/nyx77$ ls
data.txt  file
bandit12@bandit:/tmp/nyx77$ file file
file: POSIX tar archive (GNU)
bandit12@bandit:/tmp/nyx77$ mv file file.tar
bandit12@bandit:/tmp/nyx77$ tar xf file.tar
bandit12@bandit:/tmp/nyx77$ ls
data5.bin  data.txt  file.tar
bandit12@bandit:/tmp/nyx77$ file data5.bin
data5.bin: POSIX tar archive (GNU)
bandit12@bandit:/tmp/nyx77$ rm file.tar
bandit12@bandit:/tmp/nyx77$ rm data.txt
bandit12@bandit:/tmp/nyx77$ file file
file: cannot open `file' (No such file or directory)
bandit12@bandit:/tmp/nyx77$ file data5.bin
data5.bin: POSIX tar archive (GNU)
bandit12@bandit:/tmp/nyx77$ mvdata5.bin data.tar
-bash: mvdata5.bin: command not found
bandit12@bandit:/tmp/nyx77$ mv data5.bin data.tar
bandit12@bandit:/tmp/nyx77$ tar xf data
tar: data: Cannot open: No such file or directory
tar: Error is not recoverable: exiting now
bandit12@bandit:/tmp/nyx77$ tar xf data.tar
bandit12@bandit:/tmp/nyx77$ ls
data6.bin  data.tar
bandit12@bandit:/tmp/nyx77$ file data6.bin
data6.bin: bzip2 compressed data, block size = 900k
bandit12@bandit:/tmp/nyx77$ mv data6.bin data.bz2
bandit12@bandit:/tmp/nyx77$ bzip2 -d data.bz2
bandit12@bandit:/tmp/nyx77$ ls
data  data.tar
bandit12@bandit:/tmp/nyx77$ file file
file: cannot open `file' (No such file or directory)
bandit12@bandit:/tmp/nyx77$ file data
data: POSIX tar archive (GNU)
bandit12@bandit:/tmp/nyx77$ mv data data.tar
bandit12@bandit:/tmp/nyx77$ ls
data.tar
bandit12@bandit:/tmp/nyx77$ tar xf data.tar
bandit12@bandit:/tmp/nyx77$ ls
data8.bin  data.tar
bandit12@bandit:/tmp/nyx77$ file data8.bin
data8.bin: gzip compressed data, was "data9.bin", last modified: Thu May  7 18:14:30 2020, max compression, from Unix
bandit12@bandit:/tmp/nyx77$ mv data8.bin data.gz
bandit12@bandit:/tmp/nyx77$ gzip -d data.gz
bandit12@bandit:/tmp/nyx77$ ls
data  data.tar
bandit12@bandit:/tmp/nyx77$ file data
data: ASCII text
bandit12@bandit:/tmp/nyx77$ cat data
The password is 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
bandit12@bandit:/tmp/nyx77$ 
exit 
ssh bandit13@bandit.labs.overthewire.org -p 2220
8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
ls
ssh -i sshkey.private bandit14@localhost
ls
cat /etc/bandit_pass/bandit14 
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
nc localhost 30000
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
PASS FOR 15: BfMYroe26WYalil77FoDi9qh59eK5xNr
