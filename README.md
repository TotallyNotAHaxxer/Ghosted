# Ghosted
```
					______  _     _  _____  _______ _______ _______ ______ 
					|  ____ |_____| |     | |______    |    |______ |     \
					|_____| |     | |_____| ______|    |    |______ |_____/
					*******************************************************
					* Help -> Command list                                *
					* warn -> List all warnings and usages                *
					*******************************************************
					* Ghosted, A shell for automation of os deletion and  *
					* corruption. Written from go, t, asm, C.             *
					*                                                     *
					*Supported systems -> Mac, Windows, Linux             *
					*******************************************************

```

Ghosted is a shell made from pure golang written with inline assembly and C to automate system clean up or deletion
<br>
<br>
# what is this shell for or used to do? 
for some people this program can be used for most things that can take someone a bit to figure out manually. such as<br>
```
  
				________________Command______Type________DangerLevel________Desc________________________
				|[1]  Clear or cls          |None   |    | None to  0   |Clear Terminal                |
				|[2]  time                  |None   |    | None to  0   |Get time current              |
				|[3]  online?               |None   |    | None to  0   |Check connection              |
				|[4]  sys-inf               |None   |    | None to  0   |Get system info               |
				|[5]  cpu                   |None   |    | None to  0   |Get system CPU                |
				|[6]  f-size                |String |    | None to .5   |Get a files size              | 
				|[7]  hex                   |String |    | None to .5   |Read file in byte             |
				|[8]  f-del                 |String |    | None to 1    |Delete a file                 |
				|[9]  copy-f                |String |    | None to 1    |Copy a file to a new location |  
				|[10] exit                  |None   |    | None to 0    |Exit the script               |
				|[11] Ctrl+C <key hangup>   |None   |    | None to 0    |Exit the script via ctrl+C    |
				|[12] h-dir                 |String |    | None to 0    |Get the home dir content      |
				|[13] dir?                  |String |    | None to 0    |Check if a directory exists   |
				|[14] w-dir                 |None   |    | None to 0    |Get the working directory     |
				|[15] c-dir                 |String |    | None to 0    |Create a directory            |
				|[16] walk-dir-l            |String |    | None to 0    |Check a dir for large files   |
				|[17] walk-dir-s            |String |    | None to 0    |Check a dir for ALL files     |
				|[18] h-dir                 |String |    | None to 0    |Check home dir for ALL files  |
				|[19] host                  |None   |    | None to 0    |Get the systems hostname      |
				|[20] tree                  |None   |    | None to 0    |Get all subdir's in home dir  |
				|[21] laddr                 |None   |    | None to 0    |Get all your interfaces       |
				|---------------------------|-------|----|--------------|------------------------------|
				* THIS IS A COMMAND OF DANGER ZONE, COMMANDS HERE CAN RESULT IN SYSTEMATIC CORRUPTION  *
				* OR CAN RESULT IN YOUR OS BEING RESET, DELETED, CORRUPT, OR CRASH. YOU ARE WARNED     *
				****************************************************************************************
				________________Command______Type________DangerLevel________Desc________________________
				|[DE] reset-windows         |None   |    | WARN: 10     |Will reset windows 10 system   |
				|[DE] reset-mac             |None   |    | WARN: 10     |Will reset MAC OS systems      |
				|[DE] reset-linux           |None   |    | WARN: 10     |Will reset linux machines      |
				|[DE] kill-linux            |None   |    | WARN: 100    |Will kill EVERY DRIVE AND PT   | 
				|[DE] reset-settings-dconf  |None   |    | WARN: 10     |Will attempt to reset settings |

```

# what was this shell made to do? 

this shell was made to reset windows, mac and linux systems while also having the complete ability to erase you're entire system ( if you are on linux ) even reset the system settings to defualt ( linux )

# WARNINGS AND PROPER USAGES 

` download the file or git clone, unzip the file, cd into it, go build `
<br>
or you can chmod the linux binary
<br>
`
cd built-linux ; chmod +x ./main ; ./main
`
<br>
PLEASE RUN INSIDE OF A ROOT TERMINAL OR TERMINAL WITH ROOT USER/ADMIN PRIVLEGES, IT WORKS BEST AS THAT WAY
<br>
<br>
# test results from testing on linux, mac, android, and windows
```
When testing on LINUX MACHINES it ended up erasing other disks, this program erases everything from the root directory up so to prevent this, make sure you remove your partitions from the linux system if you have any other operating systems tied to that one to do this you go to your file manager 

under devices you should see the name of the system ( for mine it says parrot-system ) others will differ 

right click that partition 

click remove or unmount

if you are running VM's it is suggested to make sure no other operating systems are slaved together as you can accidentially or possibly corrupt other systems with this.

stept to prevent other corruption on other drives 

remove all usb drives from the ports of your motherboard ( the linux reset will delete everything on the drives, sub drives and  partitions )

take out any extra storage devices that may have other data on them ( MAKE SURE WHEN YOU PLUG THEM BACKIN THEY HAVE DATA ) 

i have a ubuntu rasberry pi with  a server that always keeps my data in the case of corruption it is best TO PLEASE BE CAREFUL WHEN USING THIS SCRIPT ON LINUX SYSTEMS, IT CAN BE DETRIMENTAL TO OTHER OPERATING SYSTEMS PARTITIONED, SLAVED, OR TIED IN ANYWAY.

===============================================================================
WHEN TESTING ON WINDOWS-MAC: all was fine, a smooth factory reset was completed with no worries

```


# further notes 

```
it is suggested to use a root terminal or admin terminal when using the commands in the " danger zone " this is because most of them will not execute without root or some sort of administrative access



======================================
Os's tested: Windows32Bit, Windows64Bit, parrot os linux, ubuntu linux, debian, Deepin/UOS, mint, MacOS.

Languages for programming used: Inline Assembly, Inline C. main language is go. 
```
