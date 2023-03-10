# Winter 2023 Tournament

This is a little double round-robin tournament I ran with some of the top FREE chess engines.
Enjoy.


## Results

```
Winter2023
Bern, Switzerland, 2022.12.14 - 2023.03.04
                          Score     St LC Sl Ko Re Be ro Mi Ru Se Ig Cl Ar Ca Ne Pe Ko Bo Et Fi Wa
---------------------------------------------------------------------------------------------------
 1: Stockfish 15.1      26.0 / 40   XX == == == == =1 =1 == =1 == =1 11 =1 =1 == =1 == =1 =1 =1 ==  (+12 -0 =28)
 2: LCZero 0.29.0*      25.0 / 40   == XX == == == == =1 =1 == == == =1 =1 == =1 1= == =1 =1 =1 =1  (+10 -0 =30)
 3: SlowChess 2.9       24.0 / 40   == == XX 1= == == == 01 == =1 == == == == 1= == 1= 1= =1 1= =1  (+9 -1 =30)
 4: Koivisto 8.0        23.0 / 40   == == 0= XX == 1= 01 == == =1 =1 =1 =1 == 1= == 1= == == == ==  (+8 -2 =30)
 5: Rebel-16.2          23.0 / 40   == == == == XX == == == == == == == 1= == == == 11 1= == 1= 1=  (+6 -0 =34)
 6: Berserk 10          23.0 / 40   =0 == == 0= == XX == == == == == == == 11 =1 == 1= == =1 =1 11  (+8 -2 =30)
 7: rofChade 3.0        22.5 / 40   =0 =0 == 10 == == XX == == 1= == == =1 =1 == =1 == 1= 11 == ==  (+8 -3 =29)
 8: Minic 3.32          22.0 / 40   == =0 10 == == == == XX == == == 1= == == =1 == == == =1 == 11  (+6 -2 =32)
 9: RubiChess 20221203  22.0 / 40   =0 == == == == == == == XX == == == == == == 11 1= == == 11 ==  (+5 -1 =34)
10: Seer 2.6            20.5 / 40   == == =0 =0 == == 0= == == XX 1= 0= =1 == == == == =1 1= == =1  (+5 -4 =31)
11: Igel 3.3.0          19.0 / 40   =0 == == =0 == == == == == 0= XX == == == == == == =1 == 01 ==  (+2 -4 =34)
12: Clover 3.3          19.0 / 40   00 =0 == =0 == == == 0= == 1= == XX == == == == =1 =1 =0 1= ==  (+4 -6 =30)
13: Arasan 23.4         18.5 / 40   =0 =0 == =0 0= == =0 == == =0 == == XX == == == == == 1= == 11  (+3 -6 =31)
14: Caissa 1.5          18.0 / 40   =0 == == == == 00 =0 == == == == == == XX == =0 =1 == == == ==  (+1 -5 =34)
15: Nemorino 6.00       18.0 / 40   == =0 0= 0= == =0 == =0 == == == == == == XX 1= 0= == == == =1  (+2 -6 =32)
16: Pedone 3.1          18.0 / 40   =0 0= == == == == =0 == 00 == == == == =1 0= XX == == == 1= ==  (+2 -6 =32)
17: Komodo 13           16.5 / 40   == == 0= 0= 00 0= == == 0= == == =0 == =0 1= == XX 0= == =1 ==  (+2 -9 =29)
18: Booot7              16.5 / 40   =0 =0 0= == 0= == 0= == == =0 =0 =0 == == == == 1= XX == == ==  (+1 -8 =31)
19: Ethereal 13.00**    16.0 / 40   =0 =0 =0 == == =0 00 =0 == 0= == =1 0= == == == == == XX == ==  (+1 -9 =30)
20: Fire-1072022**      15.0 / 40   =0 =0 0= == 0= =0 == == 00 == 10 0= == == == 0= =0 == == XX ==  (+1 -11 =28)
21: Wasp 6.00           14.5 / 40   == =0 =0 == 0= 00 == 00 == =0 == == 00 == =0 == == == == == XX  (+0 -11 =29)
---------------------------------------------------------------------------------------------------
420 games: +71 -25 =324
```

*net 792013 (T79 192x15)  
**non-NNUE versions


## Conditions

+ TC: game in 15 min, 10s increment
+ Permanent brain: off
+ MT:
    - PC1: 4 threads
    - PC2: 6 threads
+ no matches across different hw
+ 6-men Syzygy tablebases
+ Book: Perfect2019.bin (max 20 plys)
+ GUI: cutechess-1.3.0-beta4-win64


## Hardware

PC1: Intel Core i7 @ 3.60GHz, 8 Cores, 32GB RAM, NVIDIA GeForce RTX 2080 SUPER  
PC2: Intel Core i7 5820K @ 3.30GHz, 6 Cores, 32GB RAM, NVIDIA GeForce GTX 980 Ti

*All matches invovling Leela Lc0 were run on PC1 on the RTX 2080 Super.


[All games in PGN](https://github.com/aguet/Tournaments/blob/master/Winter2023.pgn?raw=true)

