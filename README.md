
## Large Language Models Meet NLP: A Survey

- [💡 Introduction](#-abstract)
- [📝 Papers](#-papers)
  - [Overview](#overview)
  - [Natural Language Understanding](#natural-language-understanding)
    - [Sentiment Analysis](#sentiment-analysis)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm)
    - [Information Extraction](#information-extraction)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-1)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-1)
    - [Dialogue Understanding](#dialogue-understanding)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-2)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-2)
    - [Table Understanding](#table-understanding)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-3)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-3)
  - [Natural Language Generation](#natural-language-generation)
    - [Summarization](#summarization)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-4)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-4)
    - [Code Generation](#code-generation)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-5)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-5)
    - [Machine Translation](#machine-translation)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-6)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-6)
    - [Mathematical Reasoning](#mathematical-reasoning)
      - [Parameter-Frozen Paradigm](#parameter-frozen-paradigm-7)
      - [Parameter-Tuning Paradigm](#parameter-tuning-paradigm-7)
  - [Future Work and New Frontier](#future-work-and-new-frontier)
    - [Multilingual LLMs for NLP](#multilingual-llms-for-nlp)
    - [Multi-modal LLMs for NLP](#multi-modal-llms-for-nlp)
    - [Tool-usage in LLMs for NLP](#tool-usage-in-llms-for-nlp)
    - [X-of-thought in LLMs for NLP](#x-of-thought-in-llms-for-nlp)
    - [Hallucination in LLMs for NLP](#hallucination-in-llms-for-nlp)
    - [Safety in LLMs for NLP](#safety-in-llms-for-nlp)


## 💡 Introduction

Large language models (LLMs), such as ChatGPT, have achieved remarkable success in natural language processing (NLP) tasks. Nevertheless, there is a lack of systematic investigation into LLMs for NLP. In this study, we conduct a comprehensive review of LLMs for NLP to address the following questions: (1) How are LLMs currently applied to NLP tasks in the literature? (2) Have traditional NLP tasks already been solved? (3) What is the future of the LLMs for NLP? To answer these questions, we take the first step to provide a comprehensive overview of LLMs in NLP. Specifically, we first introduce a novel taxonomy including (1) parameter-frozen application and (2) parameter-tuning application to offer a unified perspective for understanding the current progress of LLMs in NLP. Furthermore, we summarize the new frontiers as well as the corresponding challenges, hoping to spur more future breakthrough research. Finally, we build a public website containing related papers, baseline projects, and leaderboards to help researchers track the latest progress of literature. We hope this work can provide insights into the opportunities and challenges of LLMs in NLP, and serve as a practical resource for constructing effective LLMs in NLP.

---

## 📝 Papers

### Overview

### Natural Language Understanding
#### Sentiment Analysis
##### Parameter-Frozen Paradigm

1. **Sentiment Analysis in the Era of Large Language Models: A Reality Check**
   
   *Wenxuan Zhang, Yue Deng, Bing Liu, Sinno Jialin Pan, Lidong Bing.* [[abs](https://arxiv.org/abs/2305.15005)], 2023.5

2. **Zero-shot Sentiment Analysis in Low-Resource Languages Using a Multilingual Sentiment Lexicon**

   *Fajri Koto, Tilman Beck, Zeerak Talat, Iryna Gurevych, Timothy Baldwin.* [[abs](https://arxiv.org/abs/2305.15005)], 2024.2
   
3. **Is ChatGPT Equipped with Emotional Dialogue Capabilities?**
   
   *Weixiang Zhao, Yanyan Zhao, Xin Lu, Shilong Wang, Yanpeng Tong, Bing Qin.* [[abs](https://arxiv.org/abs/2304.09582)], 2023.4

4. **The Limits of ChatGPT in Extracting Aspect-Category-Opinion-Sentiment Quadruples: A Comparative Analysis**
   
   *Xiancai Xu, Jia-Dong Zhang, Rongchang Xiao, Lei Xiong.* [[abs](https://arxiv.org/abs/2310.06502)], 2023.10

5. **Sentiment Analysis through LLM Negotiations**
   
   *Xiaofei Sun, Xiaoya Li, Shengyu Zhang, Shuhe Wang, Fei Wu, Jiwei Li, Tianwei Zhang, Guoyin Wang.* [[abs](https://arxiv.org/abs/2311.01876)], 2023.11


##### Parameter-Tuning Paradigm
1. **UnifiedABSA: A Unified ABSA Framework Based on Multi-task Instruction Tuning**
   
   *Zengzhi Wang, Rui Xia, Jianfei Yu.* [[abs](https://arxiv.org/abs/2211.10986)], 2022.11

2. **Instruction Tuning for Few-Shot Aspect-Based Sentiment Analysis**
   
   *Siddharth Varia, Shuai Wang, Kishaloy Halder, Robert Vacareanu, Miguel Ballesteros, Yassine Benajiba, Neha Anna John, Rishita Anubhai, Smaranda Muresan, Dan Roth.* [[abs](https://arxiv.org/abs/2210.06629)], 2023.6

3. **Visual Elements Mining as Prompts for Instruction Learning for Target-Oriented Multimodal Sentiment Classification**
   
   *Bin Yang, Jinlong Li.* [[abs](https://aclanthology.org/2023.findings-emnlp.403/)], 2023.12

4. **Sentiment Analysis: Mining Opinions, Sentiments, and Emotions**
   
   *Jun Zhao, Kang Liu, Liheng Xu.* [[abs](https://direct.mit.edu/coli/article/42/3/595/1534/Sentiment-Analysis-Mining-Opinions-Sentiments-and)], 2016.9

5. **SMILE: Single-turn to Multi-turn Inclusive Language Expansion via ChatGPT for Mental Health Support**
   *Huachuan Qiu, Hongliang He, Shuai Zhang, Anqi Li, Zhenzhong Lan.* [[abs](https://arxiv.org/abs/2305.00450)], 2024.2

#### Information Extraction

##### Parameter-Frozen Paradigm
1. **Aligning Instruction Tasks Unlocks Large Language Models as Zero-Shot Relation Extractors**
   
   *Kai Zhang, Bernal Jiménez Gutiérrez, Yu Su.* [[abs](https://arxiv.org/abs/2305.11159)], 2023.5

2. **Zero-Shot Information Extraction via Chatting with ChatGPT**
   
   *Xiang Wei, Xingyu Cui, Ning Cheng, Xiaobin Wang, Xin Zhang, Shen Huang, Pengjun Xie, Jinan Xu, Yufeng Chen, Meishan Zhang, Yong Jiang, Wenjuan Han.* [[abs](https://arxiv.org/abs/2302.10205)], 2023.2

3. **Empirical Study of Zero-Shot NER with ChatGPT**
   
   *Tingyu Xie, Qi Li, Jian Zhang, Yan Zhang, Zuozhu Liu, Hongwei Wang.* [[abs](https://aclanthology.org/2023.emnlp-main.493/)], 2023.11

4. **How far is Language Model from 100% Few-shot Named Entity Recognition in Medical Domain**
   
   *Mingchen Li, Rui Zhang.* [[abs](https://arxiv.org/abs/2307.00186)], 2023.7

5. **CodeIE: Large Code Generation Models are Better Few-Shot Information Extractors**
   
   *Peng Li, Tianxiang Sun, Qiong Tang, Hang Yan, Yuanbin Wu, Xuanjing Huang, Xipeng Qiu.* [[abs](https://arxiv.org/abs/2305.05711)], 2023.5

6. **CodeKGC: Code Language Model for Generative Knowledge Graph Construction**
   
   *Zhen Bi, Jing Chen, Yinuo Jiang, Feiyu Xiong, Wei Guo, Huajun Chen, Ningyu Zhang.* [[abs](https://arxiv.org/abs/2304.09048)], 2024.1


##### Parameter-Tuning Paradigm

1. **Event Extraction as Question Generation and Answering**
   
   *Di Lu, Shihao Ran, Joel Tetreault, Alejandro Jaimes
.* [[abs](https://arxiv.org/abs/2307.05567)], 2023.7

2. **GIELLM: Japanese General Information Extraction Large Language Model Utilizing Mutual Reinforcement Effect**
   
   *Chengguang Gan, Qinghao Zhang, Tatsunori Mori.* [[abs](https://arxiv.org/abs/2311.06838)], 2023.11

3. **GoLLIE: Annotation Guidelines improve Zero-Shot Information-Extraction**
   
   *Oscar Sainz, Iker García-Ferrero, Rodrigo Agerri, Oier Lopez de Lacalle, German Rigau, Eneko Agirre.* [[abs](https://arxiv.org/abs/2310.03668)], 2024.5

4. **InstructUIE: Multi-task Instruction Tuning for Unified Information Extraction**
   
   *Xiao Wang, Weikang Zhou, Can Zu, Han Xia, Tianze Chen, Yuansen Zhang, Rui Zheng, Junjie Ye, Qi Zhang, Tao Gui, Jihua Kang, Jingsheng Yang, Siyuan Li, Chunsai Du.* [[abs](https://arxiv.org/abs/2304.08085)], 2023.4

5. **Unified Low-Resource Sequence Labeling by Sample-Aware Dynamic Sparse Finetuning**
   
   *Sarkar Snigdha Sarathi Das, Haoran Zhang, Peng Shi, Wenpeng Yin, Rui Zhang.* [[abs](https://aclanthology.org/2023.emnlp-main.433/)], 2023.12

6. **Prompts Can Play Lottery Tickets Well: Achieving Lifelong Information Extraction via Lottery Prompt Tuning**
   
   *Zujie Liang, Feng Wei, Yin Jie, Yuxi Qian, Zhenghong Hao, Bing Han.* [[abs](https://aclanthology.org/2023.acl-long.16/)], 2023.7




#### Dialogue Understanding

##### Parameter-Frozen Paradigm

1. **A Preliminary Evaluation of ChatGPT for Zero-shot Dialogue Understanding**
   
   *Wenbo Pan, Qiguang Chen, Xiao Xu, Wanxiang Che, Libo Qin.* [[abs](https://arxiv.org/abs/2304.04256)], 2023.4

2. **Can ChatGPT Detect Intent? Evaluating Large Language Models for Spoken Language Understanding**
   
   *Mutian He, Philip N. Garner.* [[abs](https://arxiv.org/abs/2305.13512)], 2023.8

3. **Are LLMs All You Need for Task-Oriented Dialogue?**
   
   *Vojtěch Hudeček, Ondřej Dušek.* [[abs](https://arxiv.org/abs/2304.06556)], 2023.8

4. **ChatGPT for Zero-shot Dialogue State Tracking: A Solution or an Opportunity?**
   
   *Michael Heck, Nurul Lubis, Benjamin Ruppik, Renato Vukovic, Shutong Feng, Christian Geishauser, Hsien-Chin Lin, Carel van Niekerk, Milica Gašić.* [[abs](https://arxiv.org/abs/2306.01386)], 2023.6

5. **Self-Explanation Prompting Improves Dialogue Understanding in Large Language Models**
   
   *Haoyu Gao, Ting-En Lin, Hangyu Li, Min Yang, Yuchuan Wu, Wentao Ma, Yongbin Li.* [[abs](https://arxiv.org/abs/2309.12940)], 2023.9

6. **Controllable Dialogue Simulation with In-context Learning**

   *Zekun Li, Wenhu Chen, Shiyang Li, Hong Wang, Jing Qian, Xifeng Yan.* [[abs](https://aclanthology.org/2022.findings-emnlp.318/)], 2022.12

7. **SEAGULL: An Embodied Agent for Instruction Following through Situated Dialog**
   
   *Yichi Zhang, Jianing Yang, Keunwoo Yu, Yinpei Dai, Shane Storks, Yuwei Bao, Jiayi Pan, Nikhil Devraj, Ziqiao Ma, and Joyce Chai.* [[pdf](https://assets.amazon.science/17/c5/a684745e4d6d94742d85a31e5362/simbot-challenge-technical-report-seagull-1.pdf)], 2023

8. **Semantic Parsing by Large Language Models for Intricate Updating Strategies of Zero-Shot Dialogue State Tracking**
   
   *Yuxiang Wu, Guanting Dong, Weiran Xu.* [[abs](https://arxiv.org/abs/2310.10520)], 2023.11

9. **S3-DST: Structured Open-Domain Dialogue Segmentation and State Tracking in the Era of LLMs**
   
   *Sarkar Snigdha Sarathi Das, Chirag Shah, Mengting Wan, Jennifer Neville, Longqi Yang, Reid Andersen, Georg Buscher, Tara Safavi.* [[abs](https://arxiv.org/abs/2309.08827)], 2023.9

10. **Dialogue Distillery: Crafting Interpolable, Interpretable, and Introspectable Dialogue from LLMs**
   
    *Ryan A Chi, Jeremy Kim, Scott Hickmann, Siyan Li, Gordon Chi, Thanawan Atchariyachanvanit, Katherine Yu, Nathan A Chi, Gary Dai, Shashank Rammoorthy, et al.* [[pdf](https://assets.amazon.science/c6/bc/589db16944f1a185305802f8393e/chirpy-cardinal-dialogue-distillery-crafting-interpolable-interpretable-and-introspectable-dialogue-from-llms.pdf)], 2023

11. **In-Context Learning for Few-Shot Dialogue State Tracking**
   
    *Yushi Hu, Chia-Hsuan Lee, Tianbao Xie, Tao Yu, Noah A. Smith, Mari Ostendorf.* [[abs](https://aclanthology.org/2022.findings-emnlp.193/)], 2022.12

12. **Diverse Retrieval-Augmented In-Context Learning for Dialogue State Tracking**
   
    *Brendan King, Jeffrey Flanigan.* [[abs](https://aclanthology.org/2023.findings-acl.344/)], 2023.7

13. **Multi-party Multimodal Conversations Between Patients, Their Companions, and a Social Robot in a Hospital Memory Clinic**
   
    *Angus Addlesee, Neeraj Cherakara, Nivan Nelson, Daniel Hernandez Garcia, Nancie Gunson, Weronika Sieińska, Christian Dondrup, Oliver Lemon.* [[abs]()], 2024.3

14. **InstructTODS: Large Language Models for End-to-End Task-Oriented Dialogue Systems**
   
    *Willy Chung, Samuel Cahyawijaya, Bryan Wilie, Holy Lovenia, Pascale Fung.* [[abs](https://arxiv.org/abs/2310.08885)], 2023.10

15. **OrchestraLLM: Efficient Orchestration of Language Models for Dialogue State Tracking**
   
    *Chia-Hsuan Lee, Hao Cheng, Mari Ostendorf.* [[abs](https://arxiv.org/abs/2311.09758)], 2024.2

16. **Toward a Better Understanding of the Emotional Dynamics of Negotiation with Large Language Models**
   
    *Eleanor Lin, James Hale, and Jonathan Gratch.* [[abs](https://dl.acm.org/doi/abs/10.1145/3565287.3617637)], 2023.10

17. **DiagGPT: An LLM-based and Multi-agent Dialogue System with Automatic Topic Management for Flexible Task-Oriented Dialogue**
   
    *Lang Cao.* [[abs](https://arxiv.org/abs/2308.08043)], 2024.4


##### Parameter-Tuning Paradigm
1. **UnifiedSKG: Unifying and Multi-Tasking Structured Knowledge Grounding with Text-to-Text Language Models**
   
    *Tianbao Xie, Chen Henry Wu, Peng Shi, Ruiqi Zhong, Torsten Scholak, Michihiro Yasunaga, Chien-Sheng Wu, Ming Zhong, Pengcheng Yin, Sida I. Wang, Victor Zhong, Bailin Wang, Chengzu Li, Connor Boyle, Ansong Ni, Ziyu Yao, Dragomir Radev, Caiming Xiong, Lingpeng Kong, Rui Zhang, Noah A. Smith, Luke Zettlemoyer, Tao Yu.* [[abs](https://arxiv.org/abs/2201.05966)], 2022.10

2. **Description-Driven Task-Oriented Dialog Modeling**
   
    *Jeffrey Zhao, Raghav Gupta, Yuan Cao, Dian Yu, Mingqiu Wang, Harrison Lee, Abhinav Rastogi, Izhak Shafran, Yonghui Wu.* [[abs](https://arxiv.org/abs/2201.08904)], 2022.1
3. **Show, Don’t Tell: Demonstrations Outperform Descriptions for Schema-Guided Task-Oriented Dialogue**
   
    *Raghav Gupta, Harrison Lee, Jeffrey Zhao, Yuan Cao, Abhinav Rastogi, Yonghui Wu.* [[abs](https://aclanthology.org/2022.naacl-main.336/)], 2022.7
4. **Knowledge-grounded Dialog State Tracking**
   
    *Dian Yu, Mingqiu Wang, Yuan Cao, Izhak Shafran, Laurent El Shafey, Hagen Soltau.* [[abs](https://arxiv.org/abs/2210.06656)], 2022.10

5. **Towards LLM-driven Dialogue State Tracking**
   
    *Yujie Feng, Zexin Lu, Bo Liu, Liming Zhan, Xiao-Ming Wu.* [[abs](https://arxiv.org/abs/2310.14970)], 2023.10

6. **Prompt Pool based Class-Incremental Continual Learning for Dialog State Tracking**
   
    *Hong Liu, Yucheng Cai, Yuan Zhou, Zhijian Ou, Yi Huang, Junlan Feng.* [[abs](https://arxiv.org/abs/2311.10271)], 2023.11


#### Table Understanding

##### Parameter-Frozen Paradigm
1. **Tabular Representation, Noisy Operators, and Impacts on Table Structure Understanding Tasks in LLMs**
   
   *Ananya Singha, José Cambronero, Sumit Gulwani,1212Vu Le, and Chris Parnin.* [[abs](https://neurips.cc/virtual/2023/81302)], 2023.12

2. **CABINET: Content Relevance based Noise Reduction for Table Question Answering**
   
   *Sohan Patnaik, Heril Changwal, Milan Aggarwal, Sumit Bhatia, Yaman Kumar, Balaji Krishnamurthy.* [[abs](https://arxiv.org/abs/2402.01155)], 2024.2


3. **Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning**
   
   *Yunhu Ye, Binyuan Hui, Min Yang, Binhua Li, Fei Huang, Yongbin Li.* [[abs](https://arxiv.org/abs/2301.13808)], 2023.4

4. **Table Meets LLM: Can Large Language Models Understand Structured Table Data? A Benchmark and Empirical Study**
   
   *Yuan Sui, Mengyu Zhou, Mingjie Zhou, Shi Han, Dongmei Zhang.* [[abs](https://arxiv.org/abs/2305.13062)], 2024.2

5. **Binding Language Models in Symbolic Languages**
   
   *Zhoujun Cheng, Tianbao Xie, Peng Shi, Chengzu Li, Rahul Nadkarni, Yushi Hu, Caiming Xiong, Dragomir Radev, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Tao Yu.* [[abs](https://arxiv.org/abs/2210.02875)], 2023.3

6. **Data-Copilot: Bridging Billions of Data and Humans with Autonomous Workflow**
   
   *Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang.* [[abs](https://arxiv.org/abs/2306.07209)], 2024.4

7. **Large Language Models are few(1)-shot Table Reasoners**
   
   *Wenhu Chen.* [[abs](https://arxiv.org/abs/2210.06710)], 2023.1

8. **HRoT: Hybrid prompt strategy and Retrieval of Thought for Table-Text Hybrid Question Answering**
   
   *Tongxu Luo, Fangyu Lei, Jiahe Lei, Weihao Liu, Shihu He, Jun Zhao, Kang Liu.* [[abs](https://arxiv.org/abs/2309.12669)], 2023.9

9.  **SheetCopilot: Bringing Software Productivity to the Next Level through Large Language Models**

    *Hongxin Li, Jingran Su, Yuntao Chen, Qing Li, Zhaoxiang Zhang.* [[abs](https://arxiv.org/abs/2305.19308)], 2023.10

10.  **StructGPT: A General Framework for Large Language Model to Reason over Structured Data**
    
     *Jinhao Jiang, Kun Zhou, Zican Dong, Keming Ye, Wayne Xin Zhao, Ji-Rong Wen.* [[abs](https://arxiv.org/abs/2305.09645)], 2023.10


##### Parameter-Tuning Paradigm
1. **Table-GPT: Table-tuned GPT for Diverse Table Tasks**
   
   *Peng Li, Yeye He, Dror Yashar, Weiwei Cui, Song Ge, Haidong Zhang, Danielle Rifinski Fainman, Dongmei Zhang, Surajit Chaudhuri.* [[abs](https://arxiv.org/abs/2310.09263)], 2023.10
   
2. **UnifiedSKG: Unifying and Multi-Tasking Structured Knowledge Grounding with Text-to-Text Language Models**
   
    *Tianbao Xie, Chen Henry Wu, Peng Shi, Ruiqi Zhong, Torsten Scholak, Michihiro Yasunaga, Chien-Sheng Wu, Ming Zhong, Pengcheng Yin, Sida I. Wang, Victor Zhong, Bailin Wang, Chengzu Li, Connor Boyle, Ansong Ni, Ziyu Yao, Dragomir Radev, Caiming Xiong, Lingpeng Kong, Rui Zhang, Noah A. Smith, Luke Zettlemoyer, Tao Yu.* [[abs](https://arxiv.org/abs/2201.05966)], 2022.10

3. **DB-GPT: Empowering Database Interactions with Private Large Language Models**
   
   *Siqiao Xue, Caigao Jiang, Wenhui Shi, Fangyin Cheng, Keting Chen, Hongjun Yang, Zhiping Zhang, Jianshan He, Hongyang Zhang, Ganglin Wei, Wang Zhao, Fan Zhou, Danrui Qi, Hong Yi, Shaodong Liu, Faqiang Chen.* [[abs](https://arxiv.org/abs/2312.17449)], 2024.1

4. **Jellyfish: A Large Language Model for Data Preprocessing**
   
   *Haochen Zhang, Yuyang Dong, Chuan Xiao, Masafumi Oyamada.* [[abs](https://arxiv.org/abs/2312.01678)], 2024.3

5. **TAT-LLM: A Specialized Language Model for Discrete Reasoning over Tabular and Textual Data**
   
   *Fengbin Zhu, Ziyang Liu, Fuli Feng, Chao Wang, Moxin Li, Tat-Seng Chua.* [[abs](https://arxiv.org/abs/2401.13223)], 2024.2

6. **Schema-Driven Information Extraction from Heterogeneous Tables**
   
   *Fan Bai, Junmo Kang, Gabriel Stanovsky, Dayne Freitag, Alan Ritter.* [[abs](https://arxiv.org/abs/2305.14336)], 2024.3

7. **TableLlama: Towards Open Large Generalist Models for Tables**
   
   *Tianshu Zhang, Xiang Yue, Yifei Li, Huan Sun.* [[abs](https://arxiv.org/abs/2311.09206)], 2024.4



### Natural Language Generation

#### Summarization

##### Parameter-Frozen Paradigm

1. **News Summarization and Evaluation in the Era of GPT-3**
   
   *Tanya Goyal, Junyi Jessy Li, Greg Durrett.* [[abs](https://arxiv.org/abs/2209.12356)], 2023.5

2. **On Context Utilization in Summarization with Large Language Models**
   
   *Mathieu Ravaut, Aixin Sun, Nancy F. Chen, Shafiq Joty
.* [[abs](https://arxiv.org/abs/2310.10570)], 2024.2

3. **Prompted Opinion Summarization with GPT-3.5**
   
   *Adithya Bhaskar, Alexander R. Fabbri, Greg Durrett.* [[abs](https://arxiv.org/abs/2211.15914)], 2023.5

4. **Zero-Shot Cross-Lingual Summarization via Large Language Models**
   
   *Jiaan Wang, Yunlong Liang, Fandong Meng, Beiqi Zou, Zhixu Li, Jianfeng Qu, Jie Zhou.* [[abs](https://arxiv.org/abs/2302.14229)], 2023.10

5. **Benchmarking Large Language Models for News Summarization**
   
   *Tianyi Zhang, Faisal Ladhak, Esin Durmus, Percy Liang, Kathleen McKeown, Tatsunori B. Hashimoto.* [[abs](https://arxiv.org/abs/2301.13848)], 2023.1

6. **From Sparse to Dense: GPT-4 Summarization with Chain of Density Prompting**
   
   *Griffin Adams, Alexander Fabbri, Faisal Ladhak, Eric Lehman, Noémie Elhadad.* [[abs](https://arxiv.org/abs/2309.04269)], 2023.9

7. **In-context Learning of Large Language Models for Controlled Dialogue Summarization: A Holistic Benchmark and Empirical Analysis**
   
   *Yuting Tang, Ratish Puduppully, Zhengyuan Liu, Nancy Chen.* [[abs](https://aclanthology.org/2023.newsum-1.6/)], 2023.12


##### Parameter-Tuning Paradigm

1. **Socratic Pretraining: Question-Driven Pretraining for Controllable Summarization**
   
   *Artidoro Pagnoni, Alexander R. Fabbri, Wojciech Kryściński, Chien-Sheng Wu.* [[abs](https://arxiv.org/abs/2212.10449)], 2023.6

2. **Domain-Oriented Prefix-Tuning: Towards Efficient and Generalizable Fine-tuning for Zero-Shot Dialogue Summarization**
   
   *Lulu Zhao, Fujia Zheng, Weihao Zeng, Keqing He, Weiran Xu, Huixing Jiang, Wei Wu, Yanan Wu.* [[abs](https://arxiv.org/abs/2204.04362)], 2022.4

3. **Few-shot Query-Focused Summarization with Prefix-Merging**
   
   *Ruifeng Yuan, Zili Wang, Ziqiang Cao, Wenjie Li.* [[abs](https://arxiv.org/abs/2211.16164)], 2022.11

4. **Adapter-based Selective Knowledge Distillation for Federated Multi-domain Meeting Summarization**
   
   *Xiachong Feng, Xiaocheng Feng, Xiyuan Du, Min-Yen Kan, Bing Qin.* [[abs](https://arxiv.org/abs/2308.03275)], 2023.8

5. **Prefix-Tuning: Optimizing Continuous Prompts for Generation**
   
   *Xiang Lisa Li, Percy Liang.* [[abs](https://arxiv.org/abs/2101.00190)], 2021.1

6. **PromptSum: Parameter-Efficient Controllable Abstractive Summarization**
   
   *Mathieu Ravaut, Hailin Chen, Ruochen Zhao, Chengwei Qin, Shafiq Joty, Nancy Chen.* [[abs](https://arxiv.org/abs/2308.03117)], 2023.8


#### Code Generation

##### Parameter-Frozen Paradigm

1. **Evaluating Large Language Models Trained on Code**
   
   *Mark Chen, Jerry Tworek, Heewoo Jun, Qiming Yuan, Henrique Ponde de Oliveira Pinto, Jared Kaplan, Harri Edwards, Yuri Burda, Nicholas Joseph, Greg Brockman, Alex Ray, Raul Puri, Gretchen Krueger, Michael Petrov, Heidy Khlaaf, Girish Sastry, Pamela Mishkin, Brooke Chan, Scott Gray, Nick Ryder, Mikhail Pavlov, Alethea Power, Lukasz Kaiser, Mohammad Bavarian, Clemens Winter, Philippe Tillet, Felipe Petroski Such, Dave Cummings, Matthias Plappert, Fotios Chantzis, Elizabeth Barnes, Ariel Herbert-Voss, William Hebgen Guss, Alex Nichol, Alex Paino, Nikolas Tezak, Jie Tang, Igor Babuschkin, Suchir Balaji, Shantanu Jain, William Saunders, Christopher Hesse, Andrew N. Carr, Jan Leike, Josh Achiam, Vedant Misra, Evan Morikawa, Alec Radford, Matthew Knight, Miles Brundage, Mira Murati, Katie Mayer, Peter Welinder, Bob McGrew, Dario Amodei, Sam McCandlish, Ilya Sutskever, Wojciech Zaremba.* [[abs](https://arxiv.org/abs/2107.03374)], 2021.7

2. **CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis**
   
   *Erik Nijkamp, Bo Pang, Hiroaki Hayashi, Lifu Tu, Huan Wang, Yingbo Zhou, Silvio Savarese, Caiming Xiong.* [[abs](https://arxiv.org/abs/2203.13474)], 2023.2

3. **PanGu-Coder: Program Synthesis with Function-Level Language Modeling**
   
   *Fenia Christopoulou, Gerasimos Lampouras, Milan Gritta, Guchun Zhang, Yinpeng Guo, Zhongqi Li, Qi Zhang, Meng Xiao, Bo Shen, Lin Li, Hao Yu, Li Yan, Pingyi Zhou, Xin Wang, Yuchi Ma, Ignacio Iacobacci, Yasheng Wang, Guangtai Liang, Jiansheng Wei, Xin Jiang, Qianxiang Wang, Qun Liu.* [[abs](https://arxiv.org/abs/2207.11280)], 2022.7

4. **WizardCoder: Empowering Code Large Language Models with Evol-Instruct**
   
   *Ziyang Luo, Can Xu, Pu Zhao, Qingfeng Sun, Xiubo Geng, Wenxiang Hu, Chongyang Tao, Jing Ma, Qingwei Lin, Daxin Jiang.* [[abs](https://arxiv.org/abs/2306.08568)], 2023.7

5. **SantaCoder: don't reach for the stars!**
   
   *Loubna Ben Allal, Raymond Li, Denis Kocetkov, Chenghao Mou, Christopher Akiki, Carlos Munoz Ferrandis, Niklas Muennighoff, Mayank Mishra, Alex Gu, Manan Dey, Logesh Kumar Umapathi, Carolyn Jane Anderson, Yangtian Zi, Joel Lamy Poirier, Hailey Schoelkopf, Sergey Troshin, Dmitry Abulkhanov, Manuel Romero, Michael Lappert, Francesco De Toni, Bernardo García del Río, Qian Liu, Shamik Bose, Urvashi Bhattacharyya, Terry Yue Zhuo, Ian Yu, Paulo Villegas, Marco Zocca, Sourab Mangrulkar, David Lansky, Huu Nguyen, Danish Contractor, Luis Villa, Jia Li, Dzmitry Bahdanau, Yacine Jernite, Sean Hughes, Daniel Fried, Arjun Guha, Harm de Vries, Leandro von Werra.* [[abs](https://arxiv.org/abs/2301.03988)], 2023.1

6. **Event Extraction as Question Generation and Answering**
   
   *Di Lu, Shihao Ran, Joel Tetreault, Alejandro Jaimes.* [[abs](https://arxiv.org/abs/2307.05567)], 2023.7

7. **DeepSeek-Coder: When the Large Language Model Meets Programming -- The Rise of Code Intelligence**
   
   *Daya Guo, Qihao Zhu, Dejian Yang, Zhenda Xie, Kai Dong, Wentao Zhang, Guanting Chen, Xiao Bi, Y. Wu, Y.K. Li, Fuli Luo, Yingfei Xiong, Wenfeng Liang.* [[abs](https://arxiv.org/abs/2401.14196)], 2024.1

8. **Code Llama: Open Foundation Models for Code**
   
   *Baptiste Rozière, Jonas Gehring, Fabian Gloeckle, Sten Sootla, Itai Gat, Xiaoqing Ellen Tan, Yossi Adi, Jingyu Liu, Romain Sauvestre, Tal Remez, Jérémy Rapin, Artyom Kozhevnikov, Ivan Evtimov, Joanna Bitton, Manish Bhatt, Cristian Canton Ferrer, Aaron Grattafiori, Wenhan Xiong, Alexandre Défossez, Jade Copet, Faisal Azhar, Hugo Touvron, Louis Martin, Nicolas Usunier, Thomas Scialom, Gabriel Synnaeve.* [[abs](https://arxiv.org/abs/2308.12950)], 2024.1

9. **CodeGeeX: A Pre-Trained Model for Code Generation with Multilingual Evaluations on HumanEval-X**
   
   *Qinkai Zheng, Xiao Xia, Xu Zou, Yuxiao Dong, Shan Wang, Yufei Xue, Zihan Wang, Lei Shen, Andi Wang, Yang Li, Teng Su, Zhilin Yang, Jie Tang.* [[abs](https://arxiv.org/abs/2303.17568)], 2023.3


##### Parameter-Tuning Paradigm

1. **CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation**
   
   *Yue Wang, Weishi Wang, Shafiq Joty, Steven C.H. Hoi.* [[abs](https://arxiv.org/abs/2109.00859)], 2021.9

2. **CodeRL: Mastering Code Generation through Pretrained Models and Deep Reinforcement Learning**
   
   *Hung Le, Yue Wang, Akhilesh Deepak Gotmare, Silvio Savarese, Steven C.H. Hoi.* [[abs](https://arxiv.org/abs/2207.01780)], 2022.11

3. **Execution-based Code Generation using Deep Reinforcement Learning**
   
   *Parshin Shojaee, Aneesh Jain, Sindhu Tipirneni, Chandan K. Reddy.* [[abs](https://arxiv.org/abs/2301.13816)], 2023.7

4. **Parameter-Efficient Finetuning of Transformers for Source Code**
   
   *Shamil Ayupov, Nadezhda Chirkova.* [[abs](https://arxiv.org/abs/2212.05901)], 2022.12

5. **Astraios: Parameter-Efficient Instruction Tuning Code Large Language Models**
   
   *Terry Yue Zhuo, Armel Zebaze, Nitchakarn Suppattarachai, Leandro von Werra, Harm de Vries, Qian Liu, Niklas Muennighoff.* [[abs](https://arxiv.org/abs/2401.00788)], 2024.1

6. **Exploring Parameter-Efficient Fine-Tuning Techniques for Code Generation with Large Language Models**
   
   *Martin Weyssow, Xin Zhou, Kisub Kim, David Lo, Houari Sahraoui.* [[abs](https://arxiv.org/abs/2308.10462)], 2024.1


#### Machine Translation

##### Parameter-Frozen Paradigm

1. **PolyLM: An Open Source Polyglot Large Language Model**
   
   *Xiangpeng Wei, Haoran Wei, Huan Lin, Tianhao Li, Pei Zhang, Xingzhang Ren, Mei Li, Yu Wan, Zhiwei Cao, Binbin Xie, Tianxiang Hu, Shangjie Li, Binyuan Hui, Bowen Yu, Dayiheng Liu, Baosong Yang, Fei Huang, Jun Xie.* [[abs](https://arxiv.org/abs/2307.06018)], 2023.7

2. **Extrapolating Large Language Models to Non-English by Aligning Languages**
   
   *Wenhao Zhu, Yunzhe Lv, Qingxiu Dong, Fei Yuan, Jingjing Xu, Shujian Huang, Lingpeng Kong, Jiajun Chen, Lei Li.* [[abs](https://arxiv.org/abs/2308.04948)], 2023.10

3. **MT2: Towards a Multi-Task Machine Translation Model with Translation-Specific In-Context Learning**
   
   *Chunyou Li, Mingtong Liu, Hongxiao Zhang, Yufeng Chen, Jinan Xu, Ming Zhou.* [[abs](https://aclanthology.org/2023.emnlp-main.532/)], 2023.12

4. **Steering Large Language Models for Machine Translation with Finetuning and In-Context Learning**
   
   *Duarte Alves, Nuno Guerreiro, João Alves, José Pombal, Ricardo Rei, José de Souza, Pierre Colombo, Andre Martins.* [[abs](https://aclanthology.org/2023.findings-emnlp.744/)], 2023.12


5. **Dissecting In-Context Learning of Translations in GPTs**
   
   *Vikas Raunak, Hany Hassan Awadalla, Arul Menezes.* [[abs](https://arxiv.org/abs/2310.15987)], 2023.10

6. **Chain-of-Dictionary Prompting Elicits Translation in Large Language Models**
   
   *Hongyuan Lu, Haoyang Huang, Dongdong Zhang, Haoran Yang, Wai Lam, Furu Wei.* [[abs](https://arxiv.org/abs/2305.06575)], 2023.5



##### Parameter-Tuning Paradigm

1. **A Paradigm Shift in Machine Translation: Boosting Translation Performance of Large Language Models**
   
   *Haoran Xu, Young Jin Kim, Amr Sharaf, Hany Hassan Awadalla.* [[abs](https://arxiv.org/abs/2309.11674)], 2024.2

2. **Towards Effective Disambiguation for Machine Translation with Large Language Models**
   
   *Vivek Iyer, Pinzhen Chen, Alexandra Birch.* [[abs](https://aclanthology.org/2023.wmt-1.44/)], 2023.12


3. **Fine-tuning Large Language Models for Adaptive Machine Translation**
   
   *Yasmin Moslem, Rejwanul Haque, Andy Way.* [[abs](https://arxiv.org/abs/2312.12740)], 2023.12

4. **When does Parameter-Efficient Transfer Learning Work for Machine Translation?**
   
   *Ahmet Üstün, Asa Cooper Stickland.* [[abs](https://arxiv.org/abs/2205.11277)], 2022.10

5. **Steering Large Language Models for Machine Translation with Finetuning and In-Context Learning**
   
   *Duarte Alves, Nuno Guerreiro, João Alves, José Pombal, Ricardo Rei, José de Souza, Pierre Colombo, Andre Martins.* [[abs](https://aclanthology.org/2023.findings-emnlp.744/)], 2023.12

6. **Extrapolating Multilingual Understanding Models as Multilingual Generators**
   
   *Bohong Wu, Fei Yuan, Hai Zhao, Lei Li, Jingjing Xu.* [[abs](https://arxiv.org/abs/2305.13140)], 2023.5

#### Mathematical Reasoning

##### Parameter-Frozen Paradigm

1. **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**
   
   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* [[abs](https://arxiv.org/abs/2201.11903)], 2023.1

2. **Automatic Chain of Thought Prompting in Large Language Models**
   
   *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* [[abs](https://arxiv.org/abs/2210.03493)], 2022.10

3. **Large Language Models are Zero-Shot Reasoners**
   
   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* [[abs](https://arxiv.org/abs/2205.11916)], 2023.1

4. **Self-Consistency Improves Chain of Thought Reasoning in Language Models**
   
   *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou.* [[abs](https://arxiv.org/abs/2203.11171)], 2023.5

5. **LLaMA: Open and Efficient Foundation Language Models**
   
   *Hugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave, Guillaume Lample.* [[abs](https://arxiv.org/abs/2302.13971)], 2023.2


6. **Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning**
   
   *Pan Lu, Liang Qiu, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Tanmay Rajpurohit, Peter Clark, Ashwin Kalyan.* [[abs](https://arxiv.org/abs/2209.14610)], 2023.5

7. **PAL: Program-aided Language Models**
   
   *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig.* [[abs](https://arxiv.org/abs/2211.10435)], 2023.1

##### Parameter-Tuning Paradigm

1. **WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct**
   
   *Haipeng Luo, Qingfeng Sun, Can Xu, Pu Zhao, Jianguang Lou, Chongyang Tao, Xiubo Geng, Qingwei Lin, Shifeng Chen, Dongmei Zhang.* [[abs](https://arxiv.org/abs/2308.09583)], 2023.8

2. **MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning**
   
   *Xiang Yue, Xingwei Qu, Ge Zhang, Yao Fu, Wenhao Huang, Huan Sun, Yu Su, Wenhu Chen.* [[abs](https://arxiv.org/abs/2309.05653)], 2023.10

3. **Large Language Models Are Reasoning Teachers**
   
   *Namgyu Ho, Laura Schmid, Se-Young Yun.* [[abs](https://aclanthology.org/2023.acl-long.830/)], 2023.7

4. **Toolformer: Language Models Can Teach Themselves to Use Tools**
   
   *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom.* [[abs](https://arxiv.org/abs/2302.04761)], 2023.2

5. **LoRA: Low-Rank Adaptation of Large Language Models**
   
   *Edward J. Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, Weizhu Chen.* [[abs](https://arxiv.org/abs/2106.09685)], 2021.10

### Future Work and New Frontier

#### Multilingual LLMs for NLP


1. **mT5: A massively multilingual pre-trained text-to-text transformer**
   
   *Linting Xue, Noah Constant, Adam Roberts, Mihir Kale, Rami Al-Rfou, Aditya Siddhant, Aditya Barua, Colin Raffel.* [[abs](https://arxiv.org/abs/2010.11934)], 2021.5

2. **BLOOM: A 176B-Parameter Open-Access Multilingual Language Model**
   
   *BigScience Workshop: Teven Le Scao, Angela Fan, Christopher Akiki, Ellie Pavlick, Suzana Ilić, Daniel Hesslow, Roman Castagné, Alexandra Sasha Luccioni, François Yvon, Matthias Gallé, Jonathan Tow, Alexander M. Rush, Stella Biderman, Albert Webson, Pawan Sasanka Ammanamanchi, Thomas Wang, Benoît Sagot et al.* [[abs](https://arxiv.org/abs/2211.05100)], 2023.6

3. **Cross-lingual Prompting: Improving Zero-shot Chain-of-Thought Reasoning across Languages**
   
   *Libo Qin, Qiguang Chen, Fuxuan Wei, Shijue Huang, Wanxiang Che.* [[abs](https://arxiv.org/abs/2310.14799)], 2023.10


4. **Language Models are Multilingual Chain-of-Thought Reasoners**
   
   *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei.* [[abs](https://arxiv.org/abs/2210.03057)], 2022.10

5. **The Decades Progress on Code-Switching Research in NLP: A Systematic Survey on Trends and Challenges**
   
   *Genta Winata, Alham Fikri Aji, Zheng Xin Yong, Thamar Solorio.* [[abs](https://aclanthology.org/2023.findings-acl.185)], 2023.7

#### Multi-modal LLMs for NLP


1. **Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering**
   
   *Pan Lu, Swaroop Mishra, Tony Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, Ashwin Kalyan.* [[abs](https://arxiv.org/abs/2209.09513)], 2022.10

2. **The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)**
   
   *Zhengyuan Yang, Linjie Li, Kevin Lin, Jianfeng Wang, Chung-Ching Lin, Zicheng Liu, Lijuan Wang.* [[abs](https://arxiv.org/abs/2309.17421)], 2023.10

3. **Multimodal Chain-of-Thought Reasoning in Language Models**
   
   *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* [[abs](https://arxiv.org/abs/2302.00923)], 2023.2

4. **CogVLM: Visual Expert for Pretrained Language Models**
   
   *Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song, Jiazheng Xu, Bin Xu, Juanzi Li, Yuxiao Dong, Ming Ding, Jie Tang.* [[abs](https://arxiv.org/abs/2311.03079)], 2024.2

5. **Improved Baselines with Visual Instruction Tuning**
   
   *Haotian Liu, Chunyuan Li, Yuheng Li, Yong Jae Lee.* [[abs](https://arxiv.org/abs/2310.03744)], 2023.10

6. **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action**
   
   *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* [[abs](https://arxiv.org/abs/2303.11381)], 2023.3

7. **MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts**
   
   *Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, Jianfeng Gao.* [[abs](https://arxiv.org/abs/2310.02255)], 2024.1

8. **The Role of Chain-of-Thought in Complex Vision-Language Reasoning Task**
   
   *Yifan Wu, Pengchuan Zhang, Wenhan Xiong, Barlas Oguz, James C. Gee, Yixin Nie.* [[abs](https://arxiv.org/abs/2311.09193)], 2023.11

9. **Compositional Chain-of-Thought Prompting for Large Multimodal Models**
   
   *Chancharik Mitra, Brandon Huang, Trevor Darrell, Roei Herzig.* [[abs](https://arxiv.org/abs/2311.17076)], 2023.4

#### Tool-usage in LLMs for NLP

1. **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs**
   
   *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Lauren Hong, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, Dahai Li, Zhiyuan Liu, Maosong Sun.* [[abs](https://arxiv.org/abs/2307.16789)], 2023.10

2. **Reflexion: Language Agents with Verbal Reinforcement Learning**
   
   *Noah Shinn, Federico Cassano, Edward Berman, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao.* [[abs](https://arxiv.org/abs/2303.11366)], 2023.10

3. **A Survey on Large Language Model based Autonomous Agents**
   
   *Lei Wang, Chen Ma, Xueyang Feng, Zeyu Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Jiakai Tang, Xu Chen, Yankai Lin, Wayne Xin Zhao, Zhewei Wei, Ji-Rong Wen.* [[abs](https://arxiv.org/abs/2308.11432)], 2024.4

4. **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory**
   
   *Xizhou Zhu, Yuntao Chen, Hao Tian, Chenxin Tao, Weijie Su, Chenyu Yang, Gao Huang, Bin Li, Lewei Lu, Xiaogang Wang, Yu Qiao, Zhaoxiang Zhang, Jifeng Dai.* [[abs](https://arxiv.org/abs/2305.17144)], 2023.6

5. **Tree-Planner: Efficient Close-loop Task Planning with Large Language Models**
   
   *Mengkang Hu, Yao Mu, Xinmiao Yu, Mingyu Ding, Shiguang Wu, Wenqi Shao, Qiguang Chen, Bin Wang, Yu Qiao, Ping Luo.* [[abs](https://arxiv.org/abs/2310.08582)], 2023.10


#### X-of-thought in LLMs for NLP

1. **Large Language Models are Zero-Shot Reasoners**
   
   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* [[abs](https://arxiv.org/abs/2205.11916)], 2023.1

2. **Automatic Chain of Thought Prompting in Large Language Models**
   
   *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* [[abs](https://arxiv.org/abs/2210.03493)], 2022.10

3. **Cross-lingual Prompting: Improving Zero-shot Chain-of-Thought Reasoning across Languages**
   
   *Libo Qin, Qiguang Chen, Fuxuan Wei, Shijue Huang, Wanxiang Che.* [[abs](https://arxiv.org/abs/2310.14799)], 2023.10

4. **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**
   
   *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan.* [[abs](https://arxiv.org/abs/2305.10601)], 2023.12

5. **Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks**
   
   *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen.* [[abs](https://arxiv.org/abs/2211.12588)], 2023.10

6. **Boosting Logical Reasoning in Large Language Models through a New Framework: The Graph of Thought**
   
   *Bin Lei, pei-Hung Lin, Chunhua Liao, Caiwen Ding.* [[abs](https://arxiv.org/abs/2308.08614)], 2023.8


#### Hallucination in LLMs for NLP

1. **Generating Benchmarks for Factuality Evaluation of Language Models**
   
   *Dor Muhlgay, Ori Ram, Inbal Magar, Yoav Levine, Nir Ratner, Yonatan Belinkov, Omri Abend, Kevin Leyton-Brown, Amnon Shashua, Yoav Shoham.* [[abs](https://arxiv.org/abs/2307.06908)], 2024.2

2. **FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation**
   
   *Sewon Min, Kalpesh Krishna, Xinxi Lyu, Mike Lewis, Wen-tau Yih, Pang Wei Koh, Mohit Iyyer, Luke Zettlemoyer, Hannaneh Hajishirzi.* [[abs](https://arxiv.org/abs/2305.14251)], 2023.10

3. **Evaluating Correctness and Faithfulness of Instruction-Following Models for Question Answering**
   
   *Vaibhav Adlakha, Parishad BehnamGhader, Xing Han Lu, Nicholas Meade, Siva Reddy.* [[abs](https://arxiv.org/abs/2307.16877)], 2024.4

4. **A Token-level Reference-free Hallucination Detection Benchmark for Free-form Text Generation**
   
   *Tianyu Liu, Yizhe Zhang, Chris Brockett, Yi Mao, Zhifang Sui, Weizhu Chen, Bill Dolan.* [[abs](https://arxiv.org/abs/2104.08704)], 2022.4


#### Safety in LLMs for NLP


1. **Speak, Memory: An Archaeology of Books Known to ChatGPT/GPT-4**
    
   *Kent K. Chang, Mackenzie Cramer, Sandeep Soni, David Bamman.* [[abs](https://arxiv.org/abs/2305.00118)], 2023.10

2. **ToxiGen: A Large-Scale Machine-Generated Dataset for Adversarial and Implicit Hate Speech Detection**
   
   *Thomas Hartvigsen, Saadia Gabriel, Hamid Palangi, Maarten Sap, Dipankar Ray, Ece Kamar.* [[abs](https://aclanthology.org/2022.acl-long.234/)], 2022.5

3. **BiasAsker: Measuring the Bias in Conversational AI System**
   
   *Yuxuan Wan, Wenxuan Wang, Pinjia He, Jiazhen Gu, Haonan Bai, Michael Lyu.* [[abs](https://arxiv.org/abs/2305.12434)], 2023.5

4. **BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation**
   
   *Jwala Dhamala, Tony Sun, Varun Kumar, Satyapriya Krishna, Yada Pruksachatkun, Kai-Wei Chang, Rahul Gupta.* [[abs](https://arxiv.org/abs/2101.11718)], 2021.1

5. **Emotionally Numb or Empathetic? Evaluating How LLMs Feel Using EmotionBench**
   
   *Jen-tse Huang, Man Ho Lam, Eric John Li, Shujie Ren, Wenxuan Wang, Wenxiang Jiao, Zhaopeng Tu, Michael R. Lyu.* [[abs](https://arxiv.org/abs/2308.03656)], 2024.4

6. **Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned**
   
   *Deep Ganguli, Liane Lovitt, Jackson Kernion, Amanda Askell, Yuntao Bai, Saurav Kadavath, Ben Mann, Ethan Perez, Nicholas Schiefer, Kamal Ndousse, Andy Jones, Sam Bowman, Anna Chen, Tom Conerly, Nova DasSarma, Dawn Drain, Nelson Elhage, Sheer El-Showk, Stanislav Fort, Zac Hatfield-Dodds, Tom Henighan, Danny Hernandez, Tristan Hume, Josh Jacobson, Scott Johnston, Shauna Kravec, Catherine Olsson, Sam Ringer, Eli Tran-Johnson, Dario Amodei, Tom Brown, Nicholas Joseph, Sam McCandlish, Chris Olah, Jared Kaplan, Jack Clark.* [[abs](https://arxiv.org/abs/2209.07858)], 2022.11

7. **Safety Assessment of Chinese Large Language Models**
   
   *Hao Sun, Zhexin Zhang, Jiawen Deng, Jiale Cheng, Minlie Huang.* [[abs](https://arxiv.org/abs/2304.10436)], 2023.4

