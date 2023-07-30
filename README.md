# Image-Encryption-using-chaotic-maps

the project "Implementation of an Image Encryption algorithm using the chaotic maps" is submitted as the requirement of the course INT300 -MINI PROJECT of our University

Team Members:-
Haritha Sri M @HarithasriMohanKumar, Sriram K @Sriiiiio

It uses the Confusion-Diffusion model which increases the security and makes the encryption strenuous 
to crack. Permutations are done to shuffle the image’s pixel values which decrease the
correlation(Association) between two adjacent pixels and then diffusion is done. The security
of the algorithm will be stronger since both substitution and permutation are made.

Two chaotic maps were introduced to increase the security of the Algorithm. Chaotic
maps are mathematical functions that exhibit complex and unpredictable behaviour. Chaos
maps produce random numbers with specific properties like bifurcation, unpredictableness,
and initial condition sensitivity. The Encryption Algorithm uses two chaotic maps, a Logistic
map for shuffling the image’s pixel values and a 2D Non-linear chaotic map for substitution
of the pixel value.

Base Paper: https://doi.org/10.1016/j.asej.2021.05.004

Input Image: 

![image](https://github.com/srinivasmathi/Image-Encryption-using-chaotic-maps/assets/82605661/81de879a-512f-4355-8d4d-37102fe08d84)


Shuffled Image:

![image](https://github.com/srinivasmathi/Image-Encryption-using-chaotic-maps/assets/82605661/2b0befc9-0554-497c-8c36-418a8c9f6c66)


Encrypted Image:

![image](https://github.com/srinivasmathi/Image-Encryption-using-chaotic-maps/assets/82605661/816cbbd4-7b80-4cf5-8fea-669c50cbb074)









