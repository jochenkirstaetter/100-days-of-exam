# Log [#100DaysOfExam](https://www.100daysofexam.com/) - MCSA: Linux on Azure

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