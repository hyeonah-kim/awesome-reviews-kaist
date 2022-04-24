---
description : Fu et al. / Towards Effective Context for Meta-Reinforcement Learning: an Approach based on Contrastive Learning / AAAI-2021  
---

# **Towards Effective Context for Meta-Reinforcement Learning: an Approach based on Contrastive Learning** 

[comment]: <> (Towards Effective Context for Meta-Reinforcement Learning: an Approach based on Contrastive Learning)

## **1. Problem Definition**  

비슷한 구조를 가지는 여러 task들이 주어진 상황에서 meta-RL은 과거 학습 경험을 바탕으로 common knowledge를 인식하고, 적은 양의 상호작용을 통해 이를 새로운 task에 적용.
Context-based meta-RL에서 latent context의 퀄리티는 중요한 요소록 작용하며 알고리즘의 성능에 큰 영향을 미침.
Context encoder 성능을 향상시키기 위해 contrastive learning 방법(Contrastive learning augmented Context-based Meta-RL; CCM)을 도입하고, 유용한 정보를 제공하는 trajectory 탐색 기법을 제안.


## **2. Motivation**  

Context-based meta-RL에서 latent context는 task들의 분포를 잘 파악하고 새로운 task를 잘 추론하는 것이 중요.
기존 방식들(Rakelly et al., 2019; Lee et al., 2020)은 불필요한 상관관계를 포착하거나 task 특유의 정보를 무시하는 경향을 보임.
또한 학습과정에 서로 구별되는 context 생성하기 위한 탐색(exploration)에 대한 중요성을 무시하는 경향이 있음.
본 논문에서는 context encoder 성능을 향상시키기 위해 contrastive learning 방법(Contrastive learning augmented Context-based Meta-RL; CCM)을 도입하고, 유용한 정보를 제공하는 trajectory 탐색 기법을 제안.


## **3. Method**  

### Preliminary

*Meta-RL*에서는 여러 task들이 존재. 각 task 

Please write the methodology author have proposed.  
We recommend you to provide example for understanding it more easily.  

## **4. Experiment**  

In this section, please write the overall experiment results.  
At first, write experiment setup that should be composed of contents.  

### **Experiment setup**  
* Dataset  
* baseline  
* Evaluation Metric  

### **Result**  
Then, show the experiment results which demonstrate the proposed method.  
You can attach the tables or figures, but you don't have to cover all the results.  
  



## **5. Conclusion**  

Please summarize the paper.  
It is free to write all you want. e.g, your opinion, take home message(오늘의 교훈), key idea, and etc.

---  
## **Author Information**  

* Hautian Fu
    * College of Intelligence and Computing, Tianjin University
    * Research Topic

* Hongyao Tang
    * College of Intelligence and Computing, Tianjin University
    * Research Topic

* Jianye Hao
    * College of Intelligence and Computing, Tianjin University
    * Noah’s Ark Lab, Huawei
    * Research Topic
  
* Chen Chen
    * Noah’s Ark Lab, Huawei
    * Research Topic
  
* Xidong Feng
    * Department of Automation, Tsinghua University
    * Research Topic
  
* Dong Li
    * Noah’s Ark Lab, Huawei
    * Research Topic
  
## **6. Reference & Additional materials**  

Please write the reference. If paper provides the public code or other materials, refer them.  

* Github Implementation  
* Reference  

