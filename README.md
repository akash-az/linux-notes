                                     Introduction to linux.

in 1964 linux - started -> Bell Laboratory,New Jersey -> to build operating system for multi user. 5 people
In 1969 the project was widrawn.

but Dennis ritchie( c language) and ken thompson still worked and made > UNICS (Uniplexed Information and Computing Services)>free

in 1975 > UNIX v6 > became popular.

- Now multiple companies made their own commercial version.

unics versions >

IBM > AIX
Sun > Solaris
apple > Mac OS
HP > UX

> These above are called flavour of UNIX.

Then Linux was creatd as flavour of unics.

Linus Torvald (1991) > student at hashing university > wanted free unics version.

Linus Torvald wrote Linux from scratch. (Inspired by unics os and MINIX (created by Andrew Tanenbaun for teaching students))

- Andrew Tanenbaun was a professor(computer networks pearson publication )

Around 1991 and 1995 a free software movement was started. bcus company giants like IBM and apple provided high paid softwares and people were not
able to learn. > Free Software movement was started (GNU was the name of the movement.)

GNU Members provided many free softwares.

Linux is a kernel not an operating system.
An operating system = kernel + Softwares. (linux + GNU is an OS) > but us usually reffered as LINUX

\*\* kernel is a part of an OS.

## Linux was provided as open source OS and multiple companies made their own versions.

Linux > RHEL (Red Hat Enterprise Linux) > one of the most popular. > Red Hat is a company (provides free os but paid services)
Linux > Fedora (Fedora is a group that provides fedora OS) (provides free os but paid services)
Linux > Debian (provides free os but paid services)
Linux > free Ubuntu, CentOS, Amazon Linux (these are completely free)
Linux > kali linux (mostly used by hackers)

\*\* Enetrprise versions are paid.

- CentOS is teh fastest (Community Enterprise Operating System)
- Ubuntu is 3rd most popular linux distribution (Ubunt means team work >made by an African)

\*\* Os is operated by CLI and GUI

- GUI is popular in windows
- CLI is used by linux.

\*\* Different linux versions are called linux distribution

- Distribution is aka OS

\*\* Advantages of LINUX os

-> Linux is not a UNIX derivative.
-> Linux is secure compared to windows.

- Bcus usually when virus enters a windows folder it starts dpreading in the entire system. >uses antivirus
  But when it enters a linux folder it remains there. > does not need antivirus > just delete the folder.
  ->Simplified updates of all installed softwares.
  ->Light weight (Size(aka foot print) of os is less and ram consumption is less ) (1gb ram equivalent to 50gb RAm for windows)

-> Multi User - Multi task > 1 linux sercver can be access by multiple users and have shared cpu and hardware
-> Linux supporst multiple users
-> But in windows same thing can happen but limited users
->Unlike WIndows linux has multiple distributions > Red Hat,Debian, Fedora.

Layered architecture of Windows and Linux

Windows :

1st innner most layer is the :

> hardware
> Operating System (os interacts with the hardware and provides request made by shell and manages hardware)
> Shell (Shell interacts with user, accepts requests from user and sends to the OS)
> User > provides command or requests

- Most used terms
  > folder(aka directory in linux)
  > Administrator(aka root user in linux)
  > Software(aka package)

Linux :

1st innner most layer is the :

> hardware
> Kernel(here acting as OS) ( interacts with the hardware and provides request made by shell and manages hardware)
> Shell (Shell interacts with user, accepts requests from user and sends to the OS)
> User > provides command or requests
> \*\* Most used terms
> Directory
> Root user (aka administrator)
> package (aka software in windows.)

\*\* Advatanges over windows

In Linuc CLI is used for performing operations and compared to GUI which adds extra operations of mouse movements > clicks > Accessing request >
Creating command for request and then sending to shell .

                                FIle system hierarchy

Windows :

in windows -> C:\ (backward slash ,root directory , created by default) > contains all the configuration files of windows. > Program files,users,Prograam(x86),Perflogs

Linux :
4es5dtd6te5ers5tgd
in linux -> / (forward slash, is the top level root directory) > /root,/home,/boot,/etc,/usr,/bin

/ - The main (root) directory of Linux  
/bin - Basic commands like  (cp), move (mv), and list (ls) ,Essential binaries (commands taht can be used by all users)
/sbin - Special commands for system management ,(System binaries (admin commands only used by admins))
/boot - Files needed to start (boot) the system ,(kernel, bootloader)
/dev - Special files for hardware like hard drives and USBs  
/etc - Settings and configuration files for the system (System configuration files ),like 4gb RAM, 1TB harddisk etc
/home - Personal folders for users (User home directories )
/lib - Important files that help programs run (Shared libraries for system binaries)
/media - 'p\_?>KWhere USB drives and CDs are accessed (Mount point for external media (USB, CD))
/mnt - Temporary place to attach (mount) extra storage (Temporary mount point for filesystems )  
/opt - Extra software installed manually ( Optional software packages ) like google chrome.
/proc - Information about running programs and the system ,(Virtual filesystem for system info)
/root - Personal folder for the system administrator (root user) (Root user’s home directory,also if no users are created root is default )  
/run - Temporary files needed while the system is running ,(Temporary runtime files)  
/srv - Data used by services like web servers ,( Data for system services (e.g., web, FTP))
/sys - Details about the system and hardware,(System and hardware info )  
/tmp - Temporary files that are deleted on restart ,(Temporary files (cleared on reboot) )
/usr - Programs and files for users (e.g., applications),(User applications and utilities ) are by default installed here.
/var - Frequently changing data like logs and emails ,(Variable data (logs, cache, mail))

