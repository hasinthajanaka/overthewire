# Bandit Level 4 → Level 5

## Level Goal

The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

### SSH Connect

command `ssh bandit4@bandit.labs.overthewire.org -p 2220`

### Find password for level 5

```
bandit4@bandit:~$ cd /home/bandit4/inhere/
bandit4@bandit:~/inhere$ ls
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@bandit:~/inhere$ ls
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@bandit:~/inhere$ head ./-file00
�/`2ғ�%��rL~5�g��� �����
bandit4@bandit:~/inhere$ head ./-file01
��p,k�;��r*��	�.!��C��J	�dx,�
bandit4@bandit:~/inhere$ head ./-file02
e�)�#��5��
          ��p��V�_���ׯ�mm
bandit4@bandit:~/inhere$ head ./-file03
������h!TQO�`�4"aל�߂phT��,�A
bandit4@bandit:~/inhere$ head ./-file04
?�
bandit4@bandit:~/inhere$ head ./-file05
�r�l$�?h�9('���!y�e�#�x�O��=��
bandit4@bandit:~/inhere$ head ./-file06
ly���~��A�f����-E�{���m�����ܗM
bandit4@bandit:~/inhere$ head ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit4@bandit:~/inhere$ head ./-file08
�T�?�i��j��îP�F�l�n��J����{��@
bandit4@bandit:~/inhere$ head ./-file09
�e�0$�in=��_b�5FA�P7sz��gN
bandit4@bandit:~/inhere$ 
```

Result `koReBOKuIDDepwhWk7jZC0RTdopnAYKh`