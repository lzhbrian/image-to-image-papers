# Image-to-Image papers

A collection of image-to-image papers.

Papers are ordered in arXiv first version submitting time (if applicable).

Feel free to send a PR or issue.



__TOC__

- [Supervised](#supervised)
- [Unsupervised](#unsupervised)
    - [Unsupervised - General](#unsupervised---general)
    - [Unsupervised - Attention/Instance guided](#unsupervised---attentioninstance-guided)
    - [Unsupervised - Many-to-many (Attributes)](#unsupervised---many-to-many-attributes)
    - [Unsupervised - Disentangled (and/or Exemplar guided)](#unsupervised---disentangled-andor-exemplar-guided)
- [To be classified](#to-be-classified)


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
| gesture | GestureGAN | GestureGAN for Hand Gesture-to-Gesture Translation in the Wild | MM 2018 | [1808.04859](https://arxiv.org/abs/1808.04859) | [Ha0Tang/GestureGAN](https://github.com/Ha0Tang/GestureGAN) |
| video           | vid2vid                                   | Video-to-Video Synthesis                                     | NIPS 2018  | [1808.06601](https://arxiv.org/abs/1808.06601) | [NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)          |
| video           | pix2pix-HD + Temporal Smoothing + faceGAN | Everybody Dance Now                                          | ECCVW 2018 | [1808.07371](https://arxiv.org/abs/1808.07371) | [website](https://carolineec.github.io/everybody_dance_now/) |
| (un)supervised  | MSGAN                                     | Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis | CVPR 2019  | [1903.05628](https://arxiv.org/abs/1903.05628) | [HelenMao/MSGAN](https://github.com/HelenMao/MSGAN)          |
| semantic to image | SPADE | Semantic Image Synthesis with Spatially-Adaptive Normalization | CVPR 2019 | [1903.07291](https://arxiv.org/abs/1903.07291) | [NVlabs/SPADE](https://github.com/NVlabs/SPADE) |
| Edge and color domain to reconstrcut image  | PI-REC                                     | PI-REC: Progressive Image Reconstruction Network With Edge and Color Domain |  | [1903.10146](https://arxiv.org/abs/1903.10146) | [youyuge34/PI-REC](https://github.com/youyuge34/PI-REC)          |
| Cross-view image translation | SelectionGAN | Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation | CVPR 2019 | [1904.06807](https://arxiv.org/abs/1904.06807) | [Ha0Tang/SelectionGAN](https://github.com/Ha0Tang/SelectionGAN) |
| keypoint guided | C2-GAN | Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation | MM 2019 | [1908.00999](https://arxiv.org/abs/1908.00999) |  |
| Few shot, video | Few-shot vid2vid | Few-shot Video-to-Video Synthesis | NeurIPS 2019 | [1910.12713](https://arxiv.org/abs/1910.12713) | [NVlabs/few-shot-vid2vid](https://github.com/NVlabs/few-shot-vid2vid) |



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
|                                     | Art2Real     | Art2Real: Unfolding the Reality of Artworks via Semantically-Aware Image-to-Image Translation | CVPR 2019  | [1811.10666](https://arxiv.org/abs/1811.10666)               | [aimagelab/art2real](https://github.com/aimagelab/art2real) |
| latent cross-consistency | CrossNet | CrossNet: Latent Cross-Consistency for Unpaired Image Translation |  | [1901.04530](https://arxiv.org/abs/1901.04530) |  |
|                                     | HarmonicGAN  | Harmonic Unpaired Image-to-image Translation                 | ICLR 2019  | [1902.09727](https://arxiv.org/abs/1902.09727)               |                                                              |
| Person Generation | DG-Net | Joint Discriminative and Generative Learning for Person Re-identification | CVPR 2019 | [1904.07223](https://arxiv.org/abs/1904.07223) | [NVlabs/DG-Net](https://github.com/NVlabs/DG-Net) |
|                                     | TransGaGa    | TransGaGa: Geometry-Aware Unsupervised Image-to-Image Translation | CVPR 2019  | [1904.09571](https://arxiv.org/abs/1904.09571)               | [project](https://wywu.github.io/projects/TGaGa/TGaGa.html)  |
|                      | AGUIT                | Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning |            | [1904.12428](https://arxiv.org/abs/1904.12428)         | [imlixinyang/AGUIT](https://github.com/imlixinyang/AGUIT) |
| few shot             | FUNIT                | Few-Shot Unsupervised Image-to-Image Translation             | ICCV 2019 | [1905.01723](https://arxiv.org/abs/1905.01723)         | [project](https://nvlabs.github.io/FUNIT), [nvlabs/FUNIT](https://github.com/nvlabs/FUNIT/) |
| zero shot | ZstGAN | ZstGAN: An Adversarial Approach for Unsupervised Zero-Shot Image-to-Image Translation | | [1906.00184](https://arxiv.org/abs/1906.00184) | [linjx-ustc1106/ZstGAN-PyTorch](https://github.com/linjx-ustc1106/ZstGAN-PyTorch) |
|  |  | Cross-Domain Cascaded Deep Feature Translation | | [1906.01526](https://arxiv.org/abs/1906.01526) |  |


### Unsupervised - Attention/Instance guided

| Note                  | Model                | Paper                                                        | Conference | paper link                                             | code link                                                    |
| --------------------- | -------------------- | ------------------------------------------------------------ | ---------- | ------------------------------------------------------ | ------------------------------------------------------------ |
| mask                  | ContrastGAN          | Generative Semantic Manipulation with Mask-Contrasting GAN   | ECCV 2018  | [1708.00315](https://arxiv.org/abs/1708.00315)         |                                                              |
| attention             | DA-GAN               | DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks | CVPR 2018  | [1802.06454](https://arxiv.org/abs/1802.06454)         |                                                              |
| mask / attention      | Attention-GAN        | Attention-GAN for Object Transfiguration in Wild Images      | ECCV 2018  | [1803.06798](https://arxiv.org/abs/1803.06798)         |                                                              |
| attention             | Attention guided GAN | Unsupervised Attention-guided Image to Image Translation     | NIPS 2018  | [1806.02311](https://arxiv.org/abs/1806.02311)         | [AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation) |
| attention, one-sided  |                      | Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention |            | [1806.06195](https://arxiv.org/abs/1806.06195)         |                                                              |
| instance aware - mask | InstaGAN             | Instance-aware image-to-image translation                    | ICLR 2019  | [openreview](https://openreview.net/pdf?id=ryxwJhC9YX) | [sangwoomo/instagan](https://github.com/sangwoomo/instagan)  |
|                       | AttentionGAN         | Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation | IJCNN 2019 | [1903.12296](https://arxiv.org/abs/1903.12296)         | [Ha0Tang/AttentionGAN](https://github.com/Ha0Tang/AttentionGAN) |
| instance level - bbox | INIT                 | Towards Instance-level Image-to-Image Translation            | CVPR 2019  | [1905.01744](https://arxiv.org/abs/1905.01744)         | [project](http://zhiqiangshen.com/projects/INIT/index.html)  |
| mask guided           |                      | Mask-Guided Portrait Editing with Conditional GANs           | CVPR 2019  | [1905.10346](https://arxiv.org/abs/1905.10346)         | [cientgu/Mask_Guided_Portrait_Editing](https://github.com/cientgu/Mask_Guided_Portrait_Editing) |
|                       | U-GAT-IT             | U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation |            | [1907.10830](https://arxiv.org/abs/1907.10830)         | [taki0112/UGATIT](https://github.com/taki0112/UGATIT), [znxlwm/UGATIT-pytorch](https://github.com/znxlwm/UGATIT-pytorch) |



### Unsupervised - Many-to-many (Attributes)
| Note                     | Model                        | Paper                                                        | Conference                    | paper link                                     | code link                                                    |
| ------------------------ | ---------------------------- | ------------------------------------------------------------ | ----------------------------- | ---------------------------------------------- | ------------------------------------------------------------ |
|                          | IcGAN                        | Invertible Conditional GANs for image editing                | NIPSW 2016                    | [1611.06355](https://arxiv.org/abs/1611.06355) | [Guim3/IcGAN](https://github.com/Guim3/IcGAN)                |
|                          | Conditional CycleGAN         | Conditional CycleGAN for Attribute Guided Face Image Generation | ECCV 2018                     | [1705.09966](https://arxiv.org/abs/1705.09966) |                                                              |
|                          | StarGAN                      | StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018                     | [1711.09020](https://arxiv.org/abs/1711.09020) | [yunjey/StarGAN](https://github.com/yunjey/StarGAN)          |
|                          | AttGAN                       | AttGAN: Facial Attribute Editing by Only Changing What You Want | TIP 2019                      | [1711.10678](https://arxiv.org/abs/1711.10678) | [LynnHo/AttGAN-Tensorflow](https://github.com/LynnHo/AttGAN-Tensorflow) |
|                          | ComboGAN                     | ComboGAN: Unrestrained Scalability for Image Domain Translation | CVPRW 2018                    | [1712.06909](https://arxiv.org/abs/1712.06909) | [AAnoosheh/ComboGAN](https://github.com/AAnoosheh/ComboGAN)  |
|                          | AugCGAN (Augmented CycleGAN) | Augmented CycleGAN: Learning Many-to-Many Mappings from Unpaired Data | ICML 2018                     | [1802.10151](https://arxiv.org/abs/1802.10151) | [aalmah/augmented_cyclegan](https://github.com/aalmah/augmented_cyclegan) |
|                          | ModularGAN                   | Modular Generative Adversarial Networks                      | ECCV 2018                     | [1804.03343](https://arxiv.org/abs/1804.03343) |                                                              |
| sparsely grouped dataset | SG-GAN                       | Sparsely Grouped Multi-task Generative Adversarial Networks for Facial Attribute Manipulation | MM 2018                       | [1805.07509](https://arxiv.org/abs/1805.07509) | [zhangqianhui/Sparsely-Grouped-GAN](https://github.com/zhangqianhui/Sparsely-Grouped-GAN) |
|                          | GANimation                   | GANimation: Anatomically-aware Facial Animation from a Single Image | ECCV 2018 (honorable mention) | [1807.09251](https://arxiv.org/abs/1807.09251) | [albertpumarola/GANimation](https://github.com/albertpumarola/GANimation) |
|                          | SingleGAN                    | SingleGAN: Image-to-Image Translation by a Single-Generator Network using Multiple Generative Adversarial Learning | ACCV 2018                     | [1810.04991](https://arxiv.org/abs/1810.04991) | [Xiaoming-Yu/SingleGAN](https://github.com/Xiaoming-Yu/SingleGAN) |
|                          | SMIT                         | SMIT: Stochastic Multi-Label Image-to-Image Translation      | ICCVW 2019                    | [1812.03704](https://arxiv.org/abs/1812.03704) | [BCV-Uniandes/SMIT](https://github.com/BCV-Uniandes/SMIT)    |
|                          | InjectionGAN                 | Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation |                               | [1905.08766](https://arxiv.org/abs/1905.08766) |                                                              |
|                          |                              | Image-to-Image Translation with Multi-Path Consistency Regularization | IJCAI 2019                    | [1905.12498](https://arxiv.org/abs/1905.12498) |                                                              |
|                          | RelGAN                       | RelGAN: Multi-Domain Image-to-Image Translation via Relative Attributes | ICCV 2019                     | [1908.07269](https://arxiv.org/abs/1908.07269) | [elvisyjlin/RelGAN-PyTorch](https://github.com/elvisyjlin/RelGAN-PyTorch), [willylulu/RelGAN](https://github.com/willylulu/RelGAN) |



### Unsupervised - Disentangled (and/or Exemplar guided)

| Note                                | Model                        | Paper                                                        | Conference | paper link                                                   | code link                                                    |
| ----------------------------------- | ---------------------------- | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                                     | XGAN                         | XGAN: Unsupervised Image-to-Image Translation for Many-to-Many Mappings | ICML 2018  | [1711.05139](https://arxiv.org/abs/1711.05139)               | [dataset](https://google.github.io/cartoonset/)              |
|                                     | ELEGANT                      | ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes | ECCV 2018  | [1803.10562](https://arxiv.org/abs/1803.10562)               | [Prinsphield/ELEGANT](https://github.com/Prinsphield/ELEGANT) |
|                                     | MUNIT                        | Multimodal Unsupervised Image-to-Image Translation           | ECCV 2018  | [1804.04732](https://arxiv.org/abs/1804.04732)               | [NVlabs/MUNIT](https://github.com/NVlabs/MUNIT)              |
|                                     | cd-GAN (Conditional DualGAN) | Conditional Image-to-Image Translation                       | CVPR 2018  | [1805.00251](https://arxiv.org/abs/1805.00251)               |                                                              |
|                                     | EG-UNIT                      | Exemplar Guided Unsupervised Image-to-Image Translation      | ICLR 2019  | [1805.11145](https://arxiv.org/abs/1805.11145)               |                                                              |
|                                     | PairedCycleGAN               | PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup | CVPR 2018  | [thecvf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_PairedCycleGAN_Asymmetric_Style_CVPR_2018_paper.pdf) |                                                              |
|                                     | DRIT                         | Diverse Image-to-Image Translation via Disentangled Representations | ECCV 2018  | [1808.00948](https://arxiv.org/abs/1808.00948)               | [HsinYingLee/DRIT](https://github.com/HsinYingLee/DRIT)      |
|                                     | UFDN                         | A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation | NIPS 2018  | [1809.01361](https://arxiv.org/abs/1809.01361)               | [Alexander-H-Liu/UFDN](https://github.com/Alexander-H-Liu/UFDN) |
| non-disentangle, face makeup guided | BeautyGAN                    | BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network | MM 2018    | [author](https://liusi-group.com/pdf/BeautyGAN-camera-ready.pdf) | [wtjiang98/BeautyGAN_pytorch](https://github.com/wtjiang98/BeautyGAN_pytorch) |
|                                     | GDWCT                        | Image-to-Image Translation via Group-wise Deep Whitening and Coloring Transformation | CVPR 2019  | [1812.09912](https://arxiv.org/abs/1812.09912)               | [WonwoongCho/GDWCT](https://github.com/WonwoongCho/GDWCT)    |
|                                     | DRIT++                       | DRIT++: Diverse Image-to-Image Translation via Disentangled Representations |            | [1905.01270](https://arxiv.org/abs/1905.01270)               | [project](http://vllab.ucmerced.edu/hylee/DRIT_pp/), [HsinYingLee/MDMM](https://github.com/HsinYingLee/MDMM) |



## To be classified

* Breaking the cycle -- Colleagues are all you need. https://arxiv.org/abs/1911.10538
* EDIT: Exemplar-Domain Aware Image-to-Image Translation. https://arxiv.org/abs/1911.10520
* Multi-mapping Image-to-Image Translation via Learning Disentanglement. https://arxiv.org/abs/1909.07877
