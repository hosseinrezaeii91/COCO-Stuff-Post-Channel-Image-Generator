# COCO-Stuff-Post-Channel-Image-Generator
In this dataset, we propose a flexible software that automatically transmits the semantic segmentation map images over an additive white Gaussian noise (AWGN) channel using binary phase-shift keying (BPSK). This software is beneficial in investigating the effect of channel noise on end-to-end image communication systems utilizing semantic concepts. The well-known polar codes are chosen as the channel coding scheme, with the flexibility of selecting any code rate and code length. The dataset selected for the task is the popular COCO-Stuff dataset [1], which is an augmented version of the COCO [2] dataset and contains $91$, different stuff classes. The output semantic map images corresponding to four different signal-to-noise ratios (SNRs) are generated to achieve a very small dataset, each containing a thousand images from the COCO-Stuff dataset. While this paper utilizes the COCO-Stuff dataset as an example, it should be noted that the software is not confined to this particular dataset and can be leveraged for transmitting images from any other dataset as well.

# How to use the software
You need to creat a folder named "train2017" in the same directory as the software located, and then copy the target images to this folder. The name of the images must follow "000000000009.png" format, i.e. a name with 12 charachtors length and in "png" format. Therefore, the range of images' names could be between "000000000000" to "999999999999". This is the name format in the COCO-Stuff dataset and therefore, you do not need to rename the images if you are using the COCO-Stuff dataset.

# About the software
The compiled Python version of the software is accessible on this webpage. Additionally, the software's executable file is available; nonetheless, it was not possible to upload it to this page due to its substantial size. If you require the executable file, kindly send us an email to below address.

hossein.rezaei(at)oulu.fi;

# References

[1] H. Caesar, J. Uijlings, and V. Ferrari, “Coco-stuff: Thing and stuff classes in context,” in 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018, pp. 1209–1218.

[2] T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Doll ́ar, and C. L. Zitnick, “Microsoft coco: Common objects in context,” in Computer Vision–ECCV 2014: 13th European Conference, Zurich, Switzerland, September 6-12, 2014, Proceedings, Part V 13. Springer, 2014, pp. 740–755.
