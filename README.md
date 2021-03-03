# awesome-offline-rl
This is a collection of research and review papers for **offline reinforcement learning (offline rl)**. Feel free to star and fork.


Maintainers:
- [Haruka Kiyohara](https://sites.google.com/view/harukakiyohara) (Tokyo Institute of Technology)
- [Yuta Saito](http://usaito.github.io/) (Hanjuku-kaso Co., Ltd.)

We are looking for more contributors and maintainers! Please feel free to [pull requests](https://github.com/usaito/awesome-offline-rl/pulls).

```
format:
- [title](paper link) [links]
  - author1, author2, and author3. arXiv/conferences/jornals/, year.
```

For any question, feel free to contact: saito@hanjuku-kaso.com


## Papers

### Review Papers

- [Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems](https://arxiv.org/abs/2005.01643)
  - Sergey Levine, Aviral Kumar, George Tucker, and Justin Fu. arXiv, 2020.

###离线RL：理论/方法
MetaRL：
- [具有注意和对比学习的改进的基于内置的脱机Meta-RL] （https://arxiv.org/abs/2102.10774）
  -李岚清，黄元浩和罗迪君。2021年，arXiv。
  因果：
- [Instrumental Variable Value Iteration for Causal Offline Reinforcement Learning](https://arxiv.org/abs/2102.09907)
  -廖洛峰，傅祖跃，杨卓然，姆拉登·科拉尔和王昭然。2021年，arXiv。
暂无models：
- [GELATO：用于离线强化学习的几何丰富的潜在模型] （https://arxiv.org/abs/2102.11327）
  - Guy Tennenholtz, Nir Baram, and Shie Mannor. arXiv, 2021.
 MB：
》不确定性
 MB：
- [MUSBO: Model-based Uncertainty Regularized and Sample Efficient Batch Optimization for Deployment Constrained Reinforcement Learning](https://arxiv.org/abs/2102.11448)
  - DiJia Su, Jason D. Lee, John M. Mulvey, and H. Vincent Poor. arXiv, 2021. 约束
- [COMBO: Conservative Offline Model-Based Policy Optimization](https://arxiv.org/abs/2102.08363)


- [Continuous Doubly Constrained Batch Reinforcement Learning](https://arxiv.org/abs/2102.09225)约束
  - Rasool Fakoor, Jonas Mueller, Pratik Chaudhari, and Alexander J. Smola. arXiv, 2021.

  - Tianhe Yu, Aviral Kumar, Rafael Rafailov, Aravind Rajeswaran, Sergey Levine, and Chelsea Finn. arXiv, 2021.
- [Representation Matters: Offline Pretraining for Sequential Decision Making](https://arxiv.org/abs/2102.05815)
  - Mengjiao Yang and Ofir Nachum. arXiv, 2021.表示学习
 
- [Q-Value Weighted Regression: Reinforcement Learning with Limited Data](https://arxiv.org/abs/2102.06782)
  - Piotr Kozakowski, Łukasz Kaiser, Henryk Michalewski, Afroz Mohiuddin, and Katarzyna Kańska. arXiv, 2021.
- [PerSim: Data-Efficient Offline Reinforcement Learning with Heterogeneous Agents via Personalized Simulators](https://arxiv.org/abs/2102.06961)
  - Anish Agarwal, Abdullah Alomar, Varkey Alumootil, Devavrat Shah, Dennis Shen, Zhi Xu, and Cindy Yang. arXiv, 2021.
- [Risk-Averse Offline Reinforcement Learning](https://arxiv.org/abs/2102.05371)
  - Núria Armengol Urpí, Sebastian Curi, and Andreas Krause. arXiv, 2021.
- [Finite Sample Analysis of Minimax Offline Reinforcement Learning: Completeness, Fast Rates and First-Order Efficiency](https://arxiv.org/abs/2102.02981)
  - Masatoshi Uehara, Masaaki Imaizumi, Nan Jiang, Nathan Kallus, Wen Sun, and Tengyang Xie. arXiv, 2021.
- [Fast Rates for the Regret of Offline Reinforcement Learning](https://arxiv.org/abs/2102.00479)
  - Yichun Hu, Nathan Kallus, and Masatoshi Uehara. arXiv, 2021.
- [Near-Optimal Offline Reinforcement Learning via Double Variance Reduction](https://arxiv.org/abs/2102.01748)
  - Ming Yin, Yu Bai, and Yu-Xiang Wang. arXiv, 2021.
- [Identifying Decision Points for Safe and Interpretable Reinforcement Learning in Hypotension Treatment](https://arxiv.org/abs/2101.03309)
  - Kristine Zhang, Yuanheng Wang, Jianzhun Du, Brian Chu, Leo Anthony Celi, Ryan Kindle, and Finale Doshi-Velez. arXiv, 2021.
- [Batch Reinforcement Learning Through Continuation Method](https://openreview.net/forum?id=po-DLlBuAuz)
  - Yijie Guo, Shengyu Feng, Nicolas Le Roux, Ed Chi, Honglak Lee, and Minmin Chen. ICLR, 2021.
- [Model-Based Visual Planning with Self-Supervised Functional Distances](https://openreview.net/forum?id=UcoXdfrORC)
  - Stephen Tian, Suraj Nair, Frederik Ebert, Sudeep Dasari, Benjamin Eysenbach, Chelsea Finn, and Sergey Levine. ICLR, 2021.
- [Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://openreview.net/forum?id=3hGNqpI4WS)
  - Tatsuya Matsushima, Hiroki Furuta, Yutaka Matsuo, Ofir Nachum, and Shixiang Gu. ICLR, 2021.
- [Efficient Fully-Offline Meta-Reinforcement Learning via Distance Metric Learning and Behavior Regularization](https://openreview.net/forum?id=8cpHIfgY4Dj)
  - Lanqing Li, Rui Yang, and Dijun Luo. ICLR, 2021.
- [DeepAveragers: Offline Reinforcement Learning by Solving Derived Non-Parametric MDPs](https://openreview.net/forum?id=eMP1j9efXtX)
  - Aayam Kumar Shrestha, Stefan Lee, Prasad Tadepalli, and Alan Fern. ICLR, 2021.
- [What are the Statistical Limits of Offline RL with Linear Function Approximation?](https://openreview.net/forum?id=30EvkP2aQLD)
  - Ruosong Wang, Dean Foster, and Sham M. Kakade. ICLR, 2021.
- [Reset-Free Lifelong Learning with Skill-Space Planning](https://openreview.net/forum?id=HIGSa_3kOx3) [[website](https://sites.google.com/berkeley.edu/reset-free-lifelong-learning)]
  - Kevin Lu, Aditya Grover, Pieter Abbeel, and Igor Mordatch. ICLR, 2021.
- [Exploration by Maximizing Rényi Entropy for Reward-Free RL Framework](https://arxiv.org/abs/2006.06193)
  - Chuheng Zhang, Yuanying Cai, Longbo Huang, and Jian Li. AAAI, 2021.
- [Finite-Sample Analysis For Decentralized Batch Multi-Agent Reinforcement Learning With Networked Agents](https://arxiv.org/abs/1812.02783)
  - Kaiqing Zhang, Zhuoran Yang, Han Liu, Tong Zhang, and Tamer Başar. IEEE T AUTOMATIC CONTROL, 2021.
- [Exponential Lower Bounds for Batch Reinforcement Learning: Batch RL can be Exponentially Harder than Online RL](https://arxiv.org/abs/2012.08005)
  - Andrea Zanette. arXiv, 2020.
- [Sparse Feature Selection Makes Batch Reinforcement Learning More Sample Efficient](https://arxiv.org/abs/2011.04019)
  - Botao Hao, Yaqi Duan, Tor Lattimore, Csaba Szepesvári, and Mengdi Wang. arXiv, 2020.
- [A Variant of the Wang-Foster-Kakade Lower Bound for the Discounted Setting](https://arxiv.org/abs/2011.01075)
  - Philip Amortila, Nan Jiang, and Tengyang Xie. arXiv, 2020.
- [Batch Reinforcement Learning with a Nonparametric Off-Policy Policy Gradient](https://arxiv.org/abs/2010.14771)
  - Samuele Tosatto, João Carvalho, and Jan Peters. arXiv, 2020.
- [Batch Value-function Approximation with Only Realizability](https://arxiv.org/abs/2008.04990)
  - Tengyang Xie and Nan Jiang. arXiv2020.
- [DRIFT: Deep Reinforcement Learning for Functional Software Testing](https://arxiv.org/abs/2007.08220)
  - Luke Harries, Rebekah Storan Clarke, Timothy Chapman, Swamy V. P. L. N. Nallamalli, Levent Ozgur, Shuktika Jain, Alex Leung, Steve Lim, Aaron Dietrich, José Miguel Hernández-Lobato, Tom Ellis, Cheng Zhang, and Kamil Ciosek. arXiv, 2020.
- [Causality and Batch Reinforcement Learning: Complementary Approaches To Planning In Unknown Domains](https://arxiv.org/abs/2006.02579)
  - James Bannon, Brad Windsor, Wenbo Song, and Tao Li. arXiv, 2020.
- [Goal-conditioned Batch Reinforcement Learning for Rotation Invariant Locomotion](https://arxiv.org/abs/2004.08356) [[code](https://github.com/aditimavalankar/gc-batch-rl-locomotion)]
  - Aditi Mavalankar. arXiv, 2020.
- [Semi-Supervised Reward Learning for Offline Reinforcement Learning](https://arxiv.org/abs/2012.06899)
  - Ksenia Konyushkova, Konrad Zolna, Yusuf Aytar, Alexander Novikov, Scott Reed, Serkan Cabi, and Nando de Freitas. arXiv, 2020.
- [Sample-Efficient Reinforcement Learning via Counterfactual-Based Data Augmentation](https://arxiv.org/abs/2012.09092)
  - Chaochao Lu, Biwei Huang, Ke Wang, José Miguel Hernández-Lobato, Kun Zhang, and Bernhard Schölkopf. arXiv, 2020.
- [Offline Reinforcement Learning from Images with Latent Space Models](https://arxiv.org/abs/2012.11547) [[website](https://sites.google.com/view/lompo/)]
  - Rafael Rafailov, Tianhe Yu, Aravind Rajeswaran, and Chelsea Finn. arXiv, 2020.
- [POPO: Pessimistic Offline Policy Optimization](https://arxiv.org/abs/2012.13682)
  - Qiang He and Xinwen Hou. arXiv, 2020.
- [Is Pessimism Provably Efficient for Offline RL?](https://arxiv.org/abs/2012.15085)
  - Ying Jin, Zhuoran Yang, and Zhaoran Wang. arXiv, 2020.
- [Reinforcement Learning with Videos: Combining Offline Observations with Interaction](https://arxiv.org/abs/2011.06507)
  - Karl Schmeckpeper, Oleh Rybkin, Kostas Daniilidis, Sergey Levine, and Chelsea Finn. arXiv, 2020.
- [Recovery RL: Safe Reinforcement Learning with Learned Recovery Zones](https://arxiv.org/abs/2010.15920) [[website](https://sites.google.com/berkeley.edu/recovery-rl/)]
  - Brijen Thananjeyan, Ashwin Balakrishna, Suraj Nair, Michael Luo, Krishnan Srinivasan, Minho Hwang, Joseph E. Gonzalez, Julian Ibarz, Chelsea Finn, and Ken Goldberg. arXiv, 2020.
- [Implicit Under-Parameterization Inhibits Data-Efficient Deep Reinforcement Learning](https://arxiv.org/abs/2010.14498)
  - Aviral Kumar, Rishabh Agarwal, Dibya Ghosh, and Sergey Levine. arXiv, 2020.
- [OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning](https://arxiv.org/abs/2010.13611) [[website](https://sites.google.com/view/opal-iclr)]
  - Anurag Ajay, Aviral Kumar, Pulkit Agrawal, Sergey Levine, and Ofir Nachum. arXiv, 2020.
- [Batch Exploration with Examples for Scalable Robotic Reinforcement Learning](https://arxiv.org/abs/2010.11917)
  - Annie S. Chen, HyunJi Nam, Suraj Nair, and Chelsea Finn. arXiv, 2020.
- [Learning Dexterous Manipulation from Suboptimal Experts](https://arxiv.org/abs/2010.08587) [[website](https://sites.google.com/view/rlfse)]
  - Rae Jeong, Jost Tobias Springenberg, Jackie Kay, Daniel Zheng, Yuxiang Zhou, Alexandre Galashov, Nicolas Heess, and Francesco Nori. arXiv, 2020.
- [The Reinforcement Learning-Based Multi-Agent Cooperative Approach for the Adaptive Speed Regulation on a Metallurgical Pickling Line](https://arxiv.org/abs/2008.06933)
  - Anna Bogomolova, Kseniia Kingsep, and Boris Voskresenskii. arXiv, 2020.
- [Offline Meta-Reinforcement Learning with Advantage Weighting](https://arxiv.org/abs/2008.06043)
  - Eric Mitchell, Rafael Rafailov, Xue Bin Peng, Sergey Levine, and Chelsea Finn. arXiv, 2020.
- [Model-Based Offline Planning](https://arxiv.org/abs/2008.05556) [[video](https://www.youtube.com/watch?v=nxGGHdZOFts&feature=youtu.be)]
  - Arthur Argenson and Gabriel Dulac-Arnold. arXiv, 2020.
- [Overcoming Model Bias for Robust Offline Deep Reinforcement Learning](https://arxiv.org/abs/2008.05533)
  - Phillip Swazinna, Steffen Udluft, and Thomas Runkler. arXiv, 2020.
- [Offline Meta Learning of Exploration](https://arxiv.org/abs/2008.02598)
  - Ron Dorfman, Idan Shenfeld, and Aviv Tamar. arXiv, 2020.
- [EMaQ: Expected-Max Q-Learning Operator for Simple Yet Effective Offline and Online RL](https://arxiv.org/abs/2007.11091)
  - Seyed Kamyar Seyed Ghasemipour, Dale Schuurmans, and Shixiang Shane Gu. arXiv, 2020.
- [Hyperparameter Selection for Offline Reinforcement Learning](https://arxiv.org/abs/2007.09055)
  - Tom Le Paine, Cosmin Paduraru, Andrea Michi, Caglar Gulcehre, Konrad Zolna, Alexander Novikov, Ziyu Wang, and Nando de Freitas. arXiv, 2020.
- [Interpretable Control by Reinforcement Learning](https://arxiv.org/abs/2007.09964)
  - Daniel Hein, Steffen Limmer, and Thomas A. Runkler. arXiv, 2020.
- [Efficient Evaluation of Natural Stochastic Policies in Offline Reinforcement Learning](https://arxiv.org/abs/2006.03886) [[code](https://github.com/CausalML/NaturalStochasticOPE)]
  - Nathan Kallus and Masatoshi Uehara. arXiv, 2020.
- [Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359) [[website](https://awacrl.github.io/)] [[blog](https://bair.berkeley.edu/blog/2020/09/10/awac/)]
  - Ashvin Nair, Murtaza Dalal, Abhishek Gupta, and Sergey Levine. arXiv, 2020.
- [DisCor: Corrective Feedback in Reinforcement Learning via Distribution Correction](https://arxiv.org/abs/2003.07305) [[blog](https://bair.berkeley.edu/blog/2020/03/16/discor/)]
  - Aviral Kumar, Abhishek Gupta, and Sergey Levine. arXiv, 2020.
- [Doubly Robust Off-Policy Value and Gradient Estimation for Deterministic Policies](https://papers.nips.cc/paper/2020/hash/75df63609809c7a2052fdffe5c00a84e-Abstract.html)
  - Nathan Kallus and Masatoshi Uehara. NeurIPS, 2020.
- [Critic Regularized Regression](https://proceedings.neurips.cc/paper/2020/hash/588cb956d6bbe67078f29f8de420a13d-Abstract.html)
  - Ziyu Wang, Alexander Novikov, Konrad Zolna, Josh S. Merel, Jost Tobias Springenberg, Scott E. Reed, Bobak Shahriari, Noah Siegel, Caglar Gulcehre, Nicolas Heess, and Nando de Freitas. NeurIPS, 2020
- [Provably Good Batch Off-Policy Reinforcement Learning Without Great Exploration](https://papers.nips.cc/paper/2020/hash/0dc23b6a0e4abc39904388dd3ffadcd1-Abstract.html)
  - Yao Liu, Adith Swaminathan, Alekh Agarwal, and Emma Brunskill. NeurIPS, 2020.
- [Conservative Q-Learning for Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/0d2b2061826a5df3221116a5085a6052-Abstract.html) [[website](https://sites.google.com/view/cql-offline-rl)] [[code](https://github.com/aviralkumar2907/CQL)] [[blog](https://bair.berkeley.edu/blog/2020/12/07/offline/)]
  - Aviral Kumar, Aurick Zhou, George Tucker, and Sergey Levine. NeurIPS, 2020.
- [BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/d55cbf210f175f4a37916eafe6c04f0d-Abstract.html)
  - Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu, and Keith Ross. NeurIPS, 2020.
- [MOPO: Model-based Offline Policy Optimization](https://papers.nips.cc/paper/2020/hash/a322852ce0df73e204b7e67cbbef0d0a-Abstract.html) [[code](https://github.com/tianheyu927/mopo)]
  - Tianhe Yu, Garrett Thomas, Lantao Yu, Stefano Ermon, James Y. Zou, Sergey Levine, Chelsea Finn, and Tengyu Ma. NeurIPS, 2020.
- [MOReL: Model-Based Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/f7efa4f864ae9b88d43527f4b14f750f-Abstract.html) [[podcast](https://twimlai.com/morel-model-based-offline-reinforcement-learning-with-aravind-rajeswaran/)]
  - Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli, and Thorsten Joachims. NeurIPS, 2020.
- [Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation](https://papers.nips.cc/paper/2020/hash/daf642455364613e2120c636b5a1f9c7-Abstract.html)
  - Aaron Sonabend, Junwei Lu, Leo Anthony Celi, Tianxi Cai, and Peter Szolovits. NeurIPS, 2020.
- [Multi-task Batch Reinforcement Learning with Metric Learning](https://papers.nips.cc/paper/2020/hash/4496bf24afe7fab6f046bf4923da8de6-Abstract.html)
  - Jiachen Li, Quan Vuong, Shuang Liu, Minghua Liu, Kamil Ciosek, Henrik Christensen, and Hao Su. NeurIPS, 2020.
- [Counterfactual Data Augmentation using Locally Factored Dynamics](https://papers.nips.cc/paper/2020/hash/294e09f267683c7ddc6cc5134a7e68a8-Abstract.html) [[code](https://github.com/spitis/mrl)]
  - Silviu Pitis, Elliot Creager, and Animesh Garg. NeurIPS, 2020.
- [On Reward-Free Reinforcement Learning with Linear Function Approximation](https://papers.nips.cc/paper/2020/hash/ce4449660c6523b377b22a1dc2da5556-Abstract.html)
  - Ruosong Wang, Simon S. Du, Lin Yang, and Russ R. Salakhutdinov. NeurIPS, 2020.
- [Constrained Policy Improvement for Safe and Efficient Reinforcement Learning](https://www.ijcai.org/Proceedings/2020/396)
  - Elad Sarafian, Aviv Tamar, and Sarit Kraus. IJCAI, 2020.
- [BRPO: Batch Residual Policy Optimization](https://www.ijcai.org/Proceedings/2020/391) [[code](https://github.com/eladsar/rbi)]
  - Sungryull Sohn, Yinlam Chow, Jayden Ooi, Ofir Nachum, Honglak Lee, Ed Chi, and Craig Boutilier. IJCAI, 2020.
- [From Importance Sampling to Doubly Robust Policy Gradient](http://proceedings.mlr.press/v119/huang20b.html)
  - Jiawei Huang and Nan Jiang. ICML, 2020.
- [Batch Stationary Distribution Estimation](http://proceedings.mlr.press/v119/wen20a.html)
  - Junfeng Wen, Bo Dai, Lihong Li, and Dale Schuurmans. ICML, 2020.
- [GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](http://proceedings.mlr.press/v119/zhang20r.html)
  - Shangtong Zhang, Bo Liu, and Shimon Whiteson. ICML, 2020.
- [GenDICE: Generalized Offline Estimation of Stationary Values](https://openreview.net/forum?id=HkxlcnVFwB)
  - Ruiyi Zhang, Bo Dai, Lihong Li, and Dale Schuurmans. ICLR, 2020.
- [Keep Doing What Worked: Behavior Modelling Priors for Offline Reinforcement Learning](https://openreview.net/forum?id=rke7geHtwH)
  - Noah Siegel, Jost Tobias Springenberg, Felix Berkenkamp, Abbas Abdolmaleki, Michael Neunert, Thomas Lampe, Roland Hafner, Nicolas Heess, and Martin Riedmiller. ICLR, 2020.
- [COG: Connecting New Skills to Past Experience with Offline Reinforcement Learning](https://arxiv.org/abs/2010.14500) [[website](https://sites.google.com/view/cog-rl)] [[blog](https://bair.berkeley.edu/blog/2020/12/07/offline/)] [[code](https://github.com/avisingh599/cog)]
  - Avi Singh, Albert Yu, Jonathan Yang, Jesse Zhang, Aviral Kumar, and Sergey Levine. CoRL, 2020.
- [Accelerating Reinforcement Learning with Learned Skill Priors](https://arxiv.org/abs/2010.11944)
  - Karl Pertsch, Youngwoon Lee, and Joseph J. Lim. CoRL, 2020.
- [Scaling data-driven robotics with reward sketching and batch reinforcement learning](https://arxiv.org/abs/1909.12200) [[website](https://sites.google.com/view/data-driven-robotics/)]
  - Serkan Cabi, Sergio Gómez Colmenarejo, Alexander Novikov, Ksenia Konyushkova, Scott Reed, Rae Jeong, Konrad Zolna, Yusuf Aytar, David Budden, Mel Vecerik, Oleg Sushkov, David Barker, Jonathan Scholz, Misha Denil, Nando de Freitas, and Ziyu Wang. RSS, 2020.
- [Quantile QT-Opt for Risk-Aware Vision-Based Robotic Grasping](https://arxiv.org/abs/1910.02787)
  - Cristian Bodnar, Adrian Li, Karol Hausman, Peter Pastor, and Mrinal Kalakrishnan. RSS, 2020.
- [Defining Admissible Rewards for High Confidence Policy Evaluation in Batch Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3368555.3384450)
  - Niranjani Prasad, Barbara E Engelhardt, and Finale Doshi-Velez. CHIL, 2020.
- [Learning When-to-Treat Policies](https://arxiv.org/abs/1905.09751)
  - Xinkun Nie, Emma Brunskill, and Stefan Wager. JASA, 2020.
- [Batch-Constrained Reinforcement Learning for Dynamic Distribution Network Reconfiguration](https://arxiv.org/abs/2006.12749)
  - Yuanqi Gao, Wei Wang, Jie Shi, and Nanpeng Yu. IEEE T SMART GRID, 2020.
- [Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456)
  - Natasha Jaques, Asma Ghandeharioun, Judy Hanwen Shen, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Gu, and Rosalind Picard. arXiv, 2019.
- [Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361)
  - Yifan Wu, George Tucker, and Ofir Nachum. arXiv, 2019.
- [Off-Policy Policy Gradient Algorithms by Constraining the State Distribution Shift](https://arxiv.org/abs/1911.06970)
  - Riashat Islam, Komal K. Teru, Deepak Sharma, and Joelle Pineau. arXiv, 2019.
- [Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning](https://arxiv.org/abs/1910.00177)
  - Xue Bin Peng, Aviral Kumar, Grace Zhang, and Sergey Levine. arXiv, 2019.
- [AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/abs/1912.02074)
  - Ofir Nachum, Bo Dai, Ilya Kostrikov, Yinlam Chow, Lihong Li, and Dale Schuurmans. arXiv, 2019.
- [Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://papers.nips.cc/paper/2019/hash/c2073ffa77b5357a498057413bb09d3a-Abstract.html) [[website](https://sites.google.com/view/bear-off-policyrl)] [[blog](https://bair.berkeley.edu/blog/2019/12/05/bear/)] [[code](https://github.com/aviralkumar2907/BEAR)]
  - Aviral Kumar, Justin Fu, George Tucker, and Sergey Levine. NeurIPS, 2019.
- [Off-Policy Deep Reinforcement Learning without Exploration](http://proceedings.mlr.press/v97/fujimoto19a.html)
  - Scott Fujimoto, David Meger, and Doina Precup. ICML, 2019.
- [Safe Policy Improvement with Baseline Bootstrapping](http://proceedings.mlr.press/v97/laroche19a.html)
  - Romain Laroche, Paul Trichelair, and Remi Tachet Des Combes. ICML, 2019.
- [Information-Theoretic Considerations in Batch Reinforcement Learning](http://proceedings.mlr.press/v97/chen19e.html)
  - Jinglin Chen and Nan Jiang. ICML, 2019.
- [Batch Recurrent Q-Learning for Backchannel Generation Towards Engaging Agents](https://arxiv.org/abs/1908.02037)
  - Nusrah Hussain, Engin Erzin, T. Metin Sezgin, and Yucel Yemez. ACII, 2019.
- [Safe Policy Improvement with Soft Baseline Bootstrapping](https://arxiv.org/abs/1907.05079)
  - Kimia Nadjahi, Romain Laroche, and Rémi Tachet des Combes. ECML, 2019.
- [Importance Weighted Transfer of Samples in Reinforcement Learning](http://proceedings.mlr.press/v80/tirinzoni18a.html)
  - Andrea Tirinzoni, Andrea Sessa, Matteo Pirotta, and Marcello Restelli. ICML, 2018.
- [Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation](http://proceedings.mlr.press/v87/kalashnikov18a.html) [[website](https://sites.google.com/view/qtopt)]
  - Dmitry Kalashnikov, Alex Irpan, Peter Pastor, Julian Ibarz, Alexander Herzog, Eric Jang, Deirdre Quillen, Ethan Holly, Mrinal Kalakrishnan, Vincent Vanhoucke, and Sergey Levine. CoRL, 2018.
- [Off-Policy Policy Gradient with State Distribution Correction](https://arxiv.org/abs/1904.08473)
  - Yao Liu, Adith Swaminathan, Alekh Agarwal, and Emma Brunskill. UAI, 2018.
- [Deep Exploration via Bootstrapped DQN](https://papers.nips.cc/paper/2016/hash/8d8818c8e140c64c743113f563cf750f-Abstract.html)
  - Ian Osband, Charles Blundell, Alexander Pritzel, and Benjamin Van Roy. NeurIPS, 2016.
- [Safe Policy Improvement by Minimizing Robust Baseline Regret](https://proceedings.neurips.cc/paper/2016/hash/9a3d458322d70046f63dfd8b0153ece4-Abstract.html)
  - Mohammad Ghavamzadeh, Marek Petrik, and Yinlam Chow. NeurIPS, 2016.
- [Residential Demand Response Applications Using Batch Reinforcement Learning](https://arxiv.org/abs/1504.02125)
  - Frederik Ruelens, Bert Claessens, Stijn Vandael, Bart De Schutter, Robert Babuska, and Ronnie Belmans. arXiv, 2015.
- [Structural Return Maximization for Reinforcement Learning](https://arxiv.org/abs/1405.2606)
  - Joshua Joseph, Javier Velez, and Nicholas Roy. arXiv, 2014.
- [Simultaneous Perturbation Algorithms for Batch Off-Policy Search](https://arxiv.org/abs/1403.4514)
  - Raphael Fonteneau, and L.A. Prashanth. CDC, 2014.
- [Guided Policy Search](http://proceedings.mlr.press/v28/levine13.html)
  - Sergey Levine, and Vladlen Koltun. ICML, 2013.
- [Off-Policy Actor-Critic](https://dl.acm.org/doi/10.5555/3042573.3042600)
  - Thomas Degris, Martha White, and Richard S. Sutton. ICML, 2012.
- [PAC-Bayesian Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/1202.3717)
  - Mahdi MIlani Fard, Joelle Pineau, and Csaba Szepesvari. UAI, 2011.
- [Tree-Based Batch Mode Reinforcement Learning](https://www.jmlr.org/papers/v6/ernst05a.html)
  - Damien Ernst, Pierre Geurts, and Louis Wehenkel. JMLR, 2005.
- [Neural Fitted Q Iteration–First Experiences with a Data Efficient Neural Reinforcement Learning Method](https://dl.acm.org/doi/10.1007/11564096_32)
  - Martin Riedmiller. ECML, 2005.
- [Off-Policy Temporal-Difference Learning with Function Approximation](https://dl.acm.org/doi/10.5555/645530.655817)
  - Doina Precup, Richard S. Sutton, and Sanjoy Dasgupta. ICML, 2001.

### Offline RL: Benchmarks/Experiments/Applications
- [DeepThermal: Combustion Optimization for Thermal Power Generating Units Using Offline Reinforcement Learning](https://arxiv.org/abs/2102.11492)
  - Xianyuan Zhan, Haoran Xu, Yue Zhang, Yusen Huo, Xiangyu Zhu, Honglei Yin, and Yu Zheng. arXiv, 2021.
- [Personalization for Web-based Services using Offline Reinforcement Learning](https://arxiv.org/abs/2102.05612)
  - Pavlos Athanasios Apostolopoulos, Zehui Wang, Hanson Wang, Chad Zhou, Kittipat Virochsiri, Norm Zhou, and Igor L. Markov. arXiv, 2021.
- [NeoRL: A Near Real-World Benchmark for Offline Reinforcement Learning](https://arxiv.org/abs/2102.00714) [[website](http://polixir.ai/research/neorl)] [[code](https://agit.ai/Polixir/neorl)]
  - Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang, and Yang Yu. arXiv, 2021.
- [Batch-Constrained Distributional Reinforcement Learning for Session-based Recommendation](https://arxiv.org/abs/2012.08984)
  - Diksha Garg, Priyanka Gupta, Pankaj Malhotra, Lovekesh Vig, and Gautam Shroff. arXiv, 2020.
- [An Empirical Study of Representation Learning for Reinforcement Learning in Healthcare](https://arxiv.org/abs/2011.11235)
  - Taylor W. Killian, Haoran Zhang, Jayakumar Subramanian, Mehdi Fatemi, and Marzyeh Ghassemi. arXiv, 2020.
- [Learning from Human Feedback: Challenges for Real-World Reinforcement Learning in NLP](https://arxiv.org/abs/2011.02511)
  - Julia Kreutzer, Stefan Riezler, and Carolin Lawrence. arXiv, 2020.
- [Remote Electrical Tilt Optimization via Safe Reinforcement Learning](https://arxiv.org/abs/2010.05842)
  - Filippo Vannella, Grigorios Iakovidis, Ezeddin Al Hakim, Erik Aumayr, and Saman Feghhi. arXiv, 2020.
- [Offline Reinforcement Learning Hands-On](https://arxiv.org/abs/2011.14379)
  - Louis Monier, Jakub Kmec, Alexandre Laterre, Thomas Pierrot, Valentin Courgeau, Olivier Sigaud, Karim Beguir. arXiv, 2020.
- [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219) [[website](https://sites.google.com/view/d4rl/home)] [[blog](https://bair.berkeley.edu/blog/2020/06/25/D4RL/)] [[code](https://github.com/rail-berkeley/d4rl)]
  - Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker, and Sergey Levine. arXiv, 2020.
- [RL Unplugged: Benchmarks for Offline Reinforcement Learning](https://arxiv.org/abs/2006.13888) [[code](https://github.com/deepmind/deepmind-research/tree/master/rl_unplugged)] [[dataset](https://console.cloud.google.com/storage/browser/rl_unplugged?pli=1)]
  - Caglar Gulcehre, Ziyu Wang, Alexander Novikov, Tom Le Paine, Sergio Gomez Colmenarejo, Konrad Zolna, Rishabh Agarwal, Josh Merel, Daniel Mankowitz, Cosmin Paduraru, Gabriel Dulac-Arnold, Jerry Li, Mohammad Norouzi, Matt Hoffman, Ofir Nachum, George Tucker, Nicolas Heess, and Nando de Freitas. arXiv, 2020.
- [An Optimistic Perspective on Offline Reinforcement Learning](http://proceedings.mlr.press/v119/agarwal20c.html) [[website](https://offline-rl.github.io/)] [[blog](https://ai.googleblog.com/2020/04/an-optimistic-perspective-on-offline.html)]
  - Rishabh Agarwal, Dale Schuurmans, and Mohammad Norouzi. ICML, 2020.
- [Policy Teaching via Environment Poisoning: Training-time Adversarial Attacks against Reinforcement Learning](http://proceedings.mlr.press/v119/rakhsha20a.html)
  - Amin Rakhsha, Goran Radanovic, Rati Devidze, Xiaojin Zhu, and Adish Singla. ICML, 2020.
- [Off-policy Learning in Two-stage Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3366423.3380130)
  - Jiaqi Ma, Zhe Zhao, Xinyang Yi, Ji Yang, Minmin Chen, Jiaxi Tang, Lichan Hong, and Ed H Chi. WWW, 2020.
- [Human-centric Dialog Training via Offline Reinforcement Learning](https://arxiv.org/abs/2010.05848)
  - Natasha Jaques, Judy Hanwen Shen, Asma Ghandeharioun, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Shane Gu, and Rosalind Picard. EMNLP, 2020.
- [Definition and evaluation of model-free coordination of electrical vehicle charging with reinforcement learning](https://arxiv.org/abs/1809.10679)
  - Nasrin Sadeghianpourhamami, Johannes Deleu, and Chris Develder. IEEE T SMART GRID, 2020.
- [Optimal Tap Setting of Voltage Regulation Transformers Using Batch Reinforcement Learning](https://arxiv.org/abs/1807.10997)
  - Hanchen Xu, Alejandro D. Domínguez-García, and Peter W. Sauer. IEEE T POWER SYSTEMS, 2020.
- [Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708)
  - Scott Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh, and Joelle Pineau. arXiv, 2019.
- [Top-K Off-Policy Correction for a REINFORCE Recommender System](https://arxiv.org/abs/1812.02353)
  - Minmin Chen, Alex Beutel, Paul Covington, Sagar Jain, Francois Belletti, and Ed Chi. WSDM, 2019.
- [A Clustering-Based Reinforcement Learning Approach for Tailored Personalization of E-Health Interventions](https://arxiv.org/abs/1804.03592)
  - Ali el Hassouni, Mark Hoogendoorn, Martijn van Otterlo, A. E. Eiben, Vesa Muhonen, and Eduardo Barbaro. arXiv, 2018.
- [Generating Interpretable Fuzzy Controllers using Particle Swarm Optimization and Genetic Programming](https://arxiv.org/abs/1804.10960)
  - Daniel Hein, Steffen Udluft, and Thomas A. Runkler. GECCO, 2018.
- [End-to-End Offline Goal-Oriented Dialog Policy Learning via Policy Gradient](https://arxiv.org/abs/1712.02838)
  - Li Zhou, Kevin Small, Oleg Rokhlenko, and Charles Elkan. arXiv, 2017.
- [Batch Reinforcement Learning on the Industrial Benchmark: First Experiences](https://arxiv.org/abs/1705.07262)
  - Daniel Hein, Steffen Udluft, Michel Tokic, Alexander Hentschel, Thomas A. Runkler, and Volkmar Sterzing. IJCNN, 2017.
- [Policy Networks with Two-Stage Training for Dialogue Systems](https://arxiv.org/abs/1606.03152)
  - Mehdi Fatemi, Layla El Asri, Hannes Schulz, Jing He, and Kaheer Suleman. SIGDial, 2016.
- [Adaptive Treatment of Epilepsy via Batch-mode Reinforcement Learning](https://www.aaai.org/Library/IAAI/2008/iaai08-008.php)
  - Arthur Guez, Robert D. Vincent, Massimo Avoli, and Joelle Pineau. IAAI, 2008.

### Off-Policy Evaluation: Theory/Methods

#### Reinforcement Learning
- [Sequential causal inference in a single world of connected units](https://arxiv.org/abs/2101.07380)
  - Aurelien Bibaut, Maya Petersen, Nikos Vlassis, Maria Dimakopoulou, and Mark van der Laan, arXiv, 2021.
- [Off-policy Evaluation in Infinite-Horizon Reinforcement Learning with Latent Confounders](https://arxiv.org/abs/2007.13893)
  - Andrew Bennett, Nathan Kallus, Lihong Li, and Ali Mousavi. AISTATS, 2021.
- [Bootstrapping Statistical Inference for Off-Policy Evaluation](https://arxiv.org/abs/2102.03607)
  - Botao Hao, Xiang (Jack)Ji, Yaqi Duan, Hao Lu, Csaba Szepesvári, and Mengdi Wang. arXiv, 2021.
- [Average-Reward Off-Policy Policy Evaluation with Function Approximation](https://arxiv.org/abs/2101.02808)
  - Shangtong Zhang, Yi Wan, Richard S. Sutton, and Shimon Whiteson. arXiv, 2021.
- [Near-Optimal Provable Uniform Convergence in Offline Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/2007.03760)
  - Ming Yin, Yu Bai, and Yu-Xiang Wang. arXiv, 2020.
- [Optimal Mixture Weights for Off-Policy Evaluation with Multiple Behavior Policies](https://arxiv.org/abs/2011.14359)
  - Jinlin Lai, Lixin Zou, and Jiaxing Song. arXiv, 2020.
- [Kernel Methods for Policy Evaluation: Treatment Effects, Mediation Analysis, and Off-Policy Planning](https://arxiv.org/abs/2010.04855)
  - Rahul Singh, Liyuan Xu, and Arthur Gretton. arXiv, 2020.
- [Off-policy Policy Evaluation For Sequential Decisions Under Unobserved Confounding](https://papers.nips.cc/paper/2020/hash/da21bae82c02d1e2b8168d57cd3fbab7-Abstract.html)
  - Hongseok Namkoong, Ramtin Keramati, Steve Yadlowsky, and Emma Brunskill. NeurIPS, 2020.
- [CoinDICE: Off-Policy Confidence Interval Estimation](https://papers.nips.cc/paper/2020/hash/6aaba9a124857622930ca4e50f5afed2-Abstract.html)
  - Bo Dai, Ofir Nachum, Yinlam Chow, Lihong Li, Csaba Szepesvari, and Dale Schuurmans. NeurIPS, 2020.
- [Off-Policy Interval Estimation with Lipschitz Value Iteration](https://papers.nips.cc/paper/2020/hash/59accb9fe696ce55e28b7d23a009e2d1-Abstract.html)
  - Ziyang Tang, Yihao Feng, Na Zhang, Jian Peng, and Qiang Liu. NeurIPS, 2020.
- [Off-Policy Evaluation via the Regularized Lagrangian](https://papers.nips.cc/paper/2020/hash/488e4104520c6aab692863cc1dba45af-Abstract.html)
  - Mengjiao Yang, Ofir Nachum, Bo Dai, Lihong Li, and Dale Schuurmans. NeurIPS, 2020.
- [Minimax Value Interval for Off-Policy Evaluation and Policy Optimization](https://papers.nips.cc/paper/2020/hash/1cd138d0499a68f4bb72bee04bbec2d7-Abstract.html)
  - Nan Jiang and Jiawei Huang. NeurIPS, 2020.
- [Statistical Bootstrapping for Uncertainty Estimation in Off-Policy Evaluation](https://arxiv.org/abs/2007.13609)
  - Ilya Kostrikov and Ofir Nachum. arXiv, 2020.
- [Towards Off-policy Evaluation as a Prerequisite for Real-world Reinforcement Learning in Building Control](https://dl.acm.org/doi/10.1145/3427773.3427871) [[video](https://www.youtube.com/watch?v=zlk_TDNC4qk)]
  - Bingqing Chen, Ming Jin, Zhe Wang, Tianzhen Hong, and Mario Bergés, RLEM, 2020.
- [Infinite-horizon Off-Policy Policy Evaluation with Multiple Behavior Policies](https://iclr.cc/virtual_2020/poster_rkgU1gHtvr.html)
  - Xinyun Chen, Lu Wang, Yizhe Hang, Heng Ge, and Hongyuan Zha. ICLR, 2020.
- [Doubly Robust Bias Reduction in Infinite Horizon Off-Policy Estimation](https://iclr.cc/virtual_2020/poster_S1glGANtDr.html)
  - Ziyang Tang, Yihao Feng, Lihong Li, Dengyong Zhou, and Qiang Liu. ICLR, 2020.
- [Black-box Off-policy Estimation for Infinite-Horizon Reinforcement Learning](https://iclr.cc/virtual_2020/poster_S1ltg1rFDS.html)
  - Ali Mousavi, Lihong Li, Qiang Liu, and Denny Zhou. ICLR, 2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](http://proceedings.mlr.press/v119/duan20b.html)
  - Yaqi Duan, Zeyu Jia, and Mengdi Wang. ICML, 2020.
- [Interpretable Off-Policy Evaluation in Reinforcement Learning by Highlighting Influential Transitions](http://proceedings.mlr.press/v119/gottesman20a.html)
  - Omer Gottesman, Joseph Futoma, Yao Liu, Sonali Parbhoo, Leo Celi, Emma Brunskill, and Finale Doshi-Velez. ICML, 2020.
- [Double Reinforcement Learning for Efficient and Robust Off-Policy Evaluation](http://proceedings.mlr.press/v119/kallus20b.html)
  - Nathan Kallus and Masatoshi Uehara. ICML, 2020.
- [Understanding the Curse of Horizon in Off-Policy Evaluation via Conditional Importance Sampling](http://proceedings.mlr.press/v119/liu20a.html)
  - Yao Liu, Pierre-Luc Bacon, and Emma Brunskill. ICML, 2020.
- [Minimax Weight and Q-Function Learning for Off-Policy Evaluation](http://proceedings.mlr.press/v119/uehara20a.html)
  - Masatoshi Uehara, Jiawei Huang, and Nan Jiang. ICML, 2020.
- [Accountable Off-Policy Evaluation With Kernel Bellman Statistics](http://proceedings.mlr.press/v119/feng20d.html)
  - Yihao Feng, Tongzheng Ren, Ziyang Tang, and Qiang Liu. ICML, 2020.
- [Asymptotically Efficient Off-Policy Evaluation for Tabular Reinforcement Learning](http://proceedings.mlr.press/v108/yin20b.html)
  - Ming Yin and Yu-Xiang Wang. ICML, 2020.
- [Efficiently Breaking the Curse of Horizon in Off-Policy Evaluation with Double Reinforcement Learning](https://arxiv.org/abs/1909.05850)
  - Nathan Kallus and Masatoshi Uehara. arXiv, 2019.
- [Off-Policy Evaluation in Partially Observable Environments](https://ojs.aaai.org//index.php/AAAI/article/view/6590)
  - Guy Tennenholtz, Uri Shalit, and Shie Mannor. AAAI, 2019.
- [Intrinsically Efficient, Stable, and Bounded Off-Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/1906.03735)
  - Nathan Kallus and Masatoshi Uehara. NeurIPS, 2019.
- [Towards Optimal Off-Policy Evaluation for Reinforcement Learning with Marginalized Importance Sampling](https://papers.nips.cc/paper/2019/hash/4ffb0d2ba92f664c2281970110a2e071-Abstract.html)
  - Tengyang Xie, Yifei Ma, and Yu-Xiang Wang. NeuIPS, 2019.
- [Off-Policy Evaluation via Off-Policy Classification](https://papers.nips.cc/paper/2019/hash/b5b03f06271f8917685d14cea7c6c50a-Abstract.html)
  - Alexander Irpan, Kanishka Rao, Konstantinos Bousmalis, Chris Harris, Julian Ibarz, and Sergey Levine. NeuIPS, 2019.
- [Off-Policy Evaluation and Learning from Logged Bandit Feedback: Error Reduction via Surrogate Policy](https://openreview.net/forum?id=HklKui0ct7)
  - Yuan Xie, Boyi Liu, Qiang Liu, Zhaoran Wang, Yuan Zhou, and Jian Peng. ICLR, 2019.
- [More Efficient Off-Policy Evaluation through Regularized Targeted Learning](http://proceedings.mlr.press/v97/bibaut19a.html)
  - Aurelien Bibaut, Ivana Malenica, Nikos Vlassis, and Mark Van Der Laan. ICML, 2019.
- [Combining parametric and nonparametric models for off-policy evaluation](http://proceedings.mlr.press/v97/gottesman19a.html)
  - Omer Gottesman, Yao Liu, Scott Sussex, Emma Brunskill, and Finale Doshi-Velez. ICML, 2019.
- [Counterfactual Off-Policy Evaluation with Gumbel-Max Structural Causal Models](http://proceedings.mlr.press/v97/oberst19a.html)
  - Michael Oberst and David Sontag. ICML, 2019.
- [Importance Sampling Policy Evaluation with an Estimated Behavior Policy](http://proceedings.mlr.press/v97/hanna19a.html)
  - Josiah Hanna, Scott Niekum, and Peter Stone. ICML, 2019.
- [When People Change their Mind: Off-Policy Evaluation in Non-Stationary Recommendation Environments](https://dl.acm.org/doi/10.1145/3289600.3290958)
  - Rolf Jagerman, Ilya Markov, and Maarten de Rijke. WSDM, 2019.
- [Representation Balancing MDPs for Off-policy Policy Evaluation](https://papers.nips.cc/paper/2018/hash/980ecd059122ce2e50136bda65c25e07-Abstract.html)
  - Yao Liu, Omer Gottesman, Aniruddh Raghu, Matthieu Komorowski, Aldo A. Faisal, Finale Doshi-Velez, and Emma Brunskill. NeuIPS, 2018.
- [Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation](https://papers.nips.cc/paper/2018/hash/dda04f9d634145a9c68d5dfe53b21272-Abstract.html)
  - Qiang Liu, Lihong Li, Ziyang Tang, and Dengyong Zhou. NeuIPS, 2018.
- [Confounding-Robust Policy Improvement](https://papers.nips.cc/paper/2018/hash/3a09a524440d44d7f19870070a5ad42f-Abstract.html)
  - Nathan Kallus and Angela Zhou. NeuIPS, 2018.
- [Balanced Policy Evaluation and Learning](https://papers.nips.cc/paper/2018/hash/6616758da438b02b8d360ad83a5b3d77-Abstract.html)
  - Nathan Kallus. NeuIPS, 2018.
- [More Robust Doubly Robust Off-policy Evaluation](https://arxiv.org/abs/1802.03493)
  - Mehrdad Farajtabar, Yinlam Chow, and Mohammad Ghavamzadeh. ICML, 2018.
- [Importance Sampling for Fair Policy Selection](https://people.cs.umass.edu/~pthomas/papers/Doroudi2017.pdf)
  - Shayan Doroudi, Philip Thomas, and Emma Brunskill. UAI, 2017.
- [Predictive Off-Policy Policy Evaluation for Nonstationary Decision Problems, with Applications to Digital Marketing](https://people.cs.umass.edu/~pthomas/papers/Thomas2017.pdf)
  - Philip S. Thomas, Georgios Theocharous, Mohammad Ghavamzadeh, Ishan Durugkar, and Emma Brunskill. AAAI, 2017.
- [Consistent On-Line Off-Policy Evaluation](http://proceedings.mlr.press/v70/hallak17a.html)
  - Assaf Hallak and Shie Mannor. ICML, 2017.
- [Bootstrapping with Models: Confidence Intervals for Off-Policy Evaluation](https://arxiv.org/abs/1606.06126)
  - Josiah P. Hanna, Peter Stone, and Scott Niekum. AAAMS, 2016.
- [Doubly Robust Off-policy Value Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/jiang16.html)
  - Nan Jiang and Lihong Li. ICML, 2016.
- [Data-Efficient Off-Policy Policy Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/thomasa16.html)
  - Philip Thomas and Emma Brunskill. ICML, 2016.
- [High Confidence Off-Policy Evaluation](https://people.cs.umass.edu/~pthomas/papers/Thomas2015.pdf)
  - Philip S. Thomas, Georgios Theocharous, and Mohammad Ghavamzadeh. AAAI, 2015.
- [Eligibility Traces for Off-Policy Policy Evaluation](https://dl.acm.org/doi/10.5555/645529.658134)
  - Doina Precup, Richard S. Sutton, and Satinder P. Singh. ICML, 2000.


### Off-Policy Evaluation: Benchmarks/Experiments/Applications
- [Towards Automatic Evaluation of Dialog Systems: A Model-Free Off-Policy Evaluation Approach](https://arxiv.org/abs/2102.10242)
  - Haoming Jiang, Bo Dai, Mengjiao Yang, Wei Wei, and Tuo Zhao. arXiv, 2021.
- [Benchmarks for Deep Off-Policy Evaluation](https://openreview.net/forum?id=kWSeGEeHvF8) [[code](https://github.com/google-research/deep_ope)]
  - Justin Fu, Mohammad Norouzi, Ofir Nachum, George Tucker, ziyu wang, Alexander Novikov, Mengjiao Yang, Michael R Zhang, Yutian Chen, Aviral Kumar, Cosmin Paduraru, Sergey Levine, and Thomas Paine. ICLR, 2021.
- [Open Bandit Dataset and Pipeline: Towards Realistic and Reproducible Off-Policy Evaluation](https://arxiv.org/abs/2008.07146) [[software](https://github.com/st-tech/zr-obp)] [[public dataset](https://research.zozo.com/data.html)]
  - Yuta Saito, Shunsuke Aihara, Megumi Matsutani, and Yusuke Narita. arXiv, 2020.
- [Off-Policy Evaluation of Probabilistic Identity Data in Lookalike Modeling](https://dl.acm.org/doi/10.1145/3289600.3291033)
  - Randell Cotta, Dan Jiang, Mingyang Hu, and Peizhou Liao. WSDM, 2019.
- [Offline Evaluation to Make Decisions About Playlist Recommendation](https://dl.acm.org/doi/10.1145/3289600.3291027)
  - Alois Gruson, Praveen Chandar, Christophe Charbuillet, James McInerney, Samantha Hansen, Damien Tardieu, and Ben Carterette. WSDM, 2019.
- [Evaluating Reinforcement Learning Algorithms in Observational Health Settings](https://arxiv.org/abs/1805.12298)
  - Omer Gottesman, Fredrik Johansson, Joshua Meier, Jack Dent, Donghun Lee, Srivatsan Srinivasan, Linying Zhang, Yi Ding, David Wihl, Xuefeng Peng, Jiayu Yao, Isaac Lage, Christopher Mosch, Li-wei H. Lehman, Matthieu Komorowski, Matthieu Komorowski, Aldo Faisal, Leo Anthony Celi, David Sontag, and Finale Doshi-Velez. arXiv, 2018.
- [Towards a Fair Marketplace: Counterfactual Evaluation of the trade-off between Relevance, Fairness & Satisfaction in Recommendation Systems](https://dl.acm.org/doi/10.1145/3269206.3272027)
  - Rishabh Mehrotra, James McInerney, Hugues Bouchard, Mounia Lalmas, and Fernando Diaz. CIKM, 2018.
- [Offline A/B testing for Recommender Systems](https://dl.acm.org/doi/10.1145/3159652.3159687)
  - Alexandre Gilotte, Clément Calauzènes, Thomas Nedelec, Alexandre Abraham, and Simon Dollé. WSDM, 2018.
- [Offline Comparative Evaluation with Incremental, Minimally-Invasive Online Feedback](https://dl.acm.org/doi/10.1145/3209978.3210050)
  - Ben Carterette and Praveen Chandar. SIGIR, 2018.

## Open Source Software/Implementations
- [Open Bandit Pipeline: a research framework for bandit algorithms and off-policy evaluation](https://github.com/st-tech/zr-obp) [[paper](https://arxiv.org/abs/2008.07146)] [[documentation](https://zr-obp.readthedocs.io/en/latest/index.html)] [[public dataset](https://research.zozo.com/data.html)]
  - Yuta Saito, Shunsuke Aihara, Megumi Matsutani, and Yusuke Narita.
- [d3rlpy: A data-driven deep reinforcement learning library as an out-of-the-box tool](https://github.com/takuseno/d3rlpy) [[website](https://takuseno.github.io/d3rlpy/)] [[documentation](https://d3rlpy.readthedocs.io/en/v0.70/)]
  - Takuma Seno.
- [MINERVA: An out-of-the-box GUI tool for data-driven deep reinforcement learning](https://github.com/takuseno/minerva) [[website](https://takuseno.github.io/minerva/)] [[documentation](https://minerva-ui.readthedocs.io/en/v0.20/)]
  - Takuma Seno.
- [Benchmarks for Deep Off-Policy Evaluation](https://github.com/google-research/deep_ope) [[paper](https://openreview.net/forum?id=kWSeGEeHvF8)]
  - Justin Fu, Mohammad Norouzi, Ofir Nachum, George Tucker, ziyu wang, Alexander Novikov, Mengjiao Yang, Michael R Zhang, Yutian Chen, Aviral Kumar, Cosmin Paduraru, Sergey Levine, and Thomas Paine.
- [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://github.com/rail-berkeley/d4rl) [[paper](https://arxiv.org/abs/2004.07219)] [[website](https://sites.google.com/view/d4rl/home)]
  - Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker, and Sergey Levine.
- [RL Unplugged: Benchmarks for Offline Reinforcement Learning](https://github.com/deepmind/deepmind-research/tree/master/rl_unplugged) [[paper](https://arxiv.org/abs/2006.13888)] [[dataset](https://console.cloud.google.com/storage/browser/rl_unplugged?pli=1)]
  - Caglar Gulcehre, Ziyu Wang, Alexander Novikov, Tom Le Paine, Sergio Gomez Colmenarejo, Konrad Zolna, Rishabh Agarwal, Josh Merel, Daniel Mankowitz, Cosmin Paduraru, Gabriel Dulac-Arnold, Jerry Li, Mohammad Norouzi, Matt Hoffman, Ofir Nachum, George Tucker, Nicolas Heess, and Nando de Freitas.
- [NeoRL: Near Real-World Benchmarks for Offline Reinforcement Learning](https://agit.ai/Polixir/neorl) [[paper](https://arxiv.org/abs/2102.00714)] [[website](http://polixir.ai/research/neorl)]
  - Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang, and Yang Yu.
- [RecoGym: A Reinforcement Learning Environment for the problem of Product Recommendation in Online Advertising](https://github.com/criteo-research/reco-gym) [[paper](https://arxiv.org/abs/1808.00720)]
  - David Rohde, Stephen Bonner, Travis Dunlop, Flavian Vasile, and Alexandros Karatzoglou.
- [MARS-Gym: A Gym framework to model, train, and evaluate Recommender Systems for Marketplaces](https://github.com/deeplearningbrasil/mars-gym) [[paper](https://arxiv.org/abs/2010.07035)] [[documantation](https://mars-gym.readthedocs.io/en/latest/)]
  - Marlesson R. O. Santana, Luckeciano C. Melo, Fernando H. F. Camargo, Bruno Brandão, Anderson Soares, Renan M. Oliveira, and Sandor Caetano.

## Blog/Podcast
### Blog
- [Offline Reinforcement Learning: How Conservative Algorithms Can Enable New Applications](https://bair.berkeley.edu/blog/2020/12/07/offline/)
  - Aviral Kumar and Avi Singh. BAIR Blog, 2020.
- [AWAC: Accelerating Online Reinforcement Learning with Offline Datasets](https://bair.berkeley.edu/blog/2020/09/10/awac/)
  - Ashvin Nair and Abhishek Gupta. BAIR Blog, 2020.
- [D4RL: Building Better Benchmarks for Offline Reinforcement Learning](https://bair.berkeley.edu/blog/2020/06/25/D4RL/)
  - Justin Fu. BAIR Blog, 2020.
- [Does On-Policy Data Collection Fix Errors in Off-Policy Reinforcement Learning?](https://bair.berkeley.edu/blog/2020/03/16/discor/)
  - Aviral Kumar and Abhishek Gupta. BAIR Blog, 2020.
- [Tackling Open Challenges in Offline Reinforcement Learning](https://ai.googleblog.com/2020/08/tackling-open-challenges-in-offline.html)
  - George Tucker and Sergey Levine. Google AI Blog, 2020.
- [An Optimistic Perspective on Offline Reinforcement Learning](https://ai.googleblog.com/2020/04/an-optimistic-perspective-on-offline.html)
  - Rishabh Agarwal and Mohammad Norouzi. Google AI Blog, 2020.
- [Decisions from Data: How Offline Reinforcement Learning Will Change How We Use Machine Learning](https://medium.com/@sergey.levine/decisions-from-data-how-offline-reinforcement-learning-will-change-how-we-use-ml-24d98cb069b0)
  - Sergey Levine. Medium, 2020.
- [Introducing completely free datasets for data-driven deep reinforcement learning](https://towardsdatascience.com/introducing-completely-free-datasets-for-data-driven-deep-reinforcement-learning-a51e9bed85f9)
  - Takuma Seno. towards data science, 2020.
- [Offline (Batch) Reinforcement Learning: A Review of Literature and Applications](https://danieltakeshi.github.io/2020/06/28/offline-rl/)
  - Daniel Seita. danieltakeshi.github.io, 2020.
- [Data-Driven Deep Reinforcement Learning](https://bair.berkeley.edu/blog/2019/12/05/bear/)
  - Aviral Kumar. BAIR Blog, 2019.

### Podcast
- [Off-Line, Off-Policy RL for Real-World Decision Making at Facebook](https://twimlai.com/off-line-off-policy-rl-for-real-world-decision-making-at-facebook/)
  - Jason Gauci. TWIML, 2021.
- [MOReL: Model-Based Offline Reinforcement Learning with Aravind Rajeswaran](https://twimlai.com/morel-model-based-offline-reinforcement-learning-with-aravind-rajeswaran/)
  - Aravind Rajeswaran. TWIML, 2020.

## Related Workshops

- [Reinforcement Learning Day 2021](https://www.microsoft.com/en-us/research/event/reinforcement-learning-day-2021/)
- [Offline Reinforcement Learning Workshop (NeurIPS 2020)](https://offline-rl-neurips.github.io/)
- [Reinforcement Learning from Batch Data and Simulation](https://simons.berkeley.edu/workshops/schedule/14240)
- [Virtual Conference on Reinforcement Learning for Real Life (RL4RealLife 2020)](https://sites.google.com/view/RL4RealLife)
- [Safety and Robustness in Decision Making (NeurIPS 2019)](https://sites.google.com/view/neurips19-safe-robust-workshop)

## Tutorials/Talks/Lectures

- [Offline RL](https://slideslive.com/38938455/offline-rl)
  - Nando de Freitas. NeurIPS2020 OfflineRL Workshop.
- [Data Scalability for Robot Learning](https://youtu.be/LGlgSeWemcM)
  - Chelsea Finn. RI Seminar2020.
- [Learning a Multi-Agent Simulator from Offline Demonstrations](https://slideslive.com/38938458/learning-a-multiagent-simulator-from-offline-demonstrations)
  - Brandyn White. NeurIPS2020 OfflineRL Workshop.
- [Towards Reliable Validation and Evaluation for Offline RL](https://slideslive.com/38938459/towards-reliable-validation-and-evaluation-for-offline-rl)
  - Nan Jiang. NeurIPS2020 OfflineRL Workshop.
- [Batch RL Models Built for Validation](https://slideslive.com/38938457/batch-rl-models-built-for-validation)
  - Finale Doshi-Velez. NeurIPS2020 OfflineRL Workshop.
- [Offline Reinforcement Learning: From Algorithms to Practical Challenges](https://sites.google.com/view/offlinerltutorial-neurips2020/home)
  - Aviral Kumar and Sergey Levine. NeurIPS2020.
- [Statistically Efficient Offline Reinforcement Learning](https://youtu.be/n5ZoxT_WmHo)
  - Nathan Kallus. ARL Seminor2020.
- [Near Optimal Provable Uniform Convergence in Off-Policy Evaluation for Reinforcement Learning](https://youtu.be/FWZewbQykv4)
  - Yu-Xiang Wang. RL Theory Seminar2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](https://youtu.be/TX9KBofFZ8s)
  - Mengdi Wang. RL Theory Seminar2020.
- [Exponential Lower Bounds for Batch Reinforcement Learning: Batch RL can be Exponentially Harder than Online RL](https://www.youtube.com/watch?v=YktnEdsxYfc&feature=youtu.be)
  - Andrea Zanette. RL Theory Seminar2020.
- [Beyond the Training Distribution: Embodiment, Adaptation, and Symmetry](https://www.youtube.com/watch?v=wv1zXnxRCCM&feature=youtu.be)
  - Chelsea Finn. EI Seminar2020.
- [Combining Statistical methods with Human Input for Evaluation and Optimization in Batch Settings](https://slideslive.com/38922630/combining-statistical-methods-with-human-input-for-evaluation-and-optimization-in-batch-settings)
  - Finale Doshi-Velez. NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Efficiently Breaking the Curse of Horizon with Double Reinforcement Learning](https://slideslive.com/38922636/efficiently-breaking-the-curse-of-horizon-with-double-reinforcement-learning)
  - Nathan Kallus. NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Scaling Probabilistically Safe Learning to Robotics](https://slideslive.com/38922637/scaling-probabilistically-safe-learning-to-robotics?locale=en)
  - Scott Niekum. NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
