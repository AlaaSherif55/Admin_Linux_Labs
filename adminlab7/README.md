## Lab7-1
### 1. Using the useradd command, add accounts for the following users in your system: user1, user2, user3, user4, user5, user6 and user7. Remember to give each user a password.
![UNFOUND]()
###  2. Using the groupadd command, add the following groups to your system.Group			GID sales			10000hr		10001 web			10002, Why should you set GID in this manner instead of allowing the system to set the GID by default?
![UNFOUND]()
### 3. Using the usermod command to add user1 and user2 to the sales secondary group, user3 and user4 to the hr secondary group. User5 and user6 to web secondary group. And add user7 to all secondary groups  
![UNFOUND]()
###  4.  Login as each user and use id command to verify that they are in the appropriate groups. How else might you verify this information?
![UNFOUND]()
###  5. Create a directory called /depts with a sales, hr, and web directory within the /depts directory.
![UNFOUND]()
### 6. Using the chgrp command, set the group ownership of each directory to the group with the matching name.
![UNFOUND]()
### 7. Set the permissions on the /depts directory to 755, and each subdirectory to 770
![UNFOUND]()
### 8. Set the set-gid bit on each departmental directory.
![UNFOUND]()
### 9. Use the su command to switch to the user2 account and attempt the following commands:
  #### touch /depts/sales/user2.txt
  #### touch /depts/hr/ user2.txt
 ####  touch /depts/web/ user2.txt
 ![UNFOUND]()
#### Which of these commands succeeded and which failed? What is the group ownership of the files that were created? ### 10. Configure sudoers file to allow user3 and user4 to use /bin/mount and /bin/umount commands, while allowing user5 only to use fdisk command.
![UNFOUND]()
### 11. Login by user3 and try to unmount /boot.
![UNFOUND]()
### 12. Login by user4 and remount /boot. Also try to view the partition table using fdisk.
![UNFOUND]()
### 13. Create a directory with permissions rwxrwx---, grant a second group (sales) r-x permissions
![UNFOUND]()
### 14.  create a file on that directory and grant read and write to a second group (sales)
![UNFOUND]()
### 15. set the the owning group as the owning group of any newly created file in that directory.
![UNFOUND]()
### 16. Grand your colleagues a collective directory called /opt/research, where they can store generated research results. Only members of group profs and grads should be able to create new files in the directory, and new file should have the following properties:
#### • the directory should be owned by root
![UNFOUND]()
#### • new files should be group owned by group grads
![UNFOUND]()
#### • group profs should automatically have read/write access to new files
![UNFOUND]()
#### • group interns should automatically have read only access to new files
![UNFOUND]()
#### • other users should not be able to access the directory and its contents at all.
![UNFOUND]()
