# Bandit Level 3 → Level 4

## Level Goal

The password for the next level is stored in a hidden file in the inhere directory.

### SSH Connect

command `ssh bandit2@bandit.labs.overthewire.org -p 2220`


### Gain access to level4

```language
bandit3@bandit:~$ cd /home/bandit3
bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ ls -la inhere/
total 12
drwxr-xr-x 2 root    root    4096 May  7  2020 .
drwxr-xr-x 3 root    root    4096 May  7  2020 ..
-rw-r----- 1 bandit4 bandit3   33 May  7  2020 .hidden
bandit3@bandit:~$ cat inhere/.hidden 
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit3@bandit:~$ 
```

Result `pIwrPrtPN36QITSp3EQaw936yaFoFgAB`