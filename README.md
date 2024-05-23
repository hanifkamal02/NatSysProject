# Net&Sys Assignment: Running Containers for Application Development

Group Name: **Axia Type-R** 

Team Mates:
1. **Muhammad Hanif Bin Md Kamal 2114963**
2. **Muhammad Fikri Bin Mohammad Isa 2110105**

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** <br>
**https://github.com/hanifkamal02/NatSysProject**
2. How many files and folders are in this repository. ***(1 mark)*** <br>
**There are 1 folder and 7 files including 6 files inside the folder.**


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** <br>
**Linux OS.**
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** <br>
**Basic configuration for light use and advanced configuration for heavy use.**
3. Why must we commit and sync our current work on source control? ***(1 mark)*** <br>
**To make sure that all of the work similar between the code and page for the next changes and making collaboration to allow others to see changes.**

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)***
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
3. Run the command **df** . ***(1 mark)***
4. Run the command **du** . ***(1 mark)***
5. Run the command **ls** . ***(1 mark)*** 
6. Run the command **ls -asl** . ***(1 mark)***
7. Run the command **free -h** . ***(1 mark)***
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
9. Run the command **top** and type **q** to quit. ***(1 mark)***
10. Run the command **uname -a**. ***(1 mark)*** <br> 
```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ pwd
/workspaces/NatSysProject
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 14452416  16701164  47% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24125996   6155796  80% /vscode
/dev/sdb1       46127956      108  43752272   1% /tmp
/dev/loop4      32847680 14452416  16701164  47% /workspaces
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ du
1972    ./images
8       ./.git/objects/60
16      ./.git/objects/ff
8       ./.git/objects/c6
8       ./.git/objects/4b
8       ./.git/objects/41
12      ./.git/objects/d2
8       ./.git/objects/d8
8       ./.git/objects/e7
12      ./.git/objects/2e
8       ./.git/objects/4a
8       ./.git/objects/7b
16      ./.git/objects/fb
8       ./.git/objects/fe
12      ./.git/objects/6e
8       ./.git/objects/fa
12      ./.git/objects/1c
8       ./.git/objects/f2
1820    ./.git/objects/pack
8       ./.git/objects/ea
12      ./.git/objects/70
12      ./.git/objects/64
12      ./.git/objects/44
8       ./.git/objects/74
8       ./.git/objects/0d
8       ./.git/objects/cb
8       ./.git/objects/58
12      ./.git/objects/14
8       ./.git/objects/3f
12      ./.git/objects/3d
12      ./.git/objects/af
12      ./.git/objects/79
8       ./.git/objects/f6
8       ./.git/objects/83
8       ./.git/objects/91
8       ./.git/objects/b2
8       ./.git/objects/3a
12      ./.git/objects/73
8       ./.git/objects/93
8       ./.git/objects/b6
8       ./.git/objects/a6
8       ./.git/objects/71
8       ./.git/objects/a3
8       ./.git/objects/04
8       ./.git/objects/eb
8       ./.git/objects/fc
8       ./.git/objects/49
8       ./.git/objects/4f
8       ./.git/objects/c3
8       ./.git/objects/81
12      ./.git/objects/72
8       ./.git/objects/0b
8       ./.git/objects/d9
8       ./.git/objects/1b
12      ./.git/objects/a0
4       ./.git/objects/info
8       ./.git/objects/52
8       ./.git/objects/20
8       ./.git/objects/86
8       ./.git/objects/fd
8       ./.git/objects/cd
12      ./.git/objects/62
16      ./.git/objects/b5
12      ./.git/objects/e5
12      ./.git/objects/17
8       ./.git/objects/e9
8       ./.git/objects/47
8       ./.git/objects/24
8       ./.git/objects/96
8       ./.git/objects/b9
8       ./.git/objects/ab
2464    ./.git/objects
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
8       ./.git/refs/heads
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
32      ./.git/refs
8       ./.git/info
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
64      ./.git/hooks
4       ./.git/branches
2652    ./.git
4644    .
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ ls
README.md  images
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 May 23 00:47 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 23 00:47 ..
 4 drwxrwxrwx+ 9 codespace root  4096 May 23 00:58 .git
16 -rw-rw-rw-  1 codespace root 13121 May 23 01:18 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 23 00:47 images
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.5Gi       392Mi       1.0Mi       5.9Gi       5.9Gi
Swap:            0B          0B          0B
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3077.869
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3114.314
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid
top - 01:19:15 up  1:11,  0 users,  load average: 0.15, 0.26, 0.28
Tasks:  17 total,   1 running,  16 sleeping,   0 stopped,   0 zombie
%Cpu(s):  4.5 us,  4.9 sy,  0.0 ni, 90.6 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    393.0 free,   1519.8 used,   6016.7 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6093.6 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                 
   2242 codespa+  20   0   21.1g 336508  46336 S   2.3   4.1   1:05.02 node                                                                                    
   2160 codespa+  20   0  980024 119948  42112 S   0.3   1.5   0:08.92 node                                                                                    
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.05 docker-init                                                                             
      7 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.02 sleep                                                                                   
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ uname -a
Linux codespaces-9b2a1e 6.5.0-1019-azure #20~22.04.1-Ubuntu SMP Wed Apr  3 03:28:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. ***(1 mark)*** <br>
**393MiB**
12. What is the available disk space mounted on /workspace. ***(1 mark)*** <br>
**16701164kB = Around 16GB**
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** <br>
**Version is 6.5.0-1019-azure and Hardware architecture is x86_64**
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** <br>
**ls is the list name of files and directory in the current directory. ls -asl provide detail listing including hidden files, file sizes and additional information.**
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** <br>
**2560 4k pages.**
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** <br>
**3114.314 MHz**
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** <br>
**node with process (PID2242) consume most CPU cycles with 2.3% of the CPU**

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```
Terminal <br>
```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
c6cf28de8a06: Pull complete 
Digest: sha256:fac2c0fd33e88dfd3bc88a872cfb78dcb167e74af6162d31724df69e482f886c
Status: Downloaded newer image for debian:latest
docker.io/library/debian:latest
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker run --detach -it debian
4f627c83e888c9a9bfe8ad7820548f0c07247c0be35d816c2406cd97f964bacf
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
4f627c83e888   debian    "bash"    12 seconds ago   Up 10 seconds             laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker exec -i -t laughing_cray /bin/bash
root@4f627c83e888:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [156 kB]
Fetched 9210 kB in 1s (9487 kB/s)
Reading package lists... Done
root@4f627c83e888:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (28.4 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@4f627c83e888:/# cd /root
root@4f627c83e888:~# nano helloworld.txt
root@4f627c83e888:~# exit
exit
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker stop laughing_cray
laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                       PORTS     NAMES
4f627c83e888   debian    "bash"    2 minutes ago   Exited (137) 7 seconds ago             laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker restart laughing_cray
laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS          PORTS     NAMES
4f627c83e888   debian    "bash"    3 minutes ago   Up 13 seconds             laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker stop laughing_cray
laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                       PORTS     NAMES
4f627c83e888   debian    "bash"    3 minutes ago   Exited (137) 7 seconds ago             laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker rm laughing_cray
laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker exec -i -t laughing_cray /bin/bash
Error response from daemon: No such container: laughing_cray
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
```
***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** <br>
**No, files in a Docker container are not persistent by default because the container's filesystem is ephemeral. This means that any changes made inside the container are lost when the container is stopped and removed.**
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** <br>
**Yes, you can run multiple instances of Debian Linux containers simultaneously using Docker. Each container runs independently and can be configured to have its own environment.**

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```
```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ mkdir myroot
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ cd myroot
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ pwd
/workspaces/NatSysProject/myroot
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ docker run --detach -it -v /workspaces/NatSysProject/myroot:/root debian
4f9cfb8e60386264cd4a2637bc6f9a64b3c427ff306f6e2a13f1f631840df626
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                                   NAMES
4f9cfb8e6038   debian    "bash"               25 seconds ago   Up 25 seconds                                           distracted_chaum
57b7c8d91967   busybox   "sh"                 22 minutes ago   Up 22 minutes                                           c2
c259beda79cc   busybox   "sh"                 22 minutes ago   Up 22 minutes                                           c1
5c545ba19c21   httpd     "httpd-foreground"   31 minutes ago   Up 31 minutes   0.0.0.0:8080->80/tcp, :::8080->80/tcp   admiring_vaughan
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ docker exec -it distracted_chaum bash
root@4f9cfb8e6038:/# touch /root/testfile.txt
root@4f9cfb8e6038:/# echo "Hello World!" > /root/testfile.txt
root@4f9cfb8e6038:/# exit
exit
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ ls
testfile.txt
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ ls -l
total 4
-rw-rw-rw- 1 root root 13 May 23 05:29 testfile.txt
@hanifkamal02 ➜ /workspaces/NatSysProject/myroot (main) $ ls -asl
total 16
4 drwxrwxrwx+ 2 codespace codespace 4096 May 23 05:29 .
4 drwxrwxrwx+ 6 codespace root      4096 May 23 05:25 ..
4 -rw-------  1 root      root        71 May 23 05:29 .bash_history
4 -rw-rw-rw-  1 root      root        13 May 23 05:29 testfile.txt
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** <br>
**The permission of the folder /workspaces/NetSysProject is -rw-rw-rw, and it is owned by the user root and the group root.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ mkdir webpage
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ cd webpage
@hanifkamal02 ➜ /workspaces/NatSysProject/webpage (main) $ echo '<!DOCTYPE html>
> <html>
> <head>
>     <title>My Static Webpage</title>
> </head>
> <body>
>     <h1>Welcome to My Static Webpage</h1>
>     <p>This is a simple static webpage served by Apache.</p>
> </body>
> </html>'
<!DOCTYPE html>
<html>
<head>
    <title>My Static Webpage</title>
