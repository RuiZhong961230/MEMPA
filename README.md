# MEMPA
Multi-strategy Enhanced Marine Predator Algorithm: Performance Investigation and Application in Intrusion Detection

## Abstract
Marine Predator Algorithm (MPA) is a recently proposed population-based metaheuristic algorithm (MA), and its effectiveness has been proven in many stochastic optimization challenges. However, like most MAs, MPA suffers from shortcomings such as imbalanced search preferences and stagnation in the late phase of optimization. Therefore, this paper presents a Multi-strategy Enhanced Marine predator algorithm (MEMPA), where (1) a low-discrepancy Sobol sequence is introduced to generate promising initial solutions in the high-dimensional search domain, (2) the mutualism mechanism is integrated to enhance the ability to escape from local optima, and (3) a distance-based selection scheme is embedded to enhance the diversity of the population during optimization. We conducted comprehensive numerical experiments and rigorous statistical analysis to evaluate the performance of MEMPA against eleven well-known MAs in the CEC2020 benchmark and six classic engineering problems. The experimental results and statistical analysis confirm the efficiency and effectiveness of our proposed MEMPA comprehensively. Finally, we extend the proposed MEMPA to optimize the hyper-parameters of the Extreme Learning Machine (ELM) for intrusion detection, and the performance of MEMPA-ELM increases the average accuracy by 0.79% than the second-best model. The source code of this research can be downloaded at https://github.com/RuiZhong961230/MEMPA.

## Citation
@article{Wang:25,  
title = {Multi-strategy Enhanced Marine Predator Algorithm: Performance Investigation and Application in Intrusion Detection},  
journal = {Journal of Big Data},  
volume = {12},  
pages = {1-36},  
year = {2025},  
doi = {10.1186/s40537-025-01080-2 },  
author = {Zhongmin Wang and Yujun Zhang and Jun Yu and YuanYuan Gao and Guangwei Zhao and Essam H. Houssein and Rui Zhong},  
}

## Datasets and Libraries
CEC benchmarks and Engineering problems are provided by opfunu==1.0.0 and enoppy==0.1.1 libraries, respectively. The NSL-KDD dataset is downloaded from https://www.kaggle.com/datasets/hassan06/nslkdd.

## Contact
If you have any questions, please don't hesitate to contact zhongrui[at]iic.hokudai.ac.jp
