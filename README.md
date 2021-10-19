#  *
answers to questions:
* 1)root@f798856ead4d:/# apt install less
Reading package lists... Done
Building dependency tree       
Reading state information... Done
less is already the newest version (551-1ubuntu0.1).
0 upgraded, 0 newly installed, 0 to remove and 9 not upgraded.
W: Target Packages (stable/binary-amd64/Packages) is configured multiple times in /etc/apt/sources.list:50 and /etc/apt/sources.list.d/docker.list:1
W: Target Packages (stable/binary-all/Packages) is configured multiple times in /etc/apt/sources.list:50 and /etc/apt/sources.list.d/docker.list💯
* 2)root@f798856ead4d:/# pwd
/
3)root@f798856ead4d:/# cd /
4)root@f798856ead4d:/# ls
-    boot     classics  dir1  dir3  file.1  file.3  lib    lib64   media  opt   root  sbin  sys  usr  vegetables
bin  classic  dev       dir2  etc   file.2  home    lib32  libx32  mnt    proc  run   srv   tmp  var
5)root@f798856ead4d:/# ls -F --color
-/    boot/     classics/  dir1/  dir3/  file.1  file.3  lib@    lib64@   media/  opt/   root/  sbin@  sys/  usr/  vegetables
bin@  classic/  dev/       dir2/  etc/   file.2  home/   lib32@  libx32@  mnt/    proc/  run/   srv/   tmp/  var/
6)root@f798856ead4d:/# la -F --color ~ root@f798856ead4d
ls: cannot access 'root@f798856ead4d': No such file or directory
/root:
.bash_history  .bashrc  .local/  .profile  .viminfo  classic/  classics/  dir1/  dir2/  dir3/  etc/  file1  file2  file3  student/  t.sh  test/  test1/  test2/
7)root@f798856ead4d:/# cd
root@f798856ead4d:~# 
8)root@f798856ead4d:~# pwd
/root
9)root@f798856ead4d:~# cd ..
root@f798856ead4d:/# 
10) ls- выводит список содержимого , ls-R- получаем более подробную информацию
11) root@f798856ead4d:/ls -a
-  ..          bin   classic   dev   dir2  etc     file.2  home  lib32  libx32  mnt  proc  run   srv  tmp  var
.  .dockerenv  boot  classics  dir1  dir3  file.1  file.3  lib   lib64  media   opt  root  sbin  sys  usr  vegetables
12)total 88
13) ls -F, добавляет в конце каждой строки определенный символ
14) root@f798856ead4d:/# cd
root@f798856ead4d:~# 
15)root@f798856ead4d:/# cd
root@f798856ead4d:~# cd etc
root@f798856ead4d:~/etc# cd X11
root@f798856ead4d:~/etc/X11# 
16)root@f798856ead4d:~/etc# cd /
root@f798856ead4d:/# cd ..
root@f798856ead4d:/# cd home
root@f798856ead4d:/home# 
17)root@f798856ead4d:/home# cd
root@f798856ead4d:~# cd etc
root@f798856ead4d:~/etc# 
18)root@f798856ead4d:~/etc# ls group
group
19)root@f798856ead4d:~/etc# ls -passwd
ls: invalid line width: 'd'
20)root@f798856ead4d:~/etc# ls -a
.  ..  X11  group
