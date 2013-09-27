sshpasswordchanger
==================

Python command tool for changing password remotely over ssh using paramiko module

usage:
======
<pre>
python sshpasschanger.py -c <config filename>
</pre>
config format:
==============
<pre>
HOST <host number/name>
IP: <ip address>
username: <username>
password: <current password>
newpass: <new password>

# Example Config example
HOST 1
IP: 192.168.1.2
username: testuser
password: testpass
newpass: testnewpass
</pre>
