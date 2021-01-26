# Awesome Crowd Datasets

In this repository, I only choose those crowd counting datasets used by top conferences (CVPR, ICCV and ECCV) papers, ordering by the release year of the datasets.

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Overview

In these papers published on top conferences(CVPR, ECCV) of 2020, some crowd counting benchmarks(datasets) are cited. In the following table, total reference count and release year of these datasets are showed.

||UCSD | UCF-CC-50 | WorldExpo10| TRANCOS |ShangHai Tech | UCF-QNRF |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Ref Count 2020|2|7|7|2|10|7|
|Release Year|2008|2013|2015|2015|2016|2018|

Note, only record the crowd datasets whose **refered count** is **no less than 2** times.

Summary of  statistics and comparason of the 4 most frequently used crowd datasets is presented in the following table.

|Dataset|Number of Images|Number of Annotations|	Average Count|Maximum Count|Average Resolution|	Average Density|
|----|----|----|----|----|----|----|
|UCF-CC-50|	50|	63,974|1279|	4633	| 2101 x 2888|	2.02 x 10^-4|
|WorldExpo10|3980|225,216|56|334|	576 x 720|	 1.36 x 10^-4|
|ShanghaiTech_PartA|	482|	241,677|	501|	3139	|589 x 868|9.33 x 10^-4|
|UCF-QNRF|1535|1,251,642|815|	12865|	2013 x 2902|	1.12 x 10^-4|

