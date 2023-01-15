# CIT 352: Chapter 2 

Name: _Sample Answer_ <!-- TODO --> 

Note: In this sample answer, you will see the author included the page
number of where he found the answer to the question in the textbook.
You need not do so. However, please do include your notes if you aren’t
able to complete the hands-on exercise due to some errors you encountered.
It will help the TA to grade your assignment with greater insight.

## Project 2-1

### Step 1 & 2

- Skip (you have already done these steps during VirtualBox installation)

### Step 8a

- Errata: an update with newer Fedora releases (e.g., Fedora 35)
  - [Original] Highlight the / (sda3) partition
  - [Corrected] Highlight the / (sda2) partition

__Insert the screen capture__ (If you had forgotten to take a screen capture during Step 8a, take any screen capture that shows that you have successfully installed Fedora)

_I successfully installed Fedora 28._

![Installed](media/sample0.png) <!-- TODO -->

_In step 14, rather than use my own name, I used “Unnamed User”
as the full name corresponding to username “user1.” 
 
PROBLEM: My new Fedora 34 installation crashed a couple of times during the
user creation step! I just kept shutting down and restarting the VM, and
eventually I was able to create my “Unnamed User” without having it crash._

## Project 2-2

### Step 1: 

- Windows users: Press “Ctrl+Alt+F3” or “Ctrl+Alt+Fn+F3”
- Mac users: Press one of the following key combinations:
  - “control+command+F3” or “control+command+fn+F3”
  - “control+option+F3” or “control+option+fn+F3”.  

### Step 7: 

__Insert the screen capture__, except “exit” command


_For step 6, I found the commands in “Table 2-6” in the section
Basic Shell Commands starting on page 72._

![ls](media/sample1.png) <!-- TODO -->

## Project 2-3

### Step 6:

At the end of this step, type `dnf upgrade` to update all packages on your Fedora (this may take some time to complete)

_For step 4, I saw that the GDM login display manger
was indeed still running on tty1:_

![GDM](media/sample2.png)

### Step 10: 

__Insert the screen capture__

_In step 7, after I rebooted, I was presented with two
distinct Plasma options, Wayland and X11. I chose X11, because
when I looked ahead at step 9, that seemed to be the appropriate choice._

![KDE](media/sample3.png) <!-- TODO -->

## Project 2-4

### Step 6: 

__Insert the screen capture__

_For step 2, the screen utility wasn’t yet installed, so I
needed to install it. But instead of just pressing y twice to install
it, I decided to use the command line dnf install screen to do so._


_This step 6 screen capture illustrates multiple
command shells managed by screen:_
![screen](media/sample4.png) <!-- TODO -->

### Step 10: 

__Insert the screen capture__

_This step 10 screen capture illustrates multiple
command shells managed by tmux:_
![tmux](media/sample5.png) <!-- TODO -->

## Project 2-5

### Step 2: 

- __Describe the purpose of the ; metacharacter__
  - _For step 2, I found table 2-7 in the section “Shell Metacharacters”
  starting on page 74. Usually, to issue a shell command, I hit the
  [Enter] key after typing the command. The semicolon ; metacharacter
  signals the end of a command line, just as if I had pressed [Enter]
  to issue the command, but then it also signals the beginning of
  another separate command line, which will be issued after the previous
  command completes._ <!-- TODO -->

### Step 12: 

- __What function do back quotes perform?__ 
  - _The back quotes cause a command be run first,
  and the output is used as part of the next command._ <!-- TODO -->

__Insert the screen capture__.  Note: `whoami` should be wrapped in
back quotes \` \` both beginning and end, such as `` `whoami` ``.

_For step 11, I needed to put a backslash before the
dollar symbol to get the expected output._ <!-- TODO -->
![back quotes](media/sample6.png) <!-- TODO -->

## Project 2-6

### Step 6:

__Insert the screen capture__

_For step 2, I found table 2-8 in the section
“Getting Command Help” starting on page 76.
 
For step 4: I had become accustomed to using the command man -s 5 crontab
to see the section 5 manual page. I tried it, and it still works in Fedora
34, but I suppose just typing man 5 crontab is simpler and easier._

![Alt Text](media/sample7.png) <!-- TODO -->

_For step 7, the Shift+PageUp and Shift+PageDown
keystrokes didn’t work for me._

## Project 2-7

### Step 2:

- __Which commands from Table 2-9 can also be used to power
off your Linux system immediately?__
  - _For step 2, I found Table 2-9 in section
  “Shutting Down the Linux System” starting on page 81._ <!-- TODO -->
- __Which commands from Table 2-9 can also be
used to reboot your Linux system immediately?__
  - _For step 2, I found Table 2-9 in section
  “Shutting Down the Linux System” starting on page 81._ <!-- TODO -->

## Commands Learned

List all new commands you learned in this chapter. <!-- TODO -->

I have used and administered Linux continually for almost the last thirty
years of my IT career, so most of the shell commands and other content was
familiar to me. However, during all that time I had never used the tmux
utility before until now, so I’m happy to have learned something new!
– Bro. Gibbons 
