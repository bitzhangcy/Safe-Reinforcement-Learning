# Safe-Reinforcement-Learning

Safe Reinforcement Learning: Process of learning policies that maximize the expectation of the return in problems in which it is important to ensure reasonable system performance and/or respect safety constraints during the learning and/or deployment processes.

Contributed by Chunyang Zhang.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#methods">2. Methods</a></td></tr>
<tr>
    <td>&ensp;<a href="#pinn">2.1 PINN</a></td>
    <td>&ensp;<a href="#deeponet">2.2 DeepONet</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#fourier-operator">2.3 Fourier Operator</a></td>
    <td>&ensp;<a href="#graph-networks">2.4 Graph Networks</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#machine-learning">2.5 Machine Learning</a></td>
    <td>&ensp;<a href="#identification">2.6 Identification</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#finite-element">2.7 Finite Element</a></td>
    <td>&ensp;<a href="#convolutional-filter">2.8 Convolutional Filter</a></td>
</tr>
</table>


## [Survey papers](#content)
1. **A comprehensive survey on safe reinforcement learning.** JMLR, 2015. [paper](https://www.jmlr.org/papers/v16/garcia15a.html)

   *Javier Garcí and Fern o Fernández.*

1. **Policy learning with constraints in model-free reinforcement learning: A survey.** IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/614)

   *Yongshuai Liu, Avishai Halev, and Xin Liu.* 

