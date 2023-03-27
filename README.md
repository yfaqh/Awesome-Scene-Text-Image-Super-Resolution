# Awesome Scene Text Image Super-Resolution

> A comprehensive repository of awesome ***Scene Text Image Super-Resolution (STISR)*** methods based on deep learning.

[toc]

## Papers

| *Year* |    *Venue*     |                           *Title*                            |                            *Repo*                            |      *Dataset*      |
| :----: | :------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----------------: |
|  2023  |      AAAI      | [Improving Scene Text Image Super-Resolution via Dual Prior Modulation Network](https://arxiv.org/pdf/2302.10414) |           [Code](https://github.com/jdfxzzy/DPMN)            |      TextZoom       |
|  2023  |      TIP       | [Text prior guided scene text image super-resolution](https://github.com/yfaqh/Awesome-Papers/blob/main/cv/sr/stisr/TIP2023_TPGSR.pdf) |       [Code](https://github.com/mjq11302010044/TPGSR)        |      TextZoom       |
|  2023  |     arXiv      | [Scene Text Image Super-Resolution via Content Perceptual Loss and Criss-Cross Transformer Blocks](https://arxiv.org/pdf/2210.06924.pdf)* |                                                              |      TextZoom       |
|  2022  |       -        | Scene Text Image Super-Resolution with Self-Supervised Memory Learning |           [Code](https://github.com/xyzhu1/MNTSR)            |      TextZoom       |
|  2022  |     IJCAI      | [C3-STISR: Scene Text Image Super-resolution with Triple Clues](https://arxiv.org/pdf/2204.14044) |        [Code](https://github.com/zhaominyiz/C3-STISR)        |      TextZoom       |
|  2022  |      CVPR      | [A Text Attention Network for Spatial Deformation Robust Scene Text Image Super-resolution](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_A_Text_Attention_Network_for_Spatial_Deformation_Robust_Scene_Text_CVPR_2022_paper.pdf)* |        [Code](https://github.com/mjq11302010044/TATT)        |      TextZoom       |
|  2022  |      AAAI      | [Text gestalt: Stroke-aware scene text image super-resolution](https://ojs.aaai.org/index.php/AAAI/article/download/19904/19663) | [Code](https://github.com/FudanVI/FudanOCR/tree/main/text-gestalt) |      TextZoom       |
|  2021  |      BMVC      | [Skeleton-aware text image super-resolution](https://www.bmvc2021-virtualconference.com/assets/papers/1482.pdf) |                                                              |      TextZoom       |
|  2021  | Neurocomputing | [TSRGAN: Real-world text image super-resolution based on adversarial learning and triplet attention](https://sci-hub.st/10.1016/j.neucom.2021.05.060) |                                                              |      TextZoom       |
|  2021  |     ACM MM     | [Scene text image super-resolution via parallelly contextual attention network](https://www.academia.edu/download/79581904/3474085.pdf) |           [Code](https://github.com/Shualite/PCAN)           |      TextZoom       |
|  2021  |      CVPR      | [Scene text telescope: Text-focused scene image super-resolution](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Scene_Text_Telescope_Text-Focused_Scene_Image_Super-Resolution_CVPR_2021_paper.pdf)* | [Code](https://github.com/FudanVI/FudanOCR/tree/main/scene-text-telescope) |      TextZoom       |
|  2021  |     arXiv      | [Text prior guided scene text image super-resolution](https://arxiv.org/pdf/2106.15368)@TIP |       [Code](https://github.com/mjq11302010044/TPGSR)        |      TextZoom       |
|  2021  |      ICME      | [A Novel Attention Enhanced Residual-In-Residual Dense Network for Text Image Super-Resolution](https://sci-hub.wf/10.1109/ICME51207.2021.9428128) |                                                              |  ICDAR2015-TextSR   |
|  2020  |      ECCV      | [Scene Text Image Super-Resolution in the Wild](https://arxiv.org/pdf/2005.03341) |        [Code](https://github.com/JasonBoy1/TextZoom)         |      TextZoom       |
|  2020  |     ICASSP     | [Adversarial Text Image Super-Resolution using Sinkhorn Distance](https://sci-hub.wf/10.1109/ICASSP40776.2020.9054360) |                                                              |  ICDAR2015-TextSR   |
|  2020  |      ICPR      | [On-Device Text Image Super Resolution](https://arxiv.org/pdf/2011.10251) |                                                              |      Synth90k       |
|  2019  |     arXiv      | [TextSR: Content-Aware Text Super-Resolution Guided by Recognition](https://arxiv.org/pdf/1909.07113) |          [Code](https://github.com/xieenze/TextSR)           | Synth90k; SynthText |
|  2019  |      ICME      | [Text-Attentional Conditional Generative Adversarial Network for Super-Resolution of Text Images](https://sci-hub.st/10.1109/ICME.2019.00180) |                                                              |  ICDAR2015-TextSR   |

- The "@￥" means that the paper has been **Accepted** by ￥.
- The "*" means that the work involves **Vision Transformer** for STISR.



## Datasets

| *Year* | *Venue* |                           *Title*                            | *Type* |                            *Link*                            |
| :----: | :-----: | :----------------------------------------------------------: | :----: | :----------------------------------------------------------: |
|  2020  |  ECCV   |         [TextZoom](https://arxiv.org/pdf/2005.03341)         |  Real  |    [Dataset](https://github.com/WenjiaWang0312/TextZoom)     |
|  2016  |  CVPR   | [SynthText](http://openaccess.thecvf.com/content_cvpr_2016/papers/Gupta_Synthetic_Data_for_CVPR_2016_paper.pdf) | Syntic |      [Dataset](https://github.com/ankush-me/SynthText)       |
|  2015  |  ICDAR  |   [ICDAR2015-TextSR](https://projet.liris.cnrs.fr/sr2015/)   | Syntic |    [Dataset](https://github.com/piclem/ICDAR2015-TextSR)     |
|  2014  |  NIPSW  |       [Synth90k](https://arxiv.org/pdf/1406.2227.pdf)        | Syntic | [Dataset](https://academictorrents.com/details/3d0b4f09080703d2a9c6be50715b46389fdb3af1) |

- The use of datasets **Synth90K** and **SynthText** for scene text image super-resolution requires manual creation.



## Acknowledgment

- This repository is scheduled to be updated regularyly in accordance with schedules of major AI or CV related Conferences and Journals.
- Welcome to post **Pull-requests** to update the list above.

- Thanks to all the above researchers' contribution.