Note, this table is abstracted from [UCF-QNRF dataset website](https://www.crcv.ucf.edu/data/ucf-qnrf/) 

## More Information

### UCSD Dataset
<details>
<summary>Top Conference Papers using this dataset</summary>

* Yifan Yang, Guorong Li et al. Reverse Perspective Network for Perspective-Aware Object Counting. CVPR, 2020. 
* Yifan Yang, Guorong Li et al. Weakly-Supervised Crowd Counting Learns from Sorting rather than Locations. ECCV, 2020.
</details>

Organization: **Statistical Visual Computing Lab, UC San Diego**

Website: <http://svcl.ucsd.edu/projects/peoplecnt/>

Paper: Antoni B Chan, Zhangsheng John Liang, and Nuno Vasconcelos. **Privacy preserving crowd monitoring: Counting people without people models or tracking**. Computer Vision and Pattern Recognition, pages 1–7, 2008. 


### UCF-CC-50 Crowd Counting Dataset

<details>
<summary>Top Conference Papers using this dataset</summary>

* Xiaoheng Jiang, Li Zhang et al. Attention Scaling for Crowd Counting. CVPR, 2020. [[code](https://github.com/laridzhang/ASNet)]
* Shuai Bai, Zhiqun He et al. Adaptive Dilated Network with Self-Correction Supervision for Counting. CVPR, 2020.
* Yutao Hu, Xiaolong Jiang et al. NAS-Count: Counting-by-Density with Neural Architecture Search. ECCV, 2020.
* Xiyang Liu, Jie Yang et al. Adaptive Mixture Regression Network with Local Counting Map for Crowd Counting. ECCV, 2020. [[code](https://github.com/xiyang1012/Local-Crowd-Counting)]
* Liang Liu, Hao Lu et al. Weighing Counts: Sequential Crowd Counting by Reinforcement Learning? ECCV, 2020. [[code](https://github.com/poppinace/libranet)]
* Vishwanath A. Sindagi, Rajeev Yasarla et al. Learning to Count in the Crowd from Limited Labeled Data. ECCV, 2020.
* Zhen Zhao, Miaojing Shi et al. Active Crowd Counting with Limited Supervision. ECCV, 2020.

</details>

Organization: **Center for Research in Computer Vision, UCF**

Website: <https://www.crcv.ucf.edu/data/ucf-cc-50/>

Paper: Haroon Idrees, Imran Saleemi, Cody Seibert, and Mubarak Shah. **Multi-source multi-scale counting in extremely dense crowd images**. Computer Vision and Pattern Recognition, pages 2547–2554, 2013.


### WorldExpo10 Dataset
<details>
<summary>Top Conference Papers using this dataset</summary>

* Xiaoheng Jiang, Li Zhang et al. Attention Scaling for Crowd Counting. CVPR, 2020. [[code](https://github.com/laridzhang/ASNet)]
* Yutao Hu, Xiaolong Jiang et al. NAS-Count: Counting-by-Density with Neural Architecture Search. ECCV, 2020.
* Yifan Yang, Guorong Li et al. Reverse Perspective Network for Perspective-Aware Object Counting. CVPR, 2020.
* Xiyang Liu, Jie Yang et al. Adaptive Mixture Regression Network with Local Counting Map for Crowd Counting. ECCV, 2020. [[code](https://github.com/xiyang1012/Local-Crowd-Counting)]
* Vishwanath A. Sindagi, Rajeev Yasarla et al. Learning to Count in the Crowd from Limited Labeled Data. ECCV, 2020.
* Yan Liu, Lingqiao Liu et al. Semi-Supervised Crowd Counting via Self-Training on Surrogate Tasks. ECCV, 2020.
* Yifan Yang, Guorong Li et al. Weakly-Supervised Crowd Counting Learns from Sorting rather than Locations. ECCV, 2020.
</details>

Organization: Institute of Image Communication and Network Engineering, **Shanghai Jiao Tong University**

Website: <https://www.ee.cuhk.edu.hk/~xgwang/expo.html>

Paper: Cong Zhang, Hongsheng Li, Xiaogang Wang, and Xiaokang Yang. **Cross-scene crowd counting via deep convolutional neural networks**. Computer Vision and Pattern Recognition, pages 833–841, 2015.


### TRaffic ANd COngestionS (TRANCOS) Dataset

<details>
<summary>Top Conference Papers using this dataset</summary>

* Shuai Bai, Zhiqun He et al. Adaptive Dilated Network with Self-Correction Supervision for Counting. CVPR, 2020
* Zhen Zhao, Miaojing Shi et al. Active Crowd Counting with Limited Supervision. ECCV, 2020
</details>

Organization: GRAM, **University of Alcala**, Spain

Website: <http://agamenon.tsc.uah.es/Personales/rlopez/data/trancos>

Paper: Ricardo Guerrero-Gomez-Olmedo, Beatriz Torre-Jim ´enez, ´Roberto Lopez-Sastre, Saturnino Maldonado-Basc ´ on, and ´Daniel Onoro-Rubio. **Extremely overlapping vehicle counting**. In Iberian Conference on Pattern Recognition and Image Analysis, pages 423–431. Springer, 2015.


### Shanghai Tech Dataset

<details>
<summary>Top Conference Papers using this dataset</summary>

* Xiaoheng Jiang, Li Zhang et al. Attention Scaling for Crowd Counting. CVPR, 2020. [[code](https://github.com/laridzhang/ASNet)]
* Shuai Bai, Zhiqun He et al. Adaptive Dilated Network with Self-Correction Supervision for Counting. CVPR, 2020.
* Yifan Yang, Guorong Li et al. Reverse Perspective Network for Perspective-Aware Object Counting. CVPR, 2020. 
* Yutao Hu, Xiaolong Jiang et al. NAS-Count: Counting-by-Density with Neural Architecture Search. ECCV, 2020
* Xiyang Liu, Jie Yang et al. Adaptive Mixture Regression Network with Local Counting Map for Crowd Counting. ECCV, 2020. [[code](https://github.com/xiyang1012/Local-Crowd-Counting)]
* Liang Liu, Hao Lu et al. Weighing Counts: Sequential Crowd Counting by Reinforcement Learning? ECCV, 2020. [[code](https://github.com/poppinace/libranet)]
* Vishwanath A. Sindagi, Rajeev Yasarla et al. Learning to Count in the Crowd from Limited Labeled Data. ECCV, 2020.
* Yan Liu, Lingqiao Liu et al. Semi-Supervised Crowd Counting via Self-Training on Surrogate Tasks. ECCV, 2020.
* Zhen Zhao, Miaojing Shi et al. Active Crowd Counting with Limited Supervision. ECCV, 2020.
* Yifan Yang, Guorong Li et al. Weakly-Supervised Crowd Counting Learns from Sorting rather than Locations. ECCV, 2020.

</details>

Organization: **ShanghaiTech University**

Website: <https://github.com/desenzhou/ShanghaiTechDataset>

Paper: Yingying Zhang, Desen Zhou, Siqin Chen, Shenghua Gao, and Yi Ma. **Single-image crowd counting via multi-column convolutional neural network. Computer Vision and Pattern Recognition**, pages 589–597, 2016.


### UCF-QNRF Large Crowd Counting Dataset
<details>
<summary>Top Conference Papers using this dataset</summary>

* Xiaoheng Jiang, Li Zhang et al. Attention Scaling for Crowd Counting. CVPR, 2020. [[code](https://github.com/laridzhang/ASNet)]
* Shuai Bai, Zhiqun He et al. Adaptive Dilated Network with Self-Correction Supervision for Counting. CVPR, 2020.
* Yutao Hu, Xiaolong Jiang et al. NAS-Count: Counting-by-Density with Neural Architecture Search. ECCV, 2020.
* Xiyang Liu, Jie Yang et al. Adaptive Mixture Regression Network with Local Counting Map for Crowd Counting. ECCV, 2020. [[code](https://github.com/xiyang1012/Local-Crowd-Counting)]
* Liang Liu, Hao Lu et al. Weighing Counts: Sequential Crowd Counting by Reinforcement Learning? ECCV, 2020. [[code](https://github.com/poppinace/libranet)]
* Vishwanath A. Sindagi, Rajeev Yasarla et al. Learning to Count in the Crowd from Limited Labeled Data. ECCV, 2020.
* Yan Liu, Lingqiao Liu et al. Semi-Supervised Crowd Counting via Self-Training on Surrogate Tasks. ECCV, 2020.

</details>

Organization: **Center for Research in Computer Vision, UCF**

Website: <https://www.crcv.ucf.edu/data/ucf-qnrf/>

Paper: H. Idrees, M. Tayyab, K. Athrey, D. Zhang, S. Al-Maddeed, N. Rajpoot, M. Shah, **Composition Loss for Counting, Density Map Estimation and Localization in Dense Crowds**, in Proceedings of IEEE European Conference on Computer Vision (ECCV 2018), Munich, Germany, September 8-14, 2018.

## Recommended Readings

- [Top Conference/Journal Papers related to Crowd Counting](https://github.com/gjy3035/Awesome-Crowd-Counting/blob/master/src/Top_Conference-Journal.md)
- [Awesome Crowd Counting](https://github.com/gjy3035/Awesome-Crowd-Counting)
