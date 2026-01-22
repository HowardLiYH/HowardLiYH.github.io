---
layout: single
title: "My name is Yuhao Li 李琙浩. Please feel free to call me Howard!"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---



About me 
======
Howard earned his B.A. from [Bowdoin College](https://www.bowdoin.edu/), majoring in Mathematics and Economics, and now embarks on his next chapter at the University of Pennsylvania's Master's program in [AMCS (Applied Math and Computational Science)](https://amcs.upenn.edu/).

Current Research Focus: Distributed Combinatorial Optimization for Generative Agents. 

My work treats Multi-Agent Systems as a Combinatorial Assignment Problem, aiming to optimize the bipartite matching between N agents and R tasks without central control. Instead of manual prompt engineering or standard RL, I develop population-based metaheuristics (specifically, competitive exclusion dynamics) to search the discrete strategy space of Large Language Models. This approach functions as a decentralized solver, empirically achieving near-optimal resource allocation (converging to the theoretical performance ceiling) on complex allocation benchmarks—effectively solving the Maximum Weight Matching problem in a gradient-free setting.



On-going Research
--
1. Distributed Combinatorial Optimization

<img src="https://github.com/user-attachments/assets/24b4cc14-db45-42cc-8f9d-91d85ca173bf" width="50%" />

My research focuses on Distributed Combinatorial Optimization for Generative Agents, investigating how populations of competing entities can solve complex optimization problems through emergent collective behavior rather than centralized coordination. The foundational contribution is the [NichePopulation Algorithm](https://github.com/HowardLiYH/NichePopulation), a fitness-proportional selection mechanism that enables agent populations to develop specialized roles across distinct environmental niches without explicit task assignment—demonstrating that diversity and specialization emerge naturally from competition alone. Building on this framework, [Emergent Prompt Evolution](https://github.com/HowardLiYH/Emergent-Preference-Specialization-in-LLM-Agent-Populations) extends these principles to the optimization of natural language instructions for large language models, where populations of prompt variants undergo selection pressure to discover high-performing configurations that would be intractable to engineer manually. Most recently, I have applied these methods across multiple domains—including quantitative finance, weather forecasting, and traffic prediction—uncovering the ["Blind Synchronization Effect"](https://github.com/HowardLiYH/Emergent-Applications/tree/main/apps/trading), a phenomenon where competing replicators, without access to environmental state information, develop specialization patterns that become statistically cointegrated with domain-specific regime indicators. Across these applications, a unifying theme emerges: distributed competition serves as a powerful optimization primitive, capable of discovering structured solutions in high-dimensional spaces where traditional search methods struggle, with implications spanning multi-agent systems, automated machine learning, and adaptive decision-making in non-stationary environments.


<br>
<br>


2. MAS for Finance, a Multi-agent LLM Financial Trading Model

<img width="50%" height="800" alt="image" src="https://github.com/user-attachments/assets/2c7f93c8-1d8c-45f0-9319-d3316509e807" />



Collaborating with [Xiaoxing Wang](https://scholar.google.com/citations?user=n2ewxUIAAAAJ&hl=zh-CN) and [Ning Liao](https://scholar.google.com/citations?user=6aARLhMAAAAJ&hl=zh-CN) from [SJTU](https://en.sjtu.edu.cn/) on designing multi-agent LLM orchestration with continual learning and probabilistic calibration for adaptive, explainable decision-making in financial trading systems. [Our model](https://github.com/HowardLiYH/PopAgent) incorporates five types of agents to replicate the workflow pipeline of a hedge fund: Analysts, Researchers, Traders, Risk Managers, and Evaluators. The system ingests two distinct streams of information, text-based news data and time-series price data, and enables agents to perform trading activities while continually improving through feedback. Each agent type has its own responsibilities and draws from specialized methodological inventories to complete tasks. Their performance is assessed against fixed metrics defined by the Evaluator Agent after each trading round. Following every K iterations, the top performer within each agent category transfers knowledge to its peers, and the process repeats.


Publications & Conference Papers
--

Nanna Yan, **Yuhao Li**, Yingke Mao, Zhenyi Zhu, Xiao Yu, Wenhao Guan, Jiawei Hou, Taiping Zeng. "PowerSAM: Edge-Efficient Segment Anything for Power Systems Through Visual Model Distillation," Jan 10, 2025. [Preprint](https://www.researchgate.net/publication/387980105_PowerSAM_Edge-Efficient_Segment_Anything_for_Power_Systems_Through_Visual_Model_Distillation).

Bing He, Xiaoyan Song, Yingyi Liu, **Yuhao Li**, Yun Liang, Li Huang, Xiong Li. "Insulator Condition Monitoring Based on TMR Leakage Current Sensors,"  2024 IEEE PES 16th Asia-Pacific Power and Energy Engineering Conference Oct 27, 2024.

Bing He, Haoyu Song, Yingyi Liu, Yun Liang, Li Huang, Yuansheng Dai, **Yuhao Li**. "Research on the Fusion Detection Method of Extreme Learning Machines and Sparse Coding," 2024 IEEE PES 16th Asia-Pacific Power and Energy Engineering
Conference, Oct 25, 2024.

Bing He, Qi Ni, Xiaosong Xie, Mei Wang, Haoyang Wang, Qiqi Zhang, **Yuhao Li**, Jianguo Liu, Ze Huang, Zechi Li. "AI and Blockchain-Enabled Transmission Line Inspection System for Data Sharing," Inventions Geneva, Apr 15, 2024.

Nannan Yan, Bengang Wei, **Yuhao Li**, Quan Wen. "Analysis of PD-Induced Ultraviolet Signal in GIS and Comparison with Electrical Signals." IEEE CEIDP (Conference on Electrical Insulation and Dielectric Phenomena), Oct 21, 2019.

Zhichao Lai, **Yuhao Li**, Xinting Wang, Xiu Cao, Yiran Wen, Wei Geng, Yu Kang. "Predicting Failures of High Voltage Electric Power Facilities via Multidimensional Information Analysis." 2018 International Conference on Mechatronic Systems and Robots, 25 May 2018, pp. 7–13.

Yu Kang, Xinting Wang, Xiu Cao, Yangfan Zhu, Zhichao Lai, **Yuhao Li**, Xuqi Zhang, Wei Geng. Detecting Anomalous Users via Streaming Data Processing in Smart Grid. 2018 International Conference on Mechatronic Systems and Robots, 25 May 2018, pp. 14–20.