1. **Safe learning in robotics: From learning-based control to safe reinforcement learning.** Annual Review of Control, Robotics, and Autonomous Systems, 2022. [paper](https://www.annualreviews.org/doi/10.1146/annurev-control-042920-020211)

   *Lukas Brunke, Melissa Greeff, Adam W. Hall, Zhaocong Yuan, Siqi Zhou, Jacopo Panerati, and Angela P. Schoellig.* 

1. **A review of safe reinforcement learning: Methods, theory and applications.** arXiv, 2022. [paper](https://arxiv.org/abs/2205.10330)

   *Shangding Gu, Long Yang, Yali Du, Guang Chen, Florian Walter, Jun Wang, Yaodong Yang, and Alois Knoll.* 

1. **Deep reinforcement learning for autonomous driving: A survey.** IEEE Transactions on Intelligent Transportation Systems, 2021. [paper](https://ieeexplore.ieee.org/document/9351818)

   *Kiran, B Ravi and Sobh, Ibrahim and Talpaert, Victor and Mannion, Patrick and Sallab, Ahmad A. Al and Yogamani, Senthil, and Pérez, Patrick.* 


## [Methods](#content)
### [Model](#content) 
1. **Provably efficient reinforcement learning with linear function approximation.** ICML, 2020. [paper](https://proceedings.mlr.press/v125/jin20a.html)

   *Chi Jin, Zhuoran Yang, Zhaoran Wang, and Michael I Jordan.* 

1. **Model-based safe deep reinforcement learning via a constrained proximal policy optimization algorithm.** NIPS, 2022. [paper](https://arxiv.org/abs/2210.07573)

   *Ashish Kumar Jayant and Shalabh Bhatnagar.* 

### [Lyapunov Function](#content)
1. **Lyapunov-based safe policy optimization for continuous control.** ICML, 2019. [paper](https://openreview.net/forum?id=SJgUYBVLsN)

   *Yinlam Chow, Ofir Nachum, Aleksandra Faust, Edgar Duez-Guzmn, and Mohamamd Ghavamzadeh.* 

1. **Lyapunov design for safe reinforcement learning.** JMLR, 2002. [paper](https://www.jmlr.org/papers/v3/perkins02a.html)

   *Theodore J. Perkins and Andrew G. Barto.* 

### [Actor Critic](#content) 
1. **WCSAC: Worst-case soft actor critic for safety-constrained reinforcement learning.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/17272)

   *Qisong Yang, Thiago D. Sim˜ao, Simon H. Tindemans, and Matthijs T. J. Spaan.* 

### [Latent Representation](#content) 
1. **Safe reinforcement learning from pixels using a stochastic latent representation.** ICLR, 2023. [paper](https://openreview.net/forum?id=b39dQt_uffW)

   *Yannick Hogewind, Thiago D. Simao, Tal Kachman, and Nils Jansen.* 

### [Policy Optimization](#content) 
1. **Constrained Policy Optimization.** ICML, 2017. [paper](https://proceedings.mlr.press/v70/achiam17a)

   *Joshua Achiam, David Held, Aviv Tamar, and Pieter Abbeel.* 

1. **Reward constrained policy optimization.** ICLR, 2019. [paper](https://openreview.net/forum?id=SkfrvsA9FX)

   *Chen Tessler, Daniel J. Mankowitz, and Shie Mannor.* 

1. **Projection-based constrained policy optimization.** ICLR, 2020. [paper](https://openreview.net/forum?id=rke3TJrtPS)

   *Tsung-Yen Yang, Justinian Rosca, Karthik Narasimhan, and Peter J. Ramadge.* 

1. **CRPO: A new approach for safe reinforcement learning with convergence guarantee.** ICML, 2021. [paper](https://proceedings.mlr.press/v139/xu21a.html)

   *Tengyu Xu, Yingbin Liang, and Guanghui Lan.* 

1. **When to update your model: Constrained model-based reinforcement learning.** NIPS, 2022. [paper](https://openreview.net/forum?id=ccWaPGl9Hq)

   *Tianying Ji, Yu Luo, Fuchun Sun, Mingxuan Jing, Fengxiang He, and Wenbing Huang.*

### [Inverse RL](#content) 
1. **Inverse constrained reinforcement learning.** ICML, 2021. [paper](https://proceedings.mlr.press/v139/malik21a.html)

   *Shehryar Malik, Usman Anwar, Alireza Aghasi, and Ali Ahmed.* 

## [Mechanism](#content) 
### [Safe Set](#content) 
1. **Safe reinforcement learning in constrained Markov decision processes.** ICML, 2020. [paper](http://proceedings.mlr.press/v119/wachi20a.html)

   *Akifumi Wachi and Yanan Sui .*

### [Deployment](#content) 
1. **Towards deployment-efficient reinforcement learning: Lower bound and optimality.** ICLR, 2022. [paper](https://openreview.net/forum?id=ccWaPGl9Hq)

   *Jiawei Huang, Jinglin Chen, Li Zhao, Tao Qin, Nan Jiang, and Tie-Yan Liu.*

### [Continual Learning](#content) 
1. **Experience replay for continual learning.** NIPS, 2019. [paper](https://papers.nips.cc/paper/2019/hash/fa7cdfad1a5aaf8370ebeda47a1ff1c3-Abstract.html)

   *David Rolnick, Arun Ahuja, Jonathan Schwarz, Timothy Lillicrap, and Gregory Wayne.* 

### [Rewards](#content) 
1. **Redeeming intrinsic rewards via constrained optimization.** arXiv, 2022. [paper](https://arxiv.org/abs/2211.07627)

   *Eric Chen, Zhang-Wei Hong, Joni Pajarinen, and Pulkit Agrawal.* 

### [Lagrangian](#content) 
1. **Responsive safety in reinforcement learning by PID lagrangian methods.** ICML, 2020. [paper](https://proceedings.mlr.press/v119/stooke20a.html)

   *Adam Stooke, Joshua Achiam, and Pieter Abbeel.* 

## [Application](#content) 
### [3D](#content) 
1. **Online 3D bin packing with constrained deep reinforcement learning.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16155)

   *Hang Zhao, Qijin She, Chenyang Zhu, Yin Yang, and Kai Xu.*

### [Attack](#content) 
1. **Spatiotemporally constrained action space attacks on deep reinforcement learning agents.** AAAI, 2020. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/5887)

   *Xian Yeow Lee, Sambit Ghadai, Kai Liang Tan, Chinmay Hegde, and Soumik Sarkar.*