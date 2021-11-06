## VIPLoc

- This repository contains the VIPLoc dataset for the following paper：Very Important Person Localization in Unconstrained Conditions: A New Benchmark (AAAI 2021). Very Important Person Localization (VIPLoc) aims to automatically locate core individuals that play important roles in given images. It has a guiding influence on the occurrence of current events, such as sports games, birthday parties, and speeches. In particular, analyzing the action of important person enables intelligent system to better understand what has happened and predict what will happen. Generally, existing datasets are: 1) limited in scale; 2) built under simple and constrained conditions, where the number of disturbing non-VIPs is not large, the scene is relatively simple, and the face of VIP is always in frontal view and salient. To tackle these problems, the proposed Unconstrained-7k dataset is featured in two aspects. First, it contains over 7,000 annotated images, making it the largest VIPLoc dataset under unconstrained conditions to date. Second, our dataset is collected freely on the Internet, including multiple scenes, where images are in unconstrained conditions.  

- You can download [VIPLoc](https://pan.baidu.com/s/1V-wUZr46aF2AAgtd18oLyQ) now (Extraction code：z0g3). The Unconstrained-7k Dataset is for academic use only. By downloading the dataset, you guarantee that you will use this dataset for academic work only.


- If you have any questions about the Unconstrained-7k dataset, please contact hebeiwangxiao@whu.edu.cn.

### **Benchmark**

- Performance of state-of-the-art methods.

|  Methods   | NCAA  | MS  |Unconstrained-7k|
|  :----:  | :----:  | :----:  | :----:  |
| Max-Face  | 31.4 | 35.7 | 23.8 |
| Max-Pedestrian  | 24.7 | 30.7 | 21.8 |
| Max-Saliency  | 26.4| 40.3 | 22.6 |
| Most-Center  | 30.0 | 50.9 | 26.8 |
| Max-Scale  | 31.8 | 73.9 | 25.5 |
| SVR-Person | 64.5 |75.9 | 46.7 |


### **Citation**
Please kindly cite our paper if VIPLoc is helpful to your own work.

bib:

    @inproceedings{VIPLoc,
    author={Wang, Xiao and Wang, Zheng and Yamasaki,Toshihiko and Zeng Wenjun},
    title={Very Important Person Localization in Unconstrained Conditions:A New Benchmark}, 
    booktitle={Proceedings of the Thirty-Fifth AAAI Conference on Artificial Intelligence},
    year= {2021},
    }

