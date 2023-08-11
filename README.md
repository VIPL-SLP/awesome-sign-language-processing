# awesome-gesture-recognition

collecting related resources of gesture recognition here.

- 【Wiki】[Gesture_recognition](https://en.wikipedia.org/wiki/Gesture_recognition)
- 【hand pose estimation/tracking】[xinghaochen/awesome-hand-pose-estimation](https://github.com/xinghaochen/awesome-hand-pose-estimation)


## Contents

- [Datasets](#datasets)
- [Journal Papers](#journal-papers)
- [Conference Papers](#conference-papers)
- [arXiv Papers](#arXiv-papers)

## Datasets

- 【challenges related to gesture recognition】[chalearn old website](http://gesture.chalearn.org/); [chalearn new website](http://chalearnlap.cvc.uab.es/)
- [Chalearn LAP IsoGD Database](http://www.cbsr.ia.ac.cn/users/jwan/database/isogd.html)
- [Chalearn LAP ConGD Database](http://www.cbsr.ia.ac.cn/users/jwan/database/congd.html)
- [NVIDIA Dynamic Hand Gesture Dataset](https://research.nvidia.com/publication/online-detection-and-classification-dynamic-hand-gestures-recurrent-3d-convolutional) [[Overview]](dataset/Overview_NVGesture.md)
- [SHREC 2017](http://www-rech.telecom-lille.fr/shrec2017-hand/) [[Overview]](dataset/Overview_SHREC17.md)
- [Devisign](http://vipl.ict.ac.cn/homepage/ksl/data.html)

## Conference Papers
### 2023
- 【ICCV 2023】CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition.  
*Peiqi Jiao, Yuecong Min, Yanan Li, Xiaotao Wang, Lei Lei, Xilin Chen*
- 【ICCV 2023】Human Part-wise 3D Motion Context Learning for Sign Language Recognition.       
*Taeryung Lee, Yeonguk Oh and Kyoung Mu Lee*  
- 【ICCV 2023】C2ST: Cross-modal Contextualized Sequence Transduction for Continuous Sign Language Recognition.   
*Huaiwen Zhang, Zihang Guo, Yang Yang, Xin Liu, De Hu*
- 【ICCV 2023】Gloss-free Sign Language Translation: Improving from Visual-Language Pretraining.[[paper]](https://arxiv.org/abs/2307.14768)   
*Benjia Zhou, Zhigang Chen, Albert Clapés, Jun Wan, Yanyan Liang, Sergio Escalera, Zhen Lei, Du Zhang*  
- 【ACL 2023】Neural Machine Translation Methods for Translating Text to Sign Language Glosses. [[paper]](https://aclanthology.org/2023.acl-long.700/)  
*Dele Zhu, Vera Czehmann, Eleftherios Avramidis*
- 【ACL 2023】Gloss-Free End-to-End Sign Language Translation.[[paper]](https://aclanthology.org/2023.acl-long.722/)  
*Kezhou Lin, Xiaohan Wang, Linchao Zhu, Ke Sun, Bang Zhang, Yi Yang*
- 【ACL 2023】Considerations for meaningful sign language machine translation based on glosses.[[paper]](https://aclanthology.org/2023.acl-short.60/)  
*Mathias Müller, Zifan Jiang, Amit Moryossef, Annette Rios, Sarah Ebling*
- 【ACL 2023】 Listen, Decipher and Sign: Toward Unsupervised Speech-to-Sign Language Recognition.[[paper]](https://aclanthology.org/2023.findings-acl.424/)  
*Liming Wang, Junrui Ni, Heting Gao, Jialu Li, Kai Chieh Chang, Xulin Fan, Junkai Wu, Mark Hasegawa-Johnson, Chang Yoo*
- 【ACL 2023】ISLTranslate: Dataset for Translating Indian Sign Language. [[paper]](https://aclanthology.org/2023.findings-acl.665/)
*Abhinav Joshi, Susmit Agrawal, Ashutosh Modi*
- 【ICLR 2023】SLTUNET: A Simple Unified Model for Sign Language Translation.[[paper]](https://openreview.net/forum?id=EBS4C77p_5S) [[code]](https://github.com/bzhangGo/sltunet)     
*Biao Zhang, Mathias Müller, Rico Sennrich*
- 【CVPR 2023】 Natural Language-Assisted Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zuo_Natural_Language-Assisted_Sign_Language_Recognition_CVPR_2023_paper.html)[[code]](https://github.com/FangyunWei/SLRT/tree/main/NLA-SLR)     
*Ronglai Zuo, Fangyun Wei, Brian Mak*
- 【CVPR 2023】 CiCo: Domain-Aware Sign Language Retrieval via Cross-Lingual Contrastive Learning.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Bao_CiCo_Domain-Aware_Sign_Language_Retrieval_via_Cross-Lingual_Contrastive_Learning_CVPR_2023_paper.html)[[code]](https://github.com/FangyunWei/SLRT/tree/main/CiCo)     
*Yiting Cheng, Fangyun Wei, Jianmin Bao, Dong Chen, Wenqiang Zhang*
- 【CVPR 2023】 CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html)     
*Jiangbin Zheng, Yile Wang, Cheng Tan, Siyuan Li, Ge Wang, Jun Xia, Yidong Chen, Stan Li*
- 【CVPR 2023】 Gloss Attention for Gloss-free Sign Language Translation.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yin_Gloss_Attention_for_Gloss-Free_Sign_Language_Translation_CVPR_2023_paper.html)     
*Aoxiong Yin, Tianyun Zhong, Li Tang, Weike Jin, Tao Jin, Zhou Zhao*
- 【CVPR 2023】 Continuous Sign Language Recognition with Correlation Network.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Hu_Continuous_Sign_Language_Recognition_With_Correlation_Network_CVPR_2023_paper.html)     
*Lianyu Hu, Liqing Gao, Zekang Liu, Wei Feng*
- 【CVPR 2023】 Distilling Cross-Temporal Contexts for Continuous Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Guo_Distilling_Cross-Temporal_Contexts_for_Continuous_Sign_Language_Recognition_CVPR_2023_paper.html)     
*Leming Guo, Wanli Xue, Qing Guo, Bo Liu, Kaihua Zhang, Tiantian Yuan, Shengyong Chen*
- 【CVPR 2023】 Ham2Pose: Animating Sign Language Notation into Pose Sequences. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Arkushin_Ham2Pose_Animating_Sign_Language_Notation_Into_Pose_Sequences_CVPR_2023_paper.html)     
*Rotem Shalev Arkushin, Amit Moryossef, Ohad Fried*
- 【CVPR 2023】 QPGesture: Quantization-Based and Phase-Guided Motion Matching for Natural Speech-Driven Gesture Generation.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_QPGesture_Quantization-Based_and_Phase-Guided_Motion_Matching_for_Natural_Speech-Driven_Gesture_CVPR_2023_paper.html)     
*SiCheng Yang, Zhiyong Wu, Minglei Li, Zhensong Zhang, Lei Hao, Weihong Bao, Haolin Zhuang*
- 【CVPR 2023】 Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zhu_Taming_Diffusion_Models_for_Audio-Driven_Co-Speech_Gesture_Generation_CVPR_2023_paper.html)     
*Lingting Zhu, Xian Liu, Xuanyu Liu, Rui Qian, Ziwei Liu, Lequan Yu*
- 【CVPR 2023】 Diverse 3D Hand Gesture Prediction from Body Dynamics by Bilateral Hand Disentanglement.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Qi_Diverse_3D_Hand_Gesture_Prediction_From_Body_Dynamics_by_Bilateral_CVPR_2023_paper.html)     
*Xingqun Qi, Chen Liu, Muyi Sun, Lincheng Li, Changjie Fan, Xin Yu*
- 【CVPR 2023】 Co-speech Gesture Synthesis by Reinforcement Learning with Contrastive Pre-trained Rewards.[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Sun_Co-Speech_Gesture_Synthesis_by_Reinforcement_Learning_With_Contrastive_Pre-Trained_Rewards_CVPR_2023_paper.html)     
*Mingyang Sun, Mengchen Zhao, Yaqing Hou, Minglei Li, Huang Xu, Songcen Xu, Jianye HAO*


### 2022
- 【EMNLP 2022】Open-Domain Sign Language Translation Learned from Online Video.[[paper]](https://arxiv.org/abs/2205.12870)[[code]](https://github.com/chevalierNoir/OpenASL)   
*Bowen Shi, Diane Brentari, Greg Shakhnarovich, Karen Livescu*
- 【NeurIPS 2022】 Addressing Resource Scarcity across Sign Languages with Multilingual Pretraining and Unified-Vocabulary Datasets.[[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/eb011fd258c763c44d8c6a0e9ce04f17-Abstract-Datasets_and_Benchmarks.html)     
*Gokul NC, Manideep Ladi, Sumit Negi, Prem Selvaraj, Pratyush Kumar, Mitesh Khapra*
- 【NeurIPS 2022】Two-Stream Network for Sign Language Recognition and Translation.[[paper]](https://openreview.net/forum?id=hSxK-4KGLbI) [[code]](https://github.com/FangyunWei/SLRT/tree/main/TwoStreamNetwork)     
*Yutong Chen, Ronglai Zuo, Fangyun Wei, Yu Wu, Shujie Liu, Brian Mak*
- 【BMVC 2022】Signing Outside the Studio: Benchmarking Background
Robustness for Continuous Sign Language Recognition.[[paper]](https://bmvc2022.mpi-inf.mpg.de/0322.pdf)    
*Youngjoon Jang, Youngtaek Oh, Jae Won Cho, Dong-Jin Kim, Joon Son Chung, In So Kweon*   
- 【BMVC 2022】Weakly-supervised Fingerspelling Recognition in British Sign Language Videos.[[paper]](https://bmvc2022.mpi-inf.mpg.de/0609.pdf)    
*K R Prajwal, Hannah Bull, Liliane Momeni, Samuel Albanie, Gül Varol, Andrew Zisserman*    
- 【BMVC 2022】Towards more efficient few-shot learning based human
gesture recognition via dynamic vision sensors.[[paper]](https://bmvc2022.mpi-inf.mpg.de/0938.pdf)    
*Linglin Jing, Yifan Wang, Tailin Chen, Shirin Dora, Zhigang Ji, Hui Fang*    
- 【BMVC 2022】Continuous Hand Gesture Recognition using Deep Coarse
and Fine Hand Features.[[paper]](https://bmvc2022.mpi-inf.mpg.de/1055.pdf)        
*Hazem Wannous, Jean-Philippe Vandeborre* 
- 【ECCV 2022】Deep Radial Embedding for Visual Sequence Learning. [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5670_ECCV_2022_paper.php)      
  *Yuecong Min, Peiqi Jiao, Yanan Li, Wang Xiaotao, Lei Lei, Xiujuan Chai, Xilin Chen*
- 【ECCV 2022】Temporal Lift Pooling for Continuous Sign Language Recognition.[[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/160_ECCV_2022_paper.php)      
  *Lianyu Hu, Liqing Gao, Zekang Liu, Wei Feng*     
- 【ECCV 2022】Automatic dense annotation of large-vocabulary sign language videos.[[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1028_ECCV_2022_paper.php)      
  *Liliane Momeni, Hannah Bull, Prajwal K R, Samuel Albanie, Gul Varol, Andrew Zisserman*    
- 【ECCV 2022】BEAT: A Large-Scale Semantic and Emotional Multi-Modal Dataset for Conversational Gestures Synthesis.[[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/296_ECCV_2022_paper.php)      
  *Haiyang Liu, Zihao Zhu, Naoya Iwamoto, Yichen Peng, Zhengqing Li, You Zhou, Elif Bozkurt, Bo Zheng*
- 【ECCV 2022】Audio-Driven Stylized Gesture Generation with Flow-Based Model.[[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3948_ECCV_2022_paper.php)       
  *Sheng Ye, Yu-Hui Wen, Yanan Sun, Ying He, Ziyang Zhang, Yaoyuan Wang, Weihua He, Yong-Jin Liu*

- 【CVPR 2022】MLSLT: Towards Multilingual Sign Language Translation.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Yin_MLSLT_Towards_Multilingual_Sign_Language_Translation_CVPR_2022_paper.html)          
  *Aoxiong Yin, Zhou Zhao, Weike Jin, Meng Zhang, Xingshan Zeng, Xiaofei He*
- 【CVPR 2022】A Simple Multi-Modality Transfer Learning Baseline for Sign Language Translation.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_A_Simple_Multi-Modality_Transfer_Learning_Baseline_for_Sign_Language_Translation_CVPR_2022_paper.html)      
  *Yutong Chen, Fangyun Wei, Xiao Sun, Zhirong Wu, Stephen Lin*
- 【CVPR 2022】C2SLR: Consistency-Enhanced Continuous Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html)          
  *Ronglai Zuo, Brian Mak*
- 【CVPR 2022】Signing at Scale: Learning to Co-Articulate Signs for Large-Scale Photo-Realistic Sign Language Production.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Saunders_Signing_at_Scale_Learning_to_Co-Articulate_Signs_for_Large-Scale_Photo-Realistic_CVPR_2022_paper.html)     
  *Ben Saunders, Necati Cihan Camgoz, Richard Bowden*
- 【CVPR 2022】LD-ConGR: A Large RGB-D Video Dataset for Long-Distance Continuous Gesture Recognition.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_LD-ConGR_A_Large_RGB-D_Video_Dataset_for_Long-Distance_Continuous_Gesture_CVPR_2022_paper.html)     
  *Dan Liu; Libo Zhang; Yanjun Wu*
- 【CVPR 2022】Audio-Driven Neural Gesture Reenactment With Video Motion Graphs.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Zhou_Audio-Driven_Neural_Gesture_Reenactment_With_Video_Motion_Graphs_CVPR_2022_paper.html)    
  *Yang Zhou; Jimei Yang; Dingzeyu Li; Jun Saito; Deepali Aneja; Evangelos Kalogerakis*
- 【CVPR 2022】Learning Hierarchical Cross-Modal Association for Co-Speech Gesture Generation.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Learning_Hierarchical_Cross-Modal_Association_for_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)   
  *Xian Liu; Qianyi Wu; Hang Zhou; Yinghao Xu; Rui Qian; Xinyi Lin; Xiaowei Zhou; Wayne Wu; Bo Dai; Bolei Zhou*
- 【CVPR 2022】SEEG: Semantic Energized Co-Speech Gesture Generation.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liang_SEEG_Semantic_Energized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)   
  *Yuanzhi Liang; Qianyu Feng; Linchao Zhu; Li Hu; Pan Pan; Yi Yang*
- 【CVPR 2022】Low-Resource Adaptation for Personalized Co-Speech Gesture Generation.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)       
  *Chaitanya Ahuja; Dong Won Lee; Louis-Philippe Morency*
- 【AAAI 2022】Learning Unseen Emotions from Gestures via Semantically-Conditioned Zero-Shot Perception with Adversarial Autoencoders.[[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)    
  *Abhishek Banerjee, Uttaran Bhattacharya, Aniket Bera*
- 【WACV 2022】Sign Language Translation With Hierarchical Spatio-Temporal Graph Neural Network.[[paper]](https://openaccess.thecvf.com/content/WACV2022/html/Kan_Sign_Language_Translation_With_Hierarchical_Spatio-Temporal_Graph_Neural_Network_WACV_2022_paper.html)   
  *Jichao Kan, Kun Hu, Markus Hagenbuchner, Ah Chung Tsoi, Mohammed Bennamoun, Zhiyong Wang*

### 2021

- 【ICCV 2021】YouRefIt: Embodied Reference Understanding With Language and Gesture.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_YouRefIt_Embodied_Reference_Understanding_With_Language_and_Gesture_ICCV_2021_paper.html)    
   *Yixin Chen; Qing Li; Deqian Kong; Yik Lun Kei; Song-Chun Zhu; Tao Gao; Yixin Zhu; Siyuan Huang*
- 【ICCV 2021】Speech Drives Templates: Co-Speech Gesture Synthesis With Learned Templates.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Qian_Speech_Drives_Templates_Co-Speech_Gesture_Synthesis_With_Learned_Templates_ICCV_2021_paper.html)     
   *Shenhan Qian; Zhi Tu; Yihao Zhi; Wen Liu; Shenghua Gao*
- 【ICCV 2021】Audio2Gestures: Generating Diverse Gestures From Speech Audio With Conditional Variational Autoencoders.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Li_Audio2Gestures_Generating_Diverse_Gestures_From_Speech_Audio_With_Conditional_Variational_ICCV_2021_paper.html)    
   *Jing Li; Di Kang; Wenjie Pei; Xuefei Zhe; Ying Zhang; Zhenyu He; Linchao Bao*
- 【ICCV 2021】Aligning Subtitles in Sign Language Videos.[[paper]](https://arxiv.org/abs/2105.02877)     
   *Hannah Bull; Triantafyllos Afouras; Gül Varol; Samuel Albanie; Liliane Momeni; Andrew Zisserman*
- 【ICCV 2021】Mixed SIGNals: Sign Language Production via a Mixture of Motion Primitives.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Saunders_Mixed_SIGNals_Sign_Language_Production_via_a_Mixture_of_Motion_ICCV_2021_paper.html)    
   *Ben Saunders; Necati Cihan Camgoz; Richard Bowden*
- 【ICCV 2021】SignBERT: Pre-Training of Hand-Model-Aware Representation for Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_SignBERT_Pre-Training_of_Hand-Model-Aware_Representation_for_Sign_Language_Recognition_ICCV_2021_paper.html)    
   *Hezhen Hu; Weichao Zhao; Wengang Zhou; Yuechen Wang; Houqiang Li*
- 【ICCV 2021】Visual Alignment Constraint for Continuous Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Min_Visual_Alignment_Constraint_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) [[code]](https://github.com/ycmin95/VAC_CSLR)    
   *Yuecong Min, Aiming Hao, Xiujuan Chai, and Xilin Chen*
- 【ICCV 2021】Self-Mutual Distillation Learning for Continuous Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_Self-Mutual_Distillation_Learning_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html)    
  *Aiming Hao, Yuecong Min, and Xilin Chen*
- 【ACM MM 2021】Contrastive Disentangled Meta-Learning for Signer-Independent Sign Language Translation.[[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475456)   
  *Tao Jin, Zhou Zhao*
- 【ACM MM 2021】Towards Fast and High-Quality Sign Language Production.[[paper]](https://dl.acm.org/doi/10.1145/3474085.3475463)    
  *Wencan Huang, Wenwen Pan, Zhou Zhao, Qi Tian*
- 【ACM MM 2021】SimulSLT: End-to-End Simultaneous Sign Language Translation.[[paper]](https://arxiv.org/abs/2112.04228)     
  *Aoxiong Yin, Zhou Zhao, Jinglin Liu, Weike Jin, Meng Zhang, Xingshan Zeng, Xiaofei He*
- 【ACM MM 2021】Skeleton-Aware Neural Sign Language Translation.[[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475577)      
  *Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Lei Xie, Sanglu Lu*
- 【ACM MM 2021】Speech2AffectiveGestures: Synthesizing Co-Speech Gestures with Generative Adversarial Affective Expression Learning.[[paper]](https://arxiv.org/abs/2108.00262)    
  *Uttaran Bhattacharya, Elizabeth Childs, Nicholas S Rewkowski, Dinesh Manocha*
- 【CVPR 2021】Improving Sign Language Translation With Monolingual Data by Sign Back-Translation.[[paper]](https://arxiv.org/abs/2105.12397)    
  *Hao Zhou, Wengang Zhou, Weizhen Qi, Junfu Pu, Houqiang Li*
- 【CVPR 2021】How2Sign: A Large-Scale Multimodal Dataset for Continuous American Sign Language.[[paper]](https://arxiv.org/abs/2008.08143)   
  *Amanda Duarte, Shruti Palaskar, Lucas Ventura, Deepti Ghadiyaram, Kenneth DeHaan, Florian Metze, Jordi Torres, Xavier Giro-i-Nieto*
- 【CVPR 2021】Fingerspelling Detection in American Sign Language. [[paper]](https://arxiv.org/abs/2104.01291)    
  *Bowen Shi, Diane Brentari, Greg Shakhnarovich, Karen Livescu*
- 【CVPR 2021】 Read and Attend: Temporal Localisation in Sign Language Videos.[[paper]](https://arxiv.org/abs/2103.16481)    
  *Gül Varol, Liliane Momeni, Samuel Albanie, Triantafyllos Afouras, Andrew Zisserman*
- 【CVPR 2021】iMiGUE: An Identity-Free Video Dataset for Micro-Gesture Understanding and Emotion Analysis.[[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_iMiGUE_An_Identity-Free_Video_Dataset_for_Micro-Gesture_Understanding_and_Emotion_CVPR_2021_paper.html)    
  *Xin Liu, Henglin Shi, Haoyu Chen, Zitong Yu, Xiaobai Li, Guoying Zhao*
- 【CVPR 2021】Body2Hands: Learning To Infer 3D Hands From Conversational Gesture Body Dynamics. [[paper]](https://arxiv.org/abs/2007.12287)  
  *Evonne Ng, Shiry Ginosar, Trevor Darrell, Hanbyul Joo*
- 【CVPR 2021】Model-Aware Gesture-to-Gesture Translation.[[paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Model-Aware_Gesture-to-Gesture_Translation_CVPR_2021_paper.html)   
  *Hezhen Hu, Weilun Wang, Wengang Zhou, Weichao Zhao, Houqiang Li*
- 【AAAI 2021】Hand-Model-Aware Sign Language Recognition.[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16247)    
  *Hezhen Hu, Wengang Zhou, Houqiang Li*
- 【AAAI 2021】 Regional Attention with Architecture-Rebuilt 3D Network for RGB-D Gesture Recognition.[[paper]](https://arxiv.org/pdf/2102.05348.pdf)    
  *Benjia Zhou, Yunan Li, Jun Wan*
- 【WACV 2021】 Hand Pose Guided 3D Pooling for Word-level Sign Language Recognition.[[paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Hosain_Hand_Pose_Guided_3D_Pooling_for_Word-Level_Sign_Language_Recognition_WACV_2021_paper.pdf)     
  *Al Amin Hosain; Panneer Selvam Santhalingam; Parth Pathak; Huzefa Rangwala; Jana Kosecka*
- 【WACV 2021】Whose hand is this? Person Identification from Egocentric Hand Gestures.[[paper]](https://arxiv.org/abs/2011.08900)        
  *Satoshi Tsutsui; Yanwei Fu; David Crandall*

### 2020

- 【ACM MM 2020】INCLUDE: A Large Scale Dataset for Indian Sign Language Recognition.[[paper]](https://dl.acm.org/doi/abs/10.1145/3394171.3413528)    
  *Sridhar, Advaith, Rohith Gandhi Ganesan, Pratyush Kumar, and Mitesh Khapra*
- 【ACM MM 2020】Boosting Continuous Sign Language Recognition via Cross Modality Augmentation.[[paper]](https://arxiv.org/pdf/2010.05264.pdf)    
  *Pu, Junfu, Wengang Zhou, Hezhen Hu, and Houqiang Li*
- 【ACM MM 2020】Recognizing Camera Wearer from Hand Gestures in Egocentric Videos.[[paper]](http://www.cse.iitd.ac.in/~chetan/papers/daksh-mm-2020.pdf)    
  *Thapar, Daksh, Aditya Nigam, and Chetan Arora*
- 【NeurIPS 2020】TSPNet: Hierarchical Feature Learning via Temporal Semantic Pyramid for Sign Language Translation. [[paper]](https://proceedings.neurips.cc/paper/2020/file/8c00dee24c9878fea090ed070b44f1ab-Paper.pdf)    
  *Li, Dongxu, Chenchen Xu, Xin Yu, Kaihao Zhang, Benjamin Swift, Hanna Suominen, and Hongdong Li*
- 【FG 2020】Feature Selection for Zero-Shot Gesture Recognition. [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a309/1kecI8r1WXC)    
  *Naveen Madapana, Juan Wachs*
- 【FG 2020】Image-Based Pose Representation for Action Recognition and Hand Gesture Recognition. [[paper]]()    
  *Zeyi Lin, Wei Zhang, Xiaoming Deng, Cuixia Ma, Hongan Wang*
- 【FG 2020】Neural Sign Language Translation by Learning Tokenization. [[paper]](https://arxiv.org/pdf/2002.00479.pdf)     
   *Orbay, Alptekin, and Lale Akarun* 
- 【FG 2020】Sign Language Recognition in Virtual Reality. [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a185/1kecI0aXAje)     
  *Jacob Schioppo, Zachary Meyer, Diego Fabiano, Shaun Canavan*
- 【FG 2020】SILFA: Sign Language Facial Action Database for the Development of Assistive Technologies for the Deaf.[[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a382/1kecIdR70Y0)    
  *Emely Pujólli da Silva, Paula Dornhofer Paro Costa, Kate Mamhy Oliveira Kumada, José Mario De Martino*
- 【FG 2020】FineHand: Learning Hand Shapes for American Sign Language Recognition. [[paper]](https://arxiv.org/pdf/2003.08753.pdf)    
  *Al Amin Hosain, Panneer Selvam Santhalingam, Parth Pathak, Huzefa Rangwala, Jana Košecká*
- 【FG 2020】Introduction and Analysis of an Event-Based Sign Language Dataset [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a441/1kecIyj5b0c)    
  *Ajay Vasudevan, Pablo Negri, Bernabe Linares-Barranco, Teresa Serrano-Gotarredona*
- 【FG 2020】Towards a Visual Sign Language Dataset for Home Care Services. [[paper]](https://www.computer.org/csdl/proceedings-article/fg/2020/307900a622/1kecIMIW1Bm)    
  *D. Kosmopoulos, I. Oikonomidis, C. Constantinopoulos, N. Arvanitis, K. Antzakas, A. Bifis, G. Lydakis, A. Roussos, A. Argyros*
- 【ECCV 2020】 [SLRTP 2020](https://slrtp.com/) Sign language recognition, translation & production. [[Accepted papers]](SLRTP_acccepted_list.md)
- 【ECCV 2020】BSL-1K: Scaling up co-articulated sign language recognition using mouthing cues.[[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560035.pdf)    
  *Samuel Albanie, Gül Varol, Liliane Momeni, Triantafyllos Afouras, Joon Son Chung, Neil Fox, Andrew Zisserman*
- 【ECCV 2020】Progressive Transformers for End-to-End Sign Language Production.[[paper](https://arxiv.org/pdf/2004.14874.pdf)]    
  *Ben Saunders, Necati Cihan Camgoz, and Richard Bowden*
- 【ECCV 2020】Stochastic Fine-grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition.[[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610171.pdf)   
  *Niu Zhe, Brian Mak*
- 【ECCV 2020】Fully Convolutional Networks for Continuous Sign Language Recognition.[[paper](https://arxiv.org/pdf/2007.12402v1.pdf)]   
  *Ka Leong Cheng, Zhaoyang Yang, Qifeng Chen, and Yu-Wing Tai*
- 【ECCV 2020】 Collaborative Learning of Gesture Recognition and 3D Hand Pose Estimation with Multi-Order Feature Analysis.[[paper]](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480766.pdf)    
  *Yang, Siyuan, Jun Liu, Shijian Lu, Meng Hwa Er, and Alex C. Kot.*
- 【ECCV 2020】Style Transfer for Co-Speech Gesture Animation: A Multi-Speaker Conditional-Mixture Approach. [[paper]](https://arxiv.org/pdf/2007.12553.pdf)    
  *Chaitanya Ahuja, Dong Won Lee, Yukiko I. Nakano, and Louis-Philippe Morency*
- 【ECCV 2020】Towards Efficient Coarse-to-Fine Networks for Action and Gesture Recognition.[[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750035.pdf)     
  *Quader, Niamul, Juwei Lu, Peng Dai, and Wei Li*
- 【CVPR 2020】Decoupled Representation Learning for Skeleton-Based Gesture Recognition.[[paper]](<http://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Decoupled_Representation_Learning_for_Skeleton-Based_Gesture_Recognition_CVPR_2020_paper.pdf>)  
  *Jianbo Liu, Yongcheng Liu, Ying Wang, Véronique Prinet, Shiming Xiang, Chunhong Pan*
- 【CVPR 2020】An Efficient PointLSTM for Point Clouds Based Gesture Recognition.[[paper]](<http://openaccess.thecvf.com/content_CVPR_2020/papers/Min_An_Efficient_PointLSTM_for_Point_Clouds_Based_Gesture_Recognition_CVPR_2020_paper.pdf>)  
  *Yuecong Min, Yanxiao Zhang, Xiujuan Chai, Xilin Chen*
- 【CVPR 2020】Music Gesture for Visual Sound Separation. [[paper]](<https://arxiv.org/pdf/2004.09476.pdf>)  
  *Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba*	
- 【CVPR 2020】Transferring Cross-Domain Knowledge for Video Sign Language Recognition.[[paper]](<https://arxiv.org/pdf/2003.03703.pdf>)  
  *Dongxu Li, Xin Yu, Chenchen Xu, Lars Petersson, Hongdong Li*	
- 【CVPR 2020] Sign Language Transformers: Joint End-to-End Sign Language Recognition and Translation.[[paper]](<https://arxiv.org/pdf/2003.13830.pdf>)   
  *Necati Cihan Camgöz, Oscar Koller, Simon Hadfield, Richard Bowden*	
- 【AAAI 2020】Spatial-Temporal Multi-Cue Network for Continuous Sign Language Recognition. [[paper]](<https://arxiv.org/pdf/2002.03187.pdf>)  
  *Hao Zhou, Wengang Zhou, Yun Zhou, Houqiang Li* 
- 【WACV 2020】Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison.  [[paper]](<http://openaccess.thecvf.com/content_WACV_2020/papers/Li_Word-level_Deep_Sign_Language_Recognition_from_Video_A_New_Large-scale_WACV_2020_paper.pdf>)  
  *Dongxu Li, Cristian Rodriguez, Xin Yu, Hongdong Li*
- 【WACV 2020】Neural Sign Language Synthesis: Words Are Our Glosses. [[paper]](<http://openaccess.thecvf.com/content_WACV_2020/papers/Zelinka_Neural_Sign_Language_Synthesis_Words_Are_Our_Glosses_WACV_2020_paper.pdf>)  
  *Jan Zelinka, Jakub Kanis*

### 2019

- 【ICCV 2019】Talking With Hands 16.2M: A Large-Scale Dataset of Synchronized Body-Finger Motion and Audio for Conversational Motion Analysis and Synthesis. [[paper]]( http://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Talking_With_Hands_16.2M_A_Large-Scale_Dataset_of_Synchronized_Body-Finger_ICCV_2019_paper.pdf )   
   *Gilwoo Lee, Zhiwei Deng, Shugao Ma, Takaaki Shiratori, Siddhartha S. Srinivasa, Yaser Sheikh*
- 【ICCV 2019】Drive&Act: A Multi-Modal Dataset for Fine-Grained Driver Behavior Recognition in Autonomous Vehicles. [[paper]]( http://openaccess.thecvf.com/content_ICCV_2019/html/Martin_DriveAct_A_Multi-Modal_Dataset_for_Fine-Grained_Driver_Behavior_Recognition_in_ICCV_2019_paper.html )   
   *Manuel Martin, Alina Roitberg, Monica Haurilet, Matthias Horne, Simon Reiss, Michael Voit, Rainer Stiefelhagen*

- 【CVPR 2019】Improving the Performance of Unimodal Dynamic Hand-Gesture Recognition With Multimodal Training. [[paper]](<http://openaccess.thecvf.com/content_CVPR_2019/papers/Abavisani_Improving_the_Performance_of_Unimodal_Dynamic_Hand-Gesture_Recognition_With_Multimodal_CVPR_2019_paper.pdf>)  
   *Mahdi Abavisani, Hamid Reza Vaezi Joze, Vishal M. Patel*
- 【CVPR 2019】Learning Individual Styles of Conversational Gesture. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ginosar_Learning_Individual_Styles_of_Conversational_Gesture_CVPR_2019_paper.pdf)  
   *Shiry Ginosar, Amir Bar, Gefen Kohavi, Caroline Chan, Andrew Owens, Jitendra Malik*
- 【CVPR 2019】A Neural Network Based on SPD Manifold Learning for Skeleton-Based Hand Gesture Recognition. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Nguyen_A_Neural_Network_Based_on_SPD_Manifold_Learning_for_Skeleton-Based_CVPR_2019_paper.pdf)  
   *Xuan Son Nguyen, Luc Brun, Olivier Lezoray, Sebastien Bougleux*
- 【CVPR 2019】Iterative Alignment Network for Continuous Sign Language Recognition. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pu_Iterative_Alignment_Network_for_Continuous_Sign_Language_Recognition_CVPR_2019_paper.pdf)  
   *Junfu Pu, Wengang Zhou, Houqiang Li*
- 【BMVC 2019】Construct Dynamic Graphs for Hand Gesture Recognition via Spatial-Temporal Attention. [[paper]](https://bmvc2019.org/wp-content/uploads/papers/0281-paper.pdf)  
   *Yuxiao Chen, Long Zhao, Xi Peng, Jianbo Yuan, Dimitris Metaxas*
- 【BMVC 2019】FlickerNet: Adaptive 3D Gesture Recognition from Sparse Point Clouds.[[paper]](https://bmvc2019.org/wp-content/uploads/papers/0326-paper.pdf)  
   *Yuecong Min, Xiujuan Chai, Lei Zhao, Xilin Chen*
- 【BMVC 2019】Zero-Shot Sign Language Recognition: Can Textual Data Uncover Sign Languages?[[paper]](https://bmvc2019.org/wp-content/uploads/papers/0122-paper.pdf)  
   *Yunus Can Bilge, Nazli Ikizler-Cinbis, Ramazan Gokberk Cinbis*
- 【BMVC 2019】MS-ASL: A Large-Scale Data Set and Benchmark for Understanding American Sign Language. [[paper]](https://bmvc2019.org/wp-content/uploads/papers/0254-paper.pdf)  
   *HAMID VAEZI JOZE, Oscar Koller*
- 【WACV 2019】Space-time Event Clouds for Gesture Recognition: from RGB Cameras to Event Cameras. [[paper]](https://cse.buffalo.edu/~jsyuan/papers/2019/WACV_2019_Qinyi.pdf)  
   *Qinyi Wang, Yexin Zhang, Junsong Yuan, Yilong Lu*
- 【WACV 2019】Hidden States Exploration for 3D Skeleton-Based Gesture Recognition. [[paper]](http://jultika.oulu.fi/files/nbnfi-fe2019072923218.pdf)  
   *Xin Liu, Henglin Shi, Xiaopeng Hong, Haoyu Chen, Dacheng Tao, Guoying Zhao*


### 2018

- 【CVPR 2018】Gesture Recognition: Focus on the Hands. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Narayana_Gesture_Recognition_Focus_CVPR_2018_paper.pdf)  
  *Pradyumna Narayana, Ross Beveridge, Bruce A. Draper*
- 【CVPR 2018】Neural Sign Language Translation. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Camgoz_Neural_Sign_Language_CVPR_2018_paper.pdf)  
  *Necati Cihan Camgoz, Simon Hadfield, Oscar Koller, Hermann Ney, Richard Bowden* 
- 【CVPR 2018】Making Convolutional Networks Recurrent for Visual Sequence Learning. [[paper]](<http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_Making_Convolutional_Networks_CVPR_2018_paper.pdf>)  
  *Xiaodong Yang, Pavlo Molchanov, Jan Kautz*
- 【ECCV 2018】Deformable Pose Traversal Convolution for 3D Action and Gesture Recognition. [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Junwu_Weng_Deformable_Pose_Traversal_ECCV_2018_paper.pdf)  
  *Junwu Weng, Mengyuan Liu, Xudong Jiang, Junsong Yuan*
- 【BMVC 2018】Point Attention Network for Gesture Recognition Using Point Cloud Data. [[paper]](http://bmvc2018.org/contents/papers/0427.pdf)  
  *Cherdsak Kingkan, Joshua Owoyemi, Koichi Hashimoto* 
- 【BMVC 2018】Sign Language Production using Neural Machine Translation and Generative Adversarial Networks. [[paper]](http://bmvc2018.org/contents/papers/0906.pdf)  
  *Stephanie M Stoll, Necati Cihan Camgoz, Simon Hadfield, Richard Bowden*

### 2017

- 【CVPR 2017】Personalizing Gesture Recognition Using Hierarchical Bayesian Neural Networks. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Joshi_Personalizing_Gesture_Recognition_CVPR_2017_paper.pdf)  
  *Ajjen Joshi, Soumya Ghosh, Margrit Betke, Stan Sclaroff, Hanspeter Pfister*
- 【CVPR 2017】Re-Sign: Re-Aligned End-To-End Sequence Modelling With Deep Recurrent CNN-HMMs. [[paper]]( http://openaccess.thecvf.com/content_cvpr_2017/html/Koller_Re-Sign_Re-Aligned_End-To-End_CVPR_2017_paper.html )   
  *Oscar Koller, Sepehr Zargaran, Hermann Ney*
- 【CVPR 2017】A Low Power, Fully Event-Based Gesture Recognition System. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Amir_A_Low_Power_CVPR_2017_paper.pdf)  
  *Arnon Amir, Brian Taba, David Berg, Timothy Melano, Jeffrey McKinstry, Carmelo Di Nolfo, Tapan Nayak, Alexander Andreopoulos, Guillaume Garreau, Marcela Mendoza, Jeff Kusnitz, Michael Debole, Steve Esser, Tobi Delbruck, Myron Flickner, Dharmendra Modha*
- 【CVPR 2017】Recurrent Convolutional Neural Networks for Continuous Sign Language Recognition by Staged Optimization. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Cui_Recurrent_Convolutional_Neural_CVPR_2017_paper.pdf)  
  *Runpeng Cui, Hu Liu, Changshui Zhang*
- 【ICCV 2017】Egocentric Gesture Recognition Using Recurrent 3D Convolutional Neural Networks With Spatiotemporal Transformer Modules. [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Cao_Egocentric_Gesture_Recognition_ICCV_2017_paper.pdf)  
  *Congqi Cao, Yifan Zhang, Yi Wu, Hanqing Lu, Jian Cheng* 
- 【ICCV 2017】SubUNets: End-To-End Hand Shape and Continuous Sign Language Recognition. [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Camgoz_SubUNets_End-To-End_Hand_ICCV_2017_paper.pdf)  
  *Necati Cihan Camgoz, Simon Hadfield, Oscar Koller, Richard Bowden*

### 2016

- 【CVPR 2016】Online Detection and Classification of Dynamic Hand Gestures With Recurrent 3D Convolutional Neural Network. [[paper]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Molchanov_Online_Detection_and_CVPR_2016_paper.pdf)  
  *Pavlo Molchanov, Xiaodong Yang, Shalini Gupta, Kihwan Kim, Stephen Tyree, Jan Kautz*
- 【ECCV 2016】Iterative Reference Driven Metric Learning for Signer Independent Isolated Sign. [[paper]](http://vipl.ict.ac.cn/uploadfile/upload/2018112115134267.pdf)  
  *Fang Yin, Xiujuan Chai, Xilin Chen*
- 【BMVC 2016】Deep Sign: Hybrid CNN-HMM for Continuous Sign Language Recognition. [[paper]]( http://www.bmva.org/bmvc/2016/papers/paper136/index.html )  
  *Oscar Koller, Sepehr Zargaran, Hermann Ney and Richard Bowden*

## Journal Papers

- 【2022 TMM】Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation. [[paper]](https://ieeexplore.ieee.org/abstract/document/9954921/)    
*Hezhen Hu, Junfu Pu, Wengang Zhou, Houqiang Li*
- 【2021 TMM】Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation. [[paper]](https://ieeexplore.ieee.org/abstract/document/9354538/)    
  *Hao Zhou, Wengang Zhou, Yun Zhou, Houqiang Li*
- 【2020 IJCV】Text2Sign: Towards Sign Language Production Using Neural Machine Translation and Generative Adversarial Networks. [[paper]](<https://link.springer.com/content/pdf/10.1007%2Fs11263-019-01281-2.pdf>)   
  *Stephanie Stoll, Necati Cihan Camgoz, Simon Hadfield, Richard Bowden*
- 【2019 TPAMI】Weakly Supervised Learning with Multi-Stream CNN-LSTM-HMMs to Discover Sequential Parallelism in Sign Language Videos. [[paper]]( <https://www-i6.informatik.rwth-aachen.de/publications/download/1099/Koller-PAMI-2019.pdf>)    
  *Oscar Koller, Necati Cihan Camgoz, Hermann Ney, Richard Bowden*  
- 【2018 IJCV】Deep Sign: Enabling Robust Statistical Continuous Sign Language
  Recognition via Hybrid CNN-HMMs. [[paper]]( <https://www-i6.informatik.rwth-aachen.de/publications/download/1081/Koller-IJCV-2018.pdf>)    
  *Oscar Koller, Sepehr Zargaran, Hermann Ney, Richard Bowden*  
- 【2015 TCSVT】A Survey on 3D Hand Gesture Recognition. [[paper]]( http://www.academia.edu/download/48354754/1.pdf )    
  *Hong Cheng, Lu Yang, Zicheng Liu* 
- 【2015 CVIU】Recent Methods and Databases in Vision-based Hand Gesture Recognition: A Review. [[paper]]( https://www.researchgate.net/profile/Pramod_Pisharady/publication/284070092_Recent_methods_and_databases_in_vision-based_hand_gesture_recognition_A_review/links/59db8d320f7e9b1947ef77ee/Recent-methods-and-databases-in-vision-based-hand-gesture-recognition-A-review.pdf)    
  *Pramod Kumar Pisharady, Martin Saerbeck*
- 【2015 TPAMI】Moddrop: adaptive multi-modal gesture recognition. [[paper]]( <https://arxiv.org/pdf/1501.00102.pdf>)    
  *Natalia Neverova, Christian Wolf, Graham Taylor, Florian Nebout*  
- 【2010 TPAMI】Handling Movement Epenthesis and Segmentation Ambiguities in Sign Language Recognition Nested Dynamic Programming. [[paper]]( http://figment.csee.usf.edu/~sarkar/PDFs/YangSarkarLoedingTPAMI-2008-01-0026.pdf )    
  *Ruiduo Yang, Sudeep Sarkar,  Barbara Loeding* 
- 【2007 TSMC】Gesture Recognition: A Survey. [[paper]](<http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.107.6243&rep=rep1&type=pdf>)    
  *Sushmita Mitra, Tinku Acharya* 
- 【2005 TPAMI】Automatic Sign Language Analysis: A Survey and the Future beyond Lexical Meaning. [[paper]](https://pdfs.semanticscholar.org/852e/333b06fbe9ea5bf3dd1e894cad86283b94f7.pdf )    
  *Sylvie C.W. Ong,  Surendra Ranganath* 
- 【1999 TPAMI】An HMM-Based Threshold Model Approach for Gesture Recognition. [[paper]]( <http://compbio.fmph.uniba.sk/vyuka/gm/handouts/Lee1999.pdf> )   
  *Hyeon-Kyu Lee, Jin H. Kim*
- 【1997 TPAMI】Visual interpretation of hand gestures for human-computer interaction: A review. [[paper]]( https://www.semanticscholar.org/paper/Visual-Interpretation-of-Hand-Gestures-for-A-Review-Pavlovic-Sharma/8dd3d5ef2e1c40433417cd90e21ce9a0468a7626 )   
  *VI Pavlovic, R Sharma, TS Huang*

## arXiv Papers

### 2020

- 【arXiv:2003.08759】Facial Expression Phoenix (FePh): An Annotated Sequenced Dataset for Facial and Emotion-Specified Expressions in Sign Language. [[paper]](http://arxiv.org/pdf/2003.08759v2.pdf)    
  *Marie Alaghband, Niloofar Yousefi, Ivan Garibay*
- 【arXiv:2008.09918】Quantitative Survey of the State of the Art in Sign Language Recognition. [[paper]](http://arxiv.org/pdf/2008.09918v2.pdf)   
  *Oscar Koller*

### 2019

- 【arXiv:1901.00234】Analysis of Contraction Effort Level in EMG-Based Gesture 
  Recognition Using Hyperdimensional Computing. [[paper]](https://arxiv.org/pdf/1901.00234)  
  *Ali Moin, Andy Zhou, Simone Benatti, Abbas Rahimi, Luca Benini, Jan M. Rabaey*
- 【arXiv:1903.00100】Appearance-based Gesture recognition in the compressed domain. [[paper]](https://arxiv.org/pdf/1903.00100)  
  *Shaojie Xu, Anvesha Amaravati, Justin Romberg, Arijit Raychowdhury*
- 【arXiv:1901.02602】UAV-GESTURE: A Dataset for UAV Control and Gesture Recognition. [[paper]](https://arxiv.org/pdf/1901.02602.pdf)  
  *Asanka G Perera, Yee Wei Law, Javaan Chahl*
- 【arXiv:1901.04622】 Fast and Robust Dynamic Hand Gesture Recognition via Key Frames Extraction and Feature Fusion. [[paper]](https://arxiv.org/pdf/1901.04622)  
  *Hao Tang, Hong Liu, Wei Xiao, Nicu Sebe*
- 【arXiv:1901.06958】Domain Adaptation for sEMG-based Gesture Recognition with Recurrent Neural Networks. [[paper]](https://arxiv.org/pdf/1901.06958)  
  *Istvan Ketyko, Ferenc Kovacs and Krisztian Zsolt Varga*
- 【arXiv:1901.10323】Real-time Hand Gesture Detection and Classification Using Convolutional Neural Networks. [[paper]](https://arxiv.org/pdf/1901.10323) [[code]](https://github.com/ahmetgunduz/Real-time-GesRec)  
  *Okan Kopuklu, Ahmet Gunduz, Neslihan Kose2, Gerhard Rigoll*
- 【arXiv:1903.06643】GestureKeeper: Gesture Recognition for Controlling Devices in IoT Environments. [[paper]  ](https://arxiv.org/pdf/1903.06643)  
   *Vasileios Sideridis, Andrew Zacharakis, George Tzagkarakis, Maria Papadopouli*
- 【arXiv:1903.10422】Locomotion and gesture tracking in mice and small animals for neurosceince applications: A survey. [[paper]](https://arxiv.org/pdf/1903.10422)  
  *Waseem Abbas, David Masip Rodo*

### 2018

- 【arXiv:1801.01446】 IMU2Face: Real-time Gesture-driven Facial Reenactment. [[paper]](https://arxiv.org/pdf/1801.01446)  
  *Justus Thies, Michael Zollhöfer, Matthias Nießner .*
- 【arXiv:1801.07481】 Survey on Emotional Body Gesture Recognition. [[paper]](https://arxiv.org/abs/1801.07481)  
  *Fatemeh Noroozi, Ciprian Adrian Corneanu, Dorota Kamińska, Tomasz Sapiński, Sergio Escalera, Gholamreza Anbarjafari. *
- 【arXiv:1802.10237】 An EMG Gesture Recognition System with Flexible High-Density Sensors and  Brain-Inspired High-Dimensional Classifier. [[paper]](https://arxiv.org/abs/1802.10237)  
  *Ali Moin, Andy Zhou, Abbas Rahimi, Simone Benatti, Alisha Menon, Senam Tamakloe, Jonathan Ting, Natasha Yamamoto, Yasser Khan, Fred Burghardt, Luca Benini, Ana C. Arias, Jan M. Rabaey.*
- 【arXiv:1803.10435】 Exploiting Recurrent Neural Networks and Leap Motion Controller for Sign  Language and Semaphoric Gesture Recognition. [[paper]](https://arxiv.org/abs/1803.10435)  
  *Danilo Avola, Marco Bernardi, Luigi Cinque, Gian Luca Foresti, Cristiano Massaroni.*
- 【arXiv:1804.07187】 Motion Fused Frames: Data Level Fusion Strategy for Hand Gesture  Recognition. [[paper]](https://arxiv.org/pdf/1804.07187)  
  *Okan Köpüklü, Neslihan Köse, Gerhard Rigoll .*
- 【arXiv:1804.08859】 Spatiotemporal Learning of Dynamic Gestures from 3D Point Cloud Data. [[paper]](https://arxiv.org/pdf/1804.08859)  
  *Joshua Owoyemi, Koichi Hashimoto .*
- 【arXiv:1805.00721】 Joint Surgical Gesture and Task Classification with Multi-Task and  Multimodal Learning. [[paper]](https://arxiv.org/pdf/1805.00721)  
  *Duygu Sarikaya, Khurshid A. Guru, Jason J. Corso .*
- 【arXiv:1806.05653】 HGR-Net: A Two-stage Convolutional Neural Network for Hand Gesture  Segmentation and Recognition. [[paper]](https://arxiv.org/pdf/1806.05653)  
  *Amirhossein Dadashzadeh, Alireza Tavakoli Targhi, Maryam Tahmasbi .*
- 【arXiv:1806.08089】 Deep Reinforcement Learning for Surgical Gesture Segmentation and  Classification. [[paper]](https://arxiv.org/pdf/1806.08089)  
  *Daochang Liu, Tingting Jiang .*
- 【arXiv:1806.08641】 Compact Deep Neural Networks for Computationally Efficient Gesture  Classification From Electromyography Signals. [[paper]](https://arxiv.org/pdf/1806.08641)  
  *Adam Hartwell, Visakan Kadirkamanathan, Sean R Anderson .*
- 【arXiv:1808.00130】 FMCode: A 3D In-the-Air Finger Motion Based User Login Framework for  Gesture Interface. [[paper]](https://arxiv.org/pdf/1808.00130)  
  *Duo Lu, Dijiang Huang .*
- 【arXiv:1808.04859】 GestureGAN for Hand Gesture-to-Gesture Translation in the Wild. [[paper]](https://arxiv.org/pdf/1808.04859)  
  *Hao Tang, Wei Wang, Dan Xu, Yan Yan, Nicu Sebe .*
- 【arXiv:1808.05380】 Egocentric Gesture Recognition for Head-Mounted AR devices. [[paper]](https://arxiv.org/pdf/1808.05380)  
  *Tejo Chalasani, Jan Ondrej, Aljosa Smolic .*
- 【arXiv:1809.05839】 A Generic Multi-modal Dynamic Gesture Recognition System using Machine  Learning. [[paper]](https://arxiv.org/pdf/1809.05839)  
  *Gautham Krishna G, Karthik Subramanian Nathan, Yogesh Kumar B, Ankith A Prabhu, Ajay Kannan, Vineeth Vijayaraghavan .*
- 【arXiv:1809.05911】 Robust and customized methods for real-time hand gesture recognition  under object-occlusion. [[paper]](https://arxiv.org/pdf/1809.05911)  
  *Zhishuai Han, Xiaojuan Ban, Xiaokun Wang, Di wu .*
- 【arXiv:1810.11297】 Online Human Gesture Recognition using Recurrent Neural Networks and Wearable Sensors. [[paper]](https://arxiv.org/pdf/1810.11297)  
  *Alessandro Carfi, Carola Motolese, Barbara Bruno, Fulvio Mastrogiovanni .*
- 【arXiv:1810.12514】 DeepGRU: Deep Gesture Recognition Utility. [[paper]](https://arxiv.org/pdf/1810.12514)  
  *Mehran Maghoumi, Joseph J. LaViola Jr .*
- 【arXiv:1811.07081】 Skeleton-based Gesture Recognition Using Several Fully Connected Layers with Path Signature Features and Temporal Transformer Module. [[paper]](https://arxiv.org/pdf/1811.07081)  
  *Chenyang Li, Xin Zhang, Lufan Liao, Lianwen Jin, Weixin Yang .*
- 【arXiv:1811.07802】 Event-based Gesture Recognition with Dynamic Background Suppression using Smartphone Computational Capabilities. [[paper]](https://arxiv.org/pdf/1811.07802)  
  *Jean-Matthieu Maro, Ryad Benosman .*
- 【arXiv:1811.11997】 Hand Gesture Detection and Conversion to Speech and Text. [[paper]](https://arxiv.org/pdf/1811.11997)  
  *K. Manikandan, Ayush Patidar, Pallav Walia, Aneek Barman Roy .*
- 【arXiv:1811.12467】 Hand Gesture Recognition based on Radar Micro-Doppler Signature Envelopes. [[paper]](https://arxiv.org/pdf/1811.12467)  
  *Moeness G. Amin, Zhengxin Zeng, Tao Shan .*
- 【arXiv:1812.01766】 SolarGest: Ubiquitous and Battery-free Gesture Recognition using Solar Cells. [[paper]](https://arxiv.org/pdf/1812.01766)  
  *Dong Ma, Guohao Lan, Mahbub Hassan, Wen Hu, Mushfika B. Upama, Ashraf Uddin, Moustafa Youssef .*
- 【arXiv:1812.04513】 The Impact of Quantity of Training Data on Recognition of Eating Gestures. [[paper]](https://arxiv.org/pdf/1812.04513)  
  *Yiru Shen, Eric Muth, Adam Hoover .*
- 【arXiv:1812.06145】 Improving the Performance of Unimodal Dynamic Hand-Gesture Recognition with Multimodal Training. [[paper]](https://arxiv.org/pdf/1812.06145)  
  *Mahdi Abavisani, Hamid Reza Vaezi Joze, Vishal M. Patel .*
- 【arXiv:1812.09410】 Quantifying the Security of Recognition Passwords: Gestures and Signatures. [[paper]](https://arxiv.org/pdf/1812.09410)  
  *Can Liu, Shridatt Sugrim, Gradeigh D. Clark, Janne Lindqvist .*
- 【arXiv:1812.09595】 Kinect Sensor Based Gesture Recognition for Surveillance Application. [[paper]](https://arxiv.org/pdf/1812.09595)  
  *Biswarup Ganguly, Amit Konar .*

### 2017

- 【arXiv:1701.01814】 Large-scale Isolated Gesture Recognition Using Convolutional Neural  Networks. [[paper]](https://arxiv.org/abs/1701.01814)  
  *Pichao Wang, Wanqing Li, Song Liu, Zhimin Gao, Chang Tang, Philip Ogunbona.*
- 【arXiv:1701.05921】 What makes a gesture a gesture? Neural signatures involved in gesture  recognition. [[paper]](https://arxiv.org/pdf/1701.05921)  
  *Maria Cabrera, Keisha Novak, Daniel Foti, Richard Voyles, Juan Wachs.*
- 【arXiv:1701.05924】 Coherency in One-Shot Gesture Recognition. [[paper]](https://arxiv.org/abs/1701.05924)  
  *Maria Cabrera, Richard Voyles, Juan Wachs. *
- 【arXiv:1702.07371】 Feasibility of Principal Component Analysis in hand gesture recognition  system. [[paper]](https://arxiv.org/abs/1702.07371)  
  *Tanu Srivastava, Raj Shree Singh, Sunil Kumar, Pavan Chakraborty.*
- 【arXiv:1703.02931】 Fast Gesture Recognition with Multiple Stream Discrete HMMs on 3D  Skeletons. [[paper]](https://arxiv.org/abs/1703.02931)  
  *Guido Borghi, Roberto Vezzani, Rita Cucchiara.*
- 【arXiv:1704.00180】 Complexity-Aware Assignment of Latent Values in Discriminative Models  for Accurate Gesture Recognition. [[paper]](https://arxiv.org/abs/1704.00180)  
  *Manoel Horta Ribeiro, Bruno Teixeira, Antnio Otvio Fernandes, Wagner Meira Jr., Erickson R. Nascimento.*
- 【arXiv:1704.07296】 A Real-time Hand Gesture Recognition and Human-Computer Interaction  System. [[paper]](https://arxiv.org/abs/1704.07296)  
  *Pei Xu.*
- 【arXiv:1705.05884】 Static Gesture Recognition using Leap Motion. [[paper]](https://arxiv.org/abs/1705.05884)  
  *Babak Toghiani-Rizi, Christofer Lind, Maria Svensson, Marcus Windmark.*
- 【arXiv:1706.07530】 Multiresolution Match Kernels for Gesture Video Classification. [[paper]](https://arxiv.org/pdf/1706.07530)  
  *Hemanth Venkateswara, Vineeth N. Balasubramanian, Prasanth Lade, Sethuraman Panchanathan .*
- 【arXiv:1707.02605】 Detection of bimanual gestures everywhere: why it matters, what we need  and what is missing. [[paper]](https://arxiv.org/pdf/1707.02605)  
  *Divya Shah, Ernesto Denicia, Tiago Pimentel, Barbara Bruno, Fulvio Mastrogiovanni .*
- 【arXiv:1707.03692】 Deep Fisher Discriminant Learning for Mobile Hand Gesture Recognition. [[paper]](https://arxiv.org/abs/1707.03692)  
  *Chunyu Xie, Ce Li, Baochang Zhang, Chen Chen, Jungong Han.*
- 【arXiv:1707.06691】 Real-Time Head Gesture Recognition on Head-Mounted Displays using  Cascaded Hidden Markov Models. [[paper]](https://arxiv.org/abs/1707.06691)  
  *Jingbo Zhao, Robert S. Allison.*
- 【arXiv:1707.08569】 Wisture: RNN-based Learning of Wireless Signals for Gesture Recognition  in Unmodified Smartphones. [[paper]](https://arxiv.org/abs/1707.08569)  
  *Mohamed Abudulaziz Ali Haseeb, Ramviyas Parasuraman.*
- 【arXiv:1708.03278】 Motion Feature Augmented Recurrent Neural Network for Skeleton-based  Dynamic Hand Gesture Recognition. [[paper]](https://arxiv.org/abs/1708.03278)  
  *Xinghao Chen, Hengkai Guo, Guijin Wang, Li Zhang.*
- 【arXiv:1709.00727】 Hand Gesture Real Time Paint Tool - Box. [[paper]](https://arxiv.org/pdf/1709.00727)  
  *Vandit Gajjar, Viraj Mavani, Ayesha Gurnani .*
- 【arXiv:1709.06871】 Open Source Dataset and Deep Learning Models for Online Digit Gesture  Recognition on Touchscreens. [[paper]](https://arxiv.org/pdf/1709.06871)  
  *Philip J. Corr, Guenole C. Silvestre, Chris J. Bleakley .*
- 【arXiv:1710.01297】 Visual gesture variability between talkers in continuous visual speech. [[paper]](https://arxiv.org/pdf/1710.01297)  
  *Helen L Bear .*
- 【arXiv:1710.06836】 Using Deep Convolutional Networks for Gesture Recognition in American  Sign Language. [[paper]](https://arxiv.org/abs/1710.06836)  
  *Vivek Bheda, Dianna Radpour.*
- 【arXiv:1710.08623】 Hand Gesture Recognition Using Ultrasonic Waves. [[paper]](https://arxiv.org/abs/1710.08623)  
  *Mohammed H. AlSharif, Mohamed Saad, Tareq Y. Al-Naffouri.*
- 【arXiv:1710.09441】 High Five: Improving Gesture Recognition by Embracing Uncertainty. [[paper]](https://arxiv.org/abs/1710.09441)  
  *Diman Zad Tootaghaj, Adrian Sampson, Todd Mytkowicz, Kathryn S McKinley.*
- 【arXiv:1711.01968】 Deformable Deep Convolutional Generative Adversarial Network in  Microwave Based Hand Gesture Recognition System. [[paper]](https://arxiv.org/abs/1711.01968)  
  *Jiajun Zhang, Zhiguo Shi.*
- 【arXiv:1711.02254】 Doppler-Radar Based Hand Gesture Recognition System Using Convolutional  Neural Networks. [[paper]](https://arxiv.org/abs/1711.02254)  
  *Jiajun Zhang, Jinkun Tao, Jiangtao Huangfu, Zhiguo Shi.*
- 【arXiv:1711.04293】 Hand Gesture Recognition with Leap Motion. [[paper]](https://arxiv.org/abs/1711.04293)  
  *Youchen Du, Shenglan Liu, Lin Feng, Menghui Chen, Jie Wu.*
- 【arXiv:1712.00216】 Micro Hand Gesture Recognition System Using Ultrasonic Active Sensing. [[paper]](https://arxiv.org/abs/1712.00216)  
  *Yu Sang, Laixi Shi, Yimin Liu.*
- 【arXiv:1712.04961】 Real-time Egocentric Gesture Recognition on Mobile Head Mounted Displays. [[paper]](https://arxiv.org/abs/1712.04961)  
  *Rohit Pandey, Marie White, Pavel Pidlypenskyi, Xue Wang, Christine Kaeser-Chen.*
- 【arXiv:1712.10136】 Learning Deep and Compact Models for Gesture Recognition. [[paper]](https://arxiv.org/abs/1712.10136)  
  *Koustav Mullick, Anoop M. Namboodiri.*

### 2016

- 【arXiv:1603.06531】 Deep video gesture recognition using illumination invariants. [[paper]](https://arxiv.org/abs/1603.06531)  
  *Otkrist Gupta, Dan Raviv, Ramesh Raskar.*
- 【arXiv:1603.06829】 Multi-velocity neural networks for gesture recognition in videos. [[paper]](https://arxiv.org/abs/1603.06829)  
  *Otkrist Gupta, Dan Raviv, Ramesh Raskar.*
- 【arXiv:1605.08313】 A Light-powered, Always-On, Smart Camera with Compressed Domain Gesture  Detection. [[paper]](https://arxiv.org/pdf/1605.08313)  
  *Anvesha A, Shaojie Xu, Ningyuan Cao, Justin Romberg, Arijit Raychowdhury .*
- 【arXiv:1606.07247】 Human Computer Interaction Using Marker Based Hand Gesture Recognition. [[paper]](https://arxiv.org/abs/1606.07247)  
  *Sayem Mohammad Siam, Jahidul Adnan Sakel, Md. Hasanul Kabir.*
- 【arXiv:AlbSL】 Albanian Sign Language (AlbSL) Number Recognition from Both Hand's  Gestures Acquired by Kinect Sensors. [[paper]](AlbSL)  
  *Eriglen Gani, Alda Kika .*
- 【arXiv:1608.04080】 Dynamic Hand Gesture Recognition for Wearable Devices with Low  Complexity Recurrent Neural Networks. [[paper]](https://arxiv.org/abs/1608.04080)  
  *Sungho Shin, Wonyong Sung.*
- 【arXiv:1608.06338】 Large-scale Continuous Gesture Recognition Using Convolutional Neural  Networks. [[paper]](https://arxiv.org/abs/1608.06338)  
  *Pichao Wang, Wanqing Li, Song Liu, Yuyao Zhang, Zhimin Gao, Philip Ogunbona.*
- 【arXiv:1611.04138】 Hand Gesture Recognition for Contactless Device Control in Operating  Rooms. [[paper]](https://arxiv.org/abs/1611.04138)  
  *Ebrahim Nasr-Esfahani, Nader Karimi, S.M. Reza Soroushmehr, M. Hossein Jafari, M. Amin Khorsandi, Shadrokh Samavi, Kayvan Najarian.*
- 【arXiv:1611.06689】 Multi-Modality Fusion based on Consensus-Voting and 3D Convolution for  Isolated Gesture Recognition. [[paper]](https://arxiv.org/abs/1611.06689)  
  *Jiali Duan, Shuai Zhou, Jun Wan, Xiaoyuan Guo, Stan Z. Li.*
- 【arXiv:EXPRESSION】 Adaptive Down-Sampling and Dimension Reduction in Time Elastic Kernel  Machines for Efficient Recognition of Isolated Gestures. [[paper]](EXPRESSION)  
  *Pierre-François Marteau (EXPRESSION), Sylvie Gibet (EXPRESSION), Clément Reverdy (EXPRESSION) .*
- 【arXiv:1612.02889】 Gesture-based Bootstrapping for Egocentric Hand Segmentation. [[paper]](https://arxiv.org/pdf/1612.02889)  
  *Yubo Zhang, Vishnu Naresh Boddeti, Kris M. Kitani .*

### 2015

- 【arXiv:1501.00102】 ModDrop: adaptive multi-modal gesture recognition. [[paper]](https://arxiv.org/abs/1501.00102)  
  *Natalia Neverova, Christian Wolf, Graham W. Taylor, Florian Nebout.*
- 【arXiv:1501.04301】 WiGest: A Ubiquitous WiFi-based Gesture Recognition System. [[paper]](https://arxiv.org/abs/1501.04301)  
  *Heba Abdelnasser, Moustafa Youssef, Khaled A. Harras.*
- 【arXiv:1502.01228】 Linear-time Online Action Detection From 3D Skeletal Data Using Bags of  Gesturelets. [[paper]](https://arxiv.org/pdf/1502.01228)  
  *Moustafa Meshry, Mohamed E. Hussein, Marwan Torki .*
- 【arXiv:1502.07243】 Real-Time System of Hand Detection And Gesture Recognition In Cyber  Presence Interactive System For E-Learning. [[paper]](https://arxiv.org/abs/1502.07243)  
  *Bousaaid Mourad, Ayaou Tarik, Afdel Karim, Estraillier Pascal.*
- 【arXiv:1506.01911】 Beyond Temporal Pooling: Recurrence and Temporal Convolutions for  Gesture Recognition in Video. [[paper]](https://arxiv.org/abs/1506.01911)  
  *Lionel Pigou, A ron van den Oord, Sander Dieleman, Mieke Van Herreweghe, Joni Dambre.*
- 【arXiv:1506.08006】 Spectral Collaborative Representation based Classification for Hand  Gestures recognition on Electromyography Signals. [[paper]](https://arxiv.org/pdf/1506.08006)  
  *Ali Boyali .*
- 【arXiv:1507.05243】 Hand Gesture Recognition Library. [[paper]](https://arxiv.org/abs/1507.05243)  
  *Jonathan Fidelis Paul, Dibyabiva Seth, Cijo Paul, Jayati Ghosh Dastidar.*
- 【arXiv:1510.05879】 What's the point? Frame-wise Pointing Gesture Recognition with  Latent-Dynamic Conditional Random Fields. [[paper]](https://arxiv.org/abs/1510.05879)  
  *Christian Wittner, Boris Schauerte, Rainer Stiefelhagen.*
- 【arXiv:1512.00622】 Continuous and Simultaneous Gesture and Posture Recognition for  Commanding a Robotic Wheelchair; Towards Spotting the Signal Patterns. [[paper]](https://arxiv.org/pdf/1512.00622)  
  *Ali Boyali, Naohisa Hashimoto, Manolya Kavakli .*

### 2014

- 【arXiv:1401.02058】 Gesture recognition based mouse events. [[paper]](https://arxiv.org/abs/1401.02058)  
  *Rachit Puri.*
- 【arXiv:1402.05047】 Real-time Automatic Emotion Recognition from Body Gestures. [[paper]](https://arxiv.org/pdf/1402.05047)  
  *Stefano Piana, Alessandra Staglianò, Francesca Odone, Alessandro Verri, Antonio Camurri .*
- 【arXiv:1404.07594】 Selecting a Small Set of Optimal Gestures from an Extensive Lexicon. [[paper]](https://arxiv.org/pdf/1404.07594)  
  *Jacob Grosek, J. Nathan Kutz .*
- 【arXiv:1408.01549】 Real-Time Human-Computer Interaction Based on Face and Hand Gesture  Recognition. [[paper]](https://arxiv.org/pdf/1408.01549)  
  *Reza Azad, Babak Azad, Nabil Belhaj Khalifa, Shahram Jamali .*
- 【arXiv:1408.01759】 Real-Time and Robust Method for Hand Gesture Recognition System Based on  Cross-Correlation Coefficient. [[paper]](https://arxiv.org/abs/1408.01759)  
  *Reza Azad, Babak Azad, Iman Tavakoli Kazerooni.*
- 【arXiv:IRISA】 Down-Sampling coupled to Elastic Kernel Machines for Efficient  Recognition of Isolated Gestures. [[paper]](IRISA)  
  *Pierre-François Marteau (IRISA), Sylvie Gibet (IRISA), Clement Reverdy (IRISA) .*
- 【arXiv:1410.04485】 A Gesture Recognition System for Detecting Behavioral Patterns of ADHD. [[paper]](https://arxiv.org/abs/1410.04485)  
  *Miguel Ángel Bautista, Antonio Hernández-Vela, Sergio Escalera, Laura Igual, Oriol Pujol, Josep Moya, Verónica Violant, María Teresa Anguera.*
- 【arXiv:1411.05137】 Study of Gesture Recognition methods and augmented reality. [[paper]](https://arxiv.org/abs/1411.05137)  
  *Sandeep Vasave, Amol Plave.*
- 【arXiv:1411.05394】 Wi-Fi Gesture Recognition on Existing Devices. [[paper]](https://arxiv.org/abs/1411.05394)  
  *Rajalakshmi Nandakumar, Bryce Kellogg, Shyamnath Gollakota.*

### 2013

- 【arXiv:1301.04659】 English Sentence Recognition using Artificial Neural Network through  Mouse-based Gestures. [[paper]](https://arxiv.org/pdf/1301.04659)  
  *Firoj Parwej .*
- 【arXiv:1303.02292】 Intelligent Approaches to interact with Machines using Hand Gesture  Recognition in Natural way: A Survey. [[paper]](https://arxiv.org/pdf/1303.02292)  
  *Ankit Chaudhary, J. L. Raheja, Karen Das, Sonia Raheja .*
- 【arXiv:1303.06021】 Spatio-Temporal Covariance Descriptors for Action and Gesture  Recognition. [[paper]](https://arxiv.org/pdf/1303.06021)  
  *Andres Sanin, Conrad Sanderson, Mehrtash T. Harandi, Brian C. Lovell .*
- 【arXiv:1306.02599】 Hand Gesture Recognition Based on Karhunen-Loeve Transform. [[paper]](https://arxiv.org/abs/1306.02599)  
  *Joyeeta Singha, Karen Das.*
- 【arXiv:1308.00890】 Head Gesture Recognition using Optical Flow based Classification with  Reinforcement of GMM based Background Subtraction. [[paper]](https://arxiv.org/abs/1308.00890)  
  *Parimita Saikia, Karen Das.*
- 【arXiv:1309.02093】 High-level programming and control for industrial robotics: using a  hand-held accelerometer-based input device for gesture and posture  recognition. [[paper]](https://arxiv.org/pdf/1309.02093)  
  *Pedro Neto, Norberto Pires, Paulo Moreira .*
- 【arXiv:1310.04822】 Principal motion components for gesture recognition using a  single-example. [[paper]](https://arxiv.org/abs/1310.04822)  
  *Hugo Jair Escalante, Isabelle Guyon, Vassilis Athitsos, Pat Jangyodsuk, Jun Wan.*
- 【arXiv:1312.04190】 One-Shot-Learning Gesture Recognition using HOG-HOF Features. [[paper]](https://arxiv.org/abs/1312.04190)  
  *Jakub Konečný, Michal Hagara. *

### 2012

- Vision based hand gesture recognition for human computer interaction: a survey. [[paper]](http://cgvr.informatik.uni-bremen.de/teaching/studentprojects/nui4cars/wp-content/uploads/2013/06/survey_Agrawal_AI2012_handRecod.pdf) 
- 【arXiv:1211.04226】 Education for All: Remote testing system with gesture recognition and  recording. [[paper]](https://arxiv.org/abs/1211.04226)  
  *Rivindu Perera.*

#### 2011

- 【arXiv:1110.06287】 Deciding of HMM parameters based on number of critical points for  gesture recognition from motion capture data. [[paper]](https://arxiv.org/abs/1110.06287)  
  *Michał Cholewa, Przemysław Głomb.*

### 2010

- 【arXiv:1003.01819】 Facial Gesture Recognition Using Correlation And Mahalanobis Distance. [[paper]](https://arxiv.org/abs/1003.01819)  
  *Supriya Kapoor, Shruti Khanna, Rahul Bhatia.*
- 【arXiv:1012.00084】 Survey on Various Gesture Recognition Techniques for Interfacing  Machines Based on Ambient Intelligence. [[paper]](https://arxiv.org/abs/1012.00084)  
  *Harshith C, Karthik R. Shastry, Manoj Ravindran, M.V.V.N.S. Srikanth, Naveen Lakshmikhanth.*

### 2009

- 【arXiv:0906.05039】 A new approach for digit recognition based on hand gesture analysis. [[paper]](https://arxiv.org/pdf/0906.05039)  
  *Ahmed Ben Jmaa, Walid Mahdi, Yousra Ben Jemaa, Abdelmajid Ben Hamadou .*
- 【arXiv:0912.01830】 Gesture Recognition with a Focus on Important Actions by Using a Path  Searching Method in Weighted Graph. [[paper]](https://arxiv.org/abs/0912.01830)  
  *Kazumoto Tanaka.*

## books

### 2018
- [Robust hand gesture recognition for robotic hand control](http://gen.lib.rus.ec/book/index.php?md5=08BF4EBB10A3BD6B442BAF7F96903930)
- [Gesture recognition : principles, techniques and applications](http://gen.lib.rus.ec/book/index.php?md5=477739F41797033018FA20ED603EB5F0)

### 2017
- [Gesture Recognition](http://gen.lib.rus.ec/book/index.php?md5=55ECF03504C5E0EB1D5C0BBBA860AD37)

### 2005

- [Analysis and Modelling of Faces and Gestures: Second International Workshop, AMFG 2005, Beijing, China, October 16, 2005. Proceedings](http://gen.lib.rus.ec/book/index.php?md5=40E17BEC2EE98A25A51802FB42B47752)

### 2001

- [Face Detection and Gesture Recognition for Human-Computer Interaction](http://gen.lib.rus.ec/book/index.php?md5=E1ABFE65BA1D8740A610FB1E14D74C50)



---
## Frameworks & Toolkit
-  【c++】[Gesture Recognition Toolkit](http://www.nickgillian.com/grt/)

---
## Projects
- [tz28/Chinese-number-gestures-recognition](https://github.com/tz28/Chinese-number-gestures-recognition)
