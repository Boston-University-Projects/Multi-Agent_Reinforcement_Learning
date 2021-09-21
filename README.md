
# Multi-Agent_Reinforcement_Learning

 Goal: To get a job at Mitsubishi Electric Research Laboratories and a publication for Master Thesis!
 


# Plan Outline

## Chap1 -- Intro: 

- history of RL(Reinforcement Leanring)
- Current Application
- Significance(covered in many papers)
- Promising futures


## Chap 2: Methodologies: 
- 2.1 Classical Algorithm and methods: and then we will have a quick overview of most classical and influential algorithms that people had invented in the past
- 2.2 SOTA Algorithm: Following, we will dive into some current most popular algorithms or methods that people had used to produce those SOTA(State of the art) results.

## Chap 3: Application: 

### 3.1 Realization of Algorithm: 
Then, we will dive into the detail of implementations, and try to apply those algorithms on certain senario and replicate their result. 


After having a solid understanding of the algorithms, and the capability to reproduce the result, it should be enough to make a story and showing them we have some experience and familiarity in this field, but might or might not be enough to fullfill the requirement of two JD(job description), CA1531: Learning-based multi-agent motion planning and DA1508: Safe reinforcement learning for real-life applications listed here, https://www.merl.com/internship/openings?ai=on&ml=on&ro=on.


> DA1508: Safe reinforcement learning for real-life applications, "The ideal candidate should have solid background in RL, e.g. CMDP, and RMDP theories. Knowledge of dynamical system theory and nonlinear control theory is a plus, but not a requirement. Publication of the results produced during the internship is anticipated, e.g., ICML, ICLR, NeurIPS."

==> "Solid Background" didn't not well defined, and they didn't explicitly mention the publication is a must.

> CA1531: Learning-based multi-agent motion planning, "The ideal candidate is enrolled in a PhD program in Electrical, Mechanical, Aerospace Engineering, Robotics, Computer Science or related program, with prior experience in multi-agent motion planning, machine learning (especially supervised, reinforcement, and safe ML), and convex and non-convex optimization. A successful internship will result in innovative methods for multiagent planning, in the development of well-documented (Python/MATLAB) code for validating the proposed methods, and in the submission of relevant results for publication in peer-reviewed conference proceedings and journals."

==> They mentioned their expected result, "innovative methods for multiagent planning, in the development of well-documented (Python/MATLAB) code for validating the proposed methods, and in the submission of relevant results for publication in peer-reviewed conference proceedings and journals" ==> But, they didn't explicitly mention the candidate must have publication in the field as well. 

==> I can see that a publication is sufficient for an "accepted", but not a necessity. I think they still want to open the possibility to those Master or Undergrad student who do not have publication, but being able to show some solid understand in those field. ==> So, I think that's my goal, being able to show my understanding. 


  ### 3.2. Improvement for Publication:

To show the understanding, I think I either should have a paper being published, or have a draft paper that is on the way of being published + some great demonstration of essential concept + some intriguing result/insight/analysis (So, a good interview will be critical!)

- Objective Category of this paper:

==> So, let's push it further and aiming at for a publication at [high-impact conferences/journals](https://blog.csdn.net/liz_Lee/article/details/107247831) (e.g., CoRL, ICLR, NeurIPS, ICML, UAI, RSS, ICRA, COLT, CDC, L4DC, CVPR, ICCV, ECCV, PAMI, IJCV, etc.), and that definitely will be enough to eliminate their concern.

First, we need to decided the type of paper we want to publish (At least, we should give them a reason to accept our paper right?)

- Type of Journel/Conference paper
  - Research Paper -- Invent a innocative algorithm that can be applied to certain field, and the result should be competitve to the current SOTA(not necessary outmatch them, but should outperform the traditional algorithm that invented in the past);
  - Review Article -- A comprehensive overview of current major works. (I saw most of paper has 70-80 pages)
  - and ??


### Q&A:
Q1: Research paper? Is that means I need to invent something that is really important and impactful? and making people believe my invention is useful to other scientist? ==> And, is that possible to be done in a year? ==> I feel it's very unlikely.

