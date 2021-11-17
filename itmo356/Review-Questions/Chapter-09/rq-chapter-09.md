# Review Questions - Chapter 09

1) What user account has superuser privilege in Linux?

d. ```root```

2) Which command do you use to temporarily elevate your user's privilege to the superuser (root)?

b. ```sudo```


3) How can you display the content of a file named topsecret.txt that has permissions 000 and is owned by another user?

c.  ```sudo cat topsecret.txt```


4) What license is the sudo application under?

d.  ISC

5) Which operating system doesn't have an active root account by default?

b. Ubuntu


6) What is the name of the file where sudo privilege are kept?

d. /etc/sudoers

7) What is the name of the command used to modify /etc/sudoers to grant a new user sudo privilege?

c. visudo

8) Based on this line in /etc/sudoers - ```%meninblack  ALL=(ALL:ALL) ALL``` - what does the first value by the % mean?

a.  Name of a group


9) In the /etc/sudoers file - what does this line mean: ```RMS ALL=(root) NOPASSWD: ALL```

d.  The user RMS has sudo permissions and access to all commands, and requires no password to elevate to the sudo user

10) When using the su command to switch from a regular user account to the root user account, what do you type to return to the standard user account?

b.  exit


11) What command would you use to edit the file at this location:  /var/www/html/index.html?
a.  vi /var/www/html/index.html
b.  sudo vim /var/www/html/index.html
c.  vim /var/www/html/index.html
d.  You need to ```chown``` the file and change the owner

12) On a Linux system, which directory are all the traditional system (non-systemd) logs kept in?
a.  /var/run
b.  /logs
c.  /var/adm/log
d.  /var/log

13) Under systemd and journald where are the logs kept?
a.  /var/log
b.  /var/log/error
c.  /var/log/journald
d.  Trick question - as logs are stored in a binary format and retrieved via journalctl

14) What is the command you use to query the system logs in systemd?
a.  systemctl
b.  journald
c.  journalctl
d.  showlogs

15) How would you filter the systemd log based on time? (Which is valid syntax?)
a.  ```journalctl --since=yesterday```
b.  ```journalctl --since=tomorrow```
c.  ```journalctl --yesterday```
d.  ```journalctl --filter=yesterday```

16) Where is the journald.conf file located?
a. /etc/logrotate.conf
b. /etc/systemd/journalctl.conf
c. /etc/systemd.conf
d. /etc/systemd/journald.conf

17) What command provides a dynamic real-time view of a running system?
a.  top
b.  iostat
c.  ranwhen
d.  journalctl

18) Debian based distros have an additional command to abstract the process to add users to the system - what is it?
a.  useradd
b.  usermod
c.  adduser
d.  add

19) What command would be used to modify a user account settings and add them to the sudo users group on an Ub untu distro (user is named controller)?
a.  ```sudo useradd -aG sudo controller```
b.  ```sudo usermod -aG sudo controller```
c.  ```sudo usermod -G sudo controller```
d.  ```sudo userdel controller```

20) Which below are valid useradd commands?  (Choose all that apply)
a. ```sudo useradd -c "User for spring class" -d "/home/export/controller" -G sudo -s /bin/ksh -m controller```
b. ```sudo useradd -D controller```
c. ```sudo useradd controller```
d. ```sudo useradd -G sudo -s /bin/ksh -m controller```
e. ```sudo useradd -c "User for spring class" -G sudo -m controller```