Boot process -> After a pc is switched on > all inactive files,packages are activated also POST (Power on self test is done like battery is charged or not

### Commands 

🔹 1. nano – Command-Line Text or (Beginner-Friendly)

📌 Basic Syntax: nano filename


✅ Scenarios & Examples:

🔸 Scenario 1: Create a new file

nano notes.txt
You enter nano’s or.

Type: This is my first note.

Save: Press Ctrl + O, then Enter.

Exit: Press Ctrl + X.

🔸 Scenario 2:  existing file

nano /etc/hostname
Use arrow keys to navigate.

 the hostname.

Save and exit as above.


🔸 Useful Shortcuts:
Ctrl + O: Write out (save)

Ctrl + X: Exit

Ctrl + W: Search

Ctrl + K: Cut line

Ctrl + U: Paste

🔹 2. touch – Create Empty File / Modify Timestamp


📌 Basic Syntax:

touch filename
✅ Scenarios & Examples:
🔸 Scenario 1: Create multiple files
touch file1.txt file2.txt file3.txt


🔸 Scenario 2: Update timestamp (modification time)
touch existing.txt


🔸 Scenario 3: Create files inside folders
mkdir logs
touch logs/app.log logs/db.log


🔸 Scenario 4: Use -t to set a custom timestamp
touch -t 202401011200 file.txt
(This sets the file's date to Jan 1, 2024, 12:00 PM)


🔹 3. cat – Display or Create File Content

📌 Basic Syntax:

cat filename
✅ Scenarios & Examples:

🔸 Scenario 1: View a file
cat hello.txt


🔸 Scenario 2: Create a file with cat
cat > grocery.txt
Milk
Eggs
Bread
# Press Ctrl + D to save


🔸 Scenario 3: Concatenate multiple files
cat part1.txt part2.txt > combined.txt


🔸 Scenario 4: Append to a file
cat >> notes.txt
# Type more lines
# Press Ctrl + D


🔸 Scenario 5: Number lines
cat -n script.sh



🔹 4. vi and vim – Powerful Terminal Text ors
vi is the older version; vim (Vi IMproved) is more powerful and feature-rich.

📌 Basic Syntax:

vi filename
vim filename
✅ Modes in vi/vim:
Normal mode (default): For commands

Insert mode: For typing (i to enter)

Visual mode: For selection

Command mode: For actions like save, exit (:)

✅ Scenarios & Examples:


🔸 Scenario 1: Create/ a file

vi example.txt
Press i → enter insert mode → type: "Hello Vim"

Press Esc → back to normal mode

Type :wq → save and quit

🔸 Scenario 2: Quit without saving
vim

:q!

🔸 Scenario 3: Save without quitting
vim


:w

🔸 Scenario 4:  and paste lines

yy → yank () current line

p → paste after current line

🔸 Scenario 5: Delete text

dd → delete current line

d$ → delete to end of line


🔸 Scenario 6: Search

vim


/foo

Use n for next match, N for previous

🔸 Scenario 7: Replace
vim


:%s/old/new/g

Replace all "old" with "new" in the file


## CReate Directories :

## command > mkdir : make directory

 * for creating folder > mkdir directort-name  
 * for creating folder inside a folder inside a folder >   mkdir dir2/dir3/dir4  : here slashes are called separation.
 * * / means root when nothing is behind it > /home/ec2-user : first / is root and 2nd / is separation.
  
 * cd directory-name > cd here is change directory
 * cd .. > for going to parent directory.
 * pwd : print working directory

   #Example :
   pwd : shows > /home/ec2-user/dir1/dir2/dir3
   to reach to ec2-user > cd../../..

   commands for : how to copy a file.
                  how to cut and paste file
                  how to rename a file or directory
                  how to create hidden file or directory
                  how to remove file or directory

   # how to create hidden file or directory
   touch .file-name
   ls -a : for seeing all file and folder including hidden.
   mkdir .directory-name

   * use dot before any file or folder name for any coomand

   #  how to copy a file.
   * cp file1 file2 : here file1 is source and file2 is destination

   #  how to cut and paste file
   command : mv file1 directory1 > moves file1 to directory1 

   # how to rename a file or directory
   command > mv file1 myFIle : moves content of file1 to myFile making it look like rename process.

   #  how to remove file or directory
   * rmdir > used to remove specified empty directory  > rmdir dir-name
   * rmdir -p > remove both the parent and child directory > rmdir -p dir1/dir2
   * rmdir -pv > removes all the parent and subDirectory along with the Verbrase.
  
   * rm -rp > remove non-empty directories including parent and sub directory. : p here means parent.
   * rm -rf > removes even non-empty file and directory : f here means forcefully
   * rm -r > removes empty directory 
     
  
   

    

