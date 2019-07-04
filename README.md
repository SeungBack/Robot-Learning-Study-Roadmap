# About

- This page tracks the roadmap of reinforcement learning study materials, especially for the applications in robot arm. 
- The study materials include the list of papers, presentation file, youtube links, codes, tutorials, and another paper roadmaps for the study of RL.
- Admin: [seunghyeok back](https://ai.gist.ac.kr/prog/gsPerson/ai/S/view.do) in GIST AILAB [[site]](http://ai.gist.ac.kr/)

## Table of Contents
---

- [Papers](#papers)
    - [Value](#value)
    - [Policy](#policy)
    - [Visuomotor](#visuomotor)
    - [Sim-to-Real Transfer](#sim-to-real-transfer)
    - [Etc](#etc)
 
- [Codes](#codes)
    - [Paper Implementations](#paper-implementations)
    - [Platform and Toolkits](#platform-and-toolkits)

- [Courses](#courses)
- [Roadmaps](#roadmaps)



## Papers
---

### Value
* Mnih, Volodymyr, et al. "**Playing atari with deep reinforcement learning.**" arXiv preprint arXiv:1312.5602 (2013).

* Mnih, Volodymyr, et al. "**Human-level control through deep reinforcement learning.**" Nature 518.7540 (2015): 529.

* Van Hasselt, Hado, Arthur Guez, and David Silver. "**Deep Reinforcement Learning with Double Q-Learning**."  AAAI. Vol. 2. (2016). [[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/12389/11847) [[ppt]](https://www.slideshare.net/SeungHyeokBaek/deep-reinforcement-learning-with-double-q-learning)* 

* Wang, Ziyu, et al. "**Dueling Network Architectures for Deep Reinforcement Learning.**" ICML. 2016.

* Schaul, Tom, et al. "**Prioritized experience replay**." ICLR. (2016). [[pdf]](https://arxiv.org/abs/1511.05952.pdf)*

* S. Gu et al., "**Continuous Deep Q-Learning with Model-based Acceleration**", ICML, 2016.
[[pdf]](https://arxiv.org/pdf/1603.00748.pdf)*

*  "**Towards Vision-Based Deep Reinforcement Learning for Robotic Motion Control**", F. Zhang et al., arXiv, 2015.
[[pdf]](https://arxiv.org/pdf/1511.03791.pdf)*

*  Deep Reinforcement Learning in Parameterized Action Space, M. Hausknecht et al., ICLR, 2016.
[[pdf]](https://arxiv.org/pdf/1511.04143.pdf)*

*  TD. Kulkarni et al., "**Deep Successor Reinforcement Learning**", arXiv, 2016.
[[pdf]](https://arxiv.org/pdf/1606.02396.pdf)*

*  Aravind S. L. et al., "**Dynamic Frarme skip Deep Q Network**", arXiv, 2016.

### Policy
* Mnih, Volodymyr, et al. "**Asynchronous methods for deep reinforcement learning**" International conference on machine learning. 2016. [[pdf]](https://arxiv.org/abs/1602.01783) [[ppt]](https://www.slideshare.net/SeungHyeokBaek/181123-asynchronous-method-for-deep-reinforcement-learning-seunghyeok-back) by *Seunghyeok Back*  

* Levine, Sergey, et al. "**End-to-end training of deep visuomotor policies.**" The Journal of Machine Learning Research 17.1 (2016): 1334-1373.

* Schulman, John, et al. "**Trust region policy optimization.**" International Conference on Machine Learning. 2015.

* Schulman, John, et al. "**Proximal policy optimization algorithms.**" arXiv preprint arXiv:1707.06347 (2017).


### Visuomotor
* Levine, Sergey, et al. "**Learning hand-eye coordination for robotic grasping with deep learning and large-scale data collection.**" The International Journal of Robotics Research 37.4-5 (2018): 421-436.

* Zhu, Yuke, et al. "**Reinforcement and imitation learning for diverse visuomotor skills.**" arXiv preprint arXiv:1802.09564 (2018).

* Xie, Annie, et al. "**Few-shot goal inference for visuomotor learning and planning.**" arXiv preprint arXiv:1810.00482 (2018).

* Yu, Tianhe, et al. "**One-Shot Hierarchical Imitation Learning of Compound Visuomotor Tasks.**" arXiv preprint arXiv:1810.11043 (2018).

### Sim-to-Real Transfer
* Wulfmeier, Markus, Ingmar Posner, and Pieter Abbeel. "**Mutual alignment transfer learning.**" arXiv preprint arXiv:1707.07907 (2017).

* Rusu, Andrei A., et al. "**Sim-to-Real Robot Learning from Pixels with Progressive Nets.**" Conference on Robot Learning. 2017.

* Zhang, Fangyi, et al. "**Adversarial Discriminative Sim-to-real Transfer of Visuo-motor Policies.**" arXiv preprint arXiv:1709.05746 (2017).

* Zhang, Chao, Yang Yu, and Zhi-Hua Zhou. "**Learning Environmental Calibration Actions for Policy Self-Evolution.**" IJCAI. 2018.

* Tan, Jie, et al. "**Sim-to-Real: Learning Agile Locomotion For Quadruped Robots.**" arXiv preprint arXiv:1804.10332 (2018).


### Curiosity-driven RL
* Haber, Nick, et al. "**Learning to Play with Intrinsically-Motivated Self-Aware Agents.**" arXiv preprint arXiv:1802.07442 (2018).

### Etc
* Ho, Jonathan, and Stefano Ermon. "**Generative adversarial imitation learning.**" Advances in Neural Information Processing Systems. 2016.

## Codes
---
### Paper Implementations
* Guided Policy Search [[pdf]](http://www.jmlr.org/proceedings/papers/v28/levine13.pdf) [[code]](https://github.com/siemanko/guided-policy-search)

### Platform and Toolkits
* **PyRobot**: hardware independent APIs for robotic manipulation and naviagion [[github]](https://github.com/facebookresearch/pyrobot)
* **PyRep**: a toolkit for robot learning research, built on top of the V-REP [[github]](https://github.com/stepjam/PyRep)


## Courses
---
* CS294-112 at UC Berkeley, 2018: **Deep Reinfocement Learning** [[site]](http://rail.eecs.berkeley.edu/deeprlcourse/), [[youtube]](https://www.youtube.com/playlist?list=PLkFD6_40KJIxJMR-j5A1mkxK26gh_qg37)
* COMPM050/COMPGI13 at UCL, 2015: **Reinforcement Learning** [[site]](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html), [[youtube]](https://www.youtube.com/playlist?list=PLbWDNovNB5mqFBgq7i3MY6Ui4zudcvNFJ)
* **Deep RL Course** from beginner to expert with codes [[site]](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/), [[codes]](https://github.com/simoninithomas/Deep_reinforcement_learning_Course)
* Robot Ignite Academy: **Online ROS Courses** [[site]](https://www.robotigniteacademy.com/)
* **ROS Developers LIVE Class** [[site]](http://www.theconstructsim.com/ros-developers-live-class-develop-with-ros/)


## Roadmaps
---
* [[deep-RL-papers (junhyukoh)]](https://github.com/junhyukoh/deep-reinforcement-learning-papers))
* [[key Papers in Deep RL (OpenAI)]](https://spinningup.openai.com/en/latest/spinningup/keypapers.html))
