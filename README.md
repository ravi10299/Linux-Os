# Linux-Os


day 1..
[RAVI@localhost ~]$ 
[RAVI@localhost ~]$ 
[RAVI@localhost ~]$ 
[RAVI@localhost ~]$ mkdir new1
[RAVI@localhost ~]$ ls
Desktop  directory  Documents  Downloads  Music  new  new1  newzfile  newzfile1  Pictures  Public  Templates  Videos
[RAVI@localhost ~]$ cd new 
[RAVI@localhost new]$ cd ..
[RAVI@localhost ~]$ rmdir naw
rmdir: failed to remove 'naw': No such file or directory
[RAVI@localhost ~]$ rmdir new1
[RAVI@localhost ~]$ ls
Desktop  directory  Documents  Downloads  Music  new  newzfile  newzfile1  Pictures  Public  Templates  Videos
[RAVI@localhost ~]$ clear
[RAVI@localhost ~]$ cd /
[RAVI@localhost /]$ ls
bin  boot  dev  etc  home  lib  lib64  main-backup.java  main.java  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
[RAVI@localhost /]$ su root
Password: 
[root@localhost /]# ls
bin  boot  dev  etc  home  lib  lib64  main-backup.java  main.java  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
[root@localhost /]# cd home/
[root@localhost home]# ls
RAVI
[root@localhost home]# cd RAVI/
[root@localhost RAVI]# pwd
/home/RAVI
[root@localhost RAVI]# ls
Desktop  directory  Documents  Downloads  Music  new  newzfile  newzfile1  Pictures  Public  Templates  Videos
[root@localhost RAVI]# cd D
Desktop/   Documents/ Downloads/ 
[root@localhost RAVI]# cd Desktop/
[root@localhost Desktop]# ls
[root@localhost Desktop]# cd var/
bash: cd: var/: No such file or directory
[root@localhost Desktop]# cd /
[root@localhost /]# cd var/
[root@localhost var]# c ..
bash: c: command not found...
[root@localhost var]# cd ..
[root@localhost /]# cd /home/RAVI/D
Desktop/   Documents/ Downloads/ 
[root@localhost /]# cd /home/RAVI/D
Desktop/   Documents/ Downloads/ 
[root@localhost /]# cd /home/RAVI/Desktop/
[root@localhost Desktop]# history
    1  ls
    2  cd home/
    3  ls
    4  cd RAVI/
    5  pwd
    6  ls
    7  cd Desktop/
    8  ls
    9  cd var/
   10  cd /
   11  cd var/
   12  c ..
   13  cd ..
   14  cd /home/RAVI/Desktop/
   15  history
[root@localhost Desktop]# cd ../../../
[root@localhost /]# history
    1  ls
    2  cd home/
    3  ls
    4  cd RAVI/
    5  pwd
    6  ls
    7  cd Desktop/
    8  ls
    9  cd var/
   10  cd /
   11  cd var/
   12  c ..
   13  cd ..
   14  cd /home/RAVI/Desktop/
   15  history
   16  cd ../../../
   17  history
[root@localhost /]# man ls
[root@localhost /]# su RAVI




[RAVI@localhost /]$ 
[RAVI@localhost /]$ 
[RAVI@localhost /]$ 
[RAVI@localhost /]$ 
[RAVI@localhost /]$ mkdir new-folder
mkdir: cannot create directory ‘new-folder’: Permission denied
[RAVI@localhost /]$ su root


Password: 
[root@localhost /]# cd /home/RAVI/
[root@localhost RAVI]# mkdir new-folder
[root@localhost RAVI]# ls
Desktop  directory  Documents  Downloads  Music  new  new-folder  newzfile  newzfile1  Pictures  Public  Templates  Videos
[root@localhost RAVI]# cd new-folder/
[root@localhost new-folder]# ped
bash: ped: command not found...
[root@localhost new-folder]# pwd
/home/RAVI/new-folder
[root@localhost new-folder]# mkdir dell
[root@localhost new-folder]# ls
dell
[root@localhost new-folder]# mkdir fol1 fol2 fol3
[root@localhost new-folder]# ls
dell  fol1  fol2  fol3
[root@localhost new-folder]# mkdir f{1..99}
[root@localhost new-folder]# sl
bash: sl: command not found...
Similar command is: 'ls'
[root@localhost new-folder]# ls
dell  f12  f16  f2   f23  f27  f30  f34  f38  f41  f45  f49  f52  f56  f6   f63  f67  f70  f74  f78  f81  f85  f89  f92  f96  fol1
f1    f13  f17  f20  f24  f28  f31  f35  f39  f42  f46  f5   f53  f57  f60  f64  f68  f71  f75  f79  f82  f86  f9   f93  f97  fol2
f10   f14  f18  f21  f25  f29  f32  f36  f4   f43  f47  f50  f54  f58  f61  f65  f69  f72  f76  f8   f83  f87  f90  f94  f98  fol3
f11   f15  f19  f22  f26  f3   f33  f37  f40  f44  f48  f51  f55  f59  f62  f66  f7   f73  f77  f80  f84  f88  f91  f95  f99
[root@localhost new-folder]# rmdir f{1..99}
[root@localhost new-folder]# ls
dell  fol1  fol2  fol3
[root@localhost new-folder]# pwd
/home/RAVI/new-folder
[root@localhost new-folder]# rmdir dell fol1 fol2 fol3
[root@localhost new-folder]# ls
[root@localhost new-folder]# ls
[root@localhost new-folder]# cd ..
[root@localhost RAVI]# rmdir new-folder/
[root@localhost RAVI]# ls
Desktop  directory  Documents  Downloads  Music  new  newzfile  newzfile1  Pictures  Public  Templates  Videos
[root@localhost RAVI]# mkdir data
[root@localhost RAVI]# ls
data  Desktop  directory  Documents  Downloads  Music  new  newzfile  newzfile1  Pictures  Public  Templates  Videos
[root@localhost RAVI]# cd data
[root@localhost data]# ls
[root@localhost data]# mkdir folder1
[root@localhost data]# mkdir dbdata
[root@localhost data]# ls
dbdata  folder1
[root@localhost data]# mkdir photo video gallery documents notes
[root@localhost data]# ls
dbdata  documents  folder1  gallery  notes  photo  video
[root@localhost data]# history
    1  cd /home/RAVI/
    2  mkdir new-folder
    3  ls
    4  cd new-folder/
    5  ped
    6  pwd
    7  mkdir dell
    8  ls
    9  mkdir fol1 fol2 fol3
   10  ls
   11  mkdir f{1..99}
   12  sl
   13  ls
   14  rmdir f{1..99}
   15  ls
   16  pwd
   17  rmdir dell fol1 fol2 fol3
   18  ls
   19  cd ..
   20  rmdir new-folder/
   21  ls
   22  mkdir data
   23  ls
   24  cd data
   25  ls
   26  mkdir folder1
   27  mkdir dbdata
   28  ls
   29  mkdir photo video gallery documents notes
   30  ls
   31  history
