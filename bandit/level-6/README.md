# Bandit Level 5 → Level 6

## Level Goal

The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

    - human-readable
    - 1033 bytes in size
    - not executable

### SSH Connect

commands `ssh bandit5@bandit.labs.overthewire.org -p 2220`
password koReBOKuIDDepwhWk7jZC0RTdopnAYKh

```
bandit5@bandit:~/inhere$ du -b -a
8880    ./maybehere03/.file2
9234    ./maybehere03/spaces file3
8275    ./maybehere03/-file3
6595    ./maybehere03/-file2
2282    ./maybehere03/.file3
2190    ./maybehere03/spaces file1
315 ./maybehere03/-file1
3385    ./maybehere03/spaces file2
9769    ./maybehere03/.file1
55021   ./maybehere03
4740    ./maybehere19/.file2
2307    ./maybehere19/spaces file3
7965    ./maybehere19/-file3
5594    ./maybehere19/-file2
494 ./maybehere19/.file3
7186    ./maybehere19/spaces file1
6302    ./maybehere19/-file1
8785    ./maybehere19/spaces file2
7209    ./maybehere19/.file1
54678   ./maybehere19
8976    ./maybehere06/.file2
8065    ./maybehere06/spaces file3
3443    ./maybehere06/-file3
1076    ./maybehere06/-file2
2418    ./maybehere06/.file3
4073    ./maybehere06/spaces file1
5731    ./maybehere06/-file1
4251    ./maybehere06/spaces file2
1271    ./maybehere06/.file1
43400   ./maybehere06
8244    ./maybehere12/.file2
1639    ./maybehere12/spaces file3
9076    ./maybehere12/-file3
251 ./maybehere12/-file2
1022    ./maybehere12/.file3
2157    ./maybehere12/spaces file1
9678    ./maybehere12/-file1
2460    ./maybehere12/spaces file2
5815    ./maybehere12/.file1
44438   ./maybehere12
8472    ./maybehere16/.file2
7509    ./maybehere16/spaces file3
8085    ./maybehere16/-file3
5301    ./maybehere16/-file2
1148    ./maybehere16/.file3
9773    ./maybehere16/spaces file1
4277    ./maybehere16/-file1
3146    ./maybehere16/spaces file2
5426    ./maybehere16/.file1
57233   ./maybehere16
2577    ./maybehere02/.file2
2275    ./maybehere02/spaces file3
4932    ./maybehere02/-file3
3511    ./maybehere02/-file2
7953    ./maybehere02/.file3
6746    ./maybehere02/spaces file1
3801    ./maybehere02/-file1
8488    ./maybehere02/spaces file2
6351    ./maybehere02/.file1
50730   ./maybehere02
3070    ./maybehere01/.file2
8834    ./maybehere01/spaces file3
9641    ./maybehere01/-file3
288 ./maybehere01/-file2
3792    ./maybehere01/.file3
4139    ./maybehere01/spaces file1
6028    ./maybehere01/-file1
4543    ./maybehere01/spaces file2
8944    ./maybehere01/.file1
53375   ./maybehere01
8341    ./maybehere17/.file2
6381    ./maybehere17/spaces file3
4422    ./maybehere17/-file3
1791    ./maybehere17/-file2
5094    ./maybehere17/.file3
8361    ./maybehere17/spaces file1
1133    ./maybehere17/-file1
3387    ./maybehere17/spaces file2
895 ./maybehere17/.file1
43901   ./maybehere17
6144    ./maybehere04/.file2
6002    ./maybehere04/spaces file3
2117    ./maybehere04/-file3
2619    ./maybehere04/-file2
142 ./maybehere04/.file3
5532    ./maybehere04/spaces file1
4410    ./maybehere04/-file1
2491    ./maybehere04/spaces file2
2440    ./maybehere04/.file1
35993   ./maybehere04
2501    ./maybehere11/.file2
8845    ./maybehere11/spaces file3
8854    ./maybehere11/-file3
4559    ./maybehere11/-file2
8261    ./maybehere11/.file3
3147    ./maybehere11/spaces file1
1211    ./maybehere11/-file1
503 ./maybehere11/spaces file2
452 ./maybehere11/.file1
42429   ./maybehere11
8517    ./maybehere09/.file2
7569    ./maybehere09/spaces file3
7961    ./maybehere09/-file3
774 ./maybehere09/-file2
3798    ./maybehere09/.file3
5301    ./maybehere09/spaces file1
3628    ./maybehere09/-file1
8716    ./maybehere09/spaces file2
6763    ./maybehere09/.file1
57123   ./maybehere09
279 ./maybehere15/.file2
1637    ./maybehere15/spaces file3
6299    ./maybehere15/-file3
9499    ./maybehere15/-file2
742 ./maybehere15/.file3
1623    ./maybehere15/spaces file1
8794    ./maybehere15/-file1
51  ./maybehere15/spaces file2
2159    ./maybehere15/.file1
35179   ./maybehere15
747 ./maybehere08/.file2
9138    ./maybehere08/spaces file3
2650    ./maybehere08/-file3
3825    ./maybehere08/-file2
2217    ./maybehere08/.file3
215 ./maybehere08/spaces file1
1077    ./maybehere08/-file1
3693    ./maybehere08/spaces file2
8169    ./maybehere08/.file1
35827   ./maybehere08
1503    ./maybehere14/.file2
376 ./maybehere14/spaces file3
3756    ./maybehere14/-file3
8351    ./maybehere14/-file2
4821    ./maybehere14/.file3
1382    ./maybehere14/spaces file1
4282    ./maybehere14/-file1
871 ./maybehere14/spaces file2
3427    ./maybehere14/.file1
32865   ./maybehere14
7836    ./maybehere00/.file2
1915    ./maybehere00/spaces file3
7378    ./maybehere00/-file3
9388    ./maybehere00/-file2
4802    ./maybehere00/.file3
6118    ./maybehere00/spaces file1
1039    ./maybehere00/-file1
6850    ./maybehere00/spaces file2
551 ./maybehere00/.file1
49973   ./maybehere00
2084    ./maybehere18/.file2
7040    ./maybehere18/spaces file3
2306    ./maybehere18/-file3
77  ./maybehere18/-file2
154 ./maybehere18/.file3
7334    ./maybehere18/spaces file1
9697    ./maybehere18/-file1
6348    ./maybehere18/spaces file2
5702    ./maybehere18/.file1
44838   ./maybehere18
5917    ./maybehere05/.file2
8585    ./maybehere05/spaces file3
2572    ./maybehere05/-file3
5959    ./maybehere05/-file2
4585    ./maybehere05/.file3
880 ./maybehere05/spaces file1
2346    ./maybehere05/-file1
2420    ./maybehere05/spaces file2
3201    ./maybehere05/.file1
40561   ./maybehere05
1033    ./maybehere07/.file2
1022    ./maybehere07/spaces file3
3362    ./maybehere07/-file3
2488    ./maybehere07/-file2
1997    ./maybehere07/.file3
4130    ./maybehere07/spaces file1
3663    ./maybehere07/-file1
9064    ./maybehere07/spaces file2
3065    ./maybehere07/.file1
33920   ./maybehere07
99  ./maybehere10/.file2
2155    ./maybehere10/spaces file3
1237    ./maybehere10/-file3
1991    ./maybehere10/-file2
2961    ./maybehere10/.file3
8269    ./maybehere10/spaces file1
1052    ./maybehere10/-file1
3570    ./maybehere10/spaces file2
7092    ./maybehere10/.file1
32522   ./maybehere10
8952    ./maybehere13/.file2
4389    ./maybehere13/spaces file3
3014    ./maybehere13/-file3
1423    ./maybehere13/-file2
6965    ./maybehere13/.file3
3952    ./maybehere13/spaces file1
1359    ./maybehere13/-file1
952 ./maybehere13/spaces file2
5258    ./maybehere13/.file1
40360   ./maybehere13

```

Result `1033    ./maybehere07/.file2`

```
cat ./maybehere07/.file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7

```

Password `DXjZPULLxYr17uwoI01bNLQbtFemEgo7`