# DeepEmbeddingModel_ZSL
Tensorflow code for CVPR 2017 paper: [Learning a Deep Embedding Model for Zero-Shot Learning](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Learning_a_Deep_CVPR_2017_paper.pdf)

[Li Zhang](http://www.robots.ox.ac.uk/~lz/)


# Data
Download data from [here](http://www.robots.ox.ac.uk/~lz/DEM_cvpr2017/data.zip) and unzip it `unzip data.zip`.

# Run
`AwA_attribute.py` will gives you ZSL performance on AwA with attribute.

`AwA_wordvector.py` will gives you ZSL performance on AwA with wordvector.

`AwA_fusion.py` will gives you ZSL performance on AwA with attribute and wordvector fusion.

`CUB_attribute.py`will gives you ZSL performance on CUB with attribute.

# GBU setting
`AwA1_GBU.py` will gives you ZSL and GZSL performance on AwA1 with attribute under GBU setting [1].

`CUB1_GBU.py` will gives you ZSL and GZSL performance on CUB1 with attribute under GBU setting [1].


## Citing

If you use this code in your research, please use the following BibTeX entry.

```
@inproceedings{zhang2017learning,
  title={Learning a deep embedding model for zero-shot learning},
  author={Zhang, Li and Xiang, Tao and Gong, Shaogang},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2017}
}
```

## References

- [1] [Zero-Shot Learning - A Comprehensive Evaluation of the Good, the Bad and the Ugly](https://arxiv.org/abs/1707.00600).
  Yongqin Xian, Christoph H. Lampert, Bernt Schiele, Zeynep Akata.
  arXiv, 2017.