[root@localhost data]# su root
[root@localhost data]# 8429
bash: 8429: command not found...
[root@localhost data]# su RAVI
[RAVI@localhost data]$ ls
dbdata  documents  folder1  gallery  notes  photo  video
[RAVI@localhost data]$ cd ..
[RAVI@localhost ~]$ cd /
[RAVI@localhost /]$ ls
bin  boot  dev  etc  home  lib  lib64  main-backup.java  main.java  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
[RAVI@localhost /]$ cd /home/RAVI/
[RAVI@localhost ~]$ ls
data  Desktop  directory  Documents  Downloads  Music  new  newzfile  newzfile1  Pictures  Public  Templates  Videos
[RAVI@localhost ~]$ mkdir new-folder
[RAVI@localhost ~]$ ls
data  Desktop  directory  Documents  Downloads  Music  new  new-folder  newzfile  newzfile1  Pictures  Public  Templates  Videos
[RAVI@localhost ~]$ cd new-folder/
[RAVI@localhost new-folder]$ mkdir folder1
[RAVI@localhost new-folder]$ mkdir folder2
[RAVI@localhost new-folder]$ ls
folder1  folder2
[RAVI@localhost new-folder]$ cd folder1/
[RAVI@localhost folder1]$ totch file1 file2
bash: totch: command not found...
[RAVI@localhost folder1]$ touch file1 file2
[RAVI@localhost folder1]$ ls
file1  file2
[RAVI@localhost folder1]$ cd ..
[RAVI@localhost new-folder]$ cd folder2
[RAVI@localhost folder2]$ touch file1 file2
[RAVI@localhost folder2]$ ls
file1  file2
[RAVI@localhost folder2]$ history
    1  ls
    2  cd ..
    3  cd /
    4  ls
    5  cd /home/RAVI/
    6  ls
    7  mkdir new-folder
    8  ls
    9  cd new-folder/
   10  mkdir folder1
   11  mkdir folder2
   12  ls
   13  cd folder1/
   14  totch file1 file2
   15  touch file1 file2
   16  ls
   17  cd ..
   18  cd folder2
   19  touch file1 file2
   20  ls
   21  history
[RAVI@localhost folder2]$ su RAVI
Password: 
su: Authentication failure
[RAVI@localhost folder2]$ su root
Password: 
[root@localhost folder2]# cd /
[root@localhost /]# ls
bin  boot  dev  etc  home  lib  lib64  main-backup.java  main.java  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
[root@localhost /]# cd /home/RAVI/new-folder/folder1
[root@localhost folder1]# ped
bash: ped: command not found...
[root@localhost folder1]# pwd
/home/RAVI/new-folder/folder1
[root@localhost folder1]# tree
.
├── file1
└── file2

0 directories, 2 files
[root@localhost folder1]# cd ../..
[root@localhost RAVI]# tree
.
├── data
│   ├── dbdata
│   ├── documents
│   ├── folder1
│   ├── gallery
│   ├── notes
│   ├── photo
│   └── video
├── Desktop
├── directory
├── Documents
├── Downloads
├── Music
├── new
├── new-folder
│   ├── folder1
│   │   ├── file1
│   │   └── file2
│   └── folder2
│       ├── file1
│       └── file2
├── newzfile
├── newzfile1
├── Pictures
├── Public
├── Templates
└── Videos

23 directories, 4 files
[root@localhost RAVI]# history
    1  cd /
    2  ls
    3  cd /home/RAVI/new-folder/folder1
    4  ped
    5  pwd
    6  tree
    7  cd ../..
    8  tree
    9  history
[root@localhost RAVI]# tree
.
├── data
│   ├── dbdata
│   ├── documents
│   ├── folder1
│   ├── gallery
│   ├── notes
│   ├── photo
│   └── video
├── Desktop
├── directory
├── Documents
├── Downloads
├── Music
├── new
├── new-folder
│   ├── folder1
│   │   ├── file1
│   │   └── file2
│   └── folder2
│       ├── file1
│       └── file2
├── newzfile
├── newzfile1
├── Pictures
├── Public
├── Templates
└── Videos

23 directories, 4 files
[root@localhost RAVI]# 
