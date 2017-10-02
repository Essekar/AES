# AES
The aes algorithm implementation.
Input:
Group Code  (A, B) = (4,7)
0000 0000 0000 0000 0000 0000 0000 abd6 (plaintext)
1a0c 24f2 8754 93bc b708 0e43 930f 5686 (key)


Output (Modified S-box):
ce 42 a3 6f e6 3b 3e 23 2f a6 9b 46 eb b6 74 8b
Key Schedule Results for Each Round with the modified AES:
Round 0: 
Key: 1a 0c 24 f2 87 54 93 bc b7 08 0e 43 93 0f 56 86

Round 1: 
Key: 6d bd 60 2e ea e9 f3 92 5d e1 fd d1 ce ee ab 57

Round 2: 
Key: 47 bf 3b a5 ad 36 c8 37 f0 d7 35 e6 3e 39 9e b1

Round 3: 
Key: 51 d4 f3 17 fc e2 3b 20 0c 35 0e c6 32 0c 90 77 

Round 4: 
Key: a7 b4 53 34 5b 56 68 14 57 63 66 d2 65 6f f6 a5

Round 5: 
Key: 1f f6 55 79 44 a0 3d 6d 13 c3 5b bf 76 ac ad 1a

Round 6: 
Key: ae 63 f7 23 ea c3 ca 4e f9 00 91 f1 8f ac 3c eb

Round 7: 
Key: 7f 88 1e 50 95 4b d4 1e 6c 4b 45 ef e3 e7 79 04

Round 08: 
Key: 6b b3 ec 41 fe f8 38 5f 92 b3 7d b0 71 54 04 b4 

Round 9: 
Key: 50 41 61 c2 ae b9 59 9d 3c 0a 24 2d 4d 5e 20 99

Round 10: 
Key: 3e f6 8f 3d 90 4f d6 a0 ac 45 f2 8d e1 1b d2 14




Round 0: 
-----
Start: 
00 00 00 00 00 00 00 00 00 00 00 00 00 00 ab d6
----
Output: 1a 0c 24 f2 87 54 93 bc b7 08 0e 43 93 0f fd 50
Round 1: 
----
Output: 49 eb fc c6 aa ea 5a fe dd 9b e1 bb 27 25 a0 0f
Round 2: 
----
Output: bd 28 67 6f aa df 0f b7 22 05 6b 4c 75 c1 8b 06
Round 3: 
----
Output: 5e fe 24 6d 21 a0 b0 b1 67 64 ea 2d c2 c1 41 fe
Round 4: 
----
Output: 10 1e 28 d6 e0 ef cf 90 30 84 b4 83 c6 cd ce 3d
Round 5: 
----
Output: 40 32 28 20 01 8f 8f 76 93 9a 2a fa f5 95 4b e6 
Round 6: 
----
Output: f2 6e 8d 41 57 00 8e 26 4a 8e e1 24 63 b4 68 d0
Round 7: 
----
Output: 5b a4 8f ab ee 4e e2 f2 e5 80 aa bf 9b 24 75 f8
Round 8: 
----
Output: fa d9 a6 d7 ee 81 a7 40 9b 1a f4 8c 12 69 6a 49
Round 9: 
----
Output: 17 18 e4 71 0f c6 c5 59 71 ca 72 6e a3 7d c8 78
Round 10: 
----
Output: ce 42 a3 6f e6 3b 3e 23 2f a6 9b 46 eb b6 74 8b

