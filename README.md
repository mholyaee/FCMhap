# FCMHap
FCMHap is a method based on the Fuzzy c-means (FCM) clustering algorithm for haplotype assembly problem. Time complexity and the handling high error rate datasets are the challenges of the current methods. Due to improve the FCM’s convergence speed, the proposed method consists of two phases. First, input fragments are divided into two partitions based on their distances. Second, information of bi-partitioning is employed as initial centers by fuzzy c-means (FCM) clustering method. Applying the information in FCM can improve the speed of convergence and decrease number of iterations.  

# Requirement:

This program is suitable for MATLAB R2013a and above versions.
The program has adopted by Geraci's dataset. By some little changes it can be used for any input data.

# Running method

For this purpose it is only need to run FCMhap_v2.m file.

The obtained results which includes the reconstruction rate and running time will be saved in some text files on the current path.

The details of used dataset can be accessible in the below paper:

F. Geraci, "A comparison of several algorithms for the single individual SNP haplotyping reconstruction problem," Bioinformatics, vol. 26, pp. 2217-2225, 2010.

# Feedback

Its pleasure for me to have your comment.
mh.olyaee@gmail.com
