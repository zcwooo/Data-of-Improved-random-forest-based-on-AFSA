Data-of-Improved-random-forest-based-on-AFSA
==
This repository contains all the algorithm and data used in our paper "A parametric optimization oriented, AFSA based random forest algorithm: application to detection of cervical epithelial cells". All the files are stored separately in two folders: algorithm and relative data.

Algorithm:
----
Algorithm contains the basic computation flow of the improved random forest based on AFSA, you can recurrent the code via this flow, along with the folder stores a clear chart of the flow which will help you better understand our algorithm. Our initial code was writtrn in C++ concerning at the problem of efficiency, other codes based on different languages are being developed through this open source algorithm. We also welcome anyone who is interested in our algorithm to join us to develop related cell recognition algorithms.

Relative data:
----
>Basic structure of data is showns as follows:
>>Original negative sample
>>>SZ18761
>>>SZ18762
>>>SZ18763
>>>SZ18764
>>>SZ18765
>>>SZ18766
>>>SZ18767
>>>SZ18768
>>>SZ18769
>>>SZ18770

>>Original positive sample
>>>SZ18085
>>>SZ18094
>>>SZ18185
>>>SZ18228
>>>SZ18230
>>>SZ18240
>>>SZ18343
>>>SZ18376
>>>SZ18402
>>>SZ18435

>>Processed training material
>>>epithelial cells
>>>>cancerous epithelial cells
>>>>normal epithelial cells
>>>lymphocyte cells
>>Schema of cell classification
