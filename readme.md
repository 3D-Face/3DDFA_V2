# Towards Fast, Accurate and Stable 3D Dense Face Alignment

<!-- [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) -->
![GitHub repo size](https://img.shields.io/github/repo-size/cleardusk/3DDFA_V2.svg)

By [Jianzhu Guo](https://guojianzhu.com), [Xiangyu Zhu](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/), [Yang Yang](http://www.cbsr.ia.ac.cn/users/yyang/main.htm), Fan Yang, [Zhen Lei](http://www.cbsr.ia.ac.cn/users/zlei/) and [Stan Z. Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ).

## Introduction
This is an extended work of the github improved version of [3DDFA](https://github.com/cleardusk/3DDFA), named [Towards Fast, Accurate and Stable 3D Dense Face Alignment](https://guojianzhu.com/assets/pdfs/3162.pdf), accepted by [ECCV 2020](https://eccv2020.eu/). The supplementary material is [here](https://guojianzhu.com/assets/pdfs/3162-supp.pdf).

**The code and models will be released in next days.** 😃

## Get Started
1. Clone this repo
```shell script
git clone https://github.com/cleardusk/3DDFA_V2.git
cd 3DDFA_V2
```

2. Build Cython version of NMS 
```shell script
cd FaceBoxes
sh ./build_cpu_nms.sh
```

3. Run demos
```shell script
# running on still image
python3 demo.py -f examples/inputs/emma.jpg
```

## Citation

    @inproceedings{guo2020towards,
        title =        {Towards Fast, Accurate and Stable 3D Dense Face Alignment},
        author =       {Guo, Jianzhu and Zhu, Xiangyu and Yang, Yang and Yang, Fan and Lei, Zhen and Li, Stan Z},
        booktitle =    {Proceedings of the European Conference on Computer Vision (ECCV)},
        year =         {2020}
    }

    @misc{3ddfa_cleardusk,
        author =       {Guo, Jianzhu and Zhu, Xiangyu and Lei, Zhen},
        title =        {3DDFA},
        howpublished = {\url{https://github.com/cleardusk/3DDFA}},
        year =         {2018}
    }
