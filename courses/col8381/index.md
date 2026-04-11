---
layout: course
---

# COL 8381/864: Special Topics in AI

## Responsible AI 
2025-2026 Semester 2

**Instructor:** [Vijay Keswani](mailto:vkeswani@cse.iitd.ac.in)  
**Classes:** Tues-Fri 2.00-3.30 pm at LH 605  
**Office Hours:** Wed 2.00-4.00 pm at Bharti 418

Sign up at <a href="https://calendly.com/vijaykeswani-slg/office-hours-30-min">this link</a> for office hours or email to set up another time if the above doesn’t work  

---

## Outline

The availability of large datasets and massive computing power has led to a surge in the use of AI and ML-based tools to make decisions regarding humans. Applications of these tools span a variety of domains, such as in healthcare for diagnosis and patient management, in judicial and police settings to predict recidivism and crime patterns, in banking to determine creditworthiness, and even in recruitment to screen resumes. Yet, despite the prevalence of possible use cases, AI and ML tools are also associated with, and sometimes are the source of, a myriad of social issues impacting their real-world usability, such as performance disparity across demographic groups, misrepresentation of minorities in data from generative models, uninterpretable decision processes, and misaligned objectives.


The field of Responsible AI and ML essentially studies the conundrum of how we can harness the supposed benefits of these technologies while avoiding the harms that have been presently documented and are likely to arise in the future. Research in this field proposes methods to investigate and, wherever possible, mitigate the above issues associated with the usage of these technologies. Issues like AI-based discrimination and misalignment arise during interactions of AI and ML tools with individuals (e.g., in online spaces) and societal institutions (e.g., in courts and hospitals). Discovering and formalizing them inherently requires understanding both the internal workings of the AI/ML tools and the social dynamics of the communities and institutions impacted by them, making this field quite interdisciplinary.


### Course Objectives

The purpose of this course is twofold: (a) to introduce students to well-documented AI/ML harms arising in real-world local and global applications, and (b) to prepare them to apply general techniques to evaluate and mitigate future AI/ML-based harms in common societal domains.

---

## Prerequisites

Students would be expected to have a general understanding of AI/ML basics, e.g., sufficient knowledge of topics in probability, statistics, and optimization, as they relate to the development of AI/ML systems.

---

## Topics and Schedule

The course will introduce popular topics in the field of responsible AI from the perspective of the common real-world ethical and practical issues that have been extensively studied in this literature. The topics in the course will be divided into two sections: (i) harms that arise due to a flawed AI/ML development pipeline, which require us to pursue in-depth investigations into this pipeline (to be covered in Weeks 1--8); and (ii) issues that are encountered when AI in employed in institutions to assist/replace humans in existing decision-making setups, which require us to understand the role of AI in broader institutional settings (to be covered in Weeks 9--14). The set of topics that will be covered are listed below.


- **Weeks 1 & 2:** Introduction — Biases, Misalignment, and Issues in Data Generation and Modeling
- **Weeks 3 & 4:** Algorithmic Discrimination and Fairness
- **Weeks 5 & 6:** Prediction, Causation, and Actionability
- **Weeks 7 & 8:** ML Robustness and Explainability
- **Weeks 9 & 10:** AI Alignment
- **Weeks 11 & 12:** Human-in-the-Loop and Participatory AI
- **Week 13:** AI and Social Welfare

---

## Evaluation

Final grades will be based on:
- **Weekly assignments:** ~30%
- **Class project:** ~50%
- **Class participation:** 20%

---

## Readings

### Week 1: Introduction (Jan 2)

