# An innovative feature clustering paradigm based on Hypergraph cooperative graph convolutional network for hyperspectral image classification

<a href="https://orcid.org/0000-0002-2300-7112">Zhang Zhen <img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /></a>,<a href="https://orcid.org/0009-0008-4239-2088"> Huang Lehao <img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /></a>,<a href="https://orcid.org/0000-0001-5820-5357"> Wang Qingwang<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /></a> et al.

<h2>Overview</h2>

The proposed **HCoGNN** architecture integrates four key components: the Feature Conversion Module, the Pixel-level Compensation Module, the Hypergraph Action Network, and the Hypergraph Node Feature Adaptive Aggregation Module.\
Specifically, the Feature Conversion Module converts hyperspectral images into hypergraph structure, which is then seamlessly integrated into the core HNFA2M component for supergraph node feature extraction. During training, the HACN leverages the hypergraph structure and spectral information to identify the most effective directions for feature propagation, facilitating accurate representation of each aggregation region (homogeneous region). It then adaptively aggregates regional features through a selective mechanism. The PCM extracts pixel-level features from the original spectral inputs to supplement fine-grained details overlooked by the backbone. Ultimately, the features extracted by the backbone network and the PCM are concatenated and processed through a linear projection layer to produce the final classification outcomes.

<img width="1627" height="1379" alt="HCoGNN_min2" src="https://github.com/user-attachments/assets/235febf0-c7fd-416c-88af-28e167ca99f5" />



## Citation
If you use our code, please cite the following paper: [An innovative feature clustering paradigm based on Hypergraph cooperative graph convolutional network for hyperspectral image classification](https://www.sciencedirect.com/science/article/pii/S0952197625036292).
```

@ARTICLE{ZHANG2026113597,
author = {Zhen Zhang and Lehao Huang and Yabin Hu and Qingwang Wang and Chunxue Xu and Yemao Qi and Chenxi Liu},
journal = {Engineering Applications of Artificial Intelligence},
title = {An innovative feature clustering paradigm based on Hypergraph cooperative graph convolutional network for hyperspectral image classification},
year = {2026},
volume = {166},
pages = {113597},
issn = {0952-1976},
doi = {https://doi.org/10.1016/j.engappai.2025.113597},
url = {https://www.sciencedirect.com/science/article/pii/S0952197625036292},

keywords = {Hyperspectral image classification, Graph convolution network, Hypergraph action network, Feature adaptive aggregation},


```

<h2>Code acknowledgments</h2>

We acknowledge the following code repositories that helped to build the NESSGGCN repository :  

- https://github.com/benfinkelshtein/CoGNN

- https://github.com/ShuGuoJ/GiGCN



Thank you! If there are any that have not been mentioned, please contact me to add them.

