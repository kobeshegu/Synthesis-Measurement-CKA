# Revisiting the Evaluation of Image Synthesis with GANs [NeurIPS-2023 D&B]

![image](./docs/assets/teaser.png)

> **Revisiting the Evaluation of Image Synthesis with GANs** <br>
> Mengping Yang*, Ceyuan Yang*, Yichi Zhang, Qingyan Bai, Yujun Shen, Bo Dai <br>
> *arXiv preprint arXiv:2304.01999*

[[Paper](https://arxiv.org/pdf/2304.01999.pdf)]


A good metric, which promises a reliable comparison between solutions, is essential for any well-defined task. Unlike most vision tasks that have per-sample ground-truth, image synthesis tasks target generating unseen data and hence are usually evaluated through a distributional distance between one set of real samples and another set of generated samples. This study presents an empirical investigation into the evaluation of synthesis performance, with generative adversarial networks (GANs) as a representative of generative models. In particular, we make in-depth analyses of various factors, including how to represent a data point in the representation space, how to calculate a fair distance using selected samples, and how many instances to use from each set. Extensive experiments conducted on multiple datasets and settings reveal several important findings. Firstly, a group of models that include both CNN-based and ViT-based architectures serve as reliable and robust feature extractors for measurement evaluation. Secondly, Centered Kernel Alignment (CKA) provides a better comparison across various extractors and hierarchical layers in one model. Finally, CKA is more sample-efficient and enjoys better agreement with human judgment in characterizing the similarity between two internal data correlations. These findings contribute to the development of a new measurement system, which enables a consistent and reliable re-evaluation of current state-of-the-art generative models.

## Code:

- Code is available [here](https://github.com/kobeshegu/CKA-Evaluation).

## BibTeX

```bibtex
@article{yang2023revisiting,
      title={Revisiting the Evaluation of Image Synthesis with GANs}, 
      author={Mengping Yang and Ceyuan Yang and Yichi Zhang and Qingyan Bai and Yujun Shen and Bo Dai},
      year={2023},
      eprint={2304.01999},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
