### Requirements
To run this code you will need the following python and R packages:
[numpy](https://www.numpy.org/), [pandas](https://pandas.pydata.org/), [scipy](https://www.scipy.org/) ,[pytorch 1.5.1](https://pytorch.org/), [pytorch-geometric 1.5.0](https://github.com/rusty1s/pytorch_geometric), [networkx 1.11](https://networkx.github.io/), [sklearn](https://scikit-learn.org/stable/), dplyr, sf, ggplot2, sp.

### Run
To run the experiments with the default settings:

```bash

cd code

python experiments.py
 
python multiresolution_experiments.py 
```

## Citation

If you find the methods or the datasets useful in your research, please consider adding the following citations:

```bibtex
@misc{nguyen2023predicting,
      title={Predicting COVID-19 pandemic by spatio-temporal graph neural networks: A New Zealand's study}, 
      author={Viet Bach Nguyen and Truong Son Hy and Long Tran-Thanh and Nhung Nghiem},
      year={2023},
      eprint={2305.07731},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

```bibtex
@InProceedings{pmlr-v184-hy22a,
  title = 	 {Temporal Multiresolution Graph Neural Networks For Epidemic Prediction},
  author =       {Hy, Truong Son and Nguyen, Viet Bach and Tran-Thanh, Long and Kondor, Risi},
  booktitle = 	 {Proceedings of the 1st Workshop on Healthcare AI and COVID-19, ICML 2022},
  pages = 	 {21--32},
  year = 	 {2022},
  editor = 	 {Xu, Peng and Zhu, Tingting and Zhu, Pengkai and Clifton, David A. and Belgrave, Danielle and Zhang, Yuanting},
  volume = 	 {184},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {22 Jul},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v184/hy22a/hy22a.pdf},
  url = 	 {https://proceedings.mlr.press/v184/hy22a.html},
  abstract = 	 {In this paper, we introduce Temporal Multiresolution Graph Neural Networks (TMGNN), the first architecture that both learns to construct the multiscale and multiresolution graph structures and incorporates the time-series signals to capture the temporal changes of the dynamic graphs. We have applied our proposed model to the task of predicting future spreading of epidemic and pandemic based on the historical time-series data collected from the actual COVID-19 pandemic and chickenpox epidemic in several European countries, and have obtained competitive results in comparison to other previous state-of-the-art temporal architectures and graph learning algorithms. We have shown that capturing the multiscale and multiresolution structures of graphs is important to extract either local or global information that play a critical role in understanding the dynamic of a global pandemic such as COVID-19 which started from a local city and spread to the whole world. Our work brings a promising research direction in forecasting and mitigating future epidemics and pandemics. Our source code is available at https://github.com/bachnguyenTE/temporal-mgn.}
}
```

```bibtex
@inproceedings{panagopoulos2020transfer,
  title={{Transfer Graph Neural Networks for Pandemic Forecasting}},
  author={Panagopoulos, George and Nikolentzos, Giannis and Vazirgiannis, Michalis},
  booktitle={Proceedings of the 35th AAAI Conference on Artificial Intelligence},
  year={2021},
}
```

**License**

- [MIT License](https://github.com/HySonLab/pandemic_tgnn/blob/main/LICENSE)
