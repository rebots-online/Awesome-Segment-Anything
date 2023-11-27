[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# A Comprehensive Survey on Segment Anything Model for Vision and Beyond

> **The First Comprehensive SAM Survey: A Comprehensive Survey on Segment Anything Model for Vision and Beyond.** Chunhui Zhang, Li Liu, Yawen Cui, Guanjie Huang, Weilin Lin, Yiqian Yang, Yuehong Hu. [[paper](https://arxiv.org/abs/2305.08196)] [[homepage](https://github.com/liliu-avril/Awesome-Segment-Anything)][[中文解读](https://mp.weixin.qq.com/s/uYpRzvRp22-40x8e0pLVIg)] 

> **<p align="justify"> Abstract:** *Artificial intelligence (AI) is evolving towards artificial general intelligence, which refers to the ability of an AI system to perform a wide range of tasks and exhibit a level of intelligence similar to that of a human being. This is in contrast to narrow or specialized AI, which is designed to perform specific tasks with a high degree of efficiency. Therefore, it is urgent to design a general class of models, which we term foundation models, trained on broad data that can be adapted to various downstream tasks. The recently proposed segment anything model (SAM) has made significant progress in breaking the boundaries of segmentation, greatly promoting the development of foundation models for computer vision. To fully comprehend SAM, we conduct a survey study. As the first to comprehensively review the progress of segmenting anything task for vision and beyond based on the foundation model of SAM, this work focuses on its applications to various tasks and data types by discussing its historical development, recent progress, and profound impact on broad applications. We first introduce the background and terminology for foundation models including SAM, as well as state-of-the-art methods contemporaneous with SAM that are significant for segmenting anything task. Then, we analyze and summarize the advantages and limitations of SAM across various image processing applications, including software scenes, real-world scenes, and complex scenes. Importantly, many insights are drawn to guide future research to develop more versatile foundation models and improve the architecture of SAM. We also summarize massive other amazing applications of SAM in vision and beyond. Finally, we maintain a continuously updated paper list and an open-source project summary for foundation model SAM at [here](https://github.com/liliu-avril/Awesome-Segment-Anything).* </p>

> **Awesome Segment Anything Models:** A curated list of awesome segment anything models in computer vision and beyond. This repository supplements our survey paper. We intend to continuously update it.

#### We strongly encourage authors of relevant works to make a pull request and add their paper's information [[here](https://docs.google.com/spreadsheets/d/1AdOc_mZrkKP7XoKL9g7YO4EEpjlxdxEDK2yOdRZ_edg/edit?usp=sharing)].

____

## News
```
- 2023.11.27: Latest update of this paper list.
- 2023.07.14: "Segment Anything" was accepted by ICCV 2023.
- 2023.05.16: An initial version of recent papers and projects.
- 2023.04.05: The paper of "Segment Anything" was online.
```
## Contents

- [Paper List](#paper-list) 
  - [Seminal Papers](#seminal-papers)
  - [Follow-up Papers ](#follow-up-papers)
- [Open Source Projects](#open-source-projects)
- [Awesome Repositories for SAM](#awesome-repositories-for-sam)

## Citation

If you find our work useful in your research, please consider citing:
```
@article{chunhui2023samsurvey,
  title={A Comprehensive Survey on Segment Anything Model for Vision and Beyond},
  author={Zhang, Chunhui and Liu, Li and Cui, Yawen and Huang, Guanjie and Lin, Weilin and Yang, Yiqian and Hu, Yuehong},
  journal={arXiv:2305.08196},
  year={2023}
}
```


## Paper List
### Seminal Papers
- **SAM:** Alexander Kirillov, Eric Mintun, Nikhila Ravi, Hanzi Mao, Chloe Rolland, Laura Gustafson, Tete Xiao, Spencer Whitehead, Alexander C. Berg, Wan-Yen Lo, Piotr Dollár, Ross Girshick.<br />
  "Segment Anything." **ICCV (2023)**.
  [[paper](https://arxiv.org/abs/2304.02643)] 
  [[homepage](https://segment-anything.com/)] 
  [[code](https://github.com/facebookresearch/segment-anything)]
  [[Zhihu](https://www.zhihu.com/question/593914819)]
  [[Reddit](https://www.reddit.com/r/singularity/comments/12cq56n/meta_ai_has_released_both_the_model_and_the/)]
  [2023.04]

- **SEEM:** Xueyan Zou, Jianwei Yang, Hao Zhang, Feng Li, Linjie Li, Jianfeng Gao, Yong Jae Lee.<br />
  "Segment Everything Everywhere All at Once." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2304.06718)] 
  [[code](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)]
  [2023.04]
  
- **SegGPT:** Xinlong Wang, Xiaosong Zhang, Yue Cao, Wen Wang, Chunhua Shen, Tiejun Huang.<br />
  "SegGPT: Segmenting Everything In Context." ICCV (2023).
  [[paper](https://arxiv.org/abs/2304.03284)] 
  [[code](https://github.com/baaivision/Painter)]
  [2023.04]

- **Grounding DINO:** Shilong Liu, Zhaoyang Zeng, Tianhe Ren, Feng Li, Hao Zhang, Jie Yang, Chunyuan Li, Jianwei Yang, Hang Su, Jun Zhu, Lei Zhang.<br />
  "Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2303.05499)] 
  [[code]( https://github.com/IDEA-Research/GroundingDINO)]
  [2023.04]
  
- **ImageBind:** Rohit Girdhar, Alaaeldin El-Nouby, Zhuang Liu, Mannat Singh, Kalyan Vasudev Alwala, Armand Joulin, Ishan Misra.<br />
  "ImageBind: One Embedding Space To Bind Them All." CVPR (2023).
  [[paper](https://arxiv.org/abs/2305.05665)] 
  [[homepage](https://imagebind.metademolab.com/)] 
  [[code](https://github.com/facebookresearch/ImageBind)]
  [2023.05]
  
- **Meta-Transformer:** Yiyuan Zhang, Kaixiong Gong, Kaipeng Zhang, Hongsheng Li, Yu Qiao, Wanli Ouyang, Xiangyu Yue.<br />
  "Meta-Transformer: A Unified Framework for Multimodal Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.10802)] 
  [[homepage](https://github.com/invictus717/MetaTransformer)]
  [[code](https://github.com/invictus717/MetaTransformer)]
  [[中文解读](https://mp.weixin.qq.com/s/r38bzqdJxDZUvtDI0c9CEw?poc_token=HJBW1GSjrlLI_fXbnZeCfAefBIyL3OT0__QH-hfc)]
  [2023.07]

- **OpenSeeD:** Hao Zhang, Feng Li, Xueyan Zou, Shilong Liu, Chunyuan Li, Jianfeng Gao, Jianwei Yang, Lei Zhang.<br />
  "A Simple Framework for Open-Vocabulary Segmentation and Detection." ICCV (2023).
  [[paper](https://arxiv.org/abs/2303.08131)] 
  [[code](https://github.com/IDEA-Research/OpenSeeD)]
  [2023.03]
 
- **RAM:** Youcai Zhang, Xinyu Huang, Jinyu Ma, Zhaoyang Li, Zhaochuan Luo, Yanchun Xie, Yuzhuo Qin, Tong Luo, Yaqian Li, Shilong Liu, Yandong Guo, Lei Zhang.<br />
  "Recognize Anything: A Strong Image Tagging Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03514)] 
  [[homepage](https://recognize-anything.github.io/)] 
  [[code](https://github.com/xinyu1205/Recognize_Anything-Tag2Text)]
  [2023.06]

- **PACGen:** Yuheng Li, Haotian Liu, Yangming Wen, Yong Jae Lee.<br />
  "Generate Anything Anywhere in Any Scene." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17154)] 
 [[homepage](https://github.com/Yuheng-Li/PACGen)] 
  [[code](https://yuheng-li.github.io/PACGen/)]
  [2023.06]

- **ASM:** Weiyun Wang, Min Shi, Qingyun Li, Wenhai Wang, Zhenhang Huang, Linjie Xing, Zhe Chen, Hao Li, Xizhou Zhu, Zhiguo Cao, Yushi Chen, Tong Lu, Jifeng Dai, Yu Qiao.<br />
  "The All-Seeing Project: Towards Panoptic Visual Recognition and Understanding of the Open World." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.01907)] 
  [[homepage](https://github.com/OpenGVLab/All-Seeing)] 
  [[demo](https://huggingface.co/spaces/OpenGVLab/all-seeing)]
  [2023.08]

- **OneFormer:** Jitesh Jain, Jiachen Li, MangTik Chiu, Ali Hassani, Nikita Orlov, Humphrey Shi.<br />
  "OneFormer: One Transformer to Rule Universal Image Segmentation." CVPR (2023).
  [[paper]( https://arxiv.org/abs/2211.06220)] 
[[homepage](https://praeclarumjj3.github.io/oneformer)] 
  [[code](https://github.com/SHI-Labs/OneFormer)]
  [2022.11]
  
- **OVSeg:** Feng Liang, Bichen Wu, Xiaoliang Dai, Kunpeng Li, Yinan Zhao, Hang Zhang, Peizhao Zhang, Peter Vajda, Diana Marculescu.<br />
  "Open-Vocabulary Semantic Segmentation with Mask-adapted CLIP." CVPR (2023).
  [[paper](https://arxiv.org/abs/2210.04150)] 
  [[homepage]( https://jeff-liangf.github.io/projects/ovseg/)] 
  [[code](https://github.com/facebookresearch/ov-seg)]
  [2022.10]


### Follow-up Papers
:boom:Francesco Croce, Matthias Hein.<br />
  "Segment (Almost) Nothing: Prompt-Agnostic Adversarial Attacks on Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.14450)] 
  [2023.11]

:boom:**P2RBox:** Guangming Cao, Xuehui Yu, Wenwen Yu, Xumeng Han, Xue Yang, Guorong Li, Jianbin Jiao, Zhenjun Han.<br />
  "P2RBox: A Single Point is All You Need for Oriented Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13128)] 
  [2023.11]

:boom:**PG-Video-LLaVA:** Shehan Munasinghe, Rusiru Thushara, Muhammad Maaz, Hanoona Abdul Rasheed, Salman Khan, Mubarak Shah, Fahad Khan.<br />
  "PG-Video-LLaVA: Pixel Grounding Large Video-Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13435)] 
  [[code](https://github.com/mbzuai-oryx/Video-LLaVA)]
  [2023.11]

:boom:**MetaDreamer:** Lincong Feng, Muyu Wang, Maoyu Wang, Kuo Xu, Xiaoli Liu.<br />
  "MetaDreamer: Efficient Text-to-3D Creation With Disentangling Geometry and Texture." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10123)] 
  [[code](https://metadreamer3d.github.io/)]
  [2023.11]

:boom:**Emu Edit:** Shelly Sheynin, Adam Polyak, Uriel Singer, Yuval Kirstain, Amit Zohar, Oron Ashual, Devi Parikh, Yaniv Taigman.<br />
  "Emu Edit: Precise Image Editing via Recognition and Generation Tasks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10089)] 
  [[homepage](https://emu-edit.metademolab.com/)]
  [2023.11]

:boom:Duy Minh Ho Nguyen, Tan Ngoc Pham, Nghiem Tuong Diep, Nghi Quoc Phan, Quang Pham, Vinh Tong, Binh T. Nguyen, Ngan Hoang Le, Nhat Ho, Pengtao Xie, Daniel Sonntag, Mathias Niepert.<br />
  "On the Out of Distribution Robustness of Foundation Models in Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11096)] 
  [2023.11]

:boom:Yu Ando, Nora Jee-Young Park and, Gun Oh Chong, Seokhwan Ko, Donghyeon Lee, Junghwan Cho, Hyungsoo Han.<br />
  "Interpretable pap smear cell representation for cervical cancer screening." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10269)] 
  [2023.11]

:boom:**GT-Maps:** Yimeng Li, Navid Rajabi, Sulabh Shrestha, Md Alimoor Reza, Jana Kosecka.<br />
  "Labeling Indoor Scenes with Fusion of Out-of-the-Box Perception Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10883)] 
  [2023.11]

:boom:Nam V. Nguyen, Hieu Trung Huynh, and Phuc-Lu Le.<br />
  "Deep Learning Techniques for Segmenting Breast Lesion Regions and Classifying Mammography Images." ArXiv (2023).
  [[paper](https://link.springer.com/chapter/10.1007/978-981-99-8296-7_34)] 
  [2023.11]

:boom:Ren Li, Corentin Dumery, Benoît Guillard, Pascal Fua.<br />
  "Garment Recovery with Shape and Deformation Priors." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10356)] 
  [2023.11]

:boom:**MROS:** Kechen Song, Hongwei Wen, Xiaotong Xue, Liming Huang, Yingying Ji, Yunhui Yan .<br />
  "Modality Registration and Object Search Framework for UAV-based Unregistered RGB-T Image Salient Object Detection." ArXiv (2023).
  [[paper](https://www.researchgate.net/profile/Ke-Chen-Song/publication/375623798_Modality_Registration_and_Object_Search_Framework_for_UAV-based_Unregistered_RGB-T_Image_Salient_Object_Detection/links/65558ed9b1398a779d9086ed/Modality-Registration-and-Object-Search-Framework-for-UAV-Based-Unregistered-RGB-T-Image-Salient-Object-Detection.pdf)] 
  [[code](https://github.com/VDT-2048/UAV-RGB-T-2400)]
  [2023.11]

:boom:**CPVLF:** Lv Tang, Peng-Tao Jiang, Zhihao Shen, Hao Zhang, Jinwei Chen, Bo Li.<br />
  "Generalization and Hallucination of Large Vision-Language Models through a Camouflaged Lens." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11273)] 
  [2023.11]

:boom:Zixuan Xie, Rengan Xie, Rong Li, Kai Huang, Pengju Qiao, Jingsen Zhu, Xu Yin, Qi Ye, Wei Hua, Yuchi Huo, Hujun Bao.<br />
  "Holistic Inverse Rendering of Complex Facade via Aerial 3D Scanning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11825)] 
  [2023.11]

:boom:**Clarity ChatGPT:** Yanyan Wei, Zhao Zhang, Jiahuan Ren, Xiaogang Xu, Richang Hong, Yi Yang, Shuicheng Yan, Meng Wang.<br />
  "Clarity ChatGPT: An Interactive and Adaptive Processing System for Image Restoration and Enhancement." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11695)] 
  [2023.11]

:boom:**GCDSS:** Zhengyuan Peng, Qijian Tian, Jianqing Xu, Yizhang Jin, Xuequan Lu, Xin Tan, Yuan Xie, Lizhuang Ma.<br />
  "Generalized Category Discovery in Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11525)] 
  [[code](https://github.com/JethroPeng/GCDSS)]
  [2023.11]

- **Few-shot SLVM:** Xiyu Qi, Yifan Wu, Yongqiang Mao, Wenhui Zhang, Yidan Zhang.<br />
  "Self-guided Few-shot Semantic Segmentation for Remote Sensing Imagery Based on Large Vision Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13200)] 
  [2023.11]

- **OCT-mosaicking:** Jiacheng Wang, Hao Li, Dewei Hu, Yuankai K. Tao, Ipek Oguz.<br />
  "Novel OCT mosaicking pipeline with Feature- and Pixel-based registration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.13052)] 
  [[code](https://github.com/MedICL-VU/OCT-mosaicking)]
  [2023.11]

- **PseCo:** Huang Zhizhong, Dai Mingliang, Zhang Yi, Zhang Junping, Shan Hongming.<br />
  "Point, Segment and Count: A Generalized Framework for Object Counting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12386)] 
  [[code](https://github.com/Hzzone/PseCo)]
  [2023.11]

- **FreeKD:** Yuan Zhang, Tao Huang, Jiaming Liu, Tao Jiang, Kuan Cheng, Shanghang Zhang.<br />
  "FreeKD: Knowledge Distillation via Semantic Frequency Prompt." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12079)] 
  [2023.11]

- Rohit Bharadwaj, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan.<br />
  "Enhancing Novel Object Detection via Cooperative Foundational Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12068)] 
  [[code](https://github.com/rohit901/cooperative-foundational-models)]
  [2023.11]

- **GMISeg:** Jing Xu.<br />
  "GMISeg: General Medical Image Segmentation without Re-Training." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12539)] 
  [2023.11]

- Tian Meng, Yang Tao, Wuliang Yin.<br />
  "Few-Shot Classification & Segmentation Using Large Language Models Agent." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.12065)] 
  [2023.11]

- **MorSeg-CAM-SAM:** Xin Yue, Qing Zhao, Jianqiang Li, Xiaoling Liu, Changwei Song, Suqin Liu, Guanghui Fu.<br />
  "Morphology-Enhanced CAM-Guided SAM for weakly supervised Breast Lesion Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11176)] 
  [[code](https://github.com/YueXin18/MorSeg-CAM-SAM)]
  [2023.11]

- **SA-Med2D-20M:** Jin Ye, Junlong Cheng, Jianpin Chen, Zhongying Deng, Tianbin Li, Haoyu Wang, Yanzhou Su, Ziyan Huang, Jilong Chen, Lei Jiang, Hui Sun, Min Zhu, Shaoting Zhang, Junjun He, Yu Qiao.<br />
  "SA-Med2D-20M Dataset: Segment Anything in 2D Medical Imaging with 20 Million masks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11969)] 
  [[code](https://github.com/OpenGVLab/SAM-Med2D)]
  [2023.11]

- **OmniSeg3D:** Haiyang Ying, Yixuan Yin, Jinzhi Zhang, Fan Wang, Tao Yu, Ruqi Huang, Lu Fang.<br />
  "OmniSeg3D: Omniversal 3D Segmentation via Hierarchical Contrastive Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11666)] 
  [[homepage](https://oceanying.github.io/OmniSeg3D/)]
  [2023.11]

- **GeoSAM:** Rafi Ibn Sultan, Chengyin Li, Hui Zhu, Prashant Khanduri, Marco Brocanelli, Dongxiao Zhu.<br />
  "GeoSAM: Fine-tuning SAM with Sparse and Dense Visual Prompting for Automated Segmentation of Mobility Infrastructure." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11319)] 
  [2023.11]

- **CellSAM :** Uriah Israel, Markus Marks, Rohit Dilip, Qilin Li, Morgan Schwartz, Elora Pradhan, Edward Pao, Shenyi Li, Alexander Pearson-Goulart, Pietro Perona, Georgia Gkioxari, Ross Barnowski, Yisong Yue, David Van Valen.<br />
  "A Foundation Model for Cell Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.11004)] 
  [[code](https://label-dev.deepcell.org/)]
  [2023.11]

- **RockSAM:** Zhaoyang Ma, Xupeng He, Shuyu Sun, Bicheng Yan, Hyung Kwak, Jun Gao.<br />
  "Zero-Shot Digital Rock Image Segmentation with a Fine-Tuned Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10865)] 
  [2023.11]

- **DMV3D:** Yinghao Xu, Hao Tan, Fujun Luan, Sai Bi, Peng Wang, Jiahao Li, Zifan Shi, Kalyan Sunkavalli, Gordon Wetzstein, Zexiang Xu, Kai Zhang.<br />
  "DMV3D: Denoising Multi-View Diffusion using 3D Large Reconstruction Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.09217)] 
  [[code](https://justimyhxu.github.io/projects/dmv3d/)]
  [2023.11]

- **InterpAny-Clearer:** Zhihang Zhong, Gurunandan Krishnan, Xiao Sun, Yu Qiao, Sizhuo Ma, Jian Wang.<br />
  "Clearer Frames, Anytime: Resolving Velocity Ambiguity in Video Frame Interpolation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08007)] 
  [[homepage](https://zzh-tech.github.io/InterpAny-Clearer/)]
  [[code](https://github.com/zzh-tech/InterpAny-Clearer)]
  [2023.11]

- **OSM:** Qihang Yu, Xiaohui Shen, Liang-Chieh Chen.<br />
  "Towards Open-Ended Visual Recognition with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08400)] 
  [[code](https://github.com/bytedance/OmniScient-Model)]
  [2023.11]

- **UR-SAM:** Yichi Zhang, Shiyao Hu, Chen Jiang, Yuan Cheng, Yuan Qi.<br />
  "Segment Anything Model with Uncertainty Rectification for Auto-Prompting Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10529)] 
  [2023.11]

- **DefectSAM:** Bozhen Hu, Bin Gao, Cheng Tan, Tongle Wu, Stan Z. Li.<br />
  "Segment Anything in Defect Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10245)] 
  [2023.11]

- **UnifiedVisionGPT:** Chris Kelly, Luhui Hu, Cindy Yang, Yu Tian, Deshun Yang, Bang Yang, Zaoshan Huang, Zihao Li, Yuexian Zou.<br />
  "UnifiedVisionGPT: Streamlining Vision-Oriented AI through Generalized Multimodal Framework." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10125)] 
  [[code](https://github.com/LHBuilder/SA-Segment-Anything)]
  [2023.11]

- **Slide-SAM:** Quan Quan, Fenghe Tang, Zikang Xu, Heqin Zhu, S. Kevin Zhou.<br />
  "Slide-SAM: Medical SAM Meets Sliding Window." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.10121)] 
  [2023.11]

- **MM-Navigator:** An Yan, Zhengyuan Yang, Wanrong Zhu, Kevin Lin, Linjie Li, Jianfeng Wang, Jianwei Yang, Yiwu Zhong, Julian McAuley, Jianfeng Gao, Zicheng Liu, Lijuan Wang.<br />
  “GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.07562)] 
  [[code](https://github.com/zzxslp/MM-Navigator)]
  [2023.11]

- **TriDental:** Tomáš Kunzo, Viktor Kocur, Lukáš Gajdošech, Martin Madaras.<br />
  "Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning." DISA (2023).
  [[paper](https://arxiv.org/abs/2311.07398)] 
  [2023.11]

- Hyungeun Lee, Ung Hwang, Seungwon Yu, Chang-Hun Lee, Kijung Yoon.<br />
  "Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning." ML4H (2023).
  [[paper](https://arxiv.org/abs/2311.06834)] 
  [2023.11]

- **AdapterShadow:** Leiping Jie, Hui Zhang.<br />
  "AdapterShadow: Adapting Segment Anything Model for Shadow Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08891)] 
  [[code](https://github.com/LeipingJie/AdapterShadow)]
  [2023.11]

- **Uni-COAL:** Zhiyun Song, Zengxin Qi, Xin Wang, Xiangyu Zhao, Zhenrong Shen, Sheng Wang, Manman Fei, Zhe Wang, Di Zang, Dongdong Chen, Linlin Yao, Qian Wang, Xuehai Wu, Lichi Zhang.<br />
  "Uni-COAL: A Unified Framework for Cross-Modality Synthesis and Super-Resolution of MR Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08225)] 
  [2023.11]

- **SAMIHS:** Yinuo Wang, Kai Chen, Weimin Yuan, Cai Meng, XiangZhi Bai.<br />
  "SAMIHS: Adaptation of Segment Anything Model for Intracranial Hemorrhage Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08190)] 
  [[code](https://github.com/mileswyn/SAMIHS)]
  [2023.11]

- Virmarie Maquiling, Sean Anthony Byrne, Diederick C. Niehorster, Marcus Nyström, Enkelejda Kasneci.<br />
  "Zero-Shot Segmentation of Eye Features Using the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08077)] 
  [[code](XXXXXXXXXXXXXXXXXXXXXX)]
  [2023.11]
  
- **GlanceSeg:** Hongyang Jiang, Mengdi Gao, Zirong Liu, Chen Tang, Xiaoqing Zhang, Shuai Jiang, Wu Yuan, Jiang Liu.<br />
  "GlanceSeg: Real-time microaneurysm lesion segmentation with gaze-map-guided foundation model for early detection of diabetic retinopathy." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.08075)] 
  [2023.11]

- **EviPrompt:** Yinsong Xu, Jiaqi Tang, Aidong Men, Qingchao Chen.<br />
  "EviPrompt: A Training-Free Evidential Prompt Generation Method for Segment Anything Model in Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.06400)] 
  [2023.11]

- **FDNet:** Xiang Feng, Chengkai Wang, Chengyu Wu, Yunxiang Li, Yongbo He, Shuai Wang, Yaiqi Wang.<br />
  "FDNet: Feature Decoupled Segmentation Network for Tooth CBCT Image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.06551)] 
  [2023.11]

- **GISCup23:** Xuanshu Luo, Paul Walther, Wejdene Mansour, Balthasar Teuscher, Johann Maximilian Zollner, Hao Li, Martin Werner.<br />
  "Exploring GeoAI Methods for Supraglacial Lake Mapping on Greenland Ice Sheet." ArXiv (2023).
  [[paper](https://www.bgd.ed.tum.de/pdf/2023_giscup_Luo.pdf)] 
  [[code](https://github.com/tum-bgd/GISCup23)]
  [2023.11]

- **u-LLaVA:** Jinjin Xu, Liwu Xu, Yuzhe Yang, Xiang Li, Yanchun Xie, Yi-Jie Huang, Yaqian Li.<br />
  "u-LLaVA: Unifying Multi-Modal Tasks via Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05348)] 
  [2023.11]

- **LLaVA-Plus:** Shilong Liu, Hao Cheng, Haotian Liu, Hao Zhang, Feng Li, Tianhe Ren, Xueyan Zou, Jianwei Yang, Hang Su, Jun Zhu, Lei Zhang, Jianfeng Gao, Chunyuan Li.<br />
  "LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05437)] 
  [[code](https://llava-vl.github.io/llava-plus/)]
  [2023.11]

- **EVA-VOS:** Thanos Delatolas, Vicky Kalogeiton, Dim P. Papadopoulos.<br />
  "Learning the What and How of Annotation in Video Object Segmentation." WACV  (2023).
  [[paper](https://arxiv.org/abs/2311.04414)] 
  [[code](https://eva-vos.compute.dtu.dk/)]
  [2023.11]

- **NExT-Chat:** Ao Zhang, Liming Zhao, Chen-Wei Xie, Yun Zheng, Wei Ji, Tat-Seng Chua.<br />
  "NExT-Chat: An LMM for Chat, Detection and Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.04498)] 
  [[code](https://next-chatv.github.io)]
  [2023.11]


- **SAMVG:** Haokun Zhu, Juang Ian Chong, Teng Hu, Ran Yi, Yu-Kun Lai, Paul L. Rosin.<br />
  "SAMVG: A Multi-stage Image Vectorization Model with the Segment-Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.05276)] 
  [2023.11]

- Danielle Ferreira, Rima Arnaout.<br />
  "Are foundation models efficient for medical image segmentation?" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.04847)] 
  [[code](github.com/ArnaoutLabUCSF/CardioML)]
  [2023.11]

- **VFMV:** Kejun Wu, Qiong Liu, Kim-Hui Yap, and You Yang.<br />
  "High dimensional optical data — varifocal multiview imaging, compression and evaluation." Optics Express (2023).
  [[paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-24-39483&id=541443)] 
  [2023.11]

- **T-NT:** Zhenjun Yu, Wenqiang Xu, Siqiong Yao, Jieji Ren, Tutian Tang, Yutong Li, Guoying Gu, Cewu Lu.<br />
  "Precise Robotic Needle-Threading with Tactile Perception and Reinforcement Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.02396)] 
  [[code](https://sites.google.com/view/tac-needlethreading)]
  [2023.11]

- **GLaMM:** Hanoona Rasheed, Muhammad Maaz, Sahal Shaji, Abdelrahman Shaker, Salman Khan, Hisham Cholakkal, Rao M. Anwer, Erix Xing, Ming-Hsuan Yang, Fahad S. Khan.<br />
  "GLaMM: Pixel Grounding Large Multimodal Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.03356)] 
  [[code](https://mbzuai-oryx.github.io/groundingLMM)]
  [2023.11]

- **Masking:** Elias Arbash, Andréa de Lima Ribeiro, Sam Thiele, Nina Gnann, Behnood Rasti, Margret Fuchs, Pedram Ghamisi, Richard Gloaguen.<br />
  "Masking Hyperspectral Imaging Data with Pretrained Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.03053)] 
  [[code](https://github.com/hifexplo/Masking)]
  [2023.11]

- Yiran Li, Junpeng Wang, Prince Aboagye, Michael Yeh, Yan Zheng, Liang Wang, Wei Zhang, Kwan-Liu Ma.<br />
  "Visual Analytics for Efficient Image Exploration and User-Guided Image Captioning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01016)] 
  [2023.11]

- **CSF:** Shichao Dong, Fayao Liu, Guosheng Lin.<br />
  "Leveraging Large-Scale Pretrained Vision Foundation Models for Label-Efficient 3D Point Cloud Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01989)] 
  [2023.11]

- **RegionSpot:** Haosen Yang, Chuofan Ma, Bin Wen, Yi Jiang, Zehuan Yuan, Xiatian Zhu.<br />
  "Recognize Any Regions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01373)] 
  [[code](https://github.com/Surrey-UPLab/Recognize-Any-Regions)]
  [2023.11]

- **MSMedCap:** Gaoang Wang, Zhenyu Zhang, Benlu Wang, Weijie Liang, Yizhi Li, Xuechen Guo, Guanhong Wang, Shiyan Li.<br />
  "Sam-Guided Enhanced Fine-Grained Encoding with Mixed Semantic Learning for Medical Image Captioning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.01004)] 
  [2023.11]

- **MVS:** Mykhailo Shvets, Dongxu Zhao, Marc Niethammer, Roni Sengupta, Alexander C. Berg.<br />
  "Joint Depth Prediction and Semantic Segmentation with Multi-View SAM." WACV (2024).
  [[paper](https://arxiv.org/abs/2311.00134)] 
  [2023.11]

- **EditAnything:** Shanghua Gao, Zhijie Lin, Xingyu Xie, Pan Zhou, Ming-Ming Cheng, Shuicheng Yan.<br />
  "EditAnything: Empowering Unparalleled Flexibility in Image Editing and Generation." ACM  MM (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612680)] 
  [[code](https://github.com/sail-sg/EditAnything)]
  [2023.10]

- **ImEW:** ImEW: A Framework for Editing Image in the Wild.<br />
  "Tasnim Mohiuddi, Tianyi Zhang, Maowen Nie, Jing Huang, Qianqian Chen, Wei Shi." LGM3A Workshop (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3607827.3616840)] 
  [2023.10]
  
- Fen Fang, Yi Cheng, Ying Sun, Qianli Xu.<br />
  "Team I2R-VI-FF Technical Report on EPIC-KITCHENS VISOR Hand Object Segmentation Challenge 2023." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.20120)] 
  [2023.10]

- **InsDet :** Qianqian Shen, Yunhan Zhao, Nahyun Kwon, Jeeeun Kim, Yanan Li, Shu Kong.<br />
  "A High-Resolution Dataset for Instance Detection with Multi-View Instance Capture." NeurIPS Datasets and Benchmarks Track (2023).
  [[paper](https://arxiv.org/abs/2310.19257)] 
  [[code](https://github.com/insdet/instance-detection)]
  [2023.10]

- Deepa Anand, Gurunath Reddy M, Vanika Singhal, Dattesh D. Shanbhag, Shriram KS, Uday Patil, Chitresh Bhushan, Kavitha Manickam, Dawei Gui, Rakesh Mullick, Avinash Gopal, Parminder Bhatia, Taha Kass-Hout.<br />
  "One-shot Localization and Segmentation of Medical Images with Foundation Models." NeurIPS Workshop (2023).
  [[paper](https://arxiv.org/abs/2310.18642)] 
  [2023.10]

- **AVIS :** Ruohao Guo, Yaru Chen, Yanyu Qi, Wenzhen Yue, Dantong Niu, Xianghua Ying.<br />
  "Audio-Visual Instance Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.18709)] 
  [2023.10]

- **ProMISe:** Hao Li, Han Liu, Dewei Hu, Jiacheng Wang, Ipek Oguz.<br />
  "Promise:Prompt-driven 3D Medical Image Segmentation Using Image Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.19721)] 
  [[code](https://github.com/MedICL-VU/ProMISe)]
  [2023.10]

- Joana Palés Huix, Adithya Raju Ganeshan, Johan Fredin Haslum, Magnus Söderberg, Christos Matsoukas, Kevin Smith.<br />
  "Are Natural Domain Foundation Models Useful for Medical Image Classification?." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.19522)] 
  [2023.10]

- **OBM:** Kai Li, Yupeng Deng, Yunlong Kong, Diyou Liu, Jingbo Chen, Yu Meng, Junxian Ma.<br />
  "Rebuild City Buildings from Off-Nadir Aerial Images with Offset-Building Model (OBM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16717)] 
  [[code](https://github.com/likaiucas)]
  [2023.10]

- **TGVE:** Jay Zhangjie Wu, Xiuyu Li, Difei Gao, Zhen Dong, Jinbin Bai, Aishani Singh, Xiaoyu Xiang, Youzeng Li, Zuwei Huang, Yuanxi Sun, Rui He, Feng Hu, Junhua Hu, Hai Huang, Hanyu Zhu, Xu Cheng, Jie Tang, Mike Zheng Shou, Kurt Keutzer, Forrest Iandola.<br />
  "CVPR 2023 Text Guided Video Editing Competition." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16003)] 
  [[code](https://sites.google.com/view/loveucvpr23/track4)]
  [2023.10]

- **ViewControl:** Jinbin Bai, Zhen Dong, Aosong Feng, Xiao Zhang, Tian Ye, Kaicheng Zhou, Mike Zheng Shou.<br />
  "Integrating View Conditions for Image Synthesis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16002)] 
  [2023.10]
  
- **SparseDFF:** Qianxu Wang, Haotong Zhang, Congyue Deng, Yang You, Hao Dong, Yixin Zhu, Leonidas Guibas.<br />
  "SparseDFF: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16838)] 
  [2023.10]

- **SAMPOT:** Rachana Sathish, Rahul Venkataramani, K S Shriram, Prasad Sudhakar.<br />
  "Task-driven Prompt Evolution for Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.17128)] 
  [2023.10]

- **SonoSAM:** Hariharan Ravishankar, Rohan Patil, Vikram Melapudi, Parminder Bhatia, Kass-Hout Taha, Pavan Annangi.<br />
  "SonoSAM -- Segment Anything on Ultrasound Images." ASMUS (2023).
  [[paper](https://arxiv.org/abs/2310.16872)] 
  [2023.10]

- Bertrand Chauveau, Pierre Merville.<br />
  "Segment Anything by Meta as a foundation model for image segmentation: a new era for histopathological images." Pathology (2023).
  [[paper](https://www.pathologyjournal.rcpa.edu.au/article/S0031-3025(23)00242-8/fulltext)] 
  [2023.10] 
 
- **MAFT:** Siyu Jiao, Yunchao Wei, Yaowei Wang, Yao Zhao, Humphrey Shi.<br />
  "Learning Mask-aware CLIP Representations for Zero-Shot Segmentation." NeurIPS (2023).
  [[paper](https://arxiv.org/pdf/2310.00240.pdf)] 
  [[code](https://github.com/jiaosiyu1999/MAFT.git)]
  [2023.10] 

- Ardiansyah Koeshidayatullah.<br />
  "Riding the Wave: One-Touch Automatic Salt Segmentation by Coupling SAM and SegGPT ." ArXiv (2023).
  [[paper](https://onepetro.org/SPEADIP/proceedings-abstract/23ADIP/2-23ADIP/534677)] 
  [2023.10] 

- **LuGSAM:** Dhanush Babu Ramesh, Rishika Iytha Sridhar, Pulakesh Upadhyaya and Rishikesan Kamaleswaran.<br />
  "Lung Grounded-SAM (LuGSAM): A Novel Framework for Integrating Text prompts to Segment Anything Model (SAM) for Segmentation Tasks of ICU Chest X-Rays." ArXiv (2023).
  [[paper](https://www.techrxiv.org/articles/preprint/Lung_Grounded-SAM_LuGSAM_A_Novel_Framework_for_Integrating_Text_prompts_to_Segment_Anything_Model_SAM_for_Segmentation_Tasks_of_ICU_Chest_X-Rays/24224761)] 
  [2023.10] 
  
- **Zero123++:** Ruoxi Shi, Hansheng Chen, Zhuoyang Zhang, Minghua Liu, Chao Xu, Xinyue Wei, Linghao Chen, Chong Zeng, Hao Su.<br />
  "Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15110)] 
  [[code](https://github.com/SUDO-AI-3D/zero123plus)]
  [2023.10] 

- **ConceptFusion:** Krishna Murthy Jatavallabhula, Alihusein Kuwajerwala, Qiao Gu, Mohd Omama, Tao Chen, Alaa Maalouf, Shuang Li, Ganesh Iyer, Soroush Saryazdi, Nikhil Keetha, Ayush Tewari, Joshua B. Tenenbaum, Celso Miguel de Melo, Madhava Krishna, Liam Paull, Florian Shkurti, Antonio Torralba.<br />
  "ConceptFusion: Open-set Multimodal 3D Mapping." RSS (2023).
  [[paper](https://arxiv.org/abs/2302.07241)] 
  [[code](https://github.com/concept-fusion/concept-fusion)]
  [2023.10] 
  
- **CryoSegNet:** Rajan Gyawali, Ashwin Dhakal, Liguo Wang, Jianlin Cheng.<br />
  "Accurate cryo-EM protein particle picking by integrating the foundational AI image segmentation model and specialized U-Net." ArXiv (2023).
  [[paper](https://www.biorxiv.org/content/10.1101/2023.10.02.560572v1.abstract)] 
  [2023.10] 
  
- **CISRU:** Silvia Romero-Azpitartea, Cristina Lunaa, Alba Guerraa, Mercedes Alonsoa, Pablo Romeo Manriquea, Marina L. Seoanea, Daniel Olayoa, Almudena Morenoa, Pablo Castellanosa, Fernando Gandíaa, Gianfranco Visentinb.<br />
  "Enabling In-Situ Resources Utilisation by leveraging collaborative robotics and astronaut-robot interaction." IAC (2023).
  [[paper](https://www.researchgate.net/profile/Cristina-Luna-10/publication/374451757_Enabling_In-Situ_Resources_Utilisation_by_leveraging_collaborative_robotics_and_astronaut-robot_interaction/links/651eb2bdd717ef1293cedaa1/Enabling-In-Situ-Resources-Utilisation-by-leveraging-collaborative-robotics-and-astronaut-robot-interaction.pdf)] 
  [2023.10] 
  
- **DiffPrompter:** Sanket Kalwar, Mihir Ungarala, Shruti Jain, Aaron Monis, Krishna Reddy Konda, Sourav Garg, K Madhava Krishna.<br />
  "DiffPrompter: Differentiable Implicit Visual Prompts for Semantic-Segmentation in Adverse Conditions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04181)] 
  [[code](https://diffprompter.github.io/)]
  [2023.10] 

- Alessandro Saviolo, Pratyaksh Rao, Vivek Radhakrishnan, Jiuhong Xiao, Giuseppe Loianno.<br />
  "Unifying Foundation Models with Quadrotor Control for Visual Tracking Beyond Object Categories." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04781)] 
  [2023.10] 

- Ruoqing Zhao, Xi Wang, Hongliang Dai, Pan Gao, Piji Li.<br />
  "Medical Report Generation Based on Segment-Enhanced Contrastive Representation Learning." NLPCC (2023).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-44696-2_65)] 
  [2023.10] 

- Robin Karlsson, Francisco Lepe-Salazar, Kazuya Takeda.<br />
  "Compositional Semantics for Open Vocabulary Spatio-semantic Representations." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04981)] 
  [2023.10] 
 
- **InstructDET :** Ronghao Dang, Jiangyan Feng, Haodong Zhang, Chongjian Ge, Lin Song, Lijun Gong, Chengju Liu, Qijun Chen, Feng Zhu, Rui Zhao, Yibing Song.<br />
  "InstructDET: Diversifying Referring Object Detection with Generalized Instructions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.05136)] 
  [[code](https://github.com/jyFengGoGo/InstructDet)]
  [2023.10] 

- **HICOME:** Peng Zheng.<br />
  "Discriminative Consensus Mining with A Thousand Group for More Accurate Co-Salient Object Detection." ArXiv (2023).
  [[paper](https://aaltodoc.aalto.fi/handle/123456789/124134)] 
  [[code](https://github.com/ZhengPeng7/CoSINe)]
  [2023.10] 

- **Ferret:** Haoxuan You, Haotian Zhang, Zhe Gan, Xianzhi Du, Bowen Zhang, Zirui Wang, Liangliang Cao, Shih-Fu Chang, Yinfei Yang.<br />
  "." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.07704)] 
  [[code](https://github.com/apple/ml-ferret)]
  [2023.10] 

- **OVTracktor:** Wen-Hsuan Chu, Adam W. Harley, Pavel Tokmakov, Achal Dave, Leonidas Guibas, Katerina Fragkiadaki.<br />
  "Zero-Shot Open-Vocabulary Tracking with Large Pre-Trained Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06992)] 
  [[code](https://wenhsuanchu.github.io/ovtracktor/)]
  [2023.10] 

- **OpenAnnotate3D:** Yijie Zhou, Likun Cai, Xianhui Cheng, Zhongxue Gan, Xiangyang Xue, Wenchao Ding.<br />
  "OpenAnnotate3D: Open-Vocabulary Auto-Labeling System for Multi-modal 3D Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13398)] 
  [[code](https://github.com/Fudan-ProjectTitan/OpenAnnotate3D)]
  [2023.10] 

- **SSC:** Francisco Eiras, Kemal Oksuz, Adel Bibi, Philip H.S. Torr, Puneet K. Dokania.<br />
  "Segment, Select, Correct: A Framework for Weakly-Supervised Referring Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13479)] 
  [[code](https://github.com/fgirbal/segment-select-correct)]
  [2023.10] 

- Shichang Liu, Junxin Chen, Ben-Guo He, Tao Chen, Gwanggil Jeon, Wei Wang.<br />
  "Adapting Segment Anything Model for Shield Tunnel Water Leakage Segmentation." AMC-SME Workshop (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3606042.3616453)] 
  [2023.10] 

- Sofia H. Gelado, César Quilodrán-Casas, Loïc Chagot.<br />
  "Enhancing Microdroplet Image Analysis with Deep Learning." Micromachines (2023).
  [[paper](https://www.mdpi.com/2072-666X/14/10/1964)] 
  [2023.10] 
  
- **EdgeCalib:** Xingchen Li, Yifan Duan, Beibei Wang, Haojie Ren, Guoliang You, Yu Sheng, Jianmin Ji, Yanyong Zhang.<br />
  "EdgeCalib: Multi-Frame Weighted Edge Features for Automatic Targetless LiDAR-Camera Calibration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.16629)]
  [2023.10]   

- **Open-NeRF:** Hao Zhang, Fang Li, Narendra Ahuja.<br />
  "Open-NeRF: Towards Open Vocabulary NeRF Decomposition." WACV (2024).
  [[paper](https://arxiv.org/abs/2310.16383)] 
  [2023.10] 

- **SAM-CLIP:** Haoxiang Wang, Pavan Kumar Anasosalu Vasu, Fartash Faghri, Raviteja Vemulapalli, Mehrdad Farajtabar, Sachin Mehta, Mohammad Rastegari, Oncel Tuzel, Hadi Pouransari.<br />
  "SAM-CLIP: Merging Vision Foundation Models towards Semantic and Spatial Understanding." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15308)] 
  [2023.10] 

- **SAM-Med3D:** Haoyu Wang, Sizheng Guo, Jin Ye, Zhongying Deng, Junlong Cheng, Tianbin Li, Jianpin Chen, Yanzhou Su, Ziyan Huang, Yiqing Shen, Bin Fu, Shaoting Zhang, Junjun He, Yu Qiao.<br />
  "SAM-Med3D." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.15161)] 
  [[code](https://github.com/uni-medical/SAM-Med3D)]
  [2023.10] 

- **SAMCLR:** Benjamin Missaoui, Chongbin Yuan.<br />
  "SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.14736)] 
  [2023.10] 

- Zhaozheng Chen, Qianru Sun.<br />
  "Weakly-Supervised Semantic Segmentation with Image-Level Labels: from Traditional Models to Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.13026)] 
  [2023.10] 

- Sumit Pandey, Kuan-Fu Chen, Erik B. Dam.<br />
  "Comprehensive Multimodal Segmentation in Medical Imaging: Combining YOLOv8 with SAM and HQ-SAM Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.12995)] 
  [2023.10] 

- **Mammo-SAM:** Xinyu Xiong, Churan Wang, Wenxue Li, Guanbin Li.<br />
  "Mammo-SAM: Adapting Foundation Segment Anything Model for Automatic Breast Mass Segmentation in Whole Mammograms." ResearchGate (2023).
  [[paper](https://www.researchgate.net/publication/374739539_Mammo-SAM_Adapting_Foundation_Segment_Anything_Model_for_Automatic_Breast_Mass_Segmentation_in_Whole_Mammograms)] 
  [2023.10] 

- Dongshen Han, Sheng Zheng, Chaoning Zhang.<br />
  "Segment Anything Meets Universal Adversarial Perturbation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.12431)] 
  [2023.10] 

- **SoM-GPT4V:** Jianwei Yang, Hao Zhang, Feng Li, Xueyan Zou, Chunyuan Li, Jianfeng Gao.<br />
  "Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.11441)] 
  [[homepage](https://som-gpt4v.github.io/)]
  [[code](https://github.com/microsoft/SoM)]
  [2023.10] 

- **IPSeg:** Lv Tang, Peng-Tao Jiang, Hao-Ke Xiao, Bo Li.<br />
  "Towards Training-free Open-world Segmentation via Image Prompting Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10912)] 
  [2023.10] 

- **SAM_Interactive_Histopathology:** SeungKyu Kim, Hyun-Jic Oh, Seonghui Min, Won-Ki Jeong.<br />
  "Evaluation and improvement of Segment Anything Model for interactive histopathology image segmentation." MICCAI Workshop (2023).
  [[paper](https://arxiv.org/abs/2310.10493)] 
  [[code](https://github.com/hvcl/SAM_Interactive_Histopathology)]
  [2023.10] 

- Yao Qianxiang, Bin Jiang.<br />
  "Recursive Segmentation Living Image: An eXplainable AI (XAI) Approach for Computing Structural Beauty of Images or the Livingness of Space." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10149)] 
  [2023.10] 

- Sheng Zheng, Chaoning Zhang.<br />
  "Black-box Targeted Adversarial Attack on Segment Anything (SAM)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.10010)] 
  [2023.10] 

- Jiahao Xia, Gavin Gong 2, Jiawei Liu, Zhigang Zhu, Hao Tang.<br />
  "Segment Anything Model for Pedestrian Infrastructure Inventory: Assessing Zero-Shot Segmentation on Multi-Mode Geospatial Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09918)] 
  [2023.10] 

- **PUCD :** Youngtack Oh, Minseok Seo, Doyi Ki, Junghoon Seo.<br />
  "Prototype-oriented Unsupervised Change Detection for Disaster Management." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09759)] 
  [2023.10] 

- **SAM-guided UDA:** Xidong Peng, Runnan Chen, Feng Qiao, Lingdong Kong, Youquan Liu, Tai Wang, Xinge Zhu, Yuexin Ma.<br />
  "SAM-guided Unsupervised Domain Adaptation for 3D Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08820)] 
  [2023.10] 

- **SemCom:** Avi Deb Raha, Md. Shirajum Munir, Apurba Adhikary, Yu Qiao, Choong Seon Hong.<br />
  "Generative AI-driven Semantic Communication Framework for NextG Wireless Network." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.09021)] 
  [2023.10] 

- Christian A. Schiller.<br />
  "Virtual Augmented Reality for Atari Reinforcement Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08683)]
  [2023.10]   

- **MCREA:** Xu Chen, Yunde Jia, Yuwei Wu.<br />
  "Fine-Grained Annotation for Face Anti-Spoofing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.08142)] 
  [2023.10] 

- **SAM-OCTA:** Xinrun Chen, Chengliang Wang, Haojian Ning, Shiying Li.<br />
  "SAM-OCTA: Prompting Segment-Anything for OCTA Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.07183)] 
  [[code](https://github.com/ShellRedia/SAM-OCTA)]
  [2023.10] 

- **MED:** Haijie Ren, Weiqiang Wang, Wentao Tang, Rui Zhang.<br />
  "Machine Eye for Defects: Machine Learning-Based Solution to Identify and Characterize Topological Defects in Textured Images of Nematic Materials." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06406)] 
  [2023.10] 

- Mohammad Peivandi, Jason Zhang, Michael Lu, Dongxiao Zhu, Zhifeng Kou.<br />
  "Empirical Evaluation of the Segment Anything Model (SAM) for Brain Tumor Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.06162)] 
  [2023.10] 

- **Tree-GPT:** Siqi Du, Shengjun Tang, Weixi Wang, Xiaoming Li, Renzhong Guo.<br />
  "Tree-GPT: Modular Large Language Model Expert System for Forest Remote Sensing Image Understanding and Interactive Analysis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04698)] 
  [2023.10] 

- **TiC:** Song Zhang, Qingzhong Wang, Jiang Bian, Haoyi Xiong.<br />
  "TiC: Exploring Vision Transformer in Convolution." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.04134)] 
  [[code](https://github.com/zs670980918/MSA-Conv)]
  [2023.10] 

- **SLP:** David Balaban, Justin Medich, Pranay Gosar, Justin Hart.<br />
  "Propagating Semantic Labels in Video Data." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.00783)] 
  [[homepage](https://dataverse.tdl.org/dataverse/robotics)]
  [2023.10] 

- Amin Ranem, Niklas Babendererde, Moritz Fuchs, Anirban Mukhopadhyay.<br />
  "Exploring SAM Ablations for Enhancing Medical Segmentation in Radiology and Pathology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.00504)] 
  [2023.10] 

- Xiangru Li, Yifei Zhang, Liang Zhao.<br />
  "Multi-Prompt Fine-Tuning of Foundation Models for Enhanced Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.02381)] 
  [2023.10] 

- Ali Mayladan, Hasan Nasrallah, Hasan Moughnieh, Mustafa Shukor, Ali J. Ghandour.<br />
  "Zero-Shot Refinement of Buildings' Segmentation Models using SAM." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2310.01845)] 
  [2023.10] 

- **GroupPrompter:** Yichuang Luo, Fang Wang, Jing Xing, Xiaohu Liu.<br />
  "GroupPrompter: A Prompting Method for Semantic Segmentation Based on SAM." IEEE Access  (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10265054)] 
  [2023.09] 
  
- **GAVS:** Yaoting Wang, Weisong Liu, Guangyao Li, Jian Ding, Di Hu, Xi Li.<br />
  "Prompting Segmentation with Sound is Generalizable Audio-Visual Source LocalizerPrompting Segmentation with Sound is Generalizable Audio-Visual Source Localizer." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.07929)] 
  [2023.09] 

- Raha, Avi Deb and Adhikary, Apurba and Munir, Md. Shirajum and Qiao, Yu and Hong, Choong Seon.<br />
  "Segment Anything Model Aided Beam Prediction for the Millimeter Wave Communication." APNOMS (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10258199)] 
  [2023.09]
  
- **PVLFF:** Haoran Chen, Kenneth Blomqvist, Francesco Milano, Roland Siegwart.<br />
  "Panoptic Vision-Language Feature Fields." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.05448)] 
  [[code](https://github.com/ethz-asl/autolabel)]
  [2023.09] 

- **SAMStyler:** Psychogyios, Konstantinos and Leligou, Helen C. and Melissari, Filisia and Bourou, Stavroula and Anastasakis, Zacharias and Zahariadis, Theodore.<br />
  "SAMStyler: Enhancing Visual Creativity With Neural Style Transfer and Segment Anything Model (SAM)." IEEE Access (2023).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10250775)]
  [2023.09]   
 
- Aneesh Rangnekar, Jue Jiang, Harini Veeraraghavan.<br />
  "3D Swin Transformer for Partial Medical Auto Segmentation." MICCAI-FLARE (2023).
  [[paper](https://openreview.net/forum?id=IlQQU5Pp5p)] 
  [2023.09] 

- **ASA:** Yaqin Li, Dandan Wang, Cao Yuan, Hao Li, Jing Hu.<br />
  "Enhancing Agricultural Image Segmentation with an Agricultural Segment Anything Model Adapter." Sensors (2023).
  [[paper](https://www.mdpi.com/1424-8220/23/18/7884)] 
  [2023.09] 



- **SCROD:** Valentyn Boreiko, Matthias Hein, Jan Hendrik Metzen.<br />
  "Identifying Systematic Errors in Object Detectors with the SCROD Pipeline." ICCV Workshop (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023W/BRAVO/html/Boreiko_Identifying_Systematic_Errors_in_Object_Detectors_with_the_SCROD_Pipeline_ICCVW_2023_paper.html)] 
  [2023.09] 

- Iraklis Giannakis, Anshuman Bhardwaj, Lydia Sam, Georgios Leontidis.<br />
  "A flexible deep learning crater detection scheme using Segment Anything Model (SAM)." ICARUS (2023).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0019103523003755)] 
  [2023.09] 
  
- **SuPerPM:** Shan Lin, Albert J. Miao, Ali Alabiad, Fei Liu, Kaiyuan Wang, Jingpei Lu, Florian Richter, Michael C. Yip.<br />
  "SuPerPM: A Large Deformation-Robust Surgical Perception Framework Based on Deep Point Matching Learned from Physical Constrained Simulation Data" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.13863)] 
  [2023.09] 
  
- **Bi-SAM:** Ying Zhao, Kechen Song, Wenqi Cui, Hang Ren, Yunhui Yan.<br />
  "MFS enhanced SAM: Achieving superior performance in bimodal few-shot segmentation." JVCIR (2023).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1047320323001967)] 
  [[code](https://github.com/VDT-2048/Bi-SAM)]
  [2023.09] 

- **BaDLAD:** Kazi Reyazul Hasan, Mubasshira Musarrat, Sadif Ahmed, Shahriar Raj.<br />
  "Framework and Model Analysis on Bengali Document Layout Analysis Dataset: BaDLAD." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16700)] 
  [2023.09] 

- **SAM-Adapter:** Tianrun Chen, Lanyun Zhu, Chaotao Deng, Runlong Cao, Yan Wang, Shangzhan Zhang, Zejian Li, Lingyun Sun, Ying Zang, Papa Mao.<br />
  "SAM-Adapter: Adapting Segment Anything in Underperformed Scenes." ICCV Workshop (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Chen_SAM-Adapter_Adapting_Segment_Anything_in_Underperformed_Scenes_ICCVW_2023_paper.html)] 
  [[code](http://research.kokoni3d.com/sam-adapter)]
  [2023.09] 

- **UniQuadric:** Linghao Yang, Yanmin Wu, Yu Deng, Rui Tian, Xinggang Hu, Tiefeng Ma.<br />
  "UniQuadric: A SLAM Backend for Unknown Rigid Object 3D Tracking and Light-Weight Modeling." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.17036)] 
  [2023.09] 

- **SAMFeat:**  Jingqian Wu, Rongtao Xu, Zach Wood-Doughty, Changwei Wang.<br />
  "Segment Anything Model is a Good Teacher for Local Feature Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16992)] 
  [[code](https://github.com/vignywang/SAMFeat)]
  [2023.09] 

- **nnSAM:** Yunxiang Li, Bowen Jing, Xiang Feng, Zihan Li, Yongbo He, Jing Wang, You Zhang.<br />
  "nnSAM: Plug-and-play Segment Anything Model Improves nnUNet Performance." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.16967)] 
  [[code](https://github.com/Kent0n-Li/Medical-Image-Segmentation)]
  [2023.09] 

- Mayara E. Bonani, Max Schwarz, Sven Behnke.<br />
  "Learning from SAM: Harnessing a Segmentation Foundation Model for Sim2Real Domain Adaptation through Regularization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.15562)] 
  [2023.09] 


- Khoa Dang Nguyen, Thanh-Hai Phung, Hoang-Giang Cao.<br />
  "A SAM-based Solution for Hierarchical Panoptic Segmentation of Crops and Weeds Competition." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2309.13578)] 
  [2023.09] 
  
- **MediViSTA-SAM:** Sekeun Kim, Kyungsang Kim, Jiang Hu, Cheng Chen, Zhiliang Lyu, Ren Hui, Sunghwan Kim, Zhengliang Liu, Aoxiao Zhong, Xiang Li, Tianming Liu, Quanzheng Li.<br />
  "MediViSTA-SAM: Zero-shot Medical Video Analysis with Spatio-temporal SAM Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.13539)] 
  [[code](https://github.com/kimsekeun/MediViSTA-SAM)]
  [2023.09] 

- **PointSSC:** Yuxiang Yan, Boda Liu, Jianfei Ai, Qinbu Li, Ru Wan, Jian Pu.<br />
  "PointSSC: A Cooperative Vehicle-Infrastructure Point Cloud Benchmark for Semantic Scene Completion." ICRA (2024).
  [[paper](https://arxiv.org/abs/2309.12708)] 
  [2023.09] 
  
- **NOC:** Xiaobao Wei, Renrui Zhang, Jiarui Wu, Jiaming Liu, Ming Lu, Yandong Guo, Shanghang Zhang.<br />
  "NOC: High-Quality Neural Object Cloning with 3D Lifting of Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.12790)] 
  [2023.09] 
  
- **SAM-OCTA:** Chengliang Wang, Xinrun Chen, Haojian Ning, Shiying Li.<br />
  "SAM-OCTA: A Fine-Tuning Strategy for Applying Foundation Model to OCTA Image Segmentation Tasks." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11758)] 
  [[code](https://github.com/ShellRedia/SAM-OCTA)]
  [2023.09] 

- **MoPA:**  Haozhi Cao, Yuecong Xu, Jianfei Yang, Pengyu Yin, Shenghai Yuan, Lihua Xie.<br />
  "MoPA: Multi-Modal Prior Aided Domain Adaptation for 3D Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11839)] 
  [[code](https://github.com/AronCao49/MoPA)]
  [2023.09] 

- **Deshadow-Anything:** Xiao Feng Zhang, Tian Yi Song, Jia Wei Yao.<br />
  "Deshadow-Anything: When Segment Anything Model Meets Zero-shot shadow removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11715)] 
  [2023.09] 

- **3D-U-SAM:** Yifu Zhang, Zuozhu Liu, Yang Feng, Renjing Xu.<br />
  "3D-U-SAM Network For Few-shot Tooth Segmentation in CBCT Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.11015)] 
  [2023.09] 

- **OCTA-FRNet:** Haojian Ning, Chengliang Wang, Xinrun Chen, Shiying Li.<br />
  "An Accurate and Efficient Neural Network for OCTA Vessel Segmentation and a New Dataset." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.09483)] 
  [[code](https://github.com/nhjydywd/OCTA-FRNet)]
  [2023.09] 

- **MA-SAM:** Cheng Chen, Juzheng Miao, Dufan Wu, Zhiling Yan, Sekeun Kim, Jiang Hu, Aoxiao Zhong, Zhengliang Liu, Lichao Sun, Xiang Li, Tianming Liu, Pheng-Ann Heng, Quanzheng Li.<br />
  "MA-SAM: Modality-agnostic SAM Adaptation for 3D Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.08842)] 
  [[code](https://github.com/cchen-cc/MA-SAM)]
  [2023.09] 

- **samgeo:** Qiusheng Wu and Lucas Prado Osco.<br />
  "samgeo: A Python package for segmenting geospatial data with the Segment Anything Model (SAM)." JOSS (2023).
  [[paper](https://joss.theoj.org/papers/10.21105/joss.05663)] 
  [[code](https://github.com/opengeos/segment-geospatial)]
  [2023.09] 

- Peng Zhang, Yaping Wang.<br />
  "Segment Anything Model for Brain Tumor Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.08434)] 
  [2023.09] 


- **SAMUS:** Xian Lin, Yangyang Xiang, Li Zhang, Xin Yang, Zengqiang Yan, Li Yu.<br />
  "SAMUS: Adapting Segment Anything Model for Clinically-Friendly and Generalizable Ultrasound Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.06824)] 
  [[code](https://github.com/xianlin7/SAMUS)]
  [2023.09] 
  
- **CMSF:** Swapnil Bhosale, Haosen Yang, Diptesh Kanojia, Xiatian Zhu.<br />
  "Leveraging Foundation models for Unsupervised Audio-Visual Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.06728)] 
  [2023.09] 

- Xiaodan Xing, Chunling Tang, Yunzhe Guo, Nicholas Kurniawan, Guang Yang.<br />
  "SegmentAnything helps microscopy images based automatic and quantitative organoid detection and analysis." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.04190)] 
  [2023.09]

- Chenbin Liu, Zhengliang Liu, Jason Holmes, Lu Zhang, Lian Zhang, Yuzhen Ding, Peng Shu, Zihao Wu, Haixing Dai, Yiwei Li, Dinggang Shen, Ninghao Liu, Quanzheng Li, Xiang Li, Dajiang Zhu, Tianming Liu, Wei Liu.<br />
  "Artificial General Intelligence for Radiation Oncology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.02590)] 
  [2023.09]

- **DEVA:** Ho Kei Cheng, Seoung Wug Oh, Brian Price, Alexander Schwing, Joon-Young Lee.<br />
  "Tracking Anything with Decoupled Video Segmentation." ICCV (2023).
  [[paper](https://arxiv.org/abs/2309.03903)] 
  [[project page](https://hkchengrex.com/Tracking-Anything-with-DEVA/)]
  [[code](https://github.com/hkchengrex/Tracking-Anything-with-DEVA)]
  [2023.09] 

- **SAM3D:** Nhat-Tan Bui, Dinh-Hieu Hoang, Minh-Triet Tran, Ngan Le.<br />
  "SAM3D: Segment Anything Model in Volumetric Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.03493)] 
  [2023.09] 

- **CropFormer:** Lu Qi, Jason Kuen, Weidong Guo, Tiancheng Shen, Jiuxiang Gu, Jiaya Jia, Zhe Lin, Ming-Hsuan Yang.<br />
  "High-Quality Entity Segmentation." ICCV (2023).
  [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Qi_High_Quality_Entity_Segmentation_ICCV_2023_paper.html)] 
  [[project page](https://github.com/qqlu/Entity/tree/main/Entityv2)]
  [[code](https://github.com/qqlu/Entity/blob/main/Entityv2/README.md)]
  [[中文解读](https://mp.weixin.qq.com/s/wa_AfAM4xRb1tX3vyU7a6w)]
  [2023.09] 

- **CIP-WPIS:** Qingtao Yu, Heming Du, Chen Liu, Xin Yu.<br />
  "When 3D Bounding-Box Meets SAM: Point Cloud Instance Segmentation with Weak-and-Noisy Supervision." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.00828)] 
  [2023.09] 

- **SAM-Deblur:** Siwei Li, Mingxuan Liu, Yating Zhang, Shu Chen, Haoxiang Li, Hong Chen, Zifei Dou.<br />
  "SAM-Deblur: Let Segment Anything Boost Image Deblurring." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.02270)] 
  [[code](https://github.com/HPLQAQ/SAM-Deblur)]
  [2023.09] 

- Hassan El-Hajj, Matteo Valleriani.<br />
  "Prompt me a Dataset: An investigation of text-image prompting for historical image dataset creation using foundation models." ICIAP  (2023), AI4DH workshop.
  [[paper](https://arxiv.org/abs/2309.01674)] 
  [2023.09] 

- **SAM-CD:** Lei Ding, Kun Zhu, Daifeng Peng, Hao Tang, Haitao Guo.<br />
  "Adapting Segment Anything Model for Change Detection in HR Remote Sensing Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2309.01429)] 
  [2023.09] 

- **SAM-LIV:** Junyao Shi, Jianing Qian, Yecheng Jason Ma, Dinesh Jayaraman.<br />
  "Plug-And-Play Object-Centric Representations From “What” and “Where” Foundation Models." ArXiv (2023).
  [[paper](https://mit-spark.github.io/robotRepresentations-RSS2023/assets/papers/17.pdf)]
  [2023.08]   

- **UGainS:** Alexey Nekrasov, Alexander Hermans, Lars Kuhnert, Bastian Leibe.<br />
  "UGainS: Uncertainty Guided Anomaly Instance Segmentation." GCPR (2023).
  [[paper](https://arxiv.org/abs/2308.02046)] 
  [[code](https://vision.rwth-aachen.de/ugains)]
  [2023.08] 
  
- Chaoqin Huang, Aofan Jiang, Ya Zhang, Yanfeng Wang.<br />
  "Multi-Scale Memory Comparison for Zero-/Few-Shot Anomaly Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.04789)] 
  [2023.08] 

- Dwith Chenna, Suyash Bhogawar.<br />
  "Segment Anything Model (SAM) For Brain Extraction in fMRI Studies." IJAIMED (2023).
  [[paper](https://www.researchgate.net/profile/Yn-Dwith-Chenna/publication/373013991_Segment_Anything_Model_SAM_For_Brain_Extraction_in_fMRI_Studies/links/64d40025c80b930269fb88cb/Segment-Anything-Model-SAM-For-Brain-Extraction-in-fMRI-Studies.pdf)] 
  [2023.08] 

- **OSTRA :** Jiexiong Xu, Weikun Zhao, Zhiyan Tang, Xiangchao Gan.<br />
  "A One Stop 3D Target Reconstruction and multilevel Segmentation Method." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06974)] 
  [[code](https://github.com/ganlab/OSTRA)]
  [2023.08] 

- **ROSGPT_Vision:** Bilel Benjdira, Anis Koubaa, Anas M. Ali.<br />
  "ROSGPT_Vision: Commanding Robots Using Only Language Models' Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.11236)] 
  [[code](https://github.com/bilel-bj/ROSGPT_Vision)]
  [2023.08] 

- **CoDeF:** Hao Ouyang, Qiuyu Wang, Yuxi Xiao, Qingyan Bai, Juntao Zhang, Kecheng Zheng, Xiaowei Zhou, Qifeng Chen, Yujun Shen.<br />
  "CoDeF: Content Deformation Fields for Temporally Consistent Video Processing." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.07926)] 
  [[code](https://qiuyu96.github.io/CoDeF/)]
  [2023.08] 

- **WALL-E:** Tianyu Wang, Yifan Li, Haitao Lin, Xiangyang Xue, Yanwei Fu.<br />
  "WALL-E: Embodied Robotic WAiter Load Lifting with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.15962)] 
  [[code](https://star-uu-wang.github.io/WALL-E/)]
  [2023.08] 

- **Ref-Diff:** Minheng Ni, Yabo Zhang, Kailai Feng, Xiaoming Li, Yiwen Guo, Wangmeng Zuo.<br />
  "Ref-Diff: Zero-shot Referring Image Segmentation with Generative Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16777)] 
  [[code](https://github.com/kodenii/Ref-Diff)]
  [2023.08] 

- Anwai Archit, Sushmita Nair, Nabeel Khalid, Paul Hilt, Vikas Rajashekar, Marei Freitag, Sagnik Gupta, Andreas Dengel, Sheraz Ahmed, Constantin Pape.<br />
  "Segment Anything for Microscopy." ResearchGate (2023).
  [[paper](https://www.biorxiv.org/content/10.1101/2023.08.21.554208v1.full.pdf)] 
  [2023.08] 
  

- Su Myat Noe.<br />
  "Efficient Segment-Anything Model for Automatic Mask Region Extraction in Livestock Monitoring." IEEE ICCT(2023).
  [[paper](https://www.researchgate.net/publication/373265261_Efficient_Segment-Anything_Model_for_Automatic_Mask_Region_Extraction_in_Livestock_Monitoring)] 
  [2023.08] 

- **SSM-SAM:** Yiming Zhang, Tianang Leng, Kun Han, Xiaohui Xie.<br />
  "Self-Sampling Meta SAM: Enhancing Few-shot Medical Image Segmentation with Meta-Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16466)] 
  [2023.08] 

- **SAM-Med2D:** Junlong Cheng, Jin Ye, Zhongying Deng, Jianpin Chen, Tianbin Li, Haoyu Wang, Yanzhou Su, Ziyan Huang, Jilong Chen, Lei Jiang, Hui Sun, Junjun He, Shaoting Zhang, Min Zhu, Yu Qiao.<br />
  "SAM-Med2D." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16184)] 
  [[code](https://github.com/uni-medical/SAM-Med2D)]
  [2023.08] 

- **AutoSAM Adapter:** Chengyin Li, Prashant Khanduri, Yao Qiang, Rafi Ibn Sultan, Indrin Chetty, Dongxiao Zhu.<br />
  "Auto-Prompting SAM for Mobile Friendly 3D Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.14936)] 
  [2023.08] 

- Leo Fillioux, Emilie Gontran, Jérôme Cartry, Jacques RR Mathieu, Sabrina Bedja, Alice Boilève, Paul-Henry Cournède, Fanny Jaulin, Stergios Christodoulidis, Maria Vakalopoulou.<br />
  "Spatio-Temporal Analysis of Patient-Derived Organoid Videos Using Deep Learning for the Prediction of Drug Efficacy." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.14461)] 
  [2023.08] 

- **SAM-PARSER:** Zelin Peng, Zhengqin Xu, Zhilin Zeng, Xiaokang Yang, Wei Shen.<br />
  "SAM-PARSER: Fine-tuning SAM Efficiently by Parameter Space Reconstruction." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.14604)] 
  [2023.08] 

- Weijia Feng, Lingting Zhu, Lequan Yu.<br />
  "Cheap Lunch for Medical Image Segmentation by Fine-tuning SAM on Few Exemplars." MICCAI BrainLes Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.14133)] 
  [2023.08] 
 

- Zihan Dong, ZhengDong Zhang.<br />
  "Enhancing Bloodstain Analysis Through AI-Based Segmentation: Leveraging Segment Anything Model for Crime Scene Investigation." KDD Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.13979)] 
  [[code](https://github.com/Zdong104/Bloodstain_Analysis_Ai_Tool)]
  [2023.08] 

- **SCESAME:** Hiroaki Yamagiwa, Yusuke Takase, Hiroyuki Kambe, Ryosuke Nakamoto.<br />
  "Zero-Shot Edge Detection with SCESAME: Spectral Clustering-based Ensemble for Segment Anything Model Estimation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.13779)] 
  [2023.08] 

- **SamDSK:** Yizhe Zhang, Tao Zhou, Shuo Wang, Ye Wu, Pengfei Gu, Danny Z. Chen.<br />
  "SamDSK: Combining Segment Anything Model with Domain-Specific Knowledge for Semi-Supervised Learning in Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.13759)] 
  [[code](https://github.com/yizhezhang2000/SamDSK)]
  [2023.08] 

- **RSISeg:** Zhe Wang, Shoukun Sun, Xiang Que, Xiaogang Ma.<br />
  "Interactive segmentation in aerial images: a new benchmark and an open access web-based tool." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.13174)] 
  [2023.08] 


- **DiffSeg:** Junjiao Tian, Lavisha Aggarwal, Andrea Colaco, Zsolt Kira, Mar Gonzalez-Franco.<br />
  "Diffuse, Attend, and Segment: Unsupervised Zero-Shot Segmentation using Stable Diffusion." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.12469)] 
  [2023.08]

- **SPPNet:** Qing Xu, Wenwei Kuang, Zeyu Zhang, Xueyao Bao, Haoran Chen, Wenting Duan.<br />
  "SPPNet: A Single-Point Prompt Network for Nuclei Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.12231)] 
  [[code](https://github.com/xq141839/SPPNet)]
  [2023.08]

- **SAMSNeRF:** Ange Lou, Yamin Li, Xing Yao, Yike Zhang, Jack Noble.<br />
  "SAMSNeRF: Segment Anything Model (SAM) Guides Dynamic Surgical Scene Reconstruction by Neural Radiance Field (NeRF)." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.11774)] 
  [[code](https://github.com/AngeLouCN/SAMSNeRF)]

- **SS2V:** Xing Yao, Han Liu, Dewei Hu, Daiwei Lu, Ange Lou, Hao Li, Ruining Deng, Gabriel Arenas, Baris Oguz, Nadav Schwartz, Brett C Byram, Ipek Oguz.<br />
  "False Negative/Positive Control for SAM on Noisy Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.10382)] 
  [[code](https://github.com/xyimaging/FNPC)]
  [2023.08]

- **SurgicalSAM:** Wenxi Yue, Jing Zhang, Kun Hu, Yong Xia, Jiebo Luo, Zhiyong Wang.<br />
  "SurgicalSAM: Efficient Class Promptable Surgical Instrument Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.08746)] 
  [[code](https://github.com/wenxi-yue/SurgicalSAM)]
  [2023.08]

- **SAMedOCT:** Botond Fazekas, José Morano, Dmitrii Lachinov, Guilherme Aresta, Hrvoje Bogunović.<br />
  "SAMedOCT: Adapting Segment Anything Model (SAM) for Retinal OCT." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.09331)] 
  [2023.08]

- **U-SAM:** Hantao Zhang, Weidong Guo, Chenyang Qiu, Shouhong Wan, Bingbing Zou, Wanqin Wang, Peiquan Jin.<br />
  "CARE: A Large Scale CT Image Dataset and Clinical Applicable Benchmark Model for Rectal Cancer Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.08283)] 
  [2023.08]

- **Few-Shot-Self-Prompt-SAM:** Qi Wu, Yuyao Zhang, Marawan Elbatel.<br />
  "Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation." MICCAI DART Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.07624)] 
  [[code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]
  [2023.08]

- **Dancing Avatar:** Bosheng Qin, Wentao Ye, Qifan Yu, Siliang Tang, Yueting Zhuang.<br />
  "Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.07749)] 
  [2023.08]

- **SurgicalSAM:** An Wang, Mobarakol Islam, Mengya Xu, Yang Zhang, Hongliang Ren.<br />
  "SAM Meets Robotic Surgery: An Empirical Study on Generalization, Robustness and Adaptation." MICCAI MedAGI Workshop (2023).
  [[paper](https://arxiv.org/abs/2308.07156)] 
  [2023.08]

- **OSTRA:** Jiexiong Xu, Weikun Zhao, Zhiyan Tang, Xiangchao Gan.<br />
  "A One Stop 3D Target Reconstruction and multilevel Segmentation Method." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06974)] 
  [[code](https://github.com/ganlab/OSTRA)]
  [2023.08]

- **CEmb-SAM:** Dongik Shin, Beomsuk Kim, Seungjun Baek.<br />
  "CEmb-SAM: Segment Anything Model with Condition Embedding for Joint Learning from Heterogeneous Datasets." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06957)] 
  [2023.08]

- **CLE Diffusion:** Yuyang Yin, Dejia Xu, Chuangchuang Tan, Ping Liu, Yao Zhao, Yunchao Wei.<br />
  "CLE Diffusion: Controllable Light Enhancement Diffusion Model." ACM MM (2023).
  [[paper](https://arxiv.org/abs/2308.06725)] 
  [[code](https://yuyangyin.github.io/CLEDiffusion/)]
  [2023.08]

- **Polyp-SAM++:** Risab Biswas.<br />
  "Polyp-SAM++: Can A Text Guided SAM Perform Better for Polyp Segmentation?" ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06623)] 
  [[code](https://github.com/RisabBiswas/Polyp-SAM++)]
  [2023.08]

- **TongueSAM:** Shan Cao, Qunsheng Ruan, Qingfeng Wu.<br />
  "TongueSAM: An Universal Tongue Segmentation Model Based on SAM with Zero-Shot." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.06444)] 
  [[code](https://github.com/cshan-github/TongueSAM)]
  [2023.08]

- **FoodSAM:** Xing Lan, Jiayi Lyu, Hanyu Jiang, Kun Dong, Zehai Niu, Yi Zhang, Jian Xue.<br />
  "FoodSAM: Any Food Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05938)] 
  [[code](https://github.com/jamesjg/FoodSAM)]
  [2023.08]

- **SAM-L:** Xueyuan Li, Ruining Deng, Yucheng Tang, Shunxing Bao, Haichun Yang, Yuankai Huo.<br />
  "Leverage Weakly Annotation to Pixel-wise Annotation via Zero-shot Segment Anything Model for Molecular-empowered Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05785)] 
  [2023.08]

- **FAn :** Alaa Maalouf, Ninad Jadhav, Krishna Murthy Jatavallabhula, Makram Chahine, Daniel M. Vogt, Robert J. Wood, Antonio Torralba, Daniela Rus.<br />
  "Follow Anything: Open-set detection, tracking, and following in real-time." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05737)] 
  [[code](https://github.com/alaamaalouf/FollowAnything)]
  [[demo](https://www.youtube.com/watch?v=6Mgt3EPytrw)]
  [2023.08]

- **SSOM:** Ruikai Cui, Siyuan He, Shi Qiu.<br />
  "Adaptive Low Rank Adaptation of Segment Anything to Salient Object Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.05426)] 
  [2023.08]

- **AquaSAM:** Muduo Xu, Jianhao Su, Yutao Liu.<br />
  "AquaSAM: Underwater Image Foreground Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.04218)] 
  [2023.08]

- **AdaptiveSAM:** Jay N. Paranjape, Nithin Gopalakrishnan Nair, Shameema Sikder, S. Swaroop Vedula, Vishal M. Patel.<br />
  "AdaptiveSAM: Towards Efficient Tuning of SAM for Surgical Scene Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.03726)] 
  [[code](https://github.com/JayParanjape/biastuning)]
  [2023.08]

- Ziyi Huang, Hongshan Liu, Haofeng Zhang, Fuyong Xing, Andrew Laine, Elsa Angelini, Christine Hendon, Yu Gan.<br />
  "Push the Boundary of SAM: A Pseudo-label Correction Framework for Medical Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.00883)] 
  [2023.08]

- Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister.<br />
  "Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.00675)] 
  [2023.08]

- **DEFT:** Aditya Kannan.<br />
  "Learning from Human Videos for Robotic Manipulation." ArXiv (2023).
  [[paper](http://reports-archive.adm.cs.cmu.edu/anon/anon/usr/ftp/2023/CMU-CS-23-124.pdf)] 
  [[code](https://github.com/adityak77/masters-thesis)]
  [2023.07] 

- **FOCUS :** Stefano Ferraro, Pietro Mazzaglia, Tim Verbelen, Bart Dhoedt.<br />
  "FOCUS: Object-Centric World Models for Robotics Manipulation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02427)] 
  [[code](https://focus-manipulation.github.io/)]
  [2023.07] 

- **DisCo:** Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang.<br />
  "DisCo: Disentangled Control for Realistic Human Dance Generation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00040)] 
  [[code](https://disco-dance.github.io/)]
  [2023.07] 
  
- Vaibhav Vavilala, David Forsyth.<br />
  "Applying a Color Palette with Local Control using Diffusion Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02698)] 
  [2023.07] 
  
- **SegAnimeChara:** Andy Yu-Hsiang Tseng, Wen-Fan Wang, Bing-Yu Chen.<br />
  "SegAnimeChara: Segmenting Anime Characters Generated by AI." ACM  SIGGRAPH (2023).
  [[paper](https://dl.acm.org/doi/abs/10.1145/3588028.3603685)] 
  [2023.07] 
 
- **TASS:** Mengqi He, Jing Zhang, Zhaoyuan Yang, Mingyi He, Nick Barnes, Yuchao Dai.<br />
  "Transferable Attack for Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.16572)] 
  [[code](https://github.com/anucvers/TASS)]
  [2023.07] 

- **SAM zero-shot segmentator:** Loris Nanni, Carlo Fantozzi, Alberto Pretto , Daniel Fusaro.<br />
  "Improving Existing Segmentators Performance with Zero-Shot Segmentators." ArXiv (2023).
  [[paper](https://www.preprints.org/manuscript/202307.1729/v1)] 
  [2023.07]
  
- **SAMFlow:** Shili Zhou, Ruian He, Weimin Tan, Bo Yan.<br />
  "SAMFlow: Eliminating Any Fragmentation in Optical Flow with Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.16586)] 
  [2023.07]

- **HQTrack:** Jiawen Zhu, Zhenyu Chen, Zeqi Hao, Shijie Chang, Lu Zhang, Dong Wang, Huchuan Lu, Bin Luo, Jun-Yan He, Jin-Peng Lan, Hanyuan Chen, Chenyang Li.<br />
  "Tracking Anything in High Quality." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13974)] 
  [[code](https://github.com/jiawen-zhu/HQTrack)]
  [2023.07]

- **Fashion Matrix:** Zheng Chong, Xujie Zhang, Fuwei Zhao, Zhenyu Xie, Xiaodan Liang.<br />
  "Fashion Matrix: Editing Photos by Just Talking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13240)] 
  [[homepage](https://zheng-chong.github.io/FashionMatrix/)]
  [[code](https://github.com/Zheng-Chong/FashionMatric)]
  [2023.07]

- **RoboChop:** Atharva Dikshit, Alison Bartsch, Abraham George, Amir Barati Farimani.<br />
  "RoboChop: Autonomous Framework for Fruit and Vegetable Chopping Leveraging Foundational Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.13159)] 
  [2023.07]

- **Industrial-SA:** Keno Moenck, Arne Wendt, Philipp Prünte, Julian Koch, Arne Sahrhage, Johann Gierecker, Ole Schmedemann, Falko Kähler, Dirk Holst, Martin Gomse, Thorsten Schüppstuhl, Daniel Schoepflin.<br />
  "Industrial Segment Anything -- a Case Study in Aircraft Manufacturing, Intralogistics, Maintenance, Repair, and Overhaul." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.12674)] 
  [2023.07]


- **CNOS:** Van Nguyen Nguyen, Tomas Hodan, Georgy Ponimatkin, Thibault Groueix, Vincent Lepetit.<br />
  "CNOS: A Strong Baseline for CAD-based Novel Object Segmentation." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2307.11067)] 
  [[code](https://github.com/nv-nguyen/cnos)]
  [2023.07]

- **SAM-Path:** Jingwei Zhang, Ke Ma, Saarthak Kapse, Joel Saltz, Maria Vakalopoulou, Prateek Prasanna, Dimitris Samaras.<br />
  "SAM-Path: A Segment Anything Model for Semantic Segmentation in Digital Pathology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.09570)] 
  [2023.07]

- **BuboGPT:** Yang Zhao, Zhijie Lin, Daquan Zhou, Zilong Huang, Jiashi Feng, Bingyi Kang.<br />
  "BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.08581)] 
  [[code](https://bubo-gpt.github.io)]
  [2023.07]

- **OpenSU:** Ruiping Liu, Jiaming Zhang, Kunyu Peng, Junwei Zheng, Ke Cao, Yufan Chen, Kailun Yang, Rainer Stiefelhagen.<br />
  "Open Scene Understanding: Grounded Situation Recognition Meets Segment Anything for Helping People with Visual Impairments." ICCV Workshop (2023).
  [[paper](https://arxiv.org/abs/2307.07757)] 
  [[code](https://github.com/RuipingL/OpenSU)]
  [2023.07]

- **OG:** Zichao Dong, Hang Ji, Weikun Zhang, Xufeng Huang, Junbo Chen.<br />
  "OG: Equip vision occupancy with instance segmentation and visual grounding." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.05873)] 
  [2023.07]

- **$SAM^{Med}$:** Chenglong Wang, Dexuan Li, Sucheng Wang, Chengxiu Zhang, Yida Wang, Yun Liu, Guang Yang.<br />
  $SAM^{Med}$: A medical image annotation framework based on large vision model. ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.05617)] 
  [2023.07]

- **SAM-U:** Guoyao Deng, Ke Zou, Kai Ren, Meng Wang, Xuedong Yuan, Sancong Ying, Huazhu Fu.<br />
  "SAM-U: Multi-box prompts triggered uncertainty estimation for reliable SAM in medical image." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.04973)] 
  [2023.07]

- **Semantic-SAM:** Feng Li, Hao Zhang, Peize Sun, Xueyan Zou, Shilong Liu, Jianwei Yang, Chunyuan Li, Lei Zhang, Jianfeng Gao.<br />
  "Semantic-SAM: Segment and Recognize Anything at Any Granularity." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.04767)] 
  [[code](https://github.com/UX-Decoder/Semantic-SAM)]
  [2023.07]

- **SAM-IQA:** Xinpeng Li, Ting Jiang, Haoqiang Fan, Shuaicheng Liu.<br />
  "SAM-IQA: Can Segment Anything Boost Image Quality Assessment?." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.04455)] 
  [[code](https://github.com/Hedlen/SAM-IQA)]
  [2023.07]

- **Cross-SAM:** Xiaoyu Bai, Fan Bai, Xiaofei Huo, Jia Ge, Tony C. W. Mok, Zi Li, Minfeng Xu, Jingren Zhou, Le Lu, Dakai Jin, Xianghua Ye, Jingjing Lu, Ke Yan.<br />
  "Matching in the Wild: Learning Anatomical Embeddings for Multi-Modality Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.03535)] 
  [2023.07]

- **LAM-SC:** Feibo Jiang, Yubo Peng, Li Dong, Kezhi Wang, Kun Yang, Cunhua Pan, Xiaohu You.<br />
  "Large AI Model-Based Semantic Communications." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.03492)] 
  [2023.07]

- **MSDeAOT:** Yuanyou Xu, Jiahao Li, Zongxin Yang, Yi Yang, Yueting Zhuang.<br />
  "ZJU ReLER Submission for EPIC-KITCHEN Challenge 2023: TREK-150 Single Object Tracking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02508)] 
  [2023.07]

- **EM-SAM:** Ao Cheng, Guoqiang Zhao, Lirong Wang, Ruobing Zhang.<br />
  "AxonCallosumEM Dataset: Axon Semantic Segmentation of Whole Corpus Callosum cross section from EM Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.02464)] 
  [2023.07]

- **SAM-PT:** Frano Rajič, Lei Ke, Yu-Wing Tai, Chi-Keung Tang, Martin Danelljan, Fisher Yu.<br />
  "Segment Anything Meets Point Tracking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01197)] 
  [[code](https://github.com/SysCV/sam-pt)]
  [2023.07]

- **SAMAug:** Haixing Dai, Chong Ma, Zhengliang Liu, Yiwei Li, Peng Shu, Xiaozheng Wei, Lin Zhao, Zihao Wu, Dajiang Zhu, Wei Liu, Quanzheng Li, Tianming Liu, Xiang Li.<br />
  "SAMAug: Point Prompt Augmentation for Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01187)] 
  [2023.07]

- **SAM-DA:** Liangliang Yao, Haobo Zuo, Guangze Zheng, Changhong Fu, Jia Pan.<br />
  "SAM-DA: UAV Tracks Anything at Night with SAM-Powered Domain Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01024)] 
  [[code](https://github.com/vision4robotics/SAM-DA)]
  [2023.07]

- **RefSAM:** Yonglin Li, Jing Zhang, Xiao Teng, Long Lan.<br />
  "RefSAM: Efficiently Adapting Segmenting Anything Model for Referring Video Object Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00997)] 
  [[code](https://github.com/LancasterLi/RefSAM)]
  [2023.07]

- **All-in-SAM:** Can Cui, Ruining Deng, Quan Liu, Tianyuan Yao, Shunxing Bao, Lucas W. Remedios, Yucheng Tang, Yuankai Huo.<br />
  "All-in-SAM: from Weak Annotation to Pixel-wise Nuclei Segmentation with Prompt-based Finetuning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00290)] 
  [2023.07]
  
- Zenglin Shi, Ying Sun, Mengmi Zhang.<br />
  "Training-free Object Counting with Prompts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.00038)] 
  [[code](https://github.com/shizenglin/training-free-object-counter)]
  [2023.07]

- Xiaoyu Shi, Shurong Chai, Yinhao Li, Jingliang Cheng, Jie Bai, Guohua Zhao, Yen-Wei Chen.<br />
  "Cross-modality Attention Adapter: A Glioma Segmentation Fine-tuning Method for SAM Using Multimodal Brain MR Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2307.01124)] 
  [2023.07]

- **TDA:** Ruben Glatt, Shusen Liu.<br />
  "Topological Data Analysis Guided Segment Anything Model Prompt Optimization for Zero-Shot Segmentation in Biological Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17400)] 
  [2023.06]

- **TDA:** Ruben Glatt, Shusen Liu.<br />
  "Topological Data Analysis Guided Segment Anything Model Prompt Optimization for Zero-Shot Segmentation in Biological Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17400)] 
  [2023.06]
 
- Xavier F. Cadet, Ranya Aloufi, Alain Miranville, Sara Ahmadi-Abhari, Hamed Haddadi.<br />
  "Evaluating The Robustness of Self-Supervised Representations to Background/Foreground Removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.01398)] 
  [2023.06]
  
- **3D Shape Match:** Ahmed Abdelreheem, Abdelrahman Eldesokey, Maks Ovsjanikov, Peter Wonka.<br />
  "Zero-Shot 3D Shape Correspondence." SIGGRAPH ASIA (2023).
  [[paper](https://arxiv.org/abs/2306.03253)] 
  [[code](https://samir55.github.io/3dshapematch/)]
  [2023.06]

- Siddharth Shankar, Leigh A. Stearns, Cornelis J. van der Veen.<br />
  "Segment Anything in Glaciology: An initial study implementing the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper](https://www.researchsquare.com/article/rs-3011246/v1)] 
  [2023.06]

- Xiang Li, Lu Zhang, Zihao Wu, Zhengliang Liu, Lin Zhao, Yixuan Yuan, Jun Liu, Gang Li, Dajiang Zhu, Pingkun Yan, Quanzheng Li, Wei Liu, Tianming Liu, Dinggang Shen.<br />
  "Artificial General Intelligence for Medical Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05480)] 
  [2023.06]
 
- **ViDA:** Jiaming Liu, Senqiao Yang, Peidong Jia, Renrui Zhang, Ming Lu, Yandong Guo, Wei Xue, Shanghang Zhang.<br />
  "ViDA: Homeostatic Visual Domain Adapter for Continual Test Time Adaptation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04344)] 
  [[code](https://github.com/Yangsenqiao/vida)]
  [2023.06]

- **FGVP:** Lingfeng Yang, Yueze Wang, Xiang Li, Xinlong Wang, Jian Yang.<br />
  "Fine-Grained Visual Prompting." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04356)]
  [2023.06]  

- **AssistGPT:** Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou.<br />
  "AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08640)] 
  [[code](https://showlab.github.io/assistgpt/)]
  [2023.06]

- Matthew Baugh, James Batten, Johanna P. Müller, Bernhard Kainz.<br />
  "Zero-Shot Anomaly Detection with Pre-trained Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09269)] 
  [2023.06]

- Guochen Ning, Hanyin Liang, Zhongliang Jiang, Hui Zhang, Hongen Liao.<br />
  "The potential of 'Segment Anything' (SAM) for universal intelligent ultrasound image guidance." BioScience Trends (2023).
  [[paper](https://www.jstage.jst.go.jp/article/bst/advpub/0/advpub_2023.01119/_article/-char/ja/)] 
  [2023.06] 
  
- **SeaDronesSee-3D and BOArienT:** Benjamin Kiefer, Timon Höfer, Andreas Zell.<br />
  "Stable Yaw Estimation of Boats from the Viewpoint of UAVs and USVs." ECMR  (2023).
  [[paper](https://arxiv.org/abs/2306.14056)] 
  [2023.06] 

- **DADF:** Yingxin Lai, Zhiming Luo, Zitong Yu.<br />
  "Detect Any Deepfakes: Segment Anything Meets Face Forgery Detection and Localization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.17075)] 
  [[code](https://github.com/laiyingxin2/DADF)]
  [2023.06]

- Lucas Prado Osco, Qiusheng Wu, Eduardo Lopes de Lemos, Wesley Nunes Gonçalves, Ana Paula Marques Ramos, Jonathan Li, José Marcato Junior.<br />
  "The Segment Anything Model (SAM) for Remote Sensing Applications: From Zero to One Shot." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16623)] 
  [2023.06]

- **RSPrompter:** Keyan Chen, Chenyang Liu, Hao Chen, Haotian Zhang, Wenyuan Li, Zhengxia Zou, Zhenwei Shi.<br />
  "RSPrompter: Learning to Prompt for Remote Sensing Instance Segmentation based on Visual Foundation Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16269)] 
  [[code](https://kyanchen.github.io/RSPrompter)]
  [2023.06]

- Zhewei Chen, Wai Keung Wong, Zuofeng Zhong, Jinpiao Liao, Ying Qu.<br />
  "Effective Transfer of Pretrained Large Visual Model for Fabric Defect Segmentation via Specifc Knowledge Injection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.16186)] 
  [2023.06]

- Zheyan Jin, Shiqi Chen, Yueting Chen, Zhihai Xu, Huajun Feng.<br />
  "Let Segment Anything Help Image Dehaze." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15870)] 
  [2023.06]

- **CLIP-SAM:** Evan Kellener, Ihina Nath, An Ngo, Thomas Nguyen, Joshua Schuman, Coen Adler, Arnav Kartikeya.<br />
  "Utilizing Segment Anything Model For Assessing Localization of GRAD-CAM in Medical Imaging." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15692)] 
  [2023.06]
 
- **MESS:** Benedikt Blumenstiel, Johannes Jakubik, Hilde Kühne, Michael Vössing.<br />
  "What a MESS: Multi-Domain Evaluation of Zero-Shot Semantic Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15521)] 
  [[code](https://github.com/blumenstiel/MESS)]
  [2023.06]

- **MMPM:** Jiange Yang, Wenhui Tan, Chuhao Jin, Bei Liu, Jianlong Fu, Ruihua Song, Limin Wang.<br />
  "Pave the Way to Grasp Anything: Transferring Foundation Models for Universal Pick-Place Robots." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05716)] 
  [[YouTube](https://www.youtube.com/watch?v=1m9wNzfp_4E)]
  [[Bilibili](https://www.bilibili.com/video/BV178411Z7H2/)]
  [2023.06]

- **CellViT:** Fabian Hörst, Moritz Rempe, Lukas Heine, Constantin Seibold, Julius Keyl, Giulia Baldini, Selma Ugurel, Jens Siveke, Barbara Grünwald, Jan Egger, Jens Kleesiek.<br />
  "CellViT: Vision Transformers for Precise Cell Segmentation and Classification." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.15350)] 
  [[code](https://github.com/TIO-IKIM/CellViT)]
  [2023.06]

- **MedLSAM:** Wenhui Lei, Xu Wei, Xiaofan Zhang, Kang Li, Shaoting Zhang.<br />
  "MedLSAM: Localize and Segment Anything Model for 3D Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14752)] 
  [[code](https://github.com/openmedlab/MedLSAM)]
  [2023.06]

- **MobileSAM:** Chaoning Zhang, Dongshen Han, Yu Qiao, Jung Uk Kim, Sung-Ho Bae, Seungkyu Lee, Choong Seon Hong.<br />
  "Faster Segment Anything: Towards Lightweight SAM for Mobile Applications." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14289)] 
  [[code](https://github.com/ChaoningZhang/MobileSAM)]
  [2023.06]

- **SonarSAM:** Lin Wang, Xiufen Ye, Liqiang Zhu, Weijie Wu, Jianguo Zhang, Huiming Xing, Chao Hu.<br />
  "When SAM Meets Sonar Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.14109)] 
  [[code](https://github.com/wangsssky/SonarSAM)]
  [2023.06]

- **AutoSAM:** Xinrong Hu, Xiaowei Xu, Yiyu Shi.<br />
  "How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13731)] 
  [[code](https://github.com/xhu248/AutoSAM)]
  [2023.06]

- **3DSAM-adapter:** Shizhan Gong, Yuan Zhong, Wenao Ma, Jinpeng Li, Zhao Wang, Jingyang Zhang, Pheng-Ann Heng, Qi Dou.<br />
  "3DSAM-adapter: Holistic Adaptation of SAM from 2D to 3D for Promptable Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13465)] 
  [[code](https://github.com/med-air/3DSAM-adapter)]
  [2023.06]

- Xinru Shan, Chaoning Zhang.<br />
  "Robustness of Segment Anything Model (SAM) for Autonomous Driving in Adverse Weather Conditions." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.13290)] 
  [2023.06]

- **SAM-LST:** Shurong Chai, Rahul Kumar Jain, Shiyu Teng, Jiaqing Liu, Yinhao Li, Tomoko Tateyama, Yen-wei Chen.<br />
  "Ladder Fine-tuning approach for SAM integrating complementary network." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12737)] 
  [[code](https://github.com/11yxk/SAM-LST)]
  [2023.06]

- Mohsen Ahmadi, Masoumeh Farhadi Nia, Sara Asgarian, Kasra Danesh, Elyas Irankhah, Ahmad Gholizadeh Lonbar, Abbas Sharifi.<br />
  "Comparative Analysis of Segment Anything Model and U-Net for Breast Tumor Detection in Ultrasound and Mammography Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12510)] 
  [2023.06]

- **FastSAM:** Xu Zhao, Wenchao Ding, Yongqi An, Yinglong Du, Tao Yu, Min Li, Ming Tang, Jinqiao Wang.<br />
  "Fast Segment Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.12156)] 
  [[code](https://github.com/CASIA-IVA-Lab/FastSAM)]
  [2023.06]

- **Seal:** Youquan Liu, Lingdong Kong, Jun Cen, Runnan Chen, Wenwei Zhang, Liang Pan, Kai Chen, Ziwei Liu.<br />
  "Segment Any Point Cloud Sequences by Distilling Vision Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09347)] 
  [[code](https://github.com/youquanl/Segment-Any-Point-Cloud)]
  [[homepage](https://ldkong.com/Seal)]
  [2023.06]

- Lian Zhang, Zhengliang Liu, Lu Zhang, Zihao Wu, Xiaowei Yu, Jason Holmes, Hongying Feng, Haixing Dai, Xiang Li, Quanzheng Li, Dajiang Zhu, Tianming Liu, Wei Liu.<br />
  "Segment Anything Model (SAM) for Radiation Oncology." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.11730)] 
  [2023.06]

- **Enlighten-Anything:** Qihan Zhao, Xiaofeng Zhang, Hao Tang, Chaochen Gu, Shanying Zhu.<br />
  "Enlighten-anything:When Segment Anything Model Meets Low-light Image Enhancement." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.10286)] 
  [[code](https://github.com/zhangbaijin/enlighten-anything)]
  [2023.06]

- **SAA+:** Yunkang Cao, Xiaohao Xu, Chen Sun, Yuqi Cheng, Liang Gao, Weiming Shen.<br />
  "Winning Solution for the CVPR2023 Visual Anomaly and Novelty Detection Challenge: Multimodal Prompting for Data-centric Anomaly Detection." CVPR2023 Workshop.
  [[paper](https://arxiv.org/abs/2306.09067)] 
  [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
  [2023.06]

- **TEPO:** Chuyun Shen, Wenhao Li, Ya Zhang, Xiangfeng Wang.<br />
  "Temporally-Extended Prompts Optimization for SAM in Interactive Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08958)]
  [2023.06]  

- **TomoSAM:** Federico Semeraro, Alexandre Quintart, Sergio Fraile Izquierdo, Joseph C. Ferguson.<br />
  "TomoSAM: a 3D Slicer extension using SAM for tomography segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.08609)] 
  [[code](https://github.com/fsemerar/SlicerTomoSAM)]
  [2023.06]
  
- Madeline Chantry Schiappa, Sachidanand VS, Yunhao Ge, Ondrej Miksik, Yogesh S. Rawat, Vibhav Vineet.<br />
  "Robustness Analysis on Foundational Segmentation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.09278)] 
  [[code](https://tinyurl.com/fm-robust)]
  [2023.06]

- Yu Qiao, Chaoning Zhang, Taegoo Kang, Donghun Kim, Shehbaz Tariq, Chenshuang Zhang, Choong Seon Hong.<br />
  "Robustness of SAM: Segment Anything Under Corruptions and Beyond." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.07713)] 
  [2023.06]

- **AutoSAM:** Tal Shaharabany, Aviad Dahan, Raja Giryes, Lior Wolf.<br />
  "AutoSAM: Adapting SAM to Medical Images by Overloading the Prompt Encoder." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06370)]
  [2023.06]  
 
- **SAM-shadow:** Xiaofeng Zhang, Chaochen Gu, Shanying Zhu.<br />
  "SAM-helps-Shadow:When Segment Anything Model meet shadow removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06113)] 
  [[code]( https://github.com/zhangbaijin/SAM-helps-Shadow)]
  [2023.06]

- Chaoning Zhang, Sheng Zheng, Chenghao Li, Yu Qiao, Taegoo Kang, Xinru Shan, Chenshuang Zhang, Caiyan Qin, Francois Rameau, Sung-Ho Bae, Choong Seon Hong.<br />
  "A Survey on Segment Anything Model (SAM): Vision Foundation Model Meets Prompt Engineering." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.06211)]
  [2023.06]

- **MAM:** Jiachen Li, Jitesh Jain, Humphrey Shi.<br />
  "Matting Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05399)] 
  [[code](https://chrisjuniorli.github.io/project/Matting-Anything/)]
  [2023.06]

-  Haochen Xue, Mingyu Jin, Chong Zhang, Yuxuan Huang, Qian Weng, Xiaobo Jin.<br />
  "Automatic Image Blending Algorithm Based on SAM and DINO." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.05382)] 
  [2023.06]

- **MatAny:** Jingfeng Yao, Xinggang Wang, Lang Ye, Wenyu Liu.<br />
  "Matte Anything: Interactive Natural Image Matting with Segment Anything Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.04121)] 
  [[code](https://github.com/hustvl/Matte-Anything)]
  [2023.06]

- **CNS:** Runnan Chen, Youquan Liu, Lingdong Kong, Nenglun Chen, Xinge Zhu, Yuexin Ma, Tongliang Liu, Wenping Wang.<br />
  "Towards Label-free Scene Understanding by Vision Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03899)] 
  [[code](https://github.com/runnanchen/Label-Free-Scene-Understanding)]
  [2023.06]

- **SAM3D:** Yunhan Yang, Xiaoyang Wu, Tong He, Hengshuang Zhao, Xihui Liu.<br />
  "SAM3D: Segment Anything in 3D Scenes." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.03908)] 
  [[code](https://github.com/Pointcept/SegmentAnything3D)]
  [2023.06]

- **Calib-Anything:** Zhaotong Luo, Guohang Yan, Yikang Li.<br />
  " Calib-Anything: Zero-training LiDAR-Camera Extrinsic Calibration Method Using Segment Anything." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.02656)] 
  [[code](https://github.com/OpenCalib/CalibAnything)]
  [2023.06]

-  Shijie Chang, Zeqi Hao, Ben Kang, Xiaoqi Zhao, Jiawen Zhu, Zhenyu Chen, Lihe Zhang, Lu Zhang, Huchuan Lu.<br />
  " 3rd Place Solution for PVUW2023 VSS Track: A Large Model for Semantic Segmentation on VSPW." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.02291)] 
  [2023.06]

- **USD:** Yulin He, Wei Chen, Yusong Tan, Siqi Wang.<br />
  " USD: Unknown Sensitive Detector Empowered by Decoupled Objectness and Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.02275)] 
  [2023.06]

- **SAM3D:** Dingyuan Zhang, Dingkang Liang, Hongcheng Yang, Zhikang Zou, Xiaoqing Ye, Zhe Liu, Xiang Bai.<br />
  "SAM3D: Zero-Shot 3D Object Detection via Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.02245)] 
  [[code]( https://github.com/DYZhang09/SAM3D)]
  [2023.06]

-  Shehbaz Tariq, Brian Estadimas Arfeto, Chaoning Zhang, Hyundong Shin.<br />
  "Segment Anything Meets Semantic Communication." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2306.02094)] 
  [2023.06]

- **HQ-SAM:** Lei Ke, Mingqiao Ye, Martin Danelljan, Yifan Liu, Yu-Wing Tai, Chi-Keung Tang, Fisher Yu.<br />
  "Segment Anything in High Quality." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2306.01567)] 
  [[code](https://github.com/SysCV/SAM-HQ)]
  [2023.06]

- **DeSAM:** Yifan Gao, Wei Xia, Dingdu Hu, Xin Gao.<br />
  "DeSAM: Decoupling Segment Anything Model for Generalizable Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2306.00499)] 
  [[code]( https://github.com/yifangao112/DeSAM)]
  [2023.06]

- **NP-SAM:** Rasmus Larsen, Torben L. Villadsen, Jette K. Mathiesen, Kirsten M. Ø. Jensen, Espen D. Bøjesen.<br />
  "NP-SAM: Implementing the Segment Anything Model for Easy Nanoparticle Segmentation in Electron Microscopy Images." ArXiv (2023).
  [[paper](https://chemrxiv.org/engage/chemrxiv/article-details/6463c10aa32ceeff2dc08c49)] 
  [[code](https://gitlab.au.dk/disorder/np-sam.git)]
  [2023.05]

- **EfficientViT:** Han Cai, Junyan Li, Muyan Hu, Chuang Gan, Song Han.<br />
  "EfficientViT: Multi-Scale Linear Attention for High-Resolution Dense Prediction." ICCV (2023).
  [[paper](https://arxiv.org/abs/2205.14756)] 
  [[code](https://github.com/mit-han-lab/efficientvit)]
  [2023.05] 

- **POPE:** Zhiwen Fan, Panwang Pan, Peihao Wang, Yifan Jiang, Dejia Xu, Hanwen Jiang, Zhangyang Wang.<br />
  "POPE: 6-DoF Promptable Pose Estimation of Any Object, in Any Scene, with One Reference." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.15727)] 
  [[code](https://paulpanwang.github.io/POPE/)]
  [2023.05]

- **Bridge3D:** Zhimin Chen, Bing Li.<br />
  "Bridging the Domain Gap: Self-Supervised 3D Scene Understanding with Foundation Models." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.08776)] 
  [2023.05]

- **Make-A-Protagonist:** Yuyang Zhao, Enze Xie, Lanqing Hong, Zhenguo Li, Gim Hee Lee.<br />
  "Make-A-Protagonist: Generic Video Editing with An Ensemble of Experts." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.08850)] 
  [[code](https://make-a-protagonist.github.io/)]
  [2023.05]
  
- **ZeroPose:** Jianqiu Chen, Mingshan Sun, Tianpeng Bao, Rui Zhao, Liwei Wu, Zhenyu He.<br />
  "ZeroPose: CAD-Model-based Zero-Shot Pose Estimation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.17934)] 
  [2023.05]
 
- **IIR-Net:** Zhongping Zhang, Jian Zheng, Jacob Zhiyuan Fang, Bryan A. Plummer.<br />
  "Text-to-image Editing by Image Information Removal." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.17489)] 
  [2023.05]

- Chaoning Zhang, Yu Qiao, Shehbaz Tariq, Sheng Zheng, Chenshuang Zhang, Chenghao Li, Hyundong Shin, Choong Seon Hong.<br />
  "Understanding segment anything model: Sam is biased towards texture rather than shape." ArXiv (2023).
  [[paper](https://www.researchgate.net/profile/Yu-Qiao-52/publication/371070480_Understanding_Segment_Anything_Model_SAM_is_Biased_Towards_Texture_Rather_than_Shape/links/6470de25a25e543829cedeee/Understanding-Segment-Anything-Model-SAM-is-Biased-Towards-Texture-Rather-than-Shape.pdf)] 
  [2023.05] 
 
- **FineRewards:** Guian Fang, Zutao Jiang, Jianhua Han, Guangsong Lu, Hang Xu, Xiaodan Liang.<br />
  "Boosting Text-to-Image Diffusion Models with Fine-Grained Semantic Rewards." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.19599)] 
  [[code](https://github.com/Enderfga/FineRewards)]
  [2023.05]

- **InstructEdit:** Qian Wang, Biao Zhang, Michael Birsak, Peter Wonka.<br />
  "InstructEdit: Improving Automatic Masks for Diffusion-based Image Editing With User Instructions." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.18047)] 
  [[code]( https://github.com/QianWangX/InstructEdit)]
  [2023.05]

- **AIMS:** Lu Qi, Jason Kuen, Weidong Guo, Jiuxiang Gu, Zhe Lin, Bo Du, Yu Xu, Ming-Hsuan Yang.<br />
  "AIMS: All-Inclusive Multi-Level Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.17768)] 
  [[code](https://github.com/dvlab-research/Entity)]
  [2023.05]

- **ShadowSAM:** Yonghui Wang, Wengang Zhou, Yunyao Mao, Houqiang Li.<br />
  "Detect Any Shadow: Segment Anything for Video Shadow Detection." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.16698)] 
  [[code](https://github.com/harrytea/Detect-AnyShadow)]
  [2023.05]

- **ISA-NeRF:** Xiaokang Chen, Jiaxiang Tang, Diwen Wan, Jingbo Wang, Gang Zeng.<br />
  "Interactive Segment Anything NeRF with Feature Imitation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.16233)] 
  [[homepage]( https://me.kiui.moe/san/)]
  [2023.05]

- Yihao Huang, Yue Cao, Tianlin Li, Felix Juefei-Xu, Di Lin, Ivor W. Tsang, Yang Liu, Qing Guo.<br />
  "On the Robustness of Segment Anything." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.16220)] 
  [2023.05]

- **SAMScore:** Yunxiang Li, Meixu Chen, Wenxuan Yang, Kai Wang, Jun Ma, Alan C. Bovik, You Zhang.<br />
  "SAMScore: A Semantic Structural Similarity Metric for Image Translation Evaluation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.15367)] 
  [[code]( https://github.com/Kent0n-Li/SAMScore)]
  [2023.05]

- **SAD:** Jun Cen, Yizheng Wu, Kewei Wang, Xingyi Li, Jingkang Yang, Yixuan Pei, Lingdong Kong, Ziwei Liu, Qifeng Chen.<br />
  "SAD: Segment Any RGBD." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.14207)] 
  [[code](https://github.com/Jun-CEN/SegmentAnyRGBD)]
  [2023.05]

- **SPT:** Zeyu Xiao, Jiawang Bai, Zhihe Lu, Zhiwei Xiong.<br />
  "A Dive into SAM Prior in Image Restoration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13620)] 
  [2023.05]

- **Matcher:** Yang Liu, Muzhi Zhu, Hengtao Li, Hao Chen, Xinlong Wang, Chunhua Shen.<br />
  "Matcher: Segment Anything with One Shot Using All-Purpose Feature Matching." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13310)] 
  [[code](https://github.com/aim-uofa/Matcher)]
  [2023.05]

- **RAP:** Jiaxi Jiang, Christian Holz.<br />
  "Restore Anything Pipeline: Segment Anything Meets Image Restoration." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.13093)] 
  [[code](https://github.com/eth-siplab/RAP)]
  [2023.05]

- **UVOSAM:** Zhenghao Zhang, Zhichao Wei, Shengfan Zhang, Zuozhuo Dai, Siyu Zhu.<br />
  "UVOSAM: A Mask-free Paradigm for Unsupervised Video Object Segmentation via Segment Anything Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.12659)] 
  [2023.05]

- **BreastSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "BreastSAM: A Study of Segment Anything Model for Breast Tumor Detection in Ultrasound Images." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.12447)] 
  [2023.05]

- **SAMSh:** Leiping Jie, Hui Zhang.<br />
  "When SAM Meets Shadow Detection." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.11513)] 
  [[code](https://github.com/LeipingJie/SAMSh)]
  [2023.05]

- **Instruct2Act:** Siyuan Huang, Zhengkai Jiang, Hao Dong, Yu Qiao, Peng Gao, Hongsheng Li.<br />
  "Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.11176)] 
  [[code](https://github.com/OpenGVLab/Instruct2Act)]
  [2023.05]

- **WS-SAM:** Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li.<br />
  "Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2305.11003)] 
  [2023.05]

- **SAA+:** Yunkang Cao, Xiaohao Xu, Chen Sun, Yuqi Cheng, Zongwei Du, Liang Gao, Weiming Shen.<br />
  "Segment Any Anomaly without Training via Hybrid Prompt Regularization." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10724)] 
  [[code](https://github.com/caoyunkang/Segment-Any-Anomaly)]
  [2023.05]

- **OR-NeRF:** Youtan Yin, Zhoujie Fu, Fan Yang, Guosheng Lin.<br />
  "OR-NeRF: Object Removing from 3D Scenes Guided by Multiview Segmentation with Neural Radiance Fields." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10503)] 
  [2023.05]

- **PromptUNet:** Junde Wu.<br />
  "PromptUNet: Toward Interactive Medical Image Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10300)] 
  [[code](https://github.com/WuJunde/PromptUNet)]
  [2023.05]

- **EAC:** Ao Sun, Pingchuan Ma, Yuanyuan Yuan, Shuai Wang.<br />
  "Explain Any Concept: Segment Anything Meets Concept-Based Explanation." NeurIPS (2023).
  [[paper](https://arxiv.org/abs/2305.10289)] 
  [2023.05]
  
- Xiao Yang, Haixing Dai, Zihao Wu, Ramesh Bist, Sachin Subedi, Jin Sun, Guoyu Lu, Changying Li, Tianming Liu, Lilong Chai.<br />
  "SAM for Poultry Science." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.10254)] 
  [2023.05]

- **Leaf Only SAM:** Dominic Williams, Fraser MacFarlane, Avril Britten.<br />
  "Leaf Only SAM: A Segment Anything Pipeline for Zero-Shot Automated Leaf Segmentation." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.09418)] 
  [2023.05]
  
- **KD-SAM:** Sahib Julka, Michael Granitzer.<br />
  "Knowledge distillation with Segment Anything (SAM) model for Planetary Geological Mapping." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.07586)] 
  [2023.05]
  
- **SAM-Track:** Yangming Cheng, Liulei Li, Yuanyou Xu, Xiaodi Li, Zongxin Yang, Wenguan Wang, Yi Yang.<br />
  "Segment-and-Track Anything." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2305.06558)] 
  [[code](https://github.com/z-x-yang/Segment-and-Track-Anything)]
  [2023.05]
  
- **SEEM:** Zhihe Lu, Zeyu Xiao, Jiawang Bai, Zhiwei Xiong, Xinchao Wang.<br />
  "Can SAM Boost Video Super-Resolution?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.06524)] 
  [2023.05]
	
-  Yuqing Wang, Yun Zhao, Linda Petzold.<br />
  "An Empirical Study on the Robustness of the Segment Anything Model (SAM)." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.06422)] 
  [2023.05]
  
- **SAM-WSSS:** Tianle Chen, Zheda Mai, Ruiwen Li, Wei-lun Chao.<br />
  "Segment Anything Model (SAM) Enhanced Pseudo Labels for Weakly Supervised Semantic Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.05803)] 
  [[code]( https://github.com/cskyl/SAM_WSSS)]
  [2023.05]
  
- **SAM4MIS:** Yichi Zhang, Rushi Jiao.<br />
  "How Segment Anything Model (SAM) Boost Medical Image Segmentation?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03678)] 
  [[code]( https://github.com/YichiZhang98/SAM4MIS)]
  [2023.05]
  
- **BadSAM:** Zihan Guan, Mengxuan Hu, Zhongliang Zhou, Jielu Zhang, Sheng Li, Ninghao Liu.<br />
  "BadSAM: Exploring Security Vulnerabilities of SAM via Backdoor Attacks." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03289)] 
  [2023.05]
  
- **PerSAM:** Renrui Zhang, Zhengkai Jiang, Ziyu Guo, Shilin Yan, Junting Pan, Hao Dong, Peng Gao, Hongsheng Li.<br />
  "Personalize Segment Anything Model with One Shot." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.03048)] 
  [[code]( https://github.com/ZrrSkywalker/Personalize-SAM)]
  [2023.05]

- **CAT:** Teng Wang, Jinrui Zhang, Junjie Fei, Hao Zheng, Yunlong Tang, Zhe Li, Mingqi Gao, Shanshan Zhao.<br />
  "Caption Anything: Interactive Image Description with Diverse Multimodal Controls." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.02677)] 
  [[code]( https://github.com/ttengwang/Caption-Anything)]
  [2023.05]

- **SAMRS:** Di Wang, Jing Zhang, Bo Du, Dacheng Tao, Liangpei Zhang.<br />
  "Scaling-up Remote Sensing Segmentation Dataset with Segment Anything Model." NeurIPS 2023 Datasets and Benchmarks Track (2023).
  [[paper]( https://arxiv.org/abs/2305.02034)] 
  [[code]( https://github.com/ViTAE-Transformer/SAMRS)]
  [2023.05]

- **AV-SAM:** Shentong Mo, Yapeng Tian.<br />
  "AV-SAM: Segment Anything Model Meets Audio-Visual Localization and Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01836)]
  [2023.05]

- **SAMA-AVS:** Jinxiang Liu, Yu Wang, Chen Ju, Chaofan Ma, Ya Zhang, Weidi Xie.<br />
  "Annotation-free Audio-Visual Segmentation." WACV (2024).
  [[paper]( https://arxiv.org/pdf/2305.11019v3.pdf)] 
  [[code]( https://github.com/jinxiang-liu/anno-free-AVS)]
  [2023.05]

- **WSSS:** Weixuan Sun, Zheyuan Liu, Yanhao Zhang, Yiran Zhong, Nick Barnes.<br />
  "An Alternative to WSSS? An Empirical Study of the Segment Anything Model (SAM) on Weakly-Supervised Semantic Segmentation Problems." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01586)] 
  [2023.05]

- **PLG-SAM:** Peng-Tao Jiang, Yuqi Yang.<br />
  "Segment Anything is A Good Pseudo-label Generator for Weakly Supervised Semantic Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.01275)] 
  [2023.05]

- **Attack-SAM:** Chenshuang Zhang, Chaoning Zhang, Taegoo Kang, Donghun Kim, Sung-Ho Bae, In So Kweon.<br />
  "Attack-SAM: Towards Attacking Segment Anything Model With Adversarial Examples." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00866)] 
  [2023.05]

- **Polyp-SAM:** Yuheng Li, Mingzhe Hu, Xiaofeng Yang.<br />
  "Polyp-SAM: Transfer SAM for Polyp Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00293)] 
  [[code]( https://github.com/ricklisz/Polyp-SAM)]
  [2023.05]

- Dongsheng Han, Chaoning Zhang, Yu Qiao, Maryam Qamar, Yuna Jung, SeungKyu Lee, Sung-Ho Bae, Choong Seon Hong.<br />
  "Segment Anything Model (SAM) Meets Glass: Mirror and Transparent Objects Cannot Be Easily Detected." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00278)] 
  [2023.05]

- **DSEC-MOS:** Zhuyun Zhou, Zongwei Wu, Rémi Boutteau, Fan Yang, Dominique Ginhac.<br />
  "DSEC-MOS: Segment Any Moving Object with Moving Ego Vehicle." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00126)] 
  [[code]( https://github.com/ZZY-Zhou/DSEC-MOS)]
  [2023.05]

- Christian Mattjie, Luis Vinicius de Moura, Rafaela Cappelari Ravazio, Lucas Silveira Kupssinskü, Otávio Parraga, Marcelo Mussi Delucis, Rodrigo Coelho Barros.<br />
  "Zero-shot performance of the Segment Anything Model (SAM) in 2D medical imaging: A comprehensive evaluation and practical guidelines." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00109)] 
  [[code]( https://github.com/Malta-Lab/SAM-zero-shot-in-Medical-Imaging)]
  [2023.05]

- Dongjie Cheng, Ziyuan Qin, Zekun Jiang, Shaoting Zhang, Qicheng Lao, Kang Li.<br />
  "SAM on Medical Images: A Comprehensive Study on Three Prompt Modes." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2305.00035)] 
  [2023.05]

- **Expedit-SAM:** Weicong Liang, Yuhui Yuan, Henghui Ding, Xiao Luo, Weihong Lin, Ding Jia, Zheng Zhang, Chao Zhang, Han Hu.<br />
  "Expediting Large-Scale Vision Transformer for Dense Prediction without Fine-tuning." NeurIPS (2022).
  [[paper](https://arxiv.org/abs/2210.01035)] 
  [[code](https://github.com/Expedit-LargeScale-Vision-Transformer/Expedit-SAM)]
  [2023.04] 
  
- An Wang, Mobarakol Islam, Mengya Xu, Yang Zhang, Hongliang Ren.<br />
  "SAM Meets Robotic Surgery: An Empirical Study in Robustness Perspective." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14674)] 
  [2023.04]

- Yuhao Huang, Xin Yang, Lian Liu, Han Zhou, Ao Chang, Xinrui Zhou, Rusi Chen, Junxuan Yu, Jiongquan Chen, Chaoyu Chen, Haozhe Chi, Xindi Hu, Deng-Ping Fan, Fajin Dong, Dong Ni.<br />
  "Segment Anything Model for Medical Images?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14660)] 
  [2023.04]

- **Edit Everything:** Defeng Xie, Ruichen Wang, Jian Ma, Chen Chen, Haonan Lu, Dong Yang, Fobo Shi, Xiaodong Lin.<br />
  "Edit Everything: A Text-Guided Generative System for Images Editing." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.14006)] 
  [[code]( https://github.com/DefengXie/Edit_Everything)]
  [2023.04]

- **SkinSAM:** Mingzhe Hu, Yuheng Li, Xiaofeng Yang.<br />
  "SkinSAM: Empowering Skin Cancer Segmentation with Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13973)]
  [2023.04]  

- **GazeSAM:** Bin Wang, Armstrong Aboah, Zheyuan Zhang, Ulas Bagci.<br />
  "GazeSAM: What You See is What You Segment." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13844)] 
  [[code]( https://github.com/ukaukaaaa/GazeSAM)]
  [2023.04]

- **SAMed:** Kaidong Zhang, Dong Liu.<br />
  "Customized Segment Anything Model for Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13785)] 
  [[code]( https://github.com/hitachinsk/SAMed)]
  [2023.04]

- **LearnablePromptSAM:** Zhongxi Qiu, Yan Hu, Heng Li, Jiang Liu.<br />
  "Learnable Ophthalmology SAM." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13425)] 
  [[code]( https://github.com/Qsingle/LearnablePromptSAM)]
  [2023.04]

- Simiao Ren, Francesco Luzi, Saad Lahrichi, Kaleb Kassaw, Leslie M. Collins, Kyle Bradbury, Jordan M. Malof.<br />
  "Segment anything, from space?." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.13000)] 
  [2023.04]

-  Peilun Shi, Jianing Qiu, Sai Mu Dalike Abaxi, Hao Wei, Frank P. -W. Lo, Wu Yuan.<br />
  "Generalist Vision Foundation Models for Medical Imaging: A Case Study of Segment Anything Model on Zero-Shot Medical Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12637)] 
  [2023.04]

- **MSA:** Junde Wu, Yu Zhang, Rao Fu, Huihui Fang, Yuanpei Liu, Zhaowei Wang, Yanwu Xu, Yueming Jin.<br />
  "Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12620)] 
  [[code]( https://github.com/WuJunde/Medical-SAM-Adapter)]
  [2023.04]

- Mohsen Ahmadi, Ahmad Gholizadeh Lonbar, Abbas Sharifi, Ali Tarlani Beris, Mohammadsadegh Nouri, Amir Sharifzadeh Javidi.<br />
  "Application of Segment Anything Model for Civil Infrastructure Defect Assessment." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12600)] 
  [2023.04]

- **SA3D:** Jiazhong Cen, Zanwei Zhou, Jiemin Fang, Wei Shen, Lingxi Xie, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian.<br />
  "Segment Anything in 3D with NeRFs." NeurIPS (2023).
  [[paper]( https://arxiv.org/abs/2304.12308)] 
  [[code]( https://jumpat.github.io/SA3D/)]
  [2023.04]

- **MedSAM:** Jun Ma, Bo Wang.<br />
  "Segment Anything in Medical Images." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.12306)] 
  [[code]( https://github.com/bowang-lab/MedSAM)]
  [2023.04]

- **TAM:** Jinyu Yang, Mingqi Gao, Zhe Li, Shang Gao, Fangjing Wang, Feng Zheng.<br />
  "Track Anything: Segment Anything Meets Videos." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2304.11968)] 
  [[code](https://github.com/gaomingqi/Track-Anything)]
  [2023.04]

- **HFGFA:** Rongsheng Wang, Yaofei Duan, YuKun Li.<br />
  "Segment anything also detect anything." ArXiv (2023).
  [[paper](https://6login.easychair.org/publications/preprint_download/T1rc)]
  [2023.04]

- **SNA:** Yongcheng Jing, Xinchao Wang, Dacheng Tao.<br />
  "Segment Anything in Non-Euclidean Domains: Challenges and Opportunities." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.11595)] 
  [2023.04]
  
- **SAMAug:** Yizhe Zhang, Tao Zhou, Peixian Liang, Danny Z. Chen.<br />
  "Input Augmentation with SAM: Boosting Medical Image Segmentation with Segmentation Foundation Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.11332)] 
  [2023.04]
  
- **Count-Anything:** Zhiheng Ma, Xiaopeng Hong, Qinnan Shangguan.<br />
  "Can SAM Count Anything? An Empirical Study on SAM Counting." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10817)] 
  [[code]( https://github.com/Vision-Intelligence-and-Robots-Group/count-anything)]
  [2023.04]

- **Text2Seg:** Jielu Zhang, Zhongliang Zhou, Gengchen Mai, Lan Mu, Mengxuan Hu, Sheng Li.<br />
  "Text2Seg: Remote Sensing Image Semantic Segmentation via Text-Guided Visual Foundation Models." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10597)] 
  [[code]( https://github.com/Douglas2Code/Text2Seg)]
  [2023.04]

- Maciej A. Mazurowski, Haoyu Dong, Hanxue Gu, Jichen Yang, Nicholas Konz, Yixin Zhang.<br />
  "Segment Anything Model for Medical Image Analysis: an Experimental Study." MIA (2023).
  [[paper]( https://arxiv.org/abs/2304.10517)] 
  [2023.04]

- **Anything-3D:** Qiuhong Shen, Xingyi Yang, Xinchao Wang.<br />
  "Anything-3D: Towards Single-view Anything Reconstruction in the Wild." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.10261)] 
  [[code]( https://github.com/Anything-of-anything/Anything-3D)]
  [2023.04]

- **Any-to-Any Transfer:** Songhua Liu, Jingwen Ye, Xinchao Wang.<br />
  "Any-to-Any Style Transfer: Making Picasso and Da Vinci Collaborate." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.09728)] 
  [[code]( https://github.com/Huage001/Transfer-Any-Style)]
  [2023.04]

- Sheng He, Rina Bao, Jingpeng Li, Jeffrey Stout, Atle Bjornerud, P. Ellen Grant, Yangming Ou.<br />
  "Computer-Vision Benchmark Segment-Anything Model (SAM) in Medical Images: Accuracy in 12 Datasets." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.09324)] 
  [2023.04]

- **SAM-Adapter:** Tianrun Chen, Lanyun Zhu, Chaotao Ding, Runlong Cao, Yan Wang, Zejian Li, Lingyun Sun, Papa Mao, Ying Zang.<br />
  "SAM Fails to Segment Anything? -- SAM-Adapter: Adapting SAM in Underperformed Scenes: Camouflage, Shadow, Medical Image Segmentation, and More." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.09148)] 
  [2023.04]

- Chuanfei Hu, Tianyi Xia, Shenghong Ju, Xinde Li.<br />
  "When SAM Meets Medical Images: An Investigation of Segment Anything Model (SAM) on Multi-phase Liver Tumor Segmentation." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.08506)]
  [2023.04]  

- **SATIR:** Junzhang Chen, Xiangzhi Bai.<br />
  "Learning to "Segment Anything" in Thermal Infrared Images through Knowledge Distillation with a Large Scale Dataset SATIR." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07969)] 
  [[code]( https://github.com/chenjzBUAA/SATIR)]
  [2023.04]

- Florian Putz, Johanna Grigo, Thomas Weissmann, Philipp Schubert, Daniel Hoefler, Ahmed Gomaa, Hassen Ben Tkhayat, Amr Hagag, Sebastian Lettmaier, Benjamin Frey, Udo S. Gaipl, Luitpold V. Distel, Sabine Semrau, Christoph Bert, Rainer Fietkau, Yixing Huang.<br />
  "The Segment Anything foundation model achieves favorable brain tumor autosegmentation accuracy on MRI to support radiotherapy treatment planning." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07875)] 
  [2023.04]

-  Iraklis Giannakis, Anshuman Bhardwaj, Lydia Sam, Georgios Leontidis.<br />
  "Deep learning universal crater detection using Segment Anything Model (SAM)." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07764)] 
  [2023.04]

- **SAMPolyp:** Tao Zhou, Yizhe Zhang, Yi Zhou, Ye Wu, Chen Gong.<br />
  "Can SAM Segment Polyps?" ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.07583)] 
  [[code]( https://github.com/taozh2017/SAMPolyp)]
  [2023.04]

- **Inpaint-Anything:** Tao Yu, Runseng Feng, Ruoyu Feng, Jinming Liu, Xin Jin, Wenjun Zeng, Zhibo Chen.<br />
  "Inpaint Anything: Segment Anything Meets Image Inpainting." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.06790)] 
  [[code]( https://github.com/geekyutao/Inpaint-Anything)]
  [2023.04]

- Ge-Peng Ji, Deng-Ping Fan, Peng Xu, Ming-Ming Cheng, Bowen Zhou, Luc Van Gool.<br />
  " SAM Struggles in Concealed Scenes -- Empirical Study on "Segment Anything"." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.06790)] 
  [2023.04]

- Wei Ji, Jingjing Li, Qi Bi, Wenbo Li, Li Cheng.<br />
  "Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05750)] 
  [2023.04]

- **CLIP Surgery:** Yi Li, Hualiang Wang, Yiqun Duan, Xiaomeng Li.<br />
  "CLIP Surgery for Better Explainability with Enhancement in Open-Vocabulary Tasks." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05653)] 
  [[code]( https://github.com/xmed-lab/CLIP_Surgery)]
  [2023.04]

- **SAMM:** Yihao Liu, Jiaming Zhang, Zhangcong She, Amir Kheradmand, Mehran Armand.<br />
  "SAMM (Segment Any Medical Model): A 3D Slicer Integration to SAM." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05622)] 
  [[code]( https://github.com/bingogome/samm)]
  [2023.04]

- **SAM.MD:** Saikat Roy, Tassilo Wald, Gregor Koehler, Maximilian R. Rokuss, Nico Disch, Julius Holzschuh, David Zimmerer, Klaus H. Maier-Hein.<br />
  "SAM.MD: Zero-shot medical image segmentation capabilities of the Segment Anything Model." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.05396)] 
  [2023.04]


- **SAM vs BET:** Sovesh Mohapatra, Advait Gosai, Gottfried Schlaug.<br />
  "SAM vs BET: A Comparative Study for Brain Extraction and Segmentation of Magnetic Resonance Images using Deep Learning." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.04738)] 
  [2023.04]

- **SAMCOD:** Lv Tang, Haoke Xiao, Bo Li.<br />
  "Can SAM Segment Anything? When SAM Meets Camouflaged Object Detection." ArXiv (2023).
  [[paper]( https://arxiv.org/abs/2304.04709)] 
  [[code]( https://github.com/luckybird1994/SAMCOD)]
  [2023.04]


## Open Source Projects
| No. | Project | Title | Project page | Code base | Affiliation | Description |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 001 | SAM | Segment Anything | [Project page](https://segment-anything.com/)  | [Code](https://github.com/facebookresearch/segment-anything) | Meta | A foundation model for general segmentation. |
| 002 | SAM-Track | Segment and Track Anything | [Colab](https://colab.research.google.com/drive/1R10N70AJaslzADFqb-a5OihYkllWEVxB?usp=sharing)  |  [Code](https://github.com/z-x-yang/Segment-and-Track-Anything)   |   Zhejiang University    |    A  project dedicated to tracking and segmenting any objects in videos, either automatically or interactively. |
| 003  |  Grounded-SAM  |  Grounded-Segment-Anything  |  [Colab](https://github.com/camenduru/grounded-segment-anything-colab)   |  [Code](https://github.com/IDEA-Research/Grounded-Segment-Anything)    |  IDEA-Research   |    A project by combining Grounding DINO and SAM which aims to detect and segment Anything with text inputs. |
| 004  |  MMDet-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmdet_sam)    |   OpenMMLab    |    A new way of instance segmentation by combining SAM with Closed-Set Object Detection, Open-Vocabulary Object Detection, Grounding Object Detection. |
| 005  |  MMRotate-SAM  |  Zero-shot Oriented Object Detection with SAM  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmrotate_sam)    |   OpenMMLab    |    A project join SAM and weakly supervised horizontal box detection to achieve rotated box detection. |
| 006  |  MMOCR-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmocr_sam)    |   OpenMMLab    |    A solution of Text Detection/Recognition and SAM that segments every text character, with striking text removal and text inpainting demos driven by diffusion models and Gradio. |
| 007  |  MMEditing-SAM  |  -  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/mmagic_sam)    |   OpenMMLab    |    A project join SAM and image generation to create awesome images and edit any part of them. |
|  008  |  Label-Studio-SAM  |  OpenMMLab PlayGround: Semi-Automated Annotation with Label-Studio and SAM  |  -   |  [Code](https://github.com/open-mmlab/playground/tree/main/label_anything)    |   OpenMMLab     |    A project combining Label-Studio and SAM to achieve semi-automated annotation. |
|  009  |  PaddleSeg  |  Segment Anything with PaddleSeg  |  -   |  [Code](https://github.com/PaddlePaddle/PaddleSeg/tree/release/2.8/contrib/SegmentAnything)   |   PaddlePaddle   |    A pretrained model parameters of PaddlePaddle format.|
| 010  |  SegGPT  |  Segmenting Everything In Context  |  [Hugging Face](https://huggingface.co/spaces/BAAI/SegGPT)   |  [Code](https://github.com/baaivision/Painter)    |   BAAI-Vision    |    SAM In Context based on Painter. |
| 011  |  SEEM  |  Segment Everything Everywhere All at Once  |  [Hugging Face](https://huggingface.co/spaces/xdecoder/SEEM)   |  [Code](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)    |   Microsoft    |    A project can Segment Everything Everywhere with Multi-modal prompts all at once. |
| 012  |  CLIP Surgery  |  CLIP Surgery for Better Explainability with Enhancement in Open Vocabulary Tasks   |  [Project page](https://github.com/xmed-lab/CLIP_Surgery/blob/master/demo.ipynb)   |  [Code](https://github.com/xmed-lab/CLIP_Surgery)    |   HKUST    |    A work about SAM based on CLIP's explainability to achieve text to mask without manual points. |
| 013  |  SAMCOD  | Can SAM Segment Anything? When SAM Meets Camouflaged Object Detection |-|[Code](https://github.com/luckybird1994/SAMCOD)|-|SAM +Camouflaged object detection (COD) task.|
| 014  |  Inpaint Anything  |  Segment Anything Meets Image Inpainting  |  [Hugging Face](https://huggingface.co/spaces/InpaintAI/Inpaint-Anything)  |  [Code](https://github.com/geekyutao/Inpaint-Anything)    |   USTC and EIT    |    SAM combines Inpainting, which is able to remove the object smoothly. |
|  015  |  PerSAM  |  Personalize Segment Anything Model with One Shot  |  [Hugging Face](https://huggingface.co/papers/2305.03048)   |  [Code](https://github.com/ZrrSkywalker/Personalize-SAM)    |    -   |  SAM with specific concepts.  |
| 016  |  MedSAM  |  Segment Anything in Medical Images|  -   |  [Code](https://github.com/bowang-lab/MedSAM)    |   -    |    A step-by-step tutorial with a small dataset to help you quickly utilize SAM. |
| 017  |  Segment-Any-Anomaly  |  GroundedSAM Anomaly Detection  |  [Colab](https://colab.research.google.com/drive/1Rwio_KfziuLp79Qh_ugum64Hjnq4ZwsE?usp=sharing)  |  [Code](https://github.com/caoyunkang/Segment-Any-Anomaly)    |   HUST   |    Grounding DINO + SAM to segment any anomaly. |
| 018  |   SSA  |  Semantic Segment Anything  |  -   |  [Code](https://github.com/fudan-zvg/Semantic-Segment-Anything)    |   Fudan University    |    A dense category annotation engine. |
| 019  |  Magic Copy  |  -  |  -   |  [Code](https://github.com/kevmo314/magic-copy)    |   -   |    Magic Copy is a Chrome extension that uses SAM to extract a foreground object from an image and copy it to the clipboard. |
| 020  |  Segment Anything with Clip  |  Segment Anything with Clip  |  [Hugging Face](https://huggingface.co/spaces/curt-park/segment-anything-with-clip)   |  [Code](https://github.com/Curt-Park/segment-anything-with-clip)    |   -    |    SAM combined with CLIP. |
| 021  |  MetaSeg  |  Segment Anything Video|  [Hugging Face](https://huggingface.co/spaces/ArtGAN/Segment-Anything-Video)   |  [Code](https://github.com/kadirnar/segment-anything-video)   |   -    |   Packaged version of the SAM. |
| 022 |  SAM in Napari  |  Segment Anything Model (SAM) in Napari  |  [Project page](https://www.napari-hub.org/plugins/napari-sam)   |  [Code](https://github.com/MIC-DKFZ/napari-sam)    |   Applied Computer Vision Lab and German Cancer Research Center   |    Extended SAM's click-based foreground separation to full click-based semantic segmentation and instance segmentation. |
| 023  |  SAM Medical Imaging  |  SAM Medical Imaging  |  -   | [Code](https://github.com/amine0110/SAM-Medical-Imaging)    |   - | SAM for Medical Imaging.|
|  024  |  3D-Box  |  3D-Box via Segment Anything  |  -   |  [Code](https://github.com/dvlab-research/3D-Box-Segment-Anything)    |   -    |    SAM is extended to 3D perception by combining it with VoxelNeXt. |
| 025  |  Anything-3D  |  -  |  -   |  [Code](https://github.com/Anything-of-anything/Anything-3D)    |   -    |    Anything 3DNovel View, Anything-NeRF, Any 3DFace. |
| 026  |  L2SET  |  Learning to Segment EveryThing  |   -   |  [Code](https://github.com/ronghanghu/seg_every_thing)   |  UC Berkeley, FAIR    |   A new partially supervised training paradigm for instance segmentation. |
| 027  |  Edit Anything  |  Edit Anything by Segment-Anything  |  -   |  [Code](https://github.com/sail-sg/EditAnything)    |   -    |    Edit anything in images powered by SAM, ControlNet, StableDiffusion, \etc. |
| 028  |  Image Edit Anything  |  IEA: Image Editing Anything  |  -   |  [Code](https://github.com/feizc/IEA)    |   -    |  Using stable diffusion and SAM for image editing.   |
| 029  |  SAM for Stable Diffusion Webui  |  Segment Anything for Stable Diffusion WebUI  |  -   |  [Code](https://github.com/continue-revolution/sd-webui-segment-anything)   |   -    |    This extension aim for connecting AUTOMATIC1111 Stable Diffusion WebUI and Mikubill ControlNet Extension with SAM and GroundingDINO to enhance Stable Diffusion/ControlNet inpainting. |
| 030  |  Earth Observation Tools  |  Segment Anything EO tools  |  [Colab](https://colab.research.google.com/drive/1RC1V68tD1O-YissBq9nOvS2PHEjAsFkA?usp=share_link)   |  [Code](https://github.com/aliaksandr960/segment-anything-eo)    |   -    |    An earth observation tools for SAM. |
| 031  |  Moving Object Detection  |  Towards Segmenting Anything That Moves  |  -   |  [Code](https://github.com/achalddave/segment-any-moving) | - | A project about SAM + Moving Object Detection.|
|  032  |  OCR-SAM  |  Optical Character Recognition with Segment Anything  | [Project page](https://www.zhihu.com/question/593914819/answer/2976012032) | [Code](https://github.com/yeungchenwa/OCR-SAM)   |   -    |  Combining MMOCR with SAM and Stable Diffusion. |
| 033  |  SALT  |  Segment Anything Labelling Tool  |  -   |  [Code](https://github.com/anuragxel/salt#segment-anything-labelling-tool-salt)    |   -    |   A project uses the SAM Model and adds a barebones interface to label images and saves the masks in the COCO format. |
|  034  |  Prompt Segment Anything  |  Prompt Segment Anything  |  -   |  [Code](https://github.com/RockeyCoss/Prompt-Segment-Anything)    |   -    |    An implementation of zero-shot instance segmentation using SAM. |
| 035  |  SAM-RBox  |  -  |  -   |  [Code](https://github.com/Li-Qingyun/sam-mmrotate)    |   -    |   A project uses SAM for generating rotated bounding boxes with MMRotate, which is a comparison method of H2RBox-v2. |
| 036  |  VISAM  |  MOTRv2: Bootstrapping End-to-End Multi-Object Tracking by Pretrained Object Detectors  |-|[Code](https://github.com/BingfengYan/VISAM) |-|   Combining SAM with MOT, it create the era of "MOTS". |
| 037  |  SegEO  |  Segment Anything EO tools  |  -   |  [Code](https://github.com/aliaksandr960/segment-anything-eo)    |   -    |    The tools are developed to ease the processing of spatial data (GeoTIFF and TMS) with SAM using sliding window algorithm for big files. |
| 038  |  Napari Segment Anything |  Napari Segment Anything  |  [Project page](https://app.codecov.io/gh/jookuma/napari-segment-anything)   |  [Code](https://github.com/JoOkuma/napari-segment-anything)    |   -    |    SAM native Qt UI. |
| 039  |  Segment-Anything-U-Specify  |  Segment-Anything-U-Specify  |  -   |  [Code](https://github.com/MaybeShewill-CV/segment-anything-u-specify)    |   -    |  Using CLIP and SAM to segment any instance you specify with text prompt of any instance names. |
|  040  |  SegDrawer  |  Simple static web-based mask drawer  |  [Colab](https://colab.research.google.com/drive/1PdWCpBgYwiQtvkdTBnW-y2T-s_Fc-2iI?usp=sharing)  |  [Code](https://github.com/lujiazho/SegDrawer)    |   -    |    Simple static web-based mask drawer, supporting semantic segmentation with SAM. |
| 041  |  Track Anything  |  Segment Anything Meets Videos  |  [Hugging Face](https://huggingface.co/spaces/VIPLab/Track-Anything)   |  [Code](https://github.com/gaomingqi/Track-Anything)    |   SUSTech    | Track-Anything is a flexible and interactive tool for video object tracking and segmentation. |
| 042  |  Count Anything  |  -  |  -   |  [Code](https://github.com/ylqi/Count-Anything)   |   -    |    A method uses SAM and CLIP to ground and count any object that matches a custom text prompt, without requiring any point or box annotation. |
|  043  |  RAM  |  Relate Anything Model   |  [Hugging Face](https://huggingface.co/spaces/mmlab-ntu/relate-anything-model)   |  [Code](https://github.com/Luodian/RelateAnything)    |   MMLab, NTU and VisCom Lab, KCL/TongJi    |    Relate Anything Model is capable of taking an image as input and utilizing SAM to identify the corresponding mask within the image. |
| 044  |  Segment Any RGBD  |  Segment Any RGBD  |  [Project page](https://github.com/Jun-CEN/SegmentAnyRGBD)   |   [Code](https://huggingface.co/spaces/jcenaa/Segment-Any-RGBD)   |   -    |   Segment AnyRGBD is a toolbox to segment rendered depth images based on SAM. |
|  045  |  Show Anything  |  Show Anything  |  [Hugging Face](https://huggingface.co/spaces/weijiawu/ImageEditAnything)  |  [Code](https://github.com/showlab/ShowAnything)    |   Showlab, NUS    |    Some Applications that are compatible with both SAM and Generation. |
| 046  |  Transfer Any Style|  Any-to-Any Style Transfer: Making Picasso and Da Vinci Collaborate  |  -   |  [Code](https://github.com/Huage001/Transfer-Any-Style)    |   LV-lab, NUS    |   An interactive demo based on Segment-Anything for style transfer which enables different content regions apply different styles. |
| 047  |  Caption Anything  |  -  |  [Colab](https://colab.research.google.com/github/ttengwang/Caption-Anything/blob/main/notebooks/tutorial.ipynb)  |   [Code](https://github.com/ttengwang/Caption-Anything)   |  VIP lab, SUSTech   |    Caption-Anything is a versatile image processing tool that combines the capabilities of SAM, Visual Captioning, and ChatGPT.  |
|  048  |  Image2Paragraph  |  Transform Image Into Unique Paragraph  |  [Project page](https://zhaohengyuan1.github.io/image2paragraph.github.io/)  |  [Code](https://github.com/showlab/Image2Paragraph)  |  -  |  Transform Image into Unique Paragraph with ChatGPT, BLIP2, OFA, GRIT, Segment Anything, ControlNet. |
| 049    |  LIME SAM  |  Local Interpretable Model-agnostic Explanations Segment Anything  |  [Colab](https://colab.research.google.com/drive/1bj6B-O47NHpqsWovOrVZcpWNhIfO56sj?usp=sharing)  |  [Code](https://github.com/jaydeep-work/LIME-SAM)  |  -  | LIME-SAM aims to create an Explainable Artificial Intelligence (XAI) framework for image classification using LIME (Local Interpretable Model-agnostic Explanations) as the base algorithm, with the super-pixel method replaced by SAM. |
|  050  |  Paint Anything  |  -  |  -  |  [Code](https://github.com/Huage001/Paint-Anything)  |  -  |  An interactive demo based on SAM for stroke-based painting which enables human-like painting. |
| 051  |  SAMed  |  Customized Segment Anything Model for Medical Image Segmentation  |  [Colab](https://colab.research.google.com/drive/1KCS5ulpZasYl9DgJJn59WsGEB8vwSI_m?usp=sharing)  |  [Code](https://github.com/hitachinsk/SAMed)  |  USTC  |  SAMed is built upon the large-scale image segmentation model, SAM, to explore the new research paradigm of customizing large-scale models for medical image segmentation. |
| 052  |  Personalize SAM  |  Personalize Segment Anything with 1 Shot in 10 Seconds  |  [Hugging Face](https://huggingface.co/spaces/justin-zk/Personalize-SAM)  |  [Code](https://github.com/ZrrSkywalker/Personalize-SAM)  |  MMLab, CUHK  |  A training-free Personalization approach for SAM, termed as PerSAM. Given only a single image with a reference mask, PerSAM can segment specific visual concepts. |
| 053  |  Open-vocabulary-Segment-Anything  | Open-vocabulary-Segment-Anything  |  -  |  [Code](https://github.com/ngthanhtin/owlvit_segment_anything)  |  -  |  Combining OwlViT with Segment Anything - Open-vocabulary Detection and Segmentation (Text-conditioned, and Image-conditioned). |
| 054  |  Labal-Anything-Pipeline  |  Label-Anything-Pipeline |  -  |  [Code](https://github.com/Yuqifan1117/Labal-Anything-Pipeline)  |  ZJU  |  Annotation anything in visual tasks just all in one-pipeline with GPT-4 and SAM. |
| 055  |  Grounded-Segment-Any-Parts  |  Grounded Segment Anything: From Objects to Parts  |  [Project page](https://cheems-seminar.github.io/)  |  [Code](https://github.com/Cheems-Seminar/grounded-segment-any-parts)  |  HKU  |  Expand Segment Anything Model (SAM) to support text prompt input. The text prompt could be object-level(eg, dog) and part-level(eg, dog head).  |
| 056  |  AnyLabeling  |  AnyLabeling  |  [Youtube page](https://www.youtube.com/watch?v=5qVJiYNX5Kk)  |  [Code](https://github.com/vietanhdev/anylabeling)  |  -  |  Effortless AI-assisted data labeling with AI support from Segment Anything and YOLO. |
| 057  |  SSA |  Semantic-Segment-Anything  |  [Project page](https://replicate.com/cjwbw/semantic-segment-anything)  |  [Code](https://github.com/fudan-zvg/Semantic-Segment-Anything)  |  -  |  Automated dense category annotation engine that serves as the initial semantic labeling for the Segment Anything dataset (SA-1B). |
| 058  |  RefSAM |  Label Data with Segment Anything in Roboflow  |  [Project page](https://blog.roboflow.com/label-data-segment-anything-model-sam/)   |  [Code](https://github.com/helblazer811/RefSAM)  |  -  |  Referring Image Segmentation Benchmarking with Segment Anything Model (SAM). |
| 059  |  Roboflow Annotate |  Launch: Label Data with Segment Anything in Roboflow  |  [Project page](https://blog.roboflow.com/label-data-segment-anything-model-sam/)  |  [APP](https://app.roboflow.com/)  |  Roboflow  |  SAM-assisted labeling for training computer vision models. |
| 060  |  ImageBind SAM |  -  |  -  |  [Code](https://github.com/IDEA-Research/Grounded-Segment-Anything/tree/main/playground/ImageBind_SAM)  |  IDEA-Research  |  This is an experimental demo aims to combine ImageBind and SAM to generate mask with different modalities. |
| 061  | X-AnyLabeling	|   X-AnyLabeling	|  [WeChat](https://mp.weixin.qq.com/s/Fi7i4kw0n_QsA7AgmtP-JQ) | 	[Code](https://github.com/CVHub520/X-AnyLabeling)	| CVHub	| A new interactive automatic labeling tool based on AnyLabeling.|
| 062  |Segment Anything + NNCF |	-	| [WeChat](https://mp.weixin.qq.com/s/LrUx1HEYPCU41k5VZDa7fg) |	[Code](https://github.com/openvinotoolkit/openvino_notebooks/blob/main/notebooks/237-segment-anything/237-segment-anything.ipynb)	 |  -	 | OpenVINO™ NNCF for segment anything encoder quantization acceleration.|
| 063  |YOLOv8 + SAM	|  - | 	[WeChat](https://mp.weixin.qq.com/s/-rbsvGfc-Q8LZANzUWwn-A) |	-	| - |	Use SAM in YOLOv8. |
| 064  |SearchAnything|  SearchAnything | [Zhihu blog](https://zhuanlan.zhihu.com/p/641128049), [Twitter](https://twitter.com/jd92wang/status/1676114619168067585)	 |[Code](https://github.com/Immortalise/SearchAnything)	| CAS and MSRA |	A semantic local search engine powered by various AI models. |
| 065  |SAM Meets Stable Diffusion 	|  - | 	[WeChat](https://mp.weixin.qq.com/s/HBl-PBdi4Hi6z4Z2FjiYIA) |	[Code](https://aistudio.baidu.com/aistudio/projectdetail/6300584)	| PaddlePaddle |	Segment and generate Anything. |
| 066  |Language Segment-Anything| - | - | [Code](https://github.com/luca-medeiros/lang-segment-anything) | - | SAM with text prompts generates masks for specific objects in images. |
| 067  |Expedit-SAM| - | - | [Code](https://github.com/Expedit-LargeScale-Vision-Transformer/Expedit-SAM) | - | Expediting SAM without Fine-tuning. |
| 068  |Segment-Anything-Fast |  Accelerating Generative AI with PyTorch: Segment Anything, Fast  |  [Project page](https://pytorch.org/blog/accelerating-generative-ai/)  |  [Code](https://github.com/pytorch-labs/segment-anything-fast)  | Team PyTorch | A batched offline inference oriented version of segment-anything. |

## Awesome Repositories for SAM
- [VainF/Awesome-Anything](https://github.com/VainF/Awesome-Anything)
- [Hedlen/Awesome Segment Anything](https://github.com/Hedlen/awesome-segment-anything)
- [Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything](https://github.com/Vision-Intelligence-and-Robots-Group/Awesome-Segment-Anything)
- [JerryX1110/Awesome-segment-anything-extensions](https://github.com/JerryX1110/awesome-segment-anything-extensions)
- [dk-liang/Awesome-Segment-Anything](https://github.com/dk-liang/Awesome-Segment-Anything)


## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.
