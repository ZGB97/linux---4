<h1> Managed Linux Storage Using Gparted </h1>

<h2>Description</h2>
During this tasks I modified an existing partition on Ubuntu Linux using Gparted without data loss. Through a series of steps, including resizing and remounting the partition.

<h2>Languages and Utilities Used</h2>

- <b> Operating System: Ubuntu Server </b>
- <b> Gparted (Partition Editor) </b>
- <b> Terminal commands: df, grep, ls </b>
- <b> VCASTLE </b>

<h2>Screenshots:</h2>

<p align="center">
df -h | grep sd : <br/>
<img src="https://i.imgur.com/Z0Qrrqp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Mounting the partition to the appropriate location after resizing it using Gparted:  <br/>
<img src="https://i.imgur.com/HQCKez4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
df -h | grep sd : <br/>
<img src="https://i.imgur.com/QkIAuge.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ls -l /home/NewDrive :  <br/>
<img src="https://i.imgur.com/vogiZBN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
