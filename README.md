## CIFAR-10-Warehouse: Towards Broad and More Realistic Testbeds in Model Generalization Analysis


[**CIFAR-10-Warehouse**](https://arxiv.org/pdf/2310.04414.pdf), consisting of 180 datasets collected by prompting image search engines (such as Google, Bing, Baidu, 360, Sogou, Pexels and Flickr) and diffusion models in various ways. Generally sized between 300 and 8,000 images, the datasets (domains) contain natural images, cartoons, certain colors, or objects that do not naturally appear.


## Link of the Dataset

You can access dataset [here](https://drive.google.com/drive/folders/1b5xhY2C4gcLqPYFZ9qZC9EjMLUEgZaMn?usp=drive_link).



Directories & Files of images
```shell
CIFAR-10-W
├── data_360_cartoon_original/
│   ├── 360-CT-01/
│   │      ├── airplane/
│   │      │      ├── 0001.jpg
│   │      │      ├── 0002.jpg
│   │      │      ├── ...
│   │	   ├── automobile/
│   │      │      ├── 0001.jpg
│   │      │      ├── 0002.jpg
│   │      │      ├── ...
│   │      └── ...
│   ├── 360-CT-02/
│   │      ├── airplane/
│   │      │      ├── 0001.jpg
│   │      │      ├── 0002.jpg
│   │      │      ├── ...
│   │	   ├── automobile/
│   │      │      ├── 0001.jpg
│   │      │      ├── 0002.jpg
│   │      │      ├── ...
│   │      └── ...
│   └── ...
├── data_google_original/
│   └── ...
├── data_bing_original/
│   └── ...
├── ...
└── readme.txt
```

## Codes of evaluated methods

The AccP methods evaluated in our study are accessible [here](https://github.com/xingjianleng/autoeval_baselines).


For domain generalization, we employed methods enumerated in [DomainBed](https://github.com/facebookresearch/DomainBed/tree/main). It is important to note that datasets in CIFAR-10-W are only utilized as a test set.


## Citation
Please cite this paper if it helps your research:
```bibtex
@inproceedings{sun2023privacy,
  title={Cifar-10-warehouse: Broad and more realistic testbeds in model generalization analysis},
  author={Sun, Xiaoxiao and Leng, Xingjian and Wang, Zijian and Yang, Yang and Huang, Zi and Zheng, Liang},
  booktitle={ICLR},
  year={2024}
}
```

## Acknowledgement
We express gratitude to the great work [Are Labels Always Necessary for Classifier Accuracy Evaluation?](https://github.com/Simon4Yan/Meta-set) as we benefit a lot from both the paper and code.


## License
This repository is released under the MIT license.