</head>
<body>
    <h1>Welcome to My Static Webpage</h1>
    <p>This is a simple static webpage served by Apache.</p>
</body>
</html>
@hanifkamal02 ➜ /workspaces/NatSysProject/webpage (main) $ pwd
/workspaces/NatSysProject/webpage
@hanifkamal02 ➜ /workspaces/NatSysProject/webpage (main) $ docker run --detach -v $(pwd):/usr/local/apache2/hdocs/ -p 8080:80 httpd
Unable to find image 'httpd:latest' locally
latest: Pulling from library/httpd
09f376ebb190: Pull complete 
dab55b4abfc3: Pull complete 
4f4fb700ef54: Pull complete 
1a6d0283f224: Pull complete 
1abf9110528c: Pull complete 
7bacb8f85f3a: Pull complete 
Digest: sha256:43c7661a3243c04b0955c81ac994ea13a1d8a1e53c15023a7b3cd5e8bb25de3c
Status: Downloaded newer image for httpd:latest
5c545ba19c214ce9be320d645c6f4a8b9d477bd96e90732a1cf195a44a1c7f42
@hanifkamal02 ➜ /workspaces/NatSysProject/webpage (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND              CREATED              STATUS              PORTS                                   NAMES
5c545ba19c21   httpd     "httpd-foreground"   About a minute ago   Up About a minute   0.0.0.0:8080->80/tcp, :::8080->80/tcp   admiring_vaughan
@hanifkamal02 ➜ /workspaces/NatSysProject/webpage (main) $ docker run --rm -it httpd bash -c "ls -ld /usr/local/apache2/htdocs"
drwxr-xr-x 2 root root 4096 May 14 02:57 /usr/local/apache2/htdocs
```

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** <br>
**The permission of the folder /usr/local/apache2/htdocs is drwxr-xr-x, and it is owned by the user root and the group root.**
2. What port is the apache web server running. ***(1 mark)*** <br>
**Port 80**
3. What port is open for http protocol on the host machine? ***(1 mark)*** <br>
**Port 8080**

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```

```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network create bluenet
47376be53a7f151a1fbf25303798fff57533b2aa6e417378034fed15c642dcdd
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network create rednet
d0c2c80183ad52c663f4df6bdb100c626eb12f1fd67bb98966c02bc9cf29c528
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker run -itd --net bluenet --name c1 busybox sh
Unable to find image 'busybox:latest' locally
latest: Pulling from library/busybox
ec562eabd705: Pull complete 
Digest: sha256:5eef5ed34e1e1ff0a4ae850395cbf665c4de6b4b83a32a0bc7bcb998e24e7bbb
Status: Downloaded newer image for busybox:latest
c259beda79cc4f41ef8259ccf7f1de2cb667c5f394347c25170a804f9a3a6f0b
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker run -itd --net rednet --name c2 busybox sh
57b7c8d919675f2b418c4ebc5b372f0386b1295242007631437f027ce799b9d4
```

***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** <br>
**Busybox is a small and single binary that contains many common UNIX utilities. The --name command is for giving a custom name to a container.**
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
47376be53a7f   bluenet   bridge    local
fd5e7087adb5   bridge    bridge    local
ea01c4b4bdc6   host      host      local
a113296f7117   none      null      local
d0c2c80183ad   rednet    bridge    local
```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** <br>
**Bluenet Gateway = 172.18.0.1 <br>
  Rednet Gateway  = 192.19.0.1**
4. What is the network address for the running container c1 and c2. <br>
**c1 Network Address = 172.18.0.2 <br>
  c2 Network Address = 192.19.0.2**
5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***
```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

```bash
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network create bridgenet
d3772d6fd930c362abeb4278ddfbbb18cf1f3d0c95aa231ee4b66b795d892cf4
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network connect bridgenet c1
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker network connect bridgenet c2
@hanifkamal02 ➜ /workspaces/NatSysProject (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.148 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.099 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.078 ms
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
