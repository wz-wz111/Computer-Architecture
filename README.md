# Bingo
具体复现流程请参照论文复现的pdf（注意data文件夹并未真正存放数据），下面是论文的总体介绍和源码仓库地址

This repository contains the source code accompanying the following paper:
```
@inproceedings{Bingo,
  title={Bingo Spatial Data Prefetcher},
  author={Mohammad Bakhshalipour, Mehran Shakerinava, Pejman Lotfi-Kamran, Hamid Sarbazi-Azad},
  booktitle={International Symposium on High-Performance Computer Architecture (HPCA)},
  year={2019}
}
```
<br/>

This source code includes the implementation of our proposal, named **Bingo**, as well as the implementation of competing methods such as **BOP**, **SPP**, **VLDP**, **AMPM**, and **SMS**. Everything is implemented on top of a modified version of the [ChampSim](https://github.com/ChampSim/ChampSim) simulator. Several scripts for running simulations and gathering results are also provided in this repo. Enjoy! :)
<br/>

*Please cite our paper if you use this code in your own work.*

![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) UPDATE: Bingo was recognized as the **best** data prefetching approach for multi-core processors in the [Third Data Prefetching Championship (DPC-3)](https://dpc3.compas.cs.stonybrook.edu/slides/dpc3_closing.pdf), co-located with International Symposium on Computer Architecture (ISCA), 2019.
