Data-of-Improved-random-forest-based-on-AFSA
==
This repository contains all the algorithm and data used in our paper "A parametric optimization oriented, AFSA based random forest algorithm: application to detection of cervical epithelial cells". All the files are stored separately in two folders: algorithm and relative data.

[Algorithm:](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/algorithm)
----
Algorithm contains the basic computation flow of the improved random forest based on AFSA, you can recurrent the code via this flow, along with the folder stores a clear chart of the flow which will help you better understand our algorithm. Our initial code was writtrn in C++ concerning at the problem of efficiency, other codes based on different languages are being developed through this open source algorithm. We also welcome anyone who is interested in our algorithm to join us to develop related cell recognition algorithms.

[Relative data:](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data)
----
**Basic structure of data is shown as follows:**

1.[ Original negative sample](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Original%20negative%20sample)<br>
  
2.[ Original positive sample](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Original%20positive%20sample)<br>

3.[ Processed training material](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material)<br>


4.[ Schema of cell classification](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Schema%20of%20cell%20classification)<br>

**Data description：**
* [ Original negative sample](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Original%20negative%20sample) and [ Original positive sample](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Original%20positive%20sample) are raw data collected from our cooperative unit. We used 200 cervical liquid based cell slides in total, for the sake of simplicity, we have selected 10 positive samples and 10 negative samples for publication, so that you can see the appearance of our raw data which has not been processed.


* [ Processed training material](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material) are the images which have been processed after binarization, image segmentation and image classification. This folder contains 400 [ epithelial cells](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material/epithelial%20cells) and 400 [ lymphocyte cells](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material/lymphocyte%20cells), they are the images of single cells after a series of processes. [ epithelial cells](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material/epithelial%20cells) has been divided into two categories including 200 [ cancerous epithelial cells](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material/epithelial%20cells/cancerous%20epithelial%20cells) and 200 [ normal epithelial cells](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Processed%20training%20material/epithelial%20cells/normal%20epithelial%20cells), as the names you can see, these are the typical samples we use in the classifier analogy experiment.


* [ Schema of cell classification](https://github.com/zcwooo/Data-of-Improved-random-forest-based-on-AFSA/tree/master/data%20and%20algorithm/relative%20data/Schema%20of%20cell%20classification) are 3 graphs of actual classification results. As you can see in the pictures, the cells inside the blue box are epithelial cells while the cells inside the green box are lymphocytes. We have effectively separated epithelial cells from lymphocytes.

https://zenodo.org/badge/202300361.svg
