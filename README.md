# LF-SynthSeg: Label-Free Brain Tissue-Assisted Tumor Synthesis and Segmentation
This is the official repository for our **IEEE Journal of Biomedical and Health Informatics (J-BHI)** paper "LF-SynthSeg: Label-Free Brain Tissue-Assisted Tumor Synthesis and Segmentation".

## Method
we present an innovative strategy that effectively integrates brain tissues' prior knowledge into both the synthesis and segmentation of brain tumor from T2-weighted Magnetic Resonance Imaging scans. Central to our method is the tumor synthesis mechanism, employing randomly generated ellipsoids in conjunction with the intensity profiles of brain tissues. This methodology not only fosters a significant degree of variation in the tumor presentations within the synthesized images but also facilitates the creation of an essentially unlimited pool of abnormal T2-weighted images. These synthetic images closely replicate the characteristics of real tumor-bearing scans. Our training protocol extends beyond mere tumor segmentation; it also encompasses the segmentation of brain tissues, thereby directing the network’s attention to the boundary relationship between brain tumor and brain tissue, thus improving the robustness of our method. We evaluate our approach across five widely recognized public datasets (BRATS 2019, BRATS 2020, BRATS 2021, PED and SSA), and the results show that our method outperforms state-of-the-art unsupervised tumor segmentation methods by large margins. Moreover, the proposed method achieves more than 92$\%$ of the fully supervised performance on the same testing datasets.

![image](https://github.com/xu1px/LF-Synthseg/blob/main/fig2_overview.png)

## Code
The code will be uploaded soon.
