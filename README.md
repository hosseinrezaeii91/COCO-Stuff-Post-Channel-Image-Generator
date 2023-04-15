# COCO-Stuff-Post-Channel-Image-Generator
In this dataset, we propose a flexible software that automatically transmits the semantic segmentation map images over an additive white Gaussian noise (AWGN) channel using binary phase-shift keying (BPSK). This software is beneficial in investigating the effect of channel noise on end-to-end image communication systems utilizing semantic concepts. The well-known polar codes are chosen as the channel coding scheme, with the flexibility of selecting any code rate and code length. The dataset selected for the task is the popular COCO-Stuff dataset [1], which is an augmented version of the COCO [2] dataset and contains $91$, different stuff classes. The output semantic map images corresponding to four different signal-to-noise ratios (SNRs) are generated to achieve a very small dataset, each containing a thousand images from the COCO-Stuff dataset [3]. While this paper utilizes the COCO-Stuff dataset as an example, it should be noted that the software is not confined to this particular dataset and can be leveraged for transmitting images from any other dataset as well.


References
[1] H. Caesar, J. Uijlings, and V. Ferrari, “Coco-stuff: Thing and stuff classes in context,” in 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018, pp. 1209–1218.
[2] T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Doll ́ar, and C. L. Zitnick, “Microsoft coco: Common objects in context,” in Computer Vision–ECCV 2014: 13th European Conference, Zurich, Switzerland, September 6-12, 2014, Proceedings, Part V 13. Springer, 2014, pp. 740–755.
[3] H. Rezaei, Post-Channel Map Image Image Generator. Accessed, Feb. 2023. [Online]. Available: https://github.com/hosseinrezaeii91/COCO-Stuff-Post-Channel-Image-Generator, 2023.
