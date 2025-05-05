# Lab 2 — Command Line
---
## Below are the commands, followed by the response from the terminal for each
> $ 
- DESKTOP-25RC8J8

> $ env
- ProgramFiles(x86)=C:\Program Files (x86) !::=::\ CommonProgramFiles(x86)=C:\Program Files (x86)\Common Files...
- ![](https://github.com/AnotherAnotherAustin/repotime/blob/main/env.png) 

> $ ps
-     PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAND
-     1761    1760    1761      14392  pty0      197609 11:07:36 /usr/bin/bash
-     2215    2214    2215      43640  pty4      197609 14:01:14 /usr/bin/bash
-     2084       1    2084      18016  ?         197609 11:41:51 /usr/bin/mintty
-     2270       1    2270      56316  ?         197609 14:06:12 /usr/bin/mintty
-     2271    2270    2271      59104  pty2      197609 14:06:13 /usr/bin/bash
-     2085    2084    2085      28144  pty3      197609 11:41:51 /usr/bin/bash
-     2214       1    2214      57392  ?         197609 14:01:14 /usr/bin/mintty
-     2301    2248    2301      42028  pty1      197609 14:09:08 /usr/bin/ps
-     2247       1    2247      58412  ?         197609 14:06:08 /usr/bin/mintty
-     2248    2247    2248      59412  pty1      197609 14:06:08 /usr/bin/bash
-     1760       1    1760      41100  ?         197609 11:07:36 /usr/bin/mintty

> $ pwd
- /c/Users/austi

> $ git clone https://github.com/kevinwlu/iot.git
- fatal: destination path 'iot' already exists and is not an empty directory.

> $ cd iot
- austi@DESKTOP-25RC8J8 MINGW64 ~/iot (master)

> $ ls
- README.md  economics/  lesson10/  lesson4/  lesson8/   special_problems/
- apps/      health/     lesson11/  lesson5/  lesson9/   standards/
- cases/     hype/       lesson2/   lesson6/  make/      systems/
- design/    lesson1/    lesson3/   lesson7/  projects/  tools/

> $ cd
- austi@DESKTOP-25RC8J8 MINGW64 ~

> $ df
- Filesystem           1K-blocks      Used Available Use% Mounted on
C:/Program Files/Git 497273852 383957436 113316416  78% /

> $ mkdir demo
- mkdir: cannot create directory ‘demo’: File exists

> $ cd demo
austi@DESKTOP-25RC8J8 MINGW64 ~/demo

> $ nano file
- ![](https://github.com/AnotherAnotherAustin/repotime/blob/main/nano.png) 

> $ cat file
- This is the finest demo file on this side of the equator.

> $ cp file file1
- austi@DESKTOP-25RC8J8 MINGW64 ~/demo
  
> $ mv file file2
- austi@DESKTOP-25RC8J8 MINGW64 ~/demo

> $ rm file2
- austi@DESKTOP-25RC8J8 MINGW64 ~/demo

> $ clear
- (clears terminal)

> $ man uname
- bash: man: command not found

> $ uname -a
- MINGW64_NT-10.0-26100 DESKTOP-25RC8J8 3.5.7-463ebcdc.x86_64 2025-03-03 17:26 UTC

> $ ifconfig
- bash: ifconfig: command not found

> $ ping localhost
- Pinging DESKTOP-25RC8J8 [::1] with 32 bytes of data:
- Reply from ::1: time<1ms
- Reply from ::1: time<1ms
- Reply from ::1: time<1ms
- Reply from ::1: time<1ms

- Ping statistics for ::1:
-     Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
- Approximate round trip times in milli-seconds:
-     Minimum = 0ms, Maximum = 0ms, Average = 0ms

> $ netstat
- ![](https://github.com/AnotherAnotherAustin/repotime/blob/main/ConnectionsLab3.png) 

