# Awesome Sign Language Processing     

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

A curated list of sign language procesing (e.g., sign language recognition, sign language translation) and related area (e.g., speech translation, motion generation) resources. The [old version](README_old.md) can be found here.

- [Wiki] [Sign Language](https://en.wikipedia.org/wiki/Sign_language)
- [Wiki] [Sign Language Recognition](https://en.wikipedia.org/wiki/Sign_language_recognition)
- [Wiki] [Gesture_recognition](https://en.wikipedia.org/wiki/Gesture_recognition)
- [Wiki] [Sign Language Tranlsation](https://en.wikipedia.org/wiki/Machine_translation_of_sign_languages)
- [Resource] [jinwchoi/awesome-action-recognition](https://github.com/jinwchoi/awesome-action-recognition)
- [Resource] [xinghaochen/awesome-hand-pose-estimation](https://github.com/xinghaochen/awesome-hand-pose-estimation)
- [Resource] [OpenHuman-ai/awesome-gesture_generation](https://github.com/OpenHuman-ai/awesome-gesture_generation)
- [Resource] [zzw922cn/awesome-speech-recognition-speech-synthesis-papers](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers)

## Contents
- [Conference Paper](#conference-paper)
  - [Sign Language Recognition](#sign-language-recognition)
  - [Sign Language Translation](#sign-language-translation)
  - [Sign Language Production](#sign-language-production)
  - [Other Sign Language Topic](#other-sign-language-topic)
  - [Co-speech Gesture Generation](#co-speech-gesture-generation)
  - [Gesture Recognition](#gesture-recognition)
- [Sign Language Workshop](#sign-language-workshop)
- [Dataset](#dataset)

## Conference Paper

### Sign Language Recognition
- [CVPR 2025] VSNet: Focusing on the Linguistic Characteristics of Sign Language. [[paper]](https://cvpr.thecvf.com/virtual/2025/poster/33549)     
*YuHao Li, Xinyue Chen, Hongkai Li, Xiaorong Pu, Peng Jin, Yazhou Ren*
- [OpenReview]  Representing Signs as Signs: One-Shot ISLR to Facilitate Functional Sign Language Technologies. [[paper]](https://openreview.net/forum?id=flgrH5nK4H)    
  *Toon Vandendriessche, Mathieu De Coster, Annelies Lejon, Joni Dambre*
- [NeurIPS 2024] MM-WLAuslan: Multi-View Multi-Modal Word-Level Australian Sign Language Recognition Dataset. [[paper]](https://openreview.net/forum?id=tPsw4NeLZx)     
*Xin Shen, Heming Du, Hongwei Sheng, Shuyun Wang, Hui Chen, Huiqiang Chen, Zhuojie Wu, Xiaobiao Du, Jiaying Ying, Ruihan Lu, Qingzheng Xu, Xin Yu*
- [EMNLP 2024]  SignCLIP: Connecting Text and Sign Language by Contrastive Learning. [[paper]](https://aclanthology.org/2024.emnlp-main.518/)    
  *Zifan Jiang, Gerard Sant, Amit Moryossef, Mathias Müller, Rico Sennrich, Sarah Ebling*
- [EMNLP 2024]  Towards Online Continuous Sign Language Recognition and Translation. [[paper]](https://aclanthology.org/2024.emnlp-main.619/)    
  *Ronglai Zuo, Fangyun Wei, Brian Mak*
- [CVPR 2024]  SignGraph: A Sign Sequence is Worth Graphs of Nodes. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Gan_SignGraph_A_Sign_Sequence_is_Worth_Graphs_of_Nodes_CVPR_2024_paper.html) [[code]](https://github.com/gswycf/SignGraph/tree/main)    
  *Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Hongkai Wen, Kang Xia, Lei Xie, Sanglu Lu*
- [EMNLP Findings 2023]  Handshape-Aware Sign Language Recognition: Extended Datasets and Exploration of Handshape-Inclusive Methods. [[paper]](https://aclanthology.org/2023.findings-emnlp.198/)    
  *Xuan Zhang, Kevin Duh*
- [EMNLP Findings 2023] Making Body Movement in Sign Language Corpus Accessible for Linguists and Machines with Three-Dimensional Normalization of MediaPipe. [[paper]](https://aclanthology.org/2023.findings-emnlp.124/)    
  *Houda Bouamor, Juan Pino, Kalika Bali*
- [EMNLP Findings 2023] Linguistically Motivated Sign Language Segmentation. [[paper]](https://aclanthology.org/2023.findings-emnlp.846/)       
  *Amit Moryossef, Zifan Jiang, Mathias Müller, Sarah Ebling, Yoav Goldberg*
- [NeurIPS 2023 Dataset] ASL Citizen: A Community-Sourced Dataset for Advancing Isolated Sign Language Recognition. [[paper]](https://openreview.net/forum?id=zbEYTg2F1U)     
*Aashaka Desai, Lauren Berger, Fyodor O Minakov, Vanessa Milan, Chinmay Singh, Kriston L Pumphrey, Richard Ladner, Hal Daumé III, Alex Xijie Lu, Naomi Caselli, Danielle Bragg*
- [NeurIPS 2023 Dataset] PopSign ASL v1.0: An Isolated American Sign Language Dataset Collected via Smartphones. [[paper]](https://openreview.net/forum?id=yEf8NSqTPu)       
*Thad Starner, Sean Forbes, Matthew So, David Martin, Rohit Sridhar, Gururaj Deshpande, Sam Sepah, Sahir Shahryar, Khushi Bhardwaj, Tyler Kwok, Daksh Sehgal, Saad Hassan, Bill Neubauer, Sofia Anandi Vempala, Alec Tan, Jocelyn Heath, Unnathi Utpal Kumar, Priyanka Vijayaraghavan Mosur, Tavenner M. Hall, Rajandeep Singh et al.*
- [ICCV 2023] CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Jiao_CoSign_Exploring_Co-occurrence_Signals_in_Skeleton-based_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html)       
*Peiqi Jiao, Yuecong Min, Yanan Li, Xiaotao Wang, Lei Lei, Xilin Chen*
- [ICCV 2023] Human Part-wise 3D Motion Context Learning for Sign Language Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Lee_Human_Part-wise_3D_Motion_Context_Learning_for_Sign_Language_Recognition_ICCV_2023_paper.html)       
*Taeryung Lee, Yeonguk Oh and Kyoung Mu Lee*  
- [ICCV 2023] Improving Continuous Sign Language Recognition with Cross-Lingual Signs. [[paper]](https://arxiv.org/abs/2308.10809)       
*Fangyun Wei, Yutong Chen* 
- [ICCV 2023] C2ST: Cross-modal Contextualized Sequence Transduction for Continuous Sign Language Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_C2ST_Cross-Modal_Contextualized_Sequence_Transduction_for_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html)   
*Huaiwen Zhang, Zihang Guo, Yang Yang, Xin Liu, De Hu*   
- [Complete List of Sign Language Recognition](./complete_list/sign_language_recognition.md)

### Sign Language Translation
- [ACL 2025] SHuBERT: Self-Supervised Sign Language Representation Learning via Multi-Stream Cluster Prediction. [[paper]](https://arxiv.org/abs/2411.16765)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu, Alexander H. Liu*
- [ACL 2025] Multilingual Gloss-free Sign Language Translation: Towards Building a Sign Language Foundation Model. [[paper]](https://arxiv.org/abs/2505.24355)     
*Sihan Tan, Taro Miyazaki, Kazuhiro Nakadai*
- [ACL Findings 2025] SignMusketeers: An Efficient Multi-Stream Approach for Sign Language Translation at Scale. [[paper]](https://arxiv.org/abs/2406.06907)     
*Shester Gueuwou, Xiaodan Du, Greg Shakhnarovich, Karen Livescu*
- [CVPR 2025] Lost in Translation, Found in Context: Sign Language Translation with Contextual Cues. [[paper]](https://arxiv.org/abs/2501.09754)     
*Youngjoon Jang, Haran Raajesh, Liliane Momeni, Gul Varol, Andrew Zisserman*
- [ICLR 2025] YouTube-SL-25: A Large-Scale, Open-Domain Multilingual Sign Language Parallel Corpus. [[paper]](https://openreview.net/forum?id=nFVsK3QLgs)   
  *Garrett Tanzer, Biao Zhang*
- [ICLR 2025] Uni-Sign: Toward Unified Sign Language Understanding at Scale. [[paper]](https://openreview.net/forum?id=0Xt7uT04cQ)   
  *Zecheng Li, Wengang Zhou, Weichao Zhao, Kepeng Wu, Hezhen Hu, Houqiang Li*
- [OpenReview] Hybrid Model Collaboration for Sign Language Translation with VQ-VAE and RAG Enhanced LLMS. [[paper]](https://openreview.net/forum?id=7kRFnSFN89)   
  *Jian Ma, Wenguan Wang, Yi Yang, Weili Guan, Feng Zheng*
- [NeurIPS 2024] Scaling Sign Language Translation. [[paper]](https://openreview.net/forum?id=M80WgiO2Lb)     
*Biao Zhang, Garrett Tanzer, Orhan Firat*
- [NeurIPS 2024] Improving Gloss-free Sign Language Translation by Reducing Representation Density. [[paper]](https://openreview.net/forum?id=FtzLbGoHW2)     
*Jinhui Ye, Xing Wang, Wenxiang Jiao, Junwei Liang, Hui Xiong*
- [EMNLP 2024] Reconsidering Sentence-Level Sign Language Translation. [[paper]](https://aclanthology.org/2024.emnlp-main.360/)   
  *Garrett Tanzer, Maximus Shengelia, Ken Harrenstien, David Uthus*
- [ECCV 2024] Visual Alignment Pre-training for Sign Language Translation. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05894.pdf)   
  *Peiqi Jiao, Yuecong Min, Xilin Chen*
- [ECCV 2024] EvSign: Sign Language Recognition and Translation with Streaming Events. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00799.pdf)   
  *Pengyu Zhang, Hao Yin, Zeren Wang, Wenyue Chen, Sheng Ming Li, Dong Wang, Huchuan Lu, Xu Jia*
- [ACL 2024] Towards Privacy-Aware Sign Language Translation at Scale. [[paper]](https://aclanthology.org/2024.acl-long.467/)     
  *Phillip Rust, Bowen Shi, Skyler Wang, Necati Cihan Camgoz, Jean Maillard*
- [ACL 2024] Sign Language Translation with Sentence Embedding Supervision. [[paper]](https://aclanthology.org/2024.acl-short.40/)     
  *HAMIDULLAH Yasser, Josef van Genabith, Cristina España-Bonet*
- [ACL Findings 2024] iSign: A Benchmark for Indian Sign Language Processing. [[paper]](https://aclanthology.org/2024.findings-acl.643/)     
  *Abhinav Joshi, Romit Mohanty, Mounika Kanakanti, Andesha Mangla, Sudeep Choudhary, Monali Barbate, Ashutosh Modi*
- [ACL Findings 2024] Unsupervised Sign Language Translation and Generation. [[paper]](https://aclanthology.org/2024.findings-acl.835/)     
  *Zhengsheng Guo, Zhiwei He, Wenxiang Jiao, Xing Wang, Rui Wang, Kehai Chen, Zhaopeng Tu, Yong Xu, Min Zhang*
- [CVPR 2024] LLMs are Good Sign Language Translators. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Gong_LLMs_are_Good_Sign_Language_Translators_CVPR_2024_paper.html)     
  *Jia Gong, Lin Geng Foo, Yixuan He, Hossein Rahmani, Jun Liu*
- [ICLR 2024] Sign2GPT: Leveraging Large Language Models for Gloss-Free Sign Language Translation. [[paper]](https://openreview.net/forum?id=LqaEEs3UxU)
  *Ryan Wong, Necati Cihan Camgoz, Richard Bowden*
- [EMNLP Findings 2023] JWSign: A Highly Multilingual Corpus of Bible Translations for more Diversity in Sign Language Processing. [[paper]](https://aclanthology.org/2023.findings-emnlp.664/)    
  *Shester Gueuwou, Sophie Siake, Colin Leong, Mathias Müller*
- [EMNLP Findings 2023] Cross-modality Data Augmentation for End-to-End Sign Language Translation. [[paper]](https://aclanthology.org/2023.findings-emnlp.904/)    
  *Jinhui Ye, Wenxiang Jiao, Xing Wang, Zhaopeng Tu, Hui Xiong*
- [OpenReview] Towards Faithful Sign Language Translation. [[paper]](https://openreview.net/forum?id=mWMJN0vbDF)    
  *Yuecong Min, Xilin Chen*
- [NeurIPS 2023 Dataset] YouTube-ASL: A Large-Scale, Open-Domain American Sign Language-English Parallel Corpus. [[paper]](https://openreview.net/forum?id=QEDjXv9OyY)     
*David Uthus, Garrett Tanzer, Manfred Georg*
- [NeurIPS 2023 Dataset] Auslan-Daily: Australian Sign Language Translation for Daily Communication and News. [[paper]](https://openreview.net/forum?id=g5v3Ig6WVq)      
*Xin Shen, Shaozu Yuan, Hongwei Sheng, Heming Du, Xin Yu*
- [ICCV 2023] Sign Language Translation with Iterative Prototype. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Yao_Sign_Language_Translation_with_Iterative_Prototype_ICCV_2023_paper.html)       
*Huijie Yao, Wengang Zhou, Hao Feng, Hezhen Hu, Hao Zhou, Houqiang Li* 
- [ICCV 2023] Gloss-free Sign Language Translation: Improving from Visual-Language Pretraining. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_Gloss-Free_Sign_Language_Translation_Improving_from_Visual-Language_Pretraining_ICCV_2023_paper.html)   
*Benjia Zhou, Zhigang Chen, Albert Clapés, Jun Wan, Yanyan Liang, Sergio Escalera, Zhen Lei, Du Zhang*  
- [Complete List of Sign Language Translation](./complete_list/sign_language_translation.md)

### Sign Language Production
- [CVPR 2025] Discrete to Continuous: Generating Smooth Transition Poses from Sign Language Observations. [[paper]](https://arxiv.org/abs/2411.16810)   
  *Shengeng Tang, Jiayi He, Lechao Cheng, Jingjing Wu, Dan Guo, Richang Hong*
- [EMNLP Findings 2024] Word-Conditioned 3D American Sign Language Motion Generation. [[paper]](https://aclanthology.org/2024.findings-emnlp.584/)   
  *Lu Dong, Xiao Wang, Ifeoma Nwogu*
- [ECCV 2024] A Simple Baseline for Spoken Language to Sign Language Translation with 3D Avatars. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06499.pdf)   
  *Ronglai Zuo, Fangyun Wei, Zenggui Chen, Brian Mak, Jiaolong Yang, Xin Tong*
- [ECCV 2024] Pose Guided Fine-Grained Sign Language Video Generation. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09947.pdf)   
  *Tongkai Shi, Lianyu Hu, Fanhua Shang, Jichao Feng, liu peidong, Wei Feng*
- [ECCV 2024] SignGen: End-to-End Sign Language Video Generation with Latent Diffusion. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06988.pdf)   
  *Fan Qi, Yu Duan, Changsheng Xu, Huaiwen Zhang*
- [ACL 2024] T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text. [[paper]](https://aclanthology.org/2024.acl-long.183/)     
  *Aoxiong Yin, Haoyuan Li, Kai Shen, Siliang Tang, Yueting Zhuang*
- [ACL Findings 2024] MS2SL: Multimodal Spoken Data-Driven Continuous Sign Language Production. [[paper]](https://aclanthology.org/2024.findings-acl.432/)     
  *Jian Ma, Wenguan Wang, Yi Yang, Feng Zheng*
- [CVPR 2024] Neural Sign Actors: A diffusion model for 3D sign language production from text. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Baltatzis_Neural_Sign_Actors_A_Diffusion_Model_for_3D_Sign_Language_CVPR_2024_paper.html)     
  *Vasileios Baltatzis, Rolandos Alexandros Potamias, Evangelos Ververas, Guanxiong Sun, Jiankang Deng, Stefanos Zafeiriou*
- [WACV 2024]  Sign Language Production With Latent Motion Transformer. [[paper]](https://openaccess.thecvf.com/content/WACV2024/html/Xie_Sign_Language_Production_With_Latent_Motion_Transformer_WACV_2024_paper.html)   
  *Pan Xie, Taiying Peng, Yao Du, Qipeng Zhang*
- [CVPR 2022] Signing at Scale: Learning to Co-Articulate Signs for Large-Scale Photo-Realistic Sign Language Production. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Saunders_Signing_at_Scale_Learning_to_Co-Articulate_Signs_for_Large-Scale_Photo-Realistic_CVPR_2022_paper.html)     
  *Ben Saunders, Necati Cihan Camgoz, Richard Bowden*
- [ICCV 2021] Mixed SIGNals: Sign Language Production via a Mixture of Motion Primitives. [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Saunders_Mixed_SIGNals_Sign_Language_Production_via_a_Mixture_of_Motion_ICCV_2021_paper.html)    
   *Ben Saunders; Necati Cihan Camgoz; Richard Bowden*
- [Complete List of Sign Language Production](./complete_list/sign_language_production.md)

### Other Sign Language Topic
- [ACL Findings 2025] Sign2Vis: Automated Data Visualization from Sign Language. [[paper]](http://wanyao.me/)     
*Yao Wan, Yang Wu, Zhen Li, Guobiao Zhang, Hongyu Zhang, Zhou Zhao, Hai Jin, April Wang*
- [ACL Findings 2025] 2M-BELEBELE: Highly Multilingual Speech and American Sign Language Comprehension Dataset. [[paper]](https://openreview.net/forum?id=uV0gGimcuD)     
*Marta R. Costa-jussà, Bokai YU, Pierre Andrews, Belen Alastruey, Necati Cihan Camgoz, Joe Chuang, Jean Maillard, Christophe Ropers, Arina Turkatenko, Carleigh Wood*
- [ACL Findings 2025] Large Language Models as Sign Language Interfaces: Mitigating the Requests of Deaf Users of LLMs in a Hearing-Centric World. [[paper]](https://openreview.net/forum?id=8HGvHrfFDx)     
*Mert Inan, Anthony Sicilia, Malihe Alikhani*
- [EMNLP Findings 2024] Gloss2Text: Sign Language Gloss translation using LLMs and Semantically Aware Label Smoothing.  [[paper]](https://aclanthology.org/2024.findings-emnlp.947/)   
  *Pooya Fayyazsanavi, Antonios Anastasopoulos, Jana Kosecka*
- [EMNLP 2024] Unsupervised Discrete Representations of American Sign Language.  [[paper]](https://aclanthology.org/2024.emnlp-main.1104/)   
  *Artem Abzaliev, Rada Mihalcea*
- [EMNLP 2024] Studying and Mitigating Biases in Sign Language Understanding Models.  [[paper]](https://aclanthology.org/2024.emnlp-main.17/)   
  *Katherine Atwell, Danielle Bragg, Malihe Alikhani*
- [ECCV 2024] Uncertainty-aware sign language video retrieval with probability distribution modeling.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06074.pdf)   
  *Xuan Wu, Hongxiang Li, yuanjiang luo, Xuxin Cheng, Xianwei Zhuang, Meng Cao, Keren Fu*
- [ECCV 2024] SignAvatars: A Large-scale 3D Sign Language Holistic Motion Dataset and Benchmark.  [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00653.pdf)   
  *Zhengdi Yu, Shaoli Huang, yongkang cheng, Tolga Birdal*
- [ACL 2024] Semi-Supervised Spoken Language Glossification. [[paper]](https://aclanthology.org/2024.acl-long.504/)    
  *Huijie Yao, Wengang Zhou, Hao Zhou, Houqiang Li*
- [ACL 2024] American Sign Language Handshapes Reflect Pressures for Communicative Efficiency. [[paper]](https://arxiv.org/abs/2406.04024)    
  *Kayo Yin, Terry Regier, Dan Klein*
- [EMNLP Findings 2023] Enhancing Accessible Communication: from European Portuguese to Portuguese Sign Language. [[paper]](https://aclanthology.org/2023.findings-emnlp.766/)    
  *Catarina Sousa, Luisa Coheur, Mara Moita*
- [CVPR 2023]  CiCo: Domain-Aware Sign Language Retrieval via Cross-Lingual Contrastive Learning. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Bao_CiCo_Domain-Aware_Sign_Language_Retrieval_via_Cross-Lingual_Contrastive_Learning_CVPR_2023_paper.html)[[code]](https://github.com/FangyunWei/SLRT/tree/main/CiCo)     
*Yiting Cheng, Fangyun Wei, Jianmin Bao, Dong Chen, Wenqiang Zhang*
- [CVPR 2023]  Ham2Pose: Animating Sign Language Notation into Pose Sequences. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Arkushin_Ham2Pose_Animating_Sign_Language_Notation_Into_Pose_Sequences_CVPR_2023_paper.html)     
*Rotem Shalev Arkushin, Amit Moryossef, Ohad Fried*

### Co-speech Gesture Generation
- [CVPR 2025] Retrieving Semantics from the Deep: an RAG Solution for Gesture Synthesis. [[paper]](https://arxiv.org/abs/2412.06786)    
  *Muhammad Hamza Mughal, Rishabh Dabral, Merel CJ Scholman, Vera Demberg, Christian Theobalt*
- [CVPR 2025] Co-Speech Gesture Video Generation with Implicit Motion-Audio Entanglement. [[paper]](https://cvpr.thecvf.com/virtual/2025/poster/32751)    
  *Xinjie Li, Ziyi Chen, Xinlu Yu, Iek-Heng Chu, Peng Chang, Jing Xiao*
- [CVPR 2025] HOP: Heterogeneous Topology-based Multimodal Entanglement for Co-Speech Gesture Generation. [[paper]](https://www.arxiv.org/abs/2503.01175)    
  *Hongye Cheng, Tianyu Wang, guangsi shi, Zexing Zhao, Yanwei Fu*
- [OpenReview] Realistic-Gesture: Co-Speech Gesture Video Generation through Semantic-aware Gesture Representation. [[paper]](https://openreview.net/forum?id=EXsiGFkwV6)    
  *Pinxin Liu, Pengfei Zhang, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski*
- [ICLR 2025] Co3Gesture: Towards Coherent Concurrent Co-speech 3D Gesture Generation with Interactive Diffusion. [[paper]](https://openreview.net/forum?id=VaowElpVzd)      
*Xingqun Qi, Yatian Wang, Hengyuan Zhang, Jiahao Pan, Wei Xue, Shanghang Zhang, Wenhan Luo, Qifeng Liu, Yike Guo*
- [ICLR 2025] TANGO: Co-Speech Gesture Video Reenactment with Hierarchical Audio Motion Embedding and Diffusion Interpolation. [[paper]](https://openreview.net/forum?id=LbEWwJOufy)      
*Haiyang Liu, Xingchao Yang, Tomoya Akiyama, Yuantian Huang, Qiaoge Li, Shigeru Kuriyama, Takafumi Taketomi*
- [ECCV 2024] Co-speech Gesture Video Generation with 3D Human Meshes Gestures. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/12483.pdf)    
  *Aniruddha Mahapatra, Richa Mishra, Ziyi Chen, Boyang Ding, Renda Li, Shoulei Wang, Jun-Yan Zhu, Peng Chang, Mei Han, Jing Xiao*
- [ACL 2024] LLM Knows Body Language, Too: Translating Speech Voices into Human Gestures. [[paper]](https://aclanthology.org/2024.acl-long.273/)    
  *Chenghao Xu, Guangtao Lyu, Jiexi Yan, Muli Yang, Cheng Deng*
- [CVPR 2024] EMAGE: Towards Unified Holistic Co-Speech Gesture Generation via Expressive Masked Audio Gesture Modeling. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_EMAGE_Towards_Unified_Holistic_Co-Speech_Gesture_Generation_via_Expressive_Masked_CVPR_2024_paper.html)    
  *Haiyang Liu, Zihao Zhu, Giorgio Becherini, YICHEN PENG, Mingyang Su, YOU ZHOU, Xuefei Zhe, Naoya Iwamoto, Bo Zheng, Michael J. Black*
- [CVPR 2024] Weakly-Supervised Emotion Transition Learning for Diverse 3D Co-speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Qi_Weakly-Supervised_Emotion_Transition_Learning_for_Diverse_3D_Co-speech_Gesture_Generation_CVPR_2024_paper.html)     
  *Xingqun Qi, Jiahao Pan, Peng Li, Ruibin Yuan, Xiaowei Chi, Mengfei Li, Wenhan Luo, Wei Xue, Shanghang Zhang, Qifeng Liu, Yike Guo*
- [CVPR 2024] Towards Variable and Coordinated Holistic Co-Speech Motion Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Towards_Variable_and_Coordinated_Holistic_Co-Speech_Motion_Generation_CVPR_2024_paper.html)    
  *Yifei Liu, Qiong Cao, Yandong Wen, Huaiguang Jiang, Changxing Ding*
- [CVPR 2024] ConvoFusion: Multi-Modal Conversational Diffusion for Co-Speech Gesture Synthesis. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Mughal_ConvoFusion_Multi-Modal_Conversational_Diffusion_for_Co-Speech_Gesture_Synthesis_CVPR_2024_paper.html)    
  *Muhammad Hamza Mughal, Rishabh Dabral, Ikhsanul Habibie, Lucia Donatelli, Marc Habermann, Christian Theobalt*
- [CVPR 2024] Co-Speech Gesture Video Generation via Motion-Decoupled Diffusion Model. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/He_Co-Speech_Gesture_Video_Generation_via_Motion-Decoupled_Diffusion_Model_CVPR_2024_paper.html)   
  *Xu He, Qiaochu Huang, Zhensong Zhang, Zhiwei Lin, Zhiyong Wu, Sicheng Yang, Minglei Li, Zhiyi Chen, Songcen Xu, Xiaofei Wu*
- [ICCV 2023] Continual Learning for Personalized Co-speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Ahuja_Continual_Learning_for_Personalized_Co-speech_Gesture_Generation_ICCV_2023_paper.html)     
*Chaitanya Ahuja, Pratik Joshi, Ryo Ishii, Louis-Philippe Morency*
- [ICCV 2023] LivelySpeaker: Towards Semantic-Aware Co-Speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhi_LivelySpeaker_Towards_Semantic-Aware_Co-Speech_Gesture_Generation_ICCV_2023_paper.html)     
*Yihao Zhi, Xiaodong Cun, Xuelin Chen, Xi Shen, Wen Guo, Shaoli Huang, Shenghua Gao*
- [CVPR 2023]  QPGesture: Quantization-Based and Phase-Guided Motion Matching for Natural Speech-Driven Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_QPGesture_Quantization-Based_and_Phase-Guided_Motion_Matching_for_Natural_Speech-Driven_Gesture_CVPR_2023_paper.html)     
*SiCheng Yang, Zhiyong Wu, Minglei Li, Zhensong Zhang, Lei Hao, Weihong Bao, Haolin Zhuang*
- [CVPR 2023]  Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zhu_Taming_Diffusion_Models_for_Audio-Driven_Co-Speech_Gesture_Generation_CVPR_2023_paper.html)     
*Lingting Zhu, Xian Liu, Xuanyu Liu, Rui Qian, Ziwei Liu, Lequan Yu*
- [CVPR 2023]  Diverse 3D Hand Gesture Prediction from Body Dynamics by Bilateral Hand Disentanglement. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Qi_Diverse_3D_Hand_Gesture_Prediction_From_Body_Dynamics_by_Bilateral_CVPR_2023_paper.html)     
*Xingqun Qi, Chen Liu, Muyi Sun, Lincheng Li, Changjie Fan, Xin Yu*
- [CVPR 2023]  Co-speech Gesture Synthesis by Reinforcement Learning with Contrastive Pre-trained Rewards. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Sun_Co-Speech_Gesture_Synthesis_by_Reinforcement_Learning_With_Contrastive_Pre-Trained_Rewards_CVPR_2023_paper.html)     
*Mingyang Sun, Mengchen Zhao, Yaqing Hou, Minglei Li, Huang Xu, Songcen Xu, Jianye HAO*
- [Complete List of Co-speech Gesture Generation](./complete_list/co_speech_gesture_generation.md)

### Gesture Recognition
- [CVPR 2025] Ges3ViG: Incorporating Pointing Gestures into Language-Based 3D Visual Grounding for Embodied Reference Understanding. [[paper]](https://cvpr.thecvf.com/virtual/2025/poster/35108)      
*Atharv Mahesh Mane, Dulanga Weerakoon, Vigneshwaran Subbaraju, Sougata Sen, Sanjay Sarma, Archan Misra*
- [CVPR 2025] SocialGesture: Delving into Multi-person Gesture Understanding. [[paper]](https://cvpr.thecvf.com/virtual/2025/poster/34623)      
*Xu Cao, Pranav Virupaksha, Wenqi Jia, Bolin Lai, Fiona Ryan, Sangmin Lee, James Rehg*
- [OpenReview] Revisiting Noise Resilience Strategies in Gesture Recognition: Short-Term Enhancement in Surface Electromyographic Signal Analysis. [[paper]](https://openreview.net/forum?id=B7eHRsuTSh)      
*Weiyu Guo, Ziyue Qiao, Ying Sun, Hui Xiong*
- [ICCV 2023] Learning Robust Representations with Information Bottleneck and Memory Network for RGB-D-based Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Learning_Robust_Representations_with_Information_Bottleneck_and_Memory_Network_for_ICCV_2023_paper.html)      
*Yunan Li, Huizhou Chen, Guanwen Feng, Qiguang Miao*
- [ICCV 2023] Data-Free Class-Incremental Hand Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Aich_Data-Free_Class-Incremental_Hand_Gesture_Recognition_ICCV_2023_paper.html)      
*Shubhra Aich, Jesus Ruiz-Santaquiteria, Zhenyu Lu, Prachi Garg, K J Joseph, Alvaro Fernandez Garcia, Vineeth N Balasubramanian, Kenrick Kin, Chengde Wan, Necati Cihan Camgoz, Shugao Ma, Fernando De la Torre*
- [BMVC 2022] Towards more efficient few-shot learning based human gesture recognition via dynamic vision sensors. [[paper]](https://bmvc2022.mpi-inf.mpg.de/0938.pdf)    
*Linglin Jing, Yifan Wang, Tailin Chen, Shirin Dora, Zhigang Ji, Hui Fang*    
- [BMVC 2022] Continuous Hand Gesture Recognition using Deep Coarse
and Fine Hand Features. [[paper]](https://bmvc2022.mpi-inf.mpg.de/1055.pdf)        
*Hazem Wannous, Jean-Philippe Vandeborre* 
- [CVPR 2022] LD-ConGR: A Large RGB-D Video Dataset for Long-Distance Continuous Gesture Recognition. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_LD-ConGR_A_Large_RGB-D_Video_Dataset_for_Long-Distance_Continuous_Gesture_CVPR_2022_paper.html)     
  *Dan Liu; Libo Zhang; Yanjun Wu*
- [AAAI 2022] Learning Unseen Emotions from Gestures via Semantically-Conditioned Zero-Shot Perception with Adversarial Autoencoders. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.html)    
  *Abhishek Banerjee, Uttaran Bhattacharya, Aniket Bera*
- [Complete List of Gesture Recognition](./complete_list/gesture_recognition.md)

## Sign Language Workshop
- [[ACL LoResMT 2024]](https://www.loresmt.org/) The Seventh Workshop on Technologies for Machine Translation of Low-Resource Languages
- [[ICCV ACVR 2023]](https://iplab.dmi.unict.it/acvr2023/program) Eleventh International Workshop on Assistive Computer Vision and Robotics
- [[ECCV SLRTP 2020]](https://slrtp.com/) Sign language recognition, translation & production. [[Accepted papers]](SLRTP_acccepted_list.md)

## Dataset

|    Dataset   |          | Task |            | Modality |       | Statistic |        |            |
|:------------:|:--------:|:--------:|:----------:|:--------:|:-----:|:---------:|:------:|:----------:|
| Name | Language | Isolated | Continuous |    RGB   | Depth |  #Signers | #Vocab | #Sequences |
|  DGS Kinect  |    DGS   |     √    |            |     √    |   √   |     15    |   40   |    3,000   |
|    ASLLVD    |    ASL   |     √    |            |     √    |       |     6     |  2,742 |    9,794   |
|  DEVISIGN-L  |    CSL   |     √    |            |     √    |   √   |     8     |  2,000 |   24,000   |
|    CSL-500   |    CSL   |     √    |            |     √    |       |     50    |   500  |   125,000  |
|     MSASL    |    ASL   |     √    |            |     √    |       |    222    |  1,000 |   25,513   |
|   WLASL2000  |    ASL   |     √    |            |     √    |       |    119    |  2,000 |   21,083   |
|     AUTSL    |    TSL   |     √    |            |     √    |   √   |     43    |   226  |   38,336   |
|    SIGNUM    |    DGS   |          |      √     |     √    |   √   |     9     |   455  |    2,340   |
|   Phoenix14  |    DGS   |          |      √     |     √    |       |     9     |  1,200 |    6,841   |
|     KETI     |    KSL   |          |      √     |     √    |       |     14    |   524  |   15,672   |
|      GSL     |    GSL   |          |      √     |     √    |   √   |     7     |   310  |   10,290   |
|    CSL-100   |    CSL   |          |      √     |     √    |       |     50    |  2,000 |   25,000   |
|   CSL-Daily  |    CSL   |          |      √     |     √    |       |     10    |  2,000 |   20,654   |
|    BSL-1K    |    BSL   |          |      √     |     √    |       |     40    |  1,064 |    273K    |
|   VRT-NEWS   |    VGT   |          |      √     |     √    |       |     9     |  6,325 |    7,174   |
|   How2Sign   |    BSL   |          |      √     |     √    |   √   |     11    | 15,686 |   35,191   |
|     BOBSL    |    BSL   |          |      √     |     √    |       |     39    |  2,281 |    452K    |
|    OpenASL   |    ASL   |          |      √     |     √    |       |    220    | 33,549 |   98,417   |
|  YouTube-ASL |    ASL   |          |      √     |     √    |       |   >2519   |   60K  |   11,093   |
