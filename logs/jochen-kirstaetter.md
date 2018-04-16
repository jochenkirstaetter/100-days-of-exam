# Log [#100DaysOfExam](https://www.100daysofexam.com/) - MCSA: Linux on Azure

## Day 31: 2018-04-15
### Today's Progress
Had a closer look into the manpage of `mkfs` regarding the various mount options, ie. general ones, specifics for Ext4 and specifics for XFS based on yesterday's learning module.

### Thoughts & Tweet
Today's takeaway is to look into the mount `noatime`, specifically when running Linux on a solid-state disk (SSD). Setting this option on your mountpoints is definitely going to help to increase the expected life-time of your drive.

https://twitter.com/JKirstaetter/status/985699229128511488  

### Resources
[LFCS: Linux Storage Management](https://app.pluralsight.com/library/courses/lfcs-linux-storage-management)  

---- 
## Day 30: 2018-04-14
### Today's Progress
Never looked into the actual differences between EXT4 and XFS. I'm using XFS most of the time.

### Thoughts & Tweet
Well, it's like deciding between chocolate and vanilla. It's all about personal flavour preference. 

https://twitter.com/JKirstaetter/status/985221729319452672  

### Resources
[LFCS: Linux Storage Management](https://app.pluralsight.com/library/courses/lfcs-linux-storage-management)  

---- 
## Day 29: 2018-04-13
### Today's Progress
The information about fdisk and standard partitions was pretty basic compared to previously unknown GUID partitions and the gdisk partitioning tool.

### Thoughts & Tweet
Really interesting to go beyond MBR and the regular partition table. Apart from working with `fdisk` and `dd` it was totally new to learn about GUID partitions and the corresponding `gdisk` tool.

https://twitter.com/JKirstaetter/status/985217948422881280  

### Resources
[LFCS: Linux Storage Management](https://app.pluralsight.com/library/courses/lfcs-linux-storage-management)  

---- 
## Day 28: 2018-04-12
### Today's Progress
Started a new chapter in my preparations for the Linux Foundation Certified System Administrator: It's all about storage management. Shall be interesting to learn more about clusters soon.

### Thoughts & Tweet
Pretty much of an informed repetition of how to partition disks, to assign partition types and to format them accordingly.

https://twitter.com/JKirstaetter/status/984701483886104576  

### Resources
[LFCS: Linux Storage Management](https://app.pluralsight.com/library/courses/lfcs-linux-storage-management)  

---- 
## Day 27: 2018-04-11
### Today's Progress
Another mechanism to authenticate users on Linux is using Kerberos. The importance here is to provide proper time synchronisation between machines on the network by populating a NTP server.

### Thoughts & Tweet
Fascinating to discover that proper time synchronisation is crucial when using Kerberos for user authnetication. One of the best ways under Linux is to set up and propagate your own NTP server on your network. This ensures that all system clocks are in sync and enables proper use of Kerberos.

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  
[LFCS: Linux Storage Management](https://app.pluralsight.com/library/courses/lfcs-linux-storage-management)  

---- 
## Day 26: 2018-04-10
### Today's Progress
Another challenge explored: OpenLDAP. Starting with the initial setup and configuration of a local OpenLDAP tree and schema structure to learn more about LDAP-based authentication on Linux in the second stint.

### Thoughts & Tweet
This is another tough one to master. I think that setting up a fresh OpenLDAP installation helps to better understand the basic principles of operating and managing the resources in the long run. Although it is not really relevant for the exam curriculum it was interesting to know about it. Knowing how to enable user authentication using an existing OpenLDAP system will probably be covered in the exam though.

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day X: 2018-04-09
### Today's Progress
Again, nothing done today.

---- 
## Day X: 2018-04-08
### Today's Progress
Nothing done today.

---- 
## Day 25: 2018-04-07
### Today's Progress
Did a replay on the PAM module. Too much information in short time which needed a repetition to stick properly.

### Thoughts & Tweet
After going through the material a second time and doing a bit more exercise in a live system it is now more clear what can done with PAM. The time restrictions on logins are quite useful to control access to a machine. Set up some limits on my children's laptop.

https://twitter.com/JKirstaetter/status/984308659214680064  

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 24: 2018-04-06
### Today's Progress
Linux Pluggable Authentication Modules (PAM) provide dynamic authentication support for applications and services in a Linux system.

### Thoughts & Tweet
... not yet clear ...

https://twitter.com/JKirstaetter/status/982248508815065089  

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 23: 2018-04-05
### Today's Progress
More reflection on user and group management today. Learned a bit more about primary and secondary group assignments and interesting associations related to that.

### Thoughts & Tweet
There is set of helpful commands to create, manage and delete users as well as groups. Having the ability to define a default configuration and to assign different permissions to each object under Linux is useful for the majority of tasks and requirements. Surely, there are a few more scenarios where more granularity and details on permissions are needed, but for the main part the default user/group management is sufficient and robust enough to handle it.

https://twitter.com/JKirstaetter/status/981982502234411008  

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 22: 2018-04-04
### Today's Progress
Mastering user accounts on Linux is done by a few commands, ie. `useradd`, `userdel` and `usermod`. One tool for one task...

### Thoughts & Tweet
It is interesting to note that there is a different handling of additional helper commands, ie. `adduser` and `deluser` depending on Linux distribution. On systems like CentOS or Red Hat those commands are simple symlinks to the original counter-part whereas on Debian-based distros including Ubuntu those commands are perl scripts with enhanced functionality.

https://twitter.com/JKirstaetter/status/981568172783411200  

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 21: 2018-04-03
### Today's Progress
Started with the introduction into user & group management. Got to understand the difference between login and non-login accounts and the associated login scripts - `.bash_profile` and `.bashrc`.

### Thoughts & Tweet
The relationship between the personal and system-wide login scripts and their sequence of execution is kind of interesting to discover. Also, given that it's slightly different login and non-login (using a sub-set only) accounts. Today's learning session provided some clarification in that area.

https://twitter.com/JKirstaetter/status/981230704422920192  

### Resources
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 20: 2018-04-02
### Today's Progress
Completed the second course on Pluralsight towards the LFCS exam, five more to conquer. Also reached 20% milestone in my #100DaysOfExam challenge today.

### Thoughts & Tweet
I need to pick some pace if I want to complete all materials before running out of days. Currently, I'm on approx. 35% of the LFCS material on Pluralsight, and I still have to cover the courses in the learning path "Implementing Microsoft Azure Infrastructure Solutions (70-533)". Luckily, that one is a bit shorter. The overall estimated amount of time is around 61 hours in total. By reaching day 60 I shall be through all the video material offered by Pluralsight. Doesn't sound too bad after all; but I know I'll be quite occupied with other tasks during those remaining 40 days...
Furthermore, there are other great resources to explore and to manifest my knowledge on Linux and Azure in order to be 100% ready for both exams. Gonna be fun for sure.

https://twitter.com/JKirstaetter/status/980740319124733953  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  
[LFCS: Linux User and Group Management](https://app.pluralsight.com/library/courses/lfcs-linux-user-group-management)  

---- 
## Day 19: 2018-04-01
### Today's Progress
Despite being more familiar with `apt` and `dpkg` it was easy to understand how to work with `yum` and `rpm` on a CentOS machine.

### Thoughts & Tweet
Similarities between different commands on different Linux distributions are given; although I more used to Debian/Ubuntu-based systems it wasn't such an obstacle to get into the inerts of `rpm` and `yum` to complete same tasks, ie. install, upgrade, remove and pinning/keeping packages. Even setting up a local repository of CentOS and adding it to the repository list on a client didn't appear to be complicated.

https://twitter.com/JKirstaetter/status/980473635704983552  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 18: 2018-03-31
### Today's Progress
Instead of learning, it was all about teaching today. I talked about SQL Server on Linux (Ubuntu 16.04) in a VM on Azure. Used `systemctl` and `netstat` to show attendees the status of the `mssql-server` service.

### Thoughts & Tweet
Based on the learning experience of the previous two weeks I felt way more comfortable during the actual demo periods. While talking about a certain activity it was absolutely easy to elaborate more about the commands typed and the command line switches used to achieve a the expected outcome on the big screen. Being more fluent in various keyboard shortcuts (hotkeys) added value to my talk on SQL Server on Linux. Overall it was less of an obstacle talk, type and show at the same time. It seems that this constant learning experience starts to pay off.

https://twitter.com/JKirstaetter/status/980132543012876288  

### Resources
[MSCC meeting: SQL Server on Linux](https://www.meetup.com/MauritiusSoftwareCraftsmanshipCommunity/events/247548681/)  
[SQL Server on Linux](http://sqlserveronlinux.com)  

---- 
## Day 17: 2018-03-30
### Today's Progress
Security Enhanced Linux (SELinux) - a Linux administrator's best friend to handle user's permission to objects on your system.

### Thoughts & Tweet
"SELinux defines the access and transition rights of every user, application, process, and file on the system. SELinux then governs the interactions of these entities using a security policy that specifies how strict or lenient a given Red Hat Enterprise Linux installation should be." That's quite some control options at your hand here...
It's interesting to read that SELinux is partly developed by the U.S. National Security Agency (NSA). Who knew about that?

https://twitter.com/JKirstaetter/status/979685469435777024  

### Resources
[SELinux Project](https://github.com/SELinuxProject)  
[old SELinux Project wiki](https://selinuxproject.org/)  
[Red Hat - Introduction to SELinux](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/5/html/deployment_guide/ch-selinux)  

---- 
## Day 16: 2018-03-29
### Today's Progress
While going through the chapters about log files, `journalctl`, `rsyslogd` and `logrotate` I might have discovered the Holy Grail of output parsing using `awk`.

### Thoughts & Tweet
The abilities using `awk` seem to be endless. Literally, the only frontiers are in your mind. Parsing the STDOUT of any command into the right shape and arrangement is really easy with `awk`. Also, querying log files for specific data is a breeze like this.

https://twitter.com/JKirstaetter/status/979393265463042050

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 15: 2018-03-28
### Today's Progress
Simplify your administrator life on Linux with scheduled tasks. Again, there are multiple tools available to get the job done.

### Thoughts & Tweet
Interesting lessons on commands like `cron`, `anacron`, and `at` to learn more about ways to setup and configure scheduled tasks on a Linux machine. The use of `anacron` is really interesting to achieve irregular timings on regular tasks. Could be used for real fun stuff. Today, I also checked out the corresponding man-pages of anacron(8) and cron(8) for a general overview and details on the scheduling options.

https://twitter.com/JKirstaetter/status/978832047488864256  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  
[The Official Red Hat Linux Customization Guide - Chapter 22. Automated Tasks](https://www.centos.org/docs//2/rhl-cg-en-7.2/autotasks-additional-resources.html)  

---- 
## Day 14: 2018-03-27
### Today's Progress
Working with shared libraries on Linux is greater than the sum of its parts.

### Thoughts & Tweet
Almost everything in the architecture and way of working on a Linux system is broken down into small functional binaries, ie. libraries or components, which empowers you do more given an endless number of combinations. Shared libraries below `/usr/share/` are following exactly that concept.

https://twitter.com/JKirstaetter/status/978688601927114752  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 13: 2018-03-26
### Today's Progress
Explored the various binaries in the `procps-ng` package. Whew, quite some interesting information that you get out your Linux system.

### Thoughts & Tweet
Most interestingly is that the different commands are literally reading the data from the files below the `/proc` folder and reshape them into a more human-readable and practical form.

https://twitter.com/JKirstaetter/status/978681761633730560  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 12: 2018-03-25
### Today's Progress
Flashback today: Using `nice` to change priority and processing level of a process. Learned about that command on HP AIX Unix over 20 years ago. The output options of `ps` are quite handy to get information about the processes on your system.

### Thoughts & Tweet
Lots of repetition today given that the commands discussed are commonly used on a Linux system. Was `nice` to see that the instructor Andrew seems to like the `ps aux` output. There's lot of information available in the `/proc/` folder.

https://twitter.com/JKirstaetter/status/977946586343817217  

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 11: 2018-03-24
### Today's Progress
Digging a bit deeper into the nuts & bolts of the shutdown and boot processes of Linux. Starting with `shutdown` to understand the different `runlevel` and their implications, and then to explore `grub2` and related tools to configure the boot process.

### Thoughts & Tweet
Kind of funny approach to *begin with the end*... After going through the modules I'm now more confident about how to handle a boot problem on a Linux system. The info about the `grub2` configuration options is very helpful, and working with the rescue system surely is going to be part of the exam questionnaire. Not sure what to think about `grubby` - its use seems less practical on the command line due to all kind of switches compared to editing the `grub.cfg` directly. Might give it a shot though...

https://twitter.com/JKirstaetter/status/977457073528061952 

### Resources
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 10: 2018-03-23
### Today's Progress
Milestone achieved: Completed 1st module of LFCS learning path covering Linux essentials. And directly into the operation essentials for more fun.

### Thoughts & Tweet
Interestingly and somehow relieving, this first course of LFCS certification had only a few bits and pieces unknown to me. Over the years I've used the majority of commands discussed. Just the chapters on `vim`, named pipes and some goodies using `ssh` were really new. Now, I'm looking forward to explore more commands for daily use on Linux.

https://twitter.com/JKirstaetter/status/977037472340180992 

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)  
[LFCS: Linux Operation Essentials](https://www.pluralsight.com/courses/lfcs-linux-operation-essentials)  

---- 
## Day 9: 2018-03-22
### Today's Progress
Covered the basic configuration and use of `ssh`, and embarked on a Linux Journey to [Learn the ways of Linux-fu](https://linuxjourney.com/).

### Thoughts & Tweet
Accessing another Linux machine remotely in a secure fashion is made so easy by using the SSH protocol. And by configuring public key authentication it gets even easier on the client machine to log into a remote system. Very neat and handy indeed.
Additionally, I came across a nicely made website to learn and improve your *Linux-fu*. From first looks and excersises it appears to be a helpful compagnion to prepare for the LFCS. 

https://twitter.com/JKirstaetter/status/976652113995489280 

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)  
[Linux Journey](https://linuxjourney.com/)  
[GitHub: Linux Journey](https://github.com/cindyq/linuxjourney) 

---- 
## Day 8: 2018-03-21
### Today's Progress
Explored the various help systems on Linux, and got myself into file and directory permissions.

### Thoughts & Tweet
Managing those octets is essentials in a multi-user environment but not so on a single-user machine. Also `su` and `sudo` are quite handy as Linux version of `runAs`.

https://twitter.com/JKirstaetter/status/976292923510734853

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 7: 2018-03-20
### Today's Progress
Still continuing on the Linux Essentials course modules. Today was a double-feature: `Piping and Redirection` together with `Archiving Files`.

### Thoughts & Tweet
Really practical to see how the anomynous pipes are actually working, and getting more familiar with `STDOUT`, `STDERR` and `STDIN` was kind of fun. Although, it's a little bit intimidating to work with named pipes. The chapter on archiving was mainly a refresher as I'm used to `tar`, `gzip` and `bzip`. Neat trick to use `dd` to wipe a partition or even an entire harddrive.

https://twitter.com/JKirstaetter/status/976140756720148481

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 6: 2018-03-19
### Today's Progress
Going through the suggested lessons of vimtutor. Took me longer than expected; that constant mode switching isn't obvious.

### Thoughts & Tweet
Whew, I went through the `vimtutor` lessons using #Ubuntu on WSL. Clearly, that constant switching between Normal & Insert mode is not for me. Surely something to practice more regularly in order to get a grip on it. Interesting for sure but unusual compared to my given experience.

https://twitter.com/JKirstaetter/status/975658988103548929

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)  
[Microsoft Cloud Society](https://cloudsociety.microsoft.com/)

---- 
## Day 5: 2018-03-18
### Today's Progress
Usually I'm using the nano text editor learning about Vi and Vi Improved (vim) was quite interesting.

### Thoughts & Tweet
Although it's possible to work with `nano` during the exam, it seems recommended to get more familiar with `vim`. Guess it's time for a dedicated session to go through the `vimtutor` instruction these days. Shall be fun!

https://twitter.com/JKirstaetter/status/975289038113447936

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 4: 2018-03-17
### Today's Progress
Learned about 'Reading files' and did a few experiments on the command line

### Thoughts & Tweet
It's interesting to realise there are usually more than one solution to a problem under Linux. Reading files is possible with `cat`, `less`, `head`, or `tail`. Searching in files with `grep` seems quite practical using regular expressions.

https://twitter.com/JKirstaetter/status/974882295734816768

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 3: 2018-03-16
### Today's Progress
Completed the course module `Working at the Command Line` and learned more details about files, directories and links on Linux.

### Thoughts & Tweet
Although I'm already familiar with basic file and directory handling using commands like `ls`, `mkdir`, `rm`, `mv` and `cp` it was interesting to see some of the available switches. A few of them I already knew but there some new gems among the lectures.
Got some insights about the underlying meta-data and inode information, too.

https://twitter.com/JKirstaetter/status/974396318297673730

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 2: 2018-03-15
### Today's Progress
Managed to complete the installation and configuration of CentOS 7 virtual machine on a spare system. 

### Thoughts & Tweet
Additionally to my statement about using a CentOS 7 VM on Azure I installed another virtual machine locally. Don't know but it seems more 'connected' than just having the remote access on a cloud platform. Have to see how this works out in the upcoming days.

https://twitter.com/JKirstaetter/status/974152967539453953

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)  
[Oracle VirtualBox](https://www.virtualbox.org/)

---- 
## Day 1: 2018-03-14
### Today's Progress
I decided to get into the Linux track first. The first course modules are about the purpose of the course, the Linux Foundation, about CentOS and why to use it to prepare for the LFCS.

### Thoughts & Tweet
I like the presentation style of [Andrew Mallett](https://twitter.com/theurbanpenguin). He keeps me connected to the material and skips the 'waiting' parts nicely.

https://twitter.com/JKirstaetter/status/973672046503718915

### Resources
[LFCS: Linux Essentials](https://app.pluralsight.com/library/courses/lfcs-red-hat-7-essentials)

---- 
## Day 0: 2018-03-13
### Today's Progress
I launched the #100DaysOfExam challenge to keep myself focused and accountable for my current studies. Blogged about [Next stop: MCSA: Linux on Azure](https://jochen.kirstaetter.name/mcsa-linux-on-azure/)

### Thoughts & Tweet
Not sure what I'm going to kick off here but at least I know that I have a target to go for, and this #100DaysOfExam challenge is going to help to focus and stay committed to my studies.

https://twitter.com/JKirstaetter/status/973532593470685184

### Resources
[Collection of study material for MCSA: Linux on Azure](../resources/Microsoft/mcsa-linux-on-azure.md)

---- 