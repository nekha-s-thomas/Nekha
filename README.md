# Nekha
cd // changes  directory
mkdir //makes new directory
ls //list the contents of the directory

student@hbg51:~$ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.
student@hbg51:~$ mkdir new
student@hbg51:~$ 

student@hbg51:~$ cd
student@hbg51:~$ cd..
cd..: command not found
student@hbg51:~$ cd esktop
bash: cd: esktop: No such file or directory
student@hbg51:~$ cd Desktop
student@hbg51:~/Desktop$ cd..
cd..: command not found
student@hbg51:~/Desktop$ 9  cd
9: command not found
student@hbg51:~/Desktop$ man cd //to list the manual

No manual entry for cd
student@hbg51:~/Desktop$ 
student@hbg51:~/Desktop$ cd/
bash: cd/: No such file or directory
student@hbg51:~/Desktop$ ls
1234.txt   atm.java       MultiThread.class      MultiThreadDemo.java
atm.class  Display.class  MultiThreadDemo.class  U2003149_OSlab
student@hbg51:~/Desktop$ cd /
student@hbg51:/$ ls
bin    dev   lib    libx32      mnt   root  snap  tmp
boot   etc   lib32  lost+found  opt   run   srv   usr
cdrom  home  lib64  media       proc  sbin  sys   var
student@hbg51:/$ ls -a
.    boot   etc   lib32   lost+found  opt   run   srv  usr
..   cdrom  home  lib64   media       proc  sbin  sys  var
bin  dev    lib   libx32  mnt         root  snap  tmp
student@hbg51:/$ tree

Command 'tree' not found, but can be installed with:

snap install tree  # version 1.8.0+pkg-3fd6, or
apt  install tree  # version 1.8.0-1

See 'snap info tree' for additional versions.

student@hbg51:/$ tree -d

Command 'tree' not found, but can be installed with:

snap install tree  # version 1.8.0+pkg-3fd6, or
apt  install tree  # version 1.8.0-1

See 'snap info tree' for additional versions.

student@hbg51:/$ cd home
student@hbg51:/home$ pwd
/home
student@hbg51:/home$ cd ~
student@hbg51:~$ pwd  //present working directory
/home/student
student@hbg51:~$ cat

student@hbg51:~$ rmdir A //remove a creted directory
student@hbg51:~$ nano Nekha  //create new file
student@hbg51:~$ cat Nekha.txt
Hello 
How are you?
 hOw is everything going?
