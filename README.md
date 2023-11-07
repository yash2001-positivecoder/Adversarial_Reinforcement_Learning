# Adversarial Reinforcement Learning
This repository contains implementations, experiments, and resources related to Adversarial Reinforcement Learning (Adversarial RL). Adversarial RL is an exciting research area that combines the principles of reinforcement learning and adversarial training to tackle complex decision-making problems in the presence of adversarial agents or environments.

## Introduction
### Reinforcement Learning – Decision Making
Reinforcement Learning (RL) has achieved superhuman performance in everything from data center cooling to video games, with research underway in autonomous driving, negotiation, and automated trading.
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/f400e394-6765-42f8-b278-46fa82eeaaea)

## Adversarial RL
Adversarial Reinforcement Learning is a type of machine learning where an agent learns to make decisions in an environment with adversaries who actively try to hinder its performance. The agent must adapt and respond to changing adversarial behavior while pursuing its objectives.
It is applied in game-playing, cybersecurity, finance, and autonomous driving domains to develop robust and adaptive policies in the presence of adversaries.
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/655a861e-d5e7-4797-9423-650aea3be793)

## Adversarial Example
Deceiving AI systems can lead to making mistakes. The general form of adversarial examples is the information carrier (such as image, voice, or text) with small perturbations (deviation/changes of a system) added, which can remain imperceptible to the human visual system.
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/62b4bcc4-2a49-4a20-b549-9599cbacac30)

## Applying Adversaries in Ping Pong ball game
First we have trained an agent to play the ping pong game using DQN. The results are excellent.
But then we used adversaries in the game which made agent take wrong actions resulting in losing the game.
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/1833c096-0b11-4de8-840e-d9e02aaf5076)

### Adversarial Effect
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/0590906a-b6cb-4a7c-a134-4f43d5d5c684)
![image](https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/assets/99791529/eb169957-0c49-4af0-92ca-90fa79f1941d)

## Defense Mechanism
* Adversarial training with perturbation or noise: It reduces classification errors.
* Gradient Masking: It denies the attacker access to the useful gradient.
* Robust Reinforcement learning: Using more robust algorithms like Proximal Policy Optimization (PPO) and Trust Region Policy Optimization (TRPO), incorporate regularization terms that penalize actions that deviate significantly from the original policy, making the learned policies more robust to adversarial perturbations.
* Ensemble adversarial learning: Multiple classifiers are trained and combined to improve robustness. They work only for certain adversarial policies and not against others, or they do not work against stronger attacks.

## Conclusion
* The existence of such attacks shows the vulnerabilities of function approximators like Neural Nets and forces us to rethink “Generalization in Machine Learning.” It is not that these attacks are a characteristic property of Deep Learning models like Neural Nets. They exist even in the most linear Machine Learning models that we see. Since Neural Nets are built on these architectures, they inherit this flaw.
* Nevertheless, analyzing adversarial attacks encourages us to build more robust systems and be prepared for good average-case and good worst-case performance.

## 📌 Credits :
<a href="https://github.com/yash2001-positivecoder/Adversarial_Reinforcement_Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yash2001-positivecoder/Adversarial_Reinforcement_Learning" />
</a>