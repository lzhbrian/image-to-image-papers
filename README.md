# Image-to-Image papers

A collection of image-to-image papers.

Papers are ordered in arXiv first version submitting time (if applicable).

Feel free to send a PR or issue.



__TOC__

- [Supervised](#supervised)
- [Unsupervised](#unsupervised)
    - [Unsupervised - General](#unsupervised---general)
    - [Unsupervised - Attention or Mask guided](#unsupervised---attention-or-mask-guided)
    - [Unsupervised - Many-to-many (Attributes)](#unsupervised---many-to-many-attributes)
    - [Unsupervised - Disentangled (and/or Exemplar guided)](#unsupervised---disentangled-andor-exemplar-guided)


## Supervised

| Note            | Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
| --------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
|                 | pix2pix                                   | Image-to-Image Translation with Conditional Adversarial Networks | CVPR 2017  | [1611.07004](https://arxiv.org/abs/1611.07004) | [junyanz/pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) |
| texture guided  | TextureGAN                                | TextureGAN: Controlling Deep Image Synthesis with Texture Patches | CVPR 2018  | [1706.02823](https://arxiv.org/abs/1706.02823) | [janesjanes/Pytorch-TextureGAN](https://github.com/janesjanes/Pytorch-TextureGAN) |
|                 | Contextual GAN                            | Image Generation from Sketch Constraint Using Contextual GAN | ECCV 2018  | [1711.08972](https://arxiv.org/abs/1711.08972) |                                                              |
|                 | pix2pix-HD                                | High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs | CVPR 2018  | [1711.11585](https://arxiv.org/abs/1711.11585) | [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD)      |
| one-to-many     | BicycleGAN                                | Toward Multimodal Image-to-Image Translation                 | NIPS 2017  | [1711.11586](https://arxiv.org/abs/1711.11586) | [junyanz/BicycleGAN](https://github.com/junyanz/BicycleGAN)  |
| keypoint guided | G2-GAN                                    | Geometry Guided Adversarial Facial Expression Synthesis      | MM 2018    | [1712.03474](https://arxiv.org/abs/1712.03474) |                                                              |
|                 | contour2im                                | Smart, Sparse Contours to Represent and Edit Images          | CVPR 2018  | [1712.08232](https://arxiv.org/abs/1712.08232) | [website](https://contour2im.github.io/)                     |
| disentangle     | Cross-domain disentanglement networks     | Image-to-image translation for cross-domain disentanglement  | NIPS 2018  | [1805.09730](https://arxiv.org/abs/1805.09730) |                                                              |
| video           | vid2vid                                   | Video-to-Video Synthesis                                     | NIPS 2018  | [1808.06601](https://arxiv.org/abs/1808.06601) | [NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)          |
| video           | pix2pix-HD + Temporal Smoothing + faceGAN | Everybody Dance Now                                          | ECCVW 2018 | [1808.07371](https://arxiv.org/abs/1808.07371) | [website](https://carolineec.github.io/everybody_dance_now/) |



## Unsupervised

### Unsupervised - General

| Note                                | Model        | Paper                                                        | Conference | paper link                                                   | code link                                                    |
| ----------------------------------- | ------------ | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                     | DTN          | Unsupervised Cross-Domain Image Generation                   | ICLR 2017  | [1611.02200](https://arxiv.org/abs/1611.02200)               | [yunjey/domain-transfer-network (unofficial)](https://github.com/yunjey/domain-transfer-network) |
|                                     | UNIT         | Unsupervised image-to-image translation networks             | NIPS 2017  | [1703.00848](https://arxiv.org/abs/1703.00848)               | [mingyuliutw/UNIT](https://github.com/mingyuliutw/UNIT)      |
|                                     | DiscoGAN     | Learning to Discover Cross-Domain Relations with Generative Adversarial Networks | ICML 2017  | [1703.05192](https://arxiv.org/abs/1703.05192)               | [SKTBrain/DiscoGAN](https://github.com/SKTBrain/DiscoGAN)    |
|                                     | CycleGAN     | Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks | ICCV 2017  | [1703.10593](https://arxiv.org/abs/1703.10593)               | [junyanz/pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) |
|                                     | DualGAN      | DualGAN: Unsupervised Dual Learning for Image-to-Image Translation | ICCV 2017  | [1704.02510](https://arxiv.org/abs/1704.02510)               | [duxingren14/DualGAN](https://github.com/duxingren14/DualGAN) |
|                                     | DistanceGAN  | One-Sided Unsupervised Domain Mapping                        | NIPS 2017  | [1706.00826](https://arxiv.org/abs/1706.00826)               | [sagiebenaim/DistanceGAN](https://github.com/sagiebenaim/DistanceGAN) |
| semi supervised                     | Triangle GAN | Triangle Generative Adversarial Networks                     | NIPS 2017  | [1709.06548](https://arxiv.org/abs/1709.06548)               | [LiqunChen0606/Triangle-GAN](https://github.com/LiqunChen0606/Triangle-GAN) |
|                                     | CartoonGAN   | CartoonGAN: Generative Adversarial Networks for Photo Cartoonization | CVPR 2018  | [thecvf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf) | [FlyingGoblin/CartoonGAN](https://github.com/FlyingGoblin/CartoonGAN), [unofficial test](https://github.com/Yijunmaverick/CartoonGAN-Test-Pytorch-Torch), [unofficial pytorch](https://github.com/znxlwm/pytorch-CartoonGAN) |
| non-adversarial                     | NAM          | NAM: Non-Adversarial Unsupervised Domain Mapping             | ECCV 2018  | [1806.00804](https://arxiv.org/abs/1806.00804)               | [facebookresearch/nam](https://github.com/facebookresearch/nam) |
|                                     | SCAN         | Unsupervised Image-to-Image Translation with Stacked Cycle-Consistent Adversarial Networks | ECCV 2018  | [1807.08536](https://arxiv.org/abs/1807.08536)               |                                                              |
| dilated conv, improve shape deform. | GANimorph    | Improved Shape Deformation in Unsupervised Image to Image Translation | ECCV 2018  | [1808.04325](https://arxiv.org/abs/1808.04325)               | [brownvc/ganimorph](https://github.com/brownvc/ganimorph/)   |
| video                               | Recycle-GAN  | Recycle-GAN: Unsupervised Video Retargeting                  | ECCV 2018  | [1808.05174](https://arxiv.org/abs/1808.05174)               | [aayushbansal/Recycle-GAN](https://github.com/aayushbansal/Recycle-GAN) |
|                                     | OT-CycleGAN  | Guiding the One-to-one Mapping in CycleGAN via Optimal Transport | AAAI 2019  | [1811.06284](https://arxiv.org/abs/1811.06284)               |                                                              |



### Unsupervised - Attention or Mask guided

| Note                 | Model                | Paper                                                        | Conference | paper link                                             | code link                                                    |
| -------------------- | -------------------- | ------------------------------------------------------------ | ---------- | ------------------------------------------------------ | ------------------------------------------------------------ |
| mask                 | ContrastGAN          | Generative Semantic Manipulation with Mask-Contrasting GAN   | ECCV 2018  | [1708.00315](https://arxiv.org/abs/1708.00315)         |                                                              |
| attention            | DA-GAN               | DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks | CVPR 2018  | [1802.06454](https://arxiv.org/abs/1802.06454)         |                                                              |
| mask / attention     | Attention-GAN        | Attention-GAN for Object Transfiguration in Wild Images      | ECCV 2018  | [1803.06798](https://arxiv.org/abs/1803.06798)         |                                                              |
| attention            | Attention guided GAN | Unsupervised Attention-guided Image to Image Translation     | NIPS 2018  | [1806.02311](https://arxiv.org/abs/1806.02311)         | [AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation) |
| attention, one-sided |                      | Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention |            | [1806.06195](https://arxiv.org/abs/1806.06195)         |                                                              |
| instance aware       | InstaGAN             | Instance-aware image-to-image translation                    | ICLR 2019  | [openreview](https://openreview.net/pdf?id=ryxwJhC9YX) | [sangwoomo/instagan](https://github.com/sangwoomo/instagan)  |



### Unsupervised - Many-to-many (Attributes)
| Note                     | Model                        | Paper                                                        | Conference                    | paper link                                     | code link                                                    |
| ------------------------ | ---------------------------- | ------------------------------------------------------------ | ----------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
|                          | IcGAN                        | Invertible Conditional GANs for image editing                | NIPSW 2016                    | [1611.06355](https://arxiv.org/abs/1611.06355) | [Guim3/IcGAN](https://github.com/Guim3/IcGAN)                |
|                          | Conditional CycleGAN         | Conditional CycleGAN for Attribute Guided Face Image Generation | ECCV 2018                     | [1705.09966](https://arxiv.org/abs/1705.09966) |                                                              |
|                          | StarGAN                      | StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018                     | [1711.09020](https://arxiv.org/abs/1711.09020) | [yunjey/StarGAN](https://github.com/yunjey/StarGAN)          |
|                          | AttGAN                       | AttGAN: Facial Attribute Editing by Only Changing What You Want |                               | [1711.10678](https://arxiv.org/abs/1711.10678) | [LynnHo/AttGAN-Tensorflow](https://github.com/LynnHo/AttGAN-Tensorflow) |
|                          | ComboGAN                     | ComboGAN: Unrestrained Scalability for Image Domain Translation | CVPRW 2018                    | [1712.06909](https://arxiv.org/abs/1712.06909) | [AAnoosheh/ComboGAN](https://github.com/AAnoosheh/ComboGAN)  |
|                          | AugCGAN (Augmented CycleGAN) | Augmented CycleGAN: Learning Many-to-Many Mappings from Unpaired Data | ICML 2018                     | [1802.10151](https://arxiv.org/abs/1802.10151) | [aalmah/augmented_cyclegan](https://github.com/aalmah/augmented_cyclegan) |
|                          | ModularGAN                   | Modular Generative Adversarial Networks                      | ECCV 2018                     | [1804.03343](https://arxiv.org/abs/1804.03343) |                                                              |
| sparsely grouped dataset | SG-GAN                       | Sparsely Grouped Multi-task Generative Adversarial Networks for Facial Attribute Manipulation | MM 2018                       | [1805.07509](https://arxiv.org/abs/1805.07509) | [zhangqianhui/Sparsely-Grouped-GAN](https://github.com/zhangqianhui/Sparsely-Grouped-GAN) |
|                          | GANimation                   | GANimation: Anatomically-aware Facial Animation from a Single Image | ECCV 2018 (honorable mention) | [1807.09251](https://arxiv.org/abs/1807.09251) | [albertpumarola/GANimation](https://github.com/albertpumarola/GANimation) |
|                          | SMIT                         | SMIT: Stochastic Multi-Label Image-to-Image Translation      |                               | [1812.03704](https://arxiv.org/abs/1812.03704) |                                                              |



### Unsupervised - Disentangled (and/or Exemplar guided)

| Note                                | Model                        | Paper                                                        | Conference | paper link                                                   | code link                                                    |
| ----------------------------------- | ---------------------------- | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                     | XGAN                         | XGAN: Unsupervised Image-to-Image Translation for Many-to-Many Mappings | ICML 2018  | [1711.05139](https://arxiv.org/abs/1711.05139)               | [dataset](https://google.github.io/cartoonset/)              |
|                                     | ELEGANT                      | ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes | ECCV 2018  | [1803.10562](https://arxiv.org/abs/1803.10562)               | [Prinsphield/ELEGANT](https://github.com/Prinsphield/ELEGANT) |
|                                     | MUNIT                        | Multimodal Unsupervised Image-to-Image Translation           | ECCV 2018  | [1804.04732](https://arxiv.org/abs/1804.04732)               | [NVlabs/MUNIT](https://github.com/NVlabs/MUNIT)              |
|                                     | cd-GAN (Conditional DualGAN) | Conditional Image-to-Image Translation                       | CVPR 2018  | [1805.00251](https://arxiv.org/abs/1805.00251)               |                                                              |
|                                     | EG-UNIT                      | Exemplar Guided Unsupervised Image-to-Image Translation      |            | [1805.11145](https://arxiv.org/abs/1805.11145)               |                                                              |
|                                     | PairedCycleGAN               | PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup | CVPR 2018  | [thecvf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_PairedCycleGAN_Asymmetric_Style_CVPR_2018_paper.pdf) |                                                              |
|                                     | DRIT                         | Diverse Image-to-Image Translation via Disentangled Representations | ECCV 2018  | [1808.00948](https://arxiv.org/abs/1808.00948)               | [HsinYingLee/DRIT](https://github.com/HsinYingLee/DRIT)      |
|                                     | UFDN                         | A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation | NIPS 2018  | [1809.01361](https://arxiv.org/abs/1809.01361)               | [Alexander-H-Liu/UFDN](https://github.com/Alexander-H-Liu/UFDN) |
| non-disentangle, face makeup guided | BeautyGAN                    | BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network | MM 2018    | [author](https://liusi-group.com/pdf/BeautyGAN-camera-ready.pdf) |                                                              |
|                                     | Style-based generator        | A Style-Based Generator Architecture for Generative Adversarial Networks |            | [1812.04948](https://arxiv.org/abs/1812.04948)               | [website](https://stylegan.xyz/code)                         |
|                                     | GDWTC                        | Image-to-Image Translation via Group-wise Deep Whitening and Coloring Transformation |            | [1812.09912](https://arxiv.org/abs/1812.09912)               |                                                              |


