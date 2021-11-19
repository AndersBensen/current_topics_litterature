# Current topics in computer security

- **PDF'er**
  - [Machine learning in cybersecurity: a comprehensive survey](https://learn.inside.dtu.dk/d2l/le/content/79628/viewContent/329743/View)
  - [Machine Learning-Algorithms, Real‑World Applications and Research Directions](https://learn.inside.dtu.dk/d2l/le/content/79628/viewContent/329744/View)
  - [Adversarial Machine Learning for Spam Filters](http://people.cst.cmich.edu/liao1q/papers/amlspam.pdf)
  - [Adversarial Attacks on Deep Learning Models in Natural
Language Processing: A Survey](https://arxiv.org/pdf/1901.06796.pdf)
  - [Privacy-Preserving Deep Learning on Machine
Learning as a Service—A Comprehensive Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9194237)
  - [Machine Learning as an Adversarial Service: Learning Black-Box Adversarial Examples](https://www.semanticscholar.org/paper/Machine-Learning-as-an-Adversarial-Service%3A-Hayes-Danezis/dd265843936c8dfdfba1517e1fd1ae15722e6bd4)

  - [Simple Transparent Adversarial Examples](https://arxiv.org/pdf/2105.09685.pdf)
  - [A Survey of Privacy Attacks in Machine Learning](https://arxiv.org/pdf/2007.07646.pdf)
  - [Github: Awesome ML privacy attacks](https://github.com/stratosphereips/awesome-ml-privacy-attacks)
  - [Special-purpose Model Extraction Attacks:
Stealing Coarse Model with Fewer Queries](https://findit.dtu.dk/en/catalog/2612513804)
    
- Fra ***Adversarial Attacks*** i Securing Machine Learning in the Cloud: A Systematic Review of Cloud Machine Learning Security
  - [Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/pdf/1712.04248.pdf): Decision-based and Boundary attacks (image-based attacks on MLaaS on two blackbox models from clarifai.com

  - [Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey](https://ieeexplore-ieee-org.proxy.findit.dtu.dk/stamp/stamp.jsp?tp=&arnumber=8294186)
  - [Adversarial Examples: Attacks and Defenses for Deep Learning](https://arxiv.org/pdf/1712.07107.pdf)
  - [Waf-a-mole: Evading web application firewalls through adversarial machine learning](https://dl-acm-org.proxy.findit.dtu.dk/doi/pdf/10.1145/3341105.3373962)

**MLaaS**
- (June 2019) [Evasion attacks against watermarking techniques found in MLaaS systems](https://ieeexplore-ieee-org.proxy.findit.dtu.dk/stamp/stamp.jsp?tp=&arnumber=8768572)
    - (2021) [Preventing Watermark Forging Attacks in a MLaaS Environment](https://scitepress.org/Link.aspx?doi=10.5220/0010560602950306)
    - (Feb 2018) [Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring](https://arxiv.org/abs/1802.04633)
- [Stealing Machine Learning Models via Prediction APIs](https://arxiv.org/pdf/1609.02943.pdf)
    - Det her er vidst en af de OG's i emnet
- [Membership inference attacks against machine learning models](https://www.cs.cornell.edu/~shmat/shmat_oak17.pdf)
- [ATTACKING AND DEFENDING MACHINE LEARNING APPLICATIONS OF PUBLIC CLOUD](https://arxiv.org/pdf/2008.02076.pdf)
- I tekst (NLP): 
    - [Fall of Giants: How popular text-based MLaaS fall against a simple evasion attack (Luca Pajola)](https://arxiv.org/pdf/2104.05996.pdf)
        - Snyder diverse MLaaS med ZeW
    - [Deceiving Google’s Perspective API Built for Detecting Toxic Comments](https://arxiv.org/pdf/1702.08138.pdf)
        - Snyder google perspective
    - [All You Need is “Love”: Evading Hate Speech Detection](https://arxiv.org/pdf/1808.09115.pdf)
        - Snyder google perspective
    - [Acoustic and Visual Approaches to Adversarial Text Generation for Google Perspective](https://ieeexplore.ieee.org/document/9071126)
        - Snyder google perspective (?)
    - [TEXTBUGGER: Generating Adversarial Text Against Real-world Applications](https://arxiv.org/pdf/1812.05271.pdf)
        - Snyder diverse MLaaS med evasion
- I billeder (CV): 
    - [Attacking Automatic Video Analysis Algorithms: A Case Study of Google Cloud Video Intelligence API](https://arxiv.org/pdf/1708.04301.pdf)
    - [ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models](https://arxiv.org/pdf/1806.01246.pdf)
    - [With Great Training Comes Great Vulnerability: Practical Attacks against Transfer Learning](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-wang.pdf)
    - [Disguised-Nets: Image Disguising for Privacy-preserving Outsourced Deep Learning](https://arxiv.org/pdf/1902.01878.pdf)
    - [Simple Transparent Adversarial Examples](https://findit.dtu.dk/en/catalog/2689044810)
      - Snyder object detection på azure og google lcoud
---
## Report structure

- Abstract (0,5 p)
- Introduction (2 p)
    - Machine Learning models for different applications
    - MLaaS
- Related work (2 p)
- AML in general (3 p)
    - General approaches
    - Image-based
    - Text-based
- AML in MLaaS (5 p)
    - Image-based
    - Text-based (e.g. Fall of Giants - Luca)
    - Model Extraction
    - Evasion Attacks against watermarking techniques
- Discussion 2-3 p
    - Evaluating the entire topic and sources to see if something is not covered or only partly covered (strengths, weaknesses, differences, open issues,..)
- Conclusion (1 p)

For inspiration look at:
- https://learn.inside.dtu.dk/d2l/le/content/79628/viewContent/329330/View
- https://learn.inside.dtu.dk/d2l/le/content/79628/viewContent/329344/View

## Presentation Structure

- Intro (From tricking local models to attacking MLaaS: A survey on adversarial machine learning)
- Agenda
- Applications of ML (Text-based, Image-based, ...) (Anders)
- Adversarial Machine Learning (Erik)
- AML on local models (From Articles)
    - Image-Based (Johannes)
    - Text-Based (Anders)
- What is MLaaS?
- AML in MLaaS (From Articles)
    - Image-Based ()
    - Text-Based (Anders)
    - Model Extraction ()
    - Watermarking (Erik)
- Related work (Main topics - Sources will be at the end of slideshow)
- Sources


## Must read

- (Sep 2018) [Adversarial Attacks and Defences: A Survey](https://arxiv.org/pdf/1810.00069.pdf)
- (Dec 2020) [Securing Machine Learning in the Cloud: A Systematic Review of Cloud Machine Learning Security](https://www.researchgate.net/publication/346572893_Securing_Machine_Learning_in_the_Cloud_A_Systematic_Review_of_Cloud_Machine_Learning_Security)
- (Sep 2020) [Adversarial Machine Learning in Image Classification: A Survey Towards the Defender's Perspective](https://arxiv.org/abs/2009.03728): https://pad.nordskov.io/imageaml
- (Nov 2020) [Machine Learning as a Service – Challenges in Research and Applications](https://www.researchgate.net/publication/346471896_Machine_Learning_as_a_Service_-_Challenges_in_Research_and_Applications)

---
## E-mail

Hello Nicola

We have been looking into the topic of Adversarial Machine Learning (AML). There are both surveys and technical reports on this topic.
On your recommendation, we tried looking into what areas has not been covered by surveys so far, to find some "novelty". We found that Adversarial attacks on Machine Learning as a Service (MLaaS) are somewhat covered by technical reports, but not so much by surveys. That is why we are thinking of writing a survey on this topic.
The survey will be motivated by newfound adversarial attacks on MLaaS covered in the previously mentioned technical reports but also adversarial attacks on ML models. AML in general is partly covered by surveys (such as https://arxiv.org/pdf/1810.00069.pdf), so this will just be a starting point for our survey.

At the moment, we are thinking about structuring our report something like the following:

- Abstract
- Introduction
    - Machine Learning models for different applications
    - MLaaS
- Related work
- AML in general
    - General approaches
    - Image-based
    - Text-based
- AML in MLaaS
    - Image-based
    - Text-based (e.g. Fall of Giants - Luca)
    - Model Extraction
    - Evasion Attacks against watermarking techniques
- Discussion
- Conclusion

And the title could be something like: "From tricking local models to MLaaS: A survey on adversarial machine learning"

We are a bit unsure whether we can categorize model extraction attacks and evasion attacks against watermarking techniques as AML. The articles found does not give clear answer to this.

One suggestion to accommodate this is add a section to the introduction describing definition of AML for this survey. And that could be: AML is attacks on machine learning models which manipulate the models to give a (un)desirable output or tamper with the integrity of the model. 

Some references are:
https://arxiv.org/pdf/2104.05996.pdf
https://www.researchgate.net/publication/346572893_Securing_Machine_Learning_in_the_Cloud_A_Systematic_Review_of_Cloud_Machine_Learning_Security
https://ieeexplore-ieee-org.proxy.findit.dtu.dk/stamp/stamp.jsp?tp=&arnumber=9343086
https://ieeexplore-ieee-org.proxy.findit.dtu.dk/stamp/stamp.jsp?tp=&arnumber=8768572

Br,
Johannes, Anders, and Erik