Q2: Review paper? ==> I heard some publication will accept some review paper, but I do not sure that boundary between "reject" and "accept", and I also do not sure if Chap2 will be enough for a Review paper.  Overall, I think this one is more doable given the amount of times that I have. (--> I imagine I will only have half year in getting the result, and another half year to analyze thhe result,  writing the report, and presentation all kinda stuff). 



# Learning Material(Book, Video, Tutorial, Paper, Online Courses, etc.)
--- 
Note: Here are a list of great resources that I had collected, and they will expedite my step for understanding this in the field of MARL. 


- Intro:
  - [来自DeepMind的深度强化学习大总结](https://blog.csdn.net/Mbx8X9u/article/details/78173539)
  - [CSDN 博客](https://so.csdn.net/so/search?q=reinforcement%20learning&t=&u=&utm_term=reinforcement%20learning&utm_medium=distribute.pc_toolbar_associateword.none-task-associate_word-opensearch_query-1-%3Cem%3Ereinforcement%3C%2Fem%3E%20learning.nonecase&depth_1-utm_source=distribute.pc_toolbar_associateword.none-task-associate_word-opensearch_query-1-%3Cem%3Ereinforcement%3C%2Fem%3E%20learning.nonecase&request_id=163203433916780269880564&opensearch_request_id=163203433916780269880564)
  - DeepMind – RL Course by David Silver - Lecture 1: Introduction to Reinforcement Learning, [[YouTube Video](https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ)], [[Website](https://www.davidsilver.uk/teaching/)]
  - CS 285 at UC Berkeley, Deep Reinforcement Learning, [[Slides](http://rail.eecs.berkeley.edu/deeprlcourse-fa20/)], [[Video](https://www.youtube.com/playlist?list=PL_iWQOsE6TfURIIhCrlt-wj9ByIVpbfGc)]
  - Steve Brunton
    - [Linear Algebra, 107 series of short 10 min video](https://www.youtube.com/watch?v=aHCyHbRIz44&list=PLMrJAkhIeNNRjxJ_sMtJ02geqw_-vuB7O&index=1)
    - [Control Bootcamp: Overview, 47 Series of 15-20 min vide](https://www.youtube.com/watch?v=Pi7l8mMjYVE&list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m)
      - [Deep Reinforcement Learning: Neural Networks for Learning Control Laws](https://www.youtube.com/watch?v=IUiKAD6cuTA&list=RDCMUCm5mt-A4w61lknZ9lCsZtBw&start_radio=1&rv=IUiKAD6cuTA&t=26)
      - Deep Reinforcement Learning for Fluid Dynamics and Control

- Essential Concept/Methodologies: (Summarized in [Google Docs](https://docs.google.com/document/d/15fNROr4dFXfNl95aA0ONtwxhjZ_QwqlWTocAQEK65NE/edit?usp=sharing))
  - MDP(Markov Decision Process)
  - Q-learning
  - CMDP, and RMDP


- Book
  - [Reinforcement Learning: An Introduction (352 page)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
  - [Algorithms for Reinforcement Learning(98)](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
- Paper
  - [2021] [Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms](https://arxiv.org/pdf/1911.10635.pdf)
  - [Cooperative Multi-Agent Learning: The State of the Art](https://cs.gmu.edu/~lpanait/papers/panait05cmasl.pdf)
  - [Robust Constrained-MDPs: Soft-Constrained Robust
    Policy Optimization under Model Uncertainty](https://arxiv.org/pdf/2010.04870.pdf)


- Code repo
  - ==**Browse State-of-the-Art**==, [Multi-agent Reinforcement Learning](https://paperswithcode.com/task/multi-agent-reinforcement-learning)


- People
  - BU Calin Belta, 
    - Chuangchuang Sun, Xiao Li, Calin Belta, [Automata Guided Semi-Decentralized  Multi-Agent Reinforcement Learning](https://sites.bu.edu/hyness/publications/), American Control Conference (ACC), Denver, CO, USA, 2020