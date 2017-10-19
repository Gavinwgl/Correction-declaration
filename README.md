# Vision-based-fingertip-tracking
Vision based fingertip detection and tracking

Minor Result Error Declarations in PAPER[1] and its Detailed Experimental Results
Authors:
Guile Wu and Wenxiong Kang.

Paper: 
[1] G. Wu and W. Kang, "Vision-based fingertip tracking utilizing curvature points clustering and hash model representation," IEEE Trans. Multimedia, vol. 19, no. 8, pp. 1730-1741, 2017.

Minor Result Error Declarations:
In [1], which published in 2017/07/18, we found that when we submitted the proof, we have made a mistake in TABLE I. The accuracy rate of the proposed method in PAPER[1] in Fist on SCUT database for HGR1 should be 173/194=89.18%, instead of 91.05%. This is a minor mistake, because when we calculate the average success rate (703/899=78.2%), we used the right result (173) rather than other wrong results. 

It is important to note that this minor error would not affect the other results, especially would not affect the average success rate of our proposed algorithm. Anyhow, we are really sorry if this error causes confusion to anyone. Since this paper has been published today (2017/07/18), we cannot revise it anymore but we think it is necessary and better to declare online to let everybody who is interested in [1] knows this minor error.

Detailed Experimental Results:
In [1], We employed two datasets, namely SUT databases for HGR1 and SCUT fingertip detection dataset, to verify the performance of each finger detection methods. Here, since we have made a mistake in TABLE I, we would like to introduce more about the experiments results on SUT database for HGR1.

As we mentioned in [1], the original SUT database for HGR1 contains 899 hand gesture images, which were acquired from 12 individuals performing 25 different hand gestures. Although Kawulok et al. [37] also provided skin silhouettes for this database, the original database was established for gesture recognition instead of fingertip detection, and the numbers of fingers in some of these skin silhouettes were ambiguous. Therefore, we removed some ambiguous silhouettes and supplemented the database with other silhouettes to maintain the number of images at 899. In addition, we manually marked the number of fingertips for each of these silhouettes. Here, we can call this revised database as SUT revised fingertip detection dataset.

There are 194 Fist images, 204 Single Fingertip images and 501 Multiple Fingertips images in the SUT revised fingertip detection dataset. In our experiments, the method proposed in [1] has correctly classified 173 images in Fist images sub-dataset, 153 images in Single Fingertip images sub-dataset and 377 images in Multiple Fingertips images sub-dataset. Therefore, in sum, there are 703 images are correctly classified. Just as we have mentioned above, the minor result error in TABLE I in [1] (91.05%) will not affected the overall performance since the other results are correct. The detailed results of the proposed methods are shown in the following.

Please note that we only use this dataset for research. Whenever you use this dataset, please site REF[2] or let authors (M. Kawulok, J. Kawulok, and J. Nalepa) know you use their dateset (SUT database for hand gesture recognition (HGR)).
[2] M. Kawulok, J. Kawulok, and J. Nalepa, “Spatial-based skin detection using discriminative skin-presence features,” Pattern Recog. Lett., vol. 41, no. 1, pp. 3–13, 2014.


SUT database for HGR1: 703/899=78.2%
Fist: 173/194=89.18%
 
Single fingertip: 153/204=75.00%
 
Multiple fingertips: 377/501=75.25%
 

 
AGAIN, we are really sorry if this error causes confusion to anyone. For more information, you are free to contact our authors Guile Wu (guile.wu.cn@ieee.org; auguilewu@mail.scut.edu.cn ) and Wenxiong Kang (auwxkang@scut.edu.cn ). We will be happy to address your problems if we are not in busy hour.

