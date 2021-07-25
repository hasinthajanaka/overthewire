# Bandit Level 2 → Level 3

## Level Goal

The password for the next level is stored in a file called spaces in this filename located in the home directory

### SSH Connect

command `ssh bandit2@bandit.labs.overthewire.org -p 2220`


### Gain Password

```
bandit2@bandit:~$ ls /home/bandit2
spaces in this filename

bandit2@bandit:~$ cd /home/bandit2
bandit2@bandit:~$ cat spaces\ in\ this\ filename 
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

```

Result `UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK`

