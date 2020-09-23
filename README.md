# RTR-105
Datormācība (pamatkurss) elektroniskā klade
clear - clear screen
man - view manual for a command
ls (-l) - list objects in directory 
Ctrl+Fx, x = 1..6 - switch to a different tty
history - list all executed commands
uname (-a) - show system name
whoami - print username
pwd - print working directory
[program name] & - start in background

Failu sistēmas pētīšana

Case sensitive, abc != Abc

Absolūtā adrese - /home/user

Relatīva adrese - ../Desktop/

~ - lietotāja mājas direktorija

cd bez argumentiem maina direktoriju uz mājas direktoriju

Kā uztaisīt failu:

1. touch <filename>
2. echo [something] > <filename> - pārraksta failu
3. echo [something] >> <filename> - pievieno pie faila

cat <filename> - failu attelošana

hexdump <filename> - failu attelošana hex formatā

nano - startēt GNUnano

mv <what> <where> - failu pārnēšana un pārdēvēšana
  
* works like in DOS

cp <what> <where> - failu kopēšana

whereis ls



Scripts

default: #!/bin/bash

before start:
chmod 744 <figilename>
7 == 111 rwx
4 == 100 r--
4 == 100 r--
  
23.09.2020 lesson terminal history:
    5  help
    6  man ls
    7  ls -l
    8  ls -a
    9  ls -l -a
   10  ls -la
   11  pwd
   12  cd .
   13  cd ..
   14  pwd
   15  clear
   16  pwd
   17  cd ..
   18  ls
   19  ls -la
   20  cd /home/user
   21  cd 
   22  cd /
   23  cd
   24  tree
   25  mkdir abc
   26  man lsexit
   27  man ls
   28  ls -lrt
   29  cd ./ABC/
   30  cd ./abc/
   31  ls -la
   32  cd
   33  cd Documents/
   34  ls-l
   35  ls -l
   36  rd
   37  rmdir abc
   38  cd
   39  rmdir abc
   40  help
   41  touch a.txt
   42  ls -lt
   43  echo fuck you > big.txt
   44  ls -lt
   45  cat big.txt
   46  hexdump -C big.txt
   47  delete
   48  del
   49  echo 12345 > big.txt
   50  ls -lt
   51  cat big.txt
   52  nano
   53  ls
   54  cat oof.txt 
   55  mv
   56  mv oof.txt oof.text
   57  ls
   58  cat oof.text 
   59  dl
   60  rm oof.text
   61  rm *.txt
   62  ls
   63  ls -t
   64  ls -lt
   65  gcc
   66  cd desktop
   67  cd Desktop
   68  cd
   69  cd Download
   70  cd Downloads
   71  cd ..
   72  ls -lt
   73  echo sdfasdf > test.txt
   74  cd Downloads/
   75  cp ../text.txt ../Desktop/
   76  cp ../test.txt ../Desktop/
   77  ls .-l
   78  ls . -l
   79  ls ../Desktop/ -l
   80  ls ~ -l
   81  mv ~/test.txt ~/Documents/
   82  cd Documents
   83  cd ../Documents
   84  ls -l
   85  ls .. -l
   86  cd /
   87  cp ~/Documents/test.txt ~/asd.txt
   88  cd ~
   89  ls -l
   90  cat asd.txt 
   91  cd /
   92  rm ~/Documents/test.txt
   93  ls ~/Documents/ -l
   94  cd
   95  ls
   96  ls -l /bin/ls
   97  cat bin/ls
   98  cat /bin/ls
   99  /bin/ls
  100  man for
  101  help
  102  for (int i = 0; i < 10; i++); do echo hi
  103  nano MyFirstShellScript.sh
  104  nano MyFirstShellScript.sh 
  105  ls -lt
  106  ./MyFirshShellScript.sh
  107  ./MyFirstShellScript.sh
  108  chmod rwx r-- r-- MyFirstShellScript.sh
  109  chmod 7 4 4 MyFirstShellScript.sh
  110  chmod 744 MyFirstShellScript.sh
  111  ls -lt
  112  ./MyFirstShellScript.sh 
  113  ls
  114  rm EFG
  115  rmdir EFG
  116  rmdir HIJ
  117  rm ./HIJ/*
  118  rmdir HIJ/
  119  ls
  120  rm asd.txt
  121  rm *.txt
  122  ./MyFirstShellScript.sh 
  123  ls
  124  PATH=$PATH:~
  125  $PATH
  126  echo $PATH
  127  rm ./HIJ/*
  128  rmdir HIJ/
  129  rm ./EFG/*
  130  rmdir EFG
  131  rm s.txt
  132  history
