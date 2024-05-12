# About

I categorize, annotate and write comments for all research papers I read (380+ papers since 2018).

_In June 2023, I wrote the blog post [The How and Why of Reading 300 Papers in 5 Years](https://www.fregu856.com/post/phd_of_reading/) (why I think it’s important to read a lot of papers + how I organize my reading + paper statistics + a list of 30 particularly interesting papers)._

#### Categories:

[Uncertainty Estimation], [Ensembling], [Stochastic Gradient MCMC], [Variational Inference], [Out-of-Distribution Detection], [Theoretical Properties of Deep Learning], [VAEs], [Normalizing Flows], [ML for Medicine/Healthcare], [Object Detection], [3D Object Detection], [3D Multi-Object Tracking], [3D Human Pose Estimation], [Visual Tracking], [Sequence Modeling], [Reinforcement Learning], [Energy-Based Models], [Neural Processes], [Neural ODEs], [Transformers], [Implicit Neural Representations], [Distribution Shifts], [Social Consequences of ML], [Diffusion Models], [Graph Neural Networks], [Selective Prediction], [NLP], [Representation Learning], [Vision-Language Models], [Image Restoration], [Computational Pathology], [Survival Analysis], [Miscellaneous].


### Papers:

- [Papers Read in 2024](#papers-read-in-2024)
- [Papers Read in 2023](#papers-read-in-2023)
- [Papers Read in 2022](#papers-read-in-2022)
- [Papers Read in 2021](#papers-read-in-2021)
- [Papers Read in 2020](#papers-read-in-2020)
- [Papers Read in 2019](#papers-read-in-2019)
- [Papers Read in 2018](#papers-read-in-2018)

#### Papers Read in 2024:

##### [2024-05-12] [paper3]
- NativE: Multi-modal Knowledge Graph Completion in the Wild [[pdf]](https://www.techrxiv.org/doi/full/10.36227/techrxiv.171259566.60211714/v1) [[annotated pdf]](https://github.com/binchen4110/reading_papers/blob/main/commented_pdfs/NativE%20Multi-modal%20Knowledge%20Graph%20Completion%20in%20the%20Wild.pdf)
- *Yichi Zhang, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen*
- `SIGIR 2024`
- [Multimodal KGC]
```
General comments on paper quality:
a little novel; the proposed "Wild" scenarios problem is interesting; easy to read;


Personal comment (in detail)
解决多模态KGC中的模态diversity和imbalanced 问题，设计了relation-guide的多模态融合机制；此外设计了GAN，对抗训练机制来提升表示学习和模型鲁棒性，并理论上证明了基于RotatE的score function满足K-Lipschitz约束，理论上证明了对抗训练机制的有用性；

时间效率的figure画法很有意思。总的来说，方法不是那么惊艳。
```

##### [2024-05-11] [paper2]
- Learnable Pillar-based Re-ranking for Image-Text Retrieval [[pdf]](https://arxiv.org/pdf/2304.12570) [[annotated pdf]](https://github.com/binchen4110/reading_papers/blob/main/commented_pdfs/Learnable%20Pillar-based%20Re-ranking%20for%20Image-Text%20Retrieval.pdf)
- *Leigang Qu, Meng Liu, Wenjie Wang, Zhedong Zheng, Liqiang Nie, Tat-Seng Chua*
- `SIGIR 2023`
- [Multimodal] [Multimodal Retrieval]
```
General comments on paper quality:
fairly novel; the proposed "Pillar" method is interesting; a little complex to read;


Personal comment (in detail):
Image2text的检索任务；在re-ranking阶段，使用Image的跨模态和本模态的邻居为基底（pillar）重定义特征表示，并使用两层变化的GCN学习表示，其中邻接矩阵的部分来源于对Image表示self-attention的相似度计算，文中称之为自学习的部分。

有点变换坐标轴，重新换基的味道。
```

##### [2024-05-10] [paper1]
- Composed Image Retrieval with Text Feedback via Multi-grained Uncertainty Regularization [[pdf]](https://arxiv.org/pdf/2211.07394v6) [[annotated pdf]](https://github.com/binchen4110/reading_papers/blob/main/commented_pdfs/Composed%20Image%20Retrieval%20with%20Text%20Feedback%20via%20Multi-grained%20Uncertainty%20Regularization.pdf)
- *Yiyang Chen, Zhedong Zheng, Wei Ji, Leigang Qu, Tat-Seng Chua*
- `ICLR 2024`
- [Multimodal] [Multimodal Retrieval]
```
General comments on paper quality:
very novel; the proposed method is interesting; easy to read;


Personal comment (in detail):
多模态image retrieval; 建模coarse-grained 匹配，对目标添加高斯噪音，以建模匹配的不确定性，1对多。

思路很简单。
```
