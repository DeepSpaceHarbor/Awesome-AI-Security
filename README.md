# Awesome AI Security ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A curated list of AI security resources inspired by [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning) & [awesome-ml-for-cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity).
    
[research]: https://cdn4.iconfinder.com/data/icons/48-bubbles/48/12.File-32.png "Research"
[slides]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/x-office-presentation-32.png "Slides"
[video]: https://cdn2.iconfinder.com/data/icons/snipicons/500/video-32.png "Video"
[web]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/internet-web-browser-32.png "Website or blog post"
[code]: https://cdn2.iconfinder.com/data/icons/snipicons/500/application-code-32.png "Code"
[other]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/emblem-symbolic-link-32.png "Uncategorized"

#### Legend:
|Type| Icon|
|---|---|
| Research  | ![][research]|
| Slides  | ![][slides] |
| Video | ![][video]  |
| Website / Blog post  | ![][web]  |
| Code  | ![][code]|
| Other  | ![][other]|

## Keywords:
- [Adversarial examples](#-adversarial-examples)
- [Evasion attacks](#-evasion)
- [Poisoning attacks](#-poisoning)
- [Feature selection](#-feature-selection)
- Tutorials
- [Misc](#-misc)
- [Code](#-code)
- [Links](#-links)

## [▲](#keywords) Adversarial examples
|Type|Title|
|---|:---|
|![][research]  | [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)  |
| ![][research]  | [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277)|
|![][research] | [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770)|
|![][research] | [On the (Statistical) Detection of Adversarial Examples](https://arxiv.org/abs/1702.06280)|
|![][research] | [The Space of Transferable Adversarial Examples](https://arxiv.org/abs/1704.03453)|
|![][research] | [Adversarial Attacks on Neural Network Policies](http://rll.berkeley.edu/adversarial/)|
|![][research] | [Adversarial Perturbations Against Deep Neural Networks for Malware Classification](https://arxiv.org/abs/1606.04435)|
|![][research] | [Crafting Adversarial Input Sequences for Recurrent Neural Networks](https://arxiv.org/abs/1604.08275)|
|![][research]| [Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697)|
|![][research]| [Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533)|
|![][research]| [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945)|
|![][research]| [Can you fool AI with adversarial examples on a visual Turing test?](https://arxiv.org/abs/1709.08693)|
|![][research]| [Synthesizing Robust Adversarial Examples](https://arxiv.org/abs/1707.07397)|
|![][research]| [Defensive Distillation is Not Robust to Adversarial Examples](http://nicholas.carlini.com/papers/2016_defensivedistillation.pdf)|
|![][research]| [Vulnerability of machine learning models to adversarial examples](http://ceur-ws.org/Vol-1649/187.pdf)|
|![][research]| [Adversarial Examples for Evaluating Reading Comprehension Systems](https://nlp.stanford.edu/pubs/jia2017adversarial.pdf)|
|![][video]| [Adversarial Examples and Adversarial Training by Ian Goodfellow at Stanford](https://www.youtube.com/watch?v=CIfsB_EYsVI)|
|![][research]| [Tactics of Adversarial Attack on Deep Reinforcement Learning Agents](http://yclin.me/adversarial_attack_RL/)|
|![][research]| [Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey](https://arxiv.org/abs/1801.00553)|
|![][research]| [Did you hear that? Adversarial Examples Against Automatic Speech Recognition](https://arxiv.org/abs/1801.00554)|
|![][research]| [Adversarial Manipulation of Deep Representations](https://arxiv.org/abs/1511.05122)|
|![][research]| [Exploring the Space of Adversarial Images](https://arxiv.org/abs/1510.05328)|
|![][research]| [Note on Attacking Object Detectors with Adversarial Stickers](https://arxiv.org/abs/1712.08062)|
|![][research]| [Adversarial Patch](https://arxiv.org/abs/1712.09665)|
|![][research]| [LOTS about Attacking Deep Features](https://arxiv.org/abs/1611.06179)|
|![][research]| [Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN](https://arxiv.org/abs/1702.05983)|
|![][research]| [Adversarial Images for Variational Autoencoders](https://arxiv.org/abs/1612.00155)|
|![][research]| [Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452)|
|![][research]| [Simple Black-Box Adversarial Perturbations for Deep Networks](https://arxiv.org/abs/1612.06299)|
|![][research]| [DeepFool: a simple and accurate method to fool deep neural networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Moosavi-Dezfooli_DeepFool_A_Simple_CVPR_2016_paper.pdf)|


## [▲](#keywords) Evasion
|Type|Title|
|---|:---|
|![][research]|[Query Strategies for Evading Convex-Inducing Classifiers](https://people.eecs.berkeley.edu/~adj/publications/paper-files/1007-0484v1.pdf)|
|![][research]|[Evasion attacks against machine learning at test time](https://pralab.diee.unica.it/sites/default/files/Biggio13-ecml.pdf)|
|![][research]|[Automatically Evading Classifiers A Case Study on PDF Malware Classifiers](http://evademl.org/docs/evademl.pdf)|
|![][research]|[Looking at the Bag is not Enough to Find the Bomb: An Evasion of Structural Methods for Malicious PDF Files Detection](https://pralab.diee.unica.it/sites/default/files/maiorca_ASIACCS13.pdf)|
|![][research]|[Generic Black-Box End-to-End Attack against RNNs and Other API Calls Based Malware Classifiers](https://arxiv.org/abs/1707.05970)|
|![][research]|[Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition](https://www.cs.cmu.edu/~sbhagava/papers/face-rec-ccs16.pdf)|
|![][research]| [Fast Feature Fool: A data independent approach to universal adversarial perturbations](https://arxiv.org/abs/1707.05572v1)|
|![][research]| [One pixel attack for fooling deep neural networks](https://arxiv.org/abs/1710.08864v1)|
|![][research]| [Adversarial Generative Nets: Neural Network Attacks on State-of-the-Art Face Recognition](https://arxiv.org/abs/1801.00349)|
|![][research]| [RHMD: Evasion-Resilient Hardware Malware Detectors](http://www.cs.ucr.edu/~kkhas001/pubs/micro17-rhmd.pdf)|

## [▲](#keywords) Poisoning
|Type|Title|
|---|:---|
|![][research] ![][slides]|[Poisoning Behavioral Malware Clustering](http://pralab.diee.unica.it/en/node/1121)|
|![][research]|[Efficient Label Contamination Attacks Against Black-Box Learning Models](https://www.ijcai.org/proceedings/2017/0551.pdf)|
|![][research]|[Towards Poisoning of Deep Learning Algorithms with Back-gradient Optimization](https://arxiv.org/abs/1708.08689)|

## [▲](#keywords) Feature selection
|Type|Title|
|---|:---|
|![][research] ![][slides]|[Is Feature Selection Secure against Training Data Poisoning?](https://pralab.diee.unica.it/en/node/1191)|

## [▲](#keywords) Misc
|Type|Title|
|---|:---|
|![][research] |[Can Machine Learning Be Secure?](https://people.eecs.berkeley.edu/~adj/publications/paper-files/asiaccs06.pdf)|
|![][research]|[On The Integrity Of Deep Learning Systems In Adversarial Settings](https://etda.libraries.psu.edu/catalog/28680)|
|![][research]|[Stealing Machine Learning Models via Prediction APIs](https://arxiv.org/abs/1609.02943)|
|![][research]|[Data Driven Exploratory Attacks on Black Box Classifiers in Adversarial Domains](https://arxiv.org/abs/1703.07909)|
|![][research]|[Model Inversion Attacks that Exploit Confidence Information and Basic Countermeasures](https://www.cs.cmu.edu/~mfredrik/papers/fjr2015ccs.pdf)|
|![][research]|[A Methodology for Formalizing Model-Inversion Attacks](https://andrewxiwu.github.io/public/papers/2016/WFJN16-a-methodology-for-modeling-model-inversion-attacks.pdf)|
|![][research]|[Adversarial Attacks against Intrusion Detection Systems: Taxonomy, Solutions and Open Issues](https://pdfs.semanticscholar.org/d4e8/aed54dc4c6bed41651254a49d47885648142.pdf)|
|![][slides]|[Adversarial Data Mining for Cyber Security](https://www.utdallas.edu/~muratk/CCS-tutorial.pdf)|
|![][research]| [High Dimensional Spaces, Deep Learning and Adversarial Examples](https://arxiv.org/abs/1801.00634)|
|![][research]| [Neural Networks in Adversarial Setting and Ill-Conditioned Weight Space](https://arxiv.org/abs/1801.00905)|
|![][web]| [Adversarial Machines](https://medium.com/@samim/adversarial-machines-998d8362e996)|
|![][research]| [Adversarial Task Allocation](https://arxiv.org/abs/1709.00358)|
|![][research]| [Vulnerability of Deep Reinforcement Learning to Policy Induction Attacks](https://arxiv.org/abs/1701.04143)|
|![][research]| [Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)|
|![][research]| [Adversarial Robustness: Softmax versus Openmax](https://arxiv.org/abs/1708.01697)|
|![][video]| [DEF CON 25 - Hyrum Anderson - Evading next gen AV using AI](https://youtu.be/FGCle6T0Jpc)|
|![][web]| [Adversarial Learning for Good: My Talk at #34c3 on Deep Learning Blindspots](http://blog.kjamistan.com/adversarial-learning-for-good-my-talk-at-34c3-on-deep-learning-blindspots/)|
|![][research]| [Universal adversarial perturbations](https://arxiv.org/abs/1610.08401)|
|![][other]| [Camouflage from face detection - CV Dazzle](https://www.cvdazzle.com/)|

## [▲](#keywords) Code
|Type|Title|
|---|:---|
|![][code]|[CleverHans - Python library to benchmark machine learning systems vulnerability to adversarial examples](https://github.com/tensorflow/cleverhans)|
|![][code]|[Model extraction attacks on Machine-Learning-as-a-Service platforms](https://github.com/ftramer/Steal-ML)|
|![][code]|[Foolbox - Python toolbox to create adversarial examples](https://github.com/bethgelab/foolbox)|
|![][code]|[Adversarial Machine Learning Library(Ad-lib)](https://github.com/vu-aml/adlib)|
|![][code]|[Deep-pwning](https://github.com/cchio/deep-pwning)|
|![][code]|[DeepFool](https://github.com/lts4/deepfool)|
|![][code]|[Universal adversarial perturbations](https://github.com/LTS4/universal)|
|![][code]|[Malware Env for OpenAI Gym](https://github.com/endgameinc/gym-malware)|
|![][code]|[Exploring the Space of Adversarial Images](https://github.com/tabacof/adversarial)|
|![][code]|[AntiNex - Highly Accurate Deep Neural Networks to defend Software Systems from Network Exploits (works with docker-compose, Kubernetes and Openshift)](https://github.com/jay-johnson/train-ai-with-django-swagger-jwt)|

## [▲](#keywords) Links
|Type|Title|
|---|:---|
|![][web]|[EvadeML - Machine Learning in the Presence of Adversaries](http://evademl.org/)|
|![][web]|[Adversarial Machine Learning - PRA Lab](https://pralab.diee.unica.it/en/AdversarialMachineLearning)|
|![][web]|[Adversarial Examples and their implications](https://hackernoon.com/the-implications-of-adversarial-examples-deep-learning-bits-3-4086108287c7)|