**Optional Readings**
1. *[Socially Responsible AI Algorithms: Issues, Purposes, and Challenges](https://arxiv.org/abs/2101.02032)*. Lu Cheng, Kush R. Varshney, Huan Liu (pp. 1–7)
2. *[Managing Extreme AI Risks Amid Rapid Progress](https://www.science.org/doi/full/10.1126/science.adn0117)*. Yoshua Bengio et al.

### Week 2: Data & Models (Jan 6 & 9)

**Required Readings**
1. *[A Framework for Understanding Sources of Harm throughout the Machine Learning Life Cycle](https://arxiv.org/pdf/1901.10002)*. Harini Suresh and John Guttag
2. *[Datasheets for Datasets](https://www.microsoft.com/en-us/research/wp-content/uploads/2019/01/1803.09010.pdf)*. Timnit Gebru et al. Pages 1--8
3. *[A Primer on Mitigating Gender Biases in LLMs: Insights from the Indian Context](https://www.digitalfutureslab.in/publications/a-primer-on-mitigating-gender-biases-in-llms-insights-from-the-indian-context)*. Digital Futures Lab. Pages 5--18
 

**Optional Readings**
1. *[Anatomy of an AI System](https://anatomyof.ai)*. Kate Crawford and Vladan Joler


### Week 3: Algorithmic Fairness (Jan 13 & 16)

**Required Readings**
1. *[Fairness in Machine Learning](https://fairmlbook.org/pdf/fairmlbook.pdf)* (Chapters 3 & 4). Solon Barocas, Moritz Hardt, Arvind Narayanan
2. *[Fairness Constraints: Mechanisms for Fair Classification](https://proceedings.mlr.press/v54/zafar17a.html)*. Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rogriguez, Krishna P. Gummadi 

**Optional Readings**
1. *[The Long History of Algorithmic Fairness](https://www.phenomenalworld.org/analysis/long-history-algorithmic-fairness)*. Rodrigo Ochigame
2. *[Why Don’t Generative AI Models Understand Caste?](https://www.medianama.com/2025/10/223-ai-models-caste-india)*. Medianama
3. *[Fairness in Machine Learning: Lessons from Political Philosophy](https://proceedings.mlr.press/v81/binns18a/binns18a.pdf)*. Reuben Binns

### Week 4: Algorithmic Fairness -- Limitations (Jan 20 & 23)

**Required Readings**
1. *[Fair prediction with disparate impact: A study of bias in recidivism prediction instruments](https://arxiv.org/abs/1703.00056)*. Alexandra Chouldechova
2. *[Re-imagining Algorithmic Fairness in India and Beyond](https://arxiv.org/abs/2101.09995)*. Nithya Sambasivan, Erin Arnesen, Ben Hutchinson, Tulsee Doshi, Vinodkumar Prabhakaran

**Optional Readings**
1. *[Addressing Strategic Manipulation Disparities in Fair Classification](https://arxiv.org/abs/2205.10842)*. Vijay Keswani, L. Elisa Celis
2. *[What's Sex Got To Do With Fair Machine Learning?](https://arxiv.org/abs/2006.01770)*. Lily Hu, Issa Kohler-Hausmann
3. *[Delayed Impact of Fair Machine Learning](https://arxiv.org/abs/1803.04383)*. Lydia T. Liu, Sarah Dean, Esther Rolf, Max Simchowitz, Moritz Hardt

### Week 5: Causation and Actionability (Jan 27 & 30)

**Required Readings**
1. *The Book of Why*, Chapter 1 "The Ladder of Causation". Judea Pearl, Dana Mackenzie
2. *[Actionable Recourse in Linear Classification](https://arxiv.org/abs/1809.06514)*. Berk Ustun, Alexander Spangher, Yang Liu

**Optional Readings**
1. *[Algorithmic Recourse: from Counterfactual Explanations to Interventions](https://dl.acm.org/doi/abs/10.1145/3442188.3445899)*. Amir-Hossein Karimi, Bernhard Schölkopf, Isabel Valera
2. *[Strategic Classification is Causal Modeling in Disguise](https://proceedings.mlr.press/v119/miller20b)*. John Miller, Smitha Milli, Moritz Hardt

### Week 6: Actionability and Social Choice (Feb 3 & 6)

**Required Readings**
1. *[The philosophical basis of algorithmic recourse](https://dl.acm.org/doi/abs/10.1145/3351095.3372876)*. Suresh Venkatasubramanian, Mark Alfano
2. *[Computational Social Choice: The First Four Centuries](https://dl.acm.org/doi/pdf/10.1145/2043236.2043249)*, Ariel D. Procaccia

**Optional Readings**
1. *[Against Predictive Optimization: On the Legitimacy of Decision-Making Algorithms that Optimize Predictive Accuracy](https://digitalgovernmenthub.org/wp-content/uploads/2023/08/predictive_optimiz.pdf)*. Angelina Wang, Sayash Kapoor, Solon Barocas, and Arvind Narayanan
2. *[The computational difficulty of manipulating an election](https://link.springer.com/article/10.1007/BF00295861)*. J. J. Bartholdi III, C. A. Tovey & M. A. Trick 

### Week 7: Interpretability (Feb 10 & 13)

**Required Readings**
1. *[Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)*. (Chapters 2, 3, 4, 6, 7, 9). Christoph Molnar
   
**Optional Readings**
1. *[ML interpretability: Simple isn't easy](https://www.sciencedirect.com/science/article/pii/S0039368123001723)*. Tim Räz
2. *[Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)*. (Chapters 8, 10, 11). Christoph Molnar

### Week 8: Challenges of Interpretability (Feb 17)
   
**Optional Readings**
1. *[Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)*. (Chapters 13--18). Christoph Molnar
2. *[Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead](https://www.nature.com/articles/s42256-019-0048-x)*. Cynthia Rudin
3. *[“If it is easy to understand, then it will have value”: Examining Perceptions of Explainable AI with Community Health Workers in Rural India](https://www.adityavashistha.com/uploads/2/0/8/0/20800650/xxai-chi-2024.pdf)*. CT Okolo, D Agarwal, N Dell, A Vashistha

### Week 9: Robustness (Mar 10 & 13)
   
**Required Readings**
1. *[Machine Learning Security against Data Poisoning: Are We There Yet?](https://arxiv.org/pdf/2204.05986)*. Antonio Emanuele Cinà, Kathrin Grosse, Ambra Demontis, Battista Biggio, Fabio Roli, Marcello Pelillo

**Optional Readings**
1. *[Tree of Attacks: Jailbreaking Black-Box LLMs Automatically](https://arxiv.org/abs/2312.02119)*. Anay Mehrotra, Manolis Zampetakis, Paul Kassianik, Blaine Nelson, Hyrum Anderson, Yaron Singer, Amin Karbasi

### Week 10: Alignment (Mar 17 & 20)
   
**Required Readings**
1. *[AI Alignment: A Comprehensive Survey](https://arxiv.org/pdf/2310.19852)*. (Pages 4--33). Jiaming Ji et al.
2. *[Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290)*. Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn
3. *[Concrete Problems in AI Safety](https://arxiv.org/pdf/1606.06565)*. Dario Amodei, Chris Olah, Jacob Steinhardt, Paul Christiano, John Schulman, Dan Mané

**Optional Readings**
1. *[The AI Alignment Problem: Why It’s Hard, and Where to Start](https://intelligence.org/files/AlignmentHardStart.pdf)*. Eliezer Yudkowsky

### Week 11: Alignment contd. (Mar 24 & 27)
   
**Required Readings**
1. *[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)*. Bai et al.
2. *[Deliberative Alignment: Reasoning Enables Safer Language Models](https://arxiv.org/abs/2412.16339)*. Guan et al.
3. *[The Alignment Problem from a Deep Learning Perspective](https://arxiv.org/pdf/2209.00626)*. Richard Ngo, Lawrence Chan, Sören Mindermann

### Week 12: Alignment Challenges (Apr 7 & 10)
   
**Required Readings**
1. *[Artificial Intelligence, Values, and Alignment](https://link.springer.com/article/10.1007/s11023-020-09539-2)*. Iason Gabriel
2. *[Distributional Preference Learning: Understanding and Accounting for Hidden Context in RLHF](https://arxiv.org/abs/2312.08358)*. Anand Siththaranjan, Cassidy Laidlaw, Dylan Hadfield-Menell

**Optional Readings**
1. *[Beyond Preferences in AI Alignment](https://link.springer.com/article/10.1007/s11098-024-02249-w)*. Tan Zhi-Xuan, Micah Carroll, Matija Franklin & Hal Ashton
2. *[Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback](https://arxiv.org/pdf/2307.15217)*. Casper et al.
3. *[Can AI Model the Complexities of Human Moral Decision-Making? A Qualitative Study of Kidney Allocation Decisions](https://arxiv.org/abs/2503.00940)*. Vijay Keswani, Vincent Conitzer, Walter Sinnott-Armstrong, Breanna K. Nguyen, Hoda Heidari, Jana Schaich Borg

### Week 13: Local Applications (Apr 14 & 17)
   
**Required Readings**
1. *[Artificial intelligence policy in India: a framework for engaging the limits of data-driven decision-making](https://royalsocietypublishing.org/rsta/article/376/2133/20180087/115650/Artificial-intelligence-policy-in-India-a)*. Vidushi Marda
2. *[Seeing Like an Infrastructure: Low-resolution Citizens and the Aadhaar Identification Project](https://dl.acm.org/doi/abs/10.1145/3476056)*. Ranjit Singh, Steven Jackson

**Optional Readings**
1. *[Enough With “Human-AI Collaboration”](https://dl.acm.org/doi/pdf/10.1145/3544549.3582735)*. Advait Sarkar





