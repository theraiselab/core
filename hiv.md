---
layout: page
title: AI for Public Health
subtitle: HIV Prevention & Substance Abuse Prevention among Homeless Youth in the United States
bigimg: 
  - "core/img/spy.png" : "Safe Place for Youth, Venice Beach"
---

## Project Description

<p align="justify">In collaboration with social-work scientists, we have addressed three different challenges faced by homeless youth in the United States: (i) preventing HIV among homeless youth through the development of robust end-to-end influence maximization algorithms, which can maximize the efficiency of Popular Opinion Leader (POL) interventions; (ii) mitigating opioid abuse among homeless youth by removing the bottlenecks in COR-12 rehabilitation programs through a combination of causal inference and robust prediction-driven optimization that incorporates fairness constraints; and (iii) suicide prevention among homeless youth by developing algorithms for robust graph covering problems with group fairness constraints, which can maximize the efficiency of Gatekeeper training interventions. In collaboration with homeless shelters, our research group was the first to deploy influence maximization based algorithms in the real-world, e.g., we ran a multi-year clinical trial showing the effectiveness of my influence maximization algorithms in minimizing risky sexual behaviors among homeless youth.</p>

<p align="justify"><b>Robust End-to-End Influence Maximization for HIV Prevention</b>: Popular Opinion Leader (POL) is a community-level HIV prevention intervention based on diffusion of innovation principles in which a cadre of trusted, well-liked key opinion leaders are trained to endorse safer sexual behaviors among peers. While the influence maximization problem provides a nice computational framework to find high-quality opinion leaders (or "seeds") which can maximize the diffusion of HIV preventative information inside a social network of homeless youth, most prior work makes several strong assumptions (such as accurate knowledge of social network structure and diffusion models) which rarely hold in real-world domains involving marginalized communities. Motivated by these real-world uncertainties, we have designed the first algorithms and models for tackling uncertainties in influence maximization, leading to a new era of influence maximization research.</p>

<p align="justify"><b>Causal Inference + Optimization for Opioid Abuse Prevention</b>: COR-12 rehabilitation programs are designed for people suffering from Opioid Use Disorders, but they are difficult to implement because of ad-hoc assessments (made by rehabilitation centers) about the cause of opioid use among individual patients. In collaboration with social-work scientists, we developed CORTA, a novel software agent which optimizes the delivery of opioid rehabilitation services to homeless youth. CORTA collects data about opioid usage behaviors of homeless youth and uses that data to train high dimensional causal inference models which can predict susceptibility of homeless youth to opioid addiction, and can uncover causative factors that lead to opioid abuse. Finally, using counterfactual estimates derived from these causal inference models, CORTA solves novel Integer Linear Program (ILP) formulations to determine the optimal assignment of homeless youth to the correct rehabilitation programs. CORTA’s ILP formulation finds such optimal assignments by minimizing the expected number of homeless youth suffering from opioid addiction, while respecting fairness and limited capacity constraints faced by rehabilitation centers.</p>

<p align="justify"><b>Fair and Robust Graph Covering for Suicide Prevention</b>: Gatekeeper training involving identifying and training key nodes in social networks as gatekeepers who can actively look out for suicidal tendencies among their immediate neighbors in the network. While these problems can be cast as robust graph covering problems, state-of-the-art graph covering algorithms result in biased node coverage, i.e., they tend to discriminate individuals (nodes) based on membership in traditionally marginalized groups. In collaboration with social-work scientists, we incorporated group fairness constraints in robust graph covering problems, and developed tractable approximation schemes to solve these problems on real-world networks, which allows us to find the optimal set of gatekeepers for suicide prevention among homeless youth.</p>


## Publications
* Eric Rice, Bryan Wilder, Laura Onasch-Vera, Graham DiGuiseppi, Robin Petering, Chyna Hill, Amulya Yadav, Sung-Jae Lee and Milind Tambe. [A Peer-Led, Artificial Intelligence-Augmented Social Network Intervention to Prevent HIV among Youth Experiencing Homelessness](https://journals.lww.com/jaids/Fulltext/2021/12151/A_Peer_Led,_Artificial_Intelligence_Augmented.4.aspx). In Proc. of the Journal of Acquired Immunodeficiency Syndrome (JAIDS), Volume 88, Issue S1, pp. S20--S26, 2021.

* Zi-Yi Dou, Anamika Barman-Adhikari, Fei Fang, and Amulya Yadav. [Harnessing Social Media to Identify Homeless Youth At-Risk of Substance Use](http://amulyayadav.com/Papers/aaai21fb.pdf). In Proc. 35th AAAI Conference on Artificial Intelligence, pp. 14748--14756, 2021.

* Bryan Wilder, Laura Onasch-Vera, Graham Diguiseppi, Robin Petering, Chyna Hill, Amulya Yadav, Eric Rice and Milind Tambe. [Clinical trial of an AI-augmented intervention for HIV prevention in youth experiencing homelessness](http://amulyayadav.com/Papers/aaai21hiv.pdf). In Proc. 35th AAAI Conference on Artificial Intelligence, pp. 14948--14956, 2021. **Best Student Paper Award at the Mechanism Design for Social Good (MD4SG) Workshop, 2020.**

* Maryam Tabar, Heesoo Park, Stephanie Winkler, Dongwon Lee, Anamika Barman-Adhikari, Amulya Yadav. [Identifying Homeless Youth at-risk of Substance Use Disorder: Data Driven Insights for Policymakers](http://amulyayadav.com/Papers/kdd2020.pdf). In Proc. 26th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), pp. 3092--3100, 2020.

* Amulya Yadav, Roopali Singh, Nikolas Siapoutis, Anamika Barman-Adhikari, Yu Liang. [Optimal and Non-Discriminative Rehabilitation Program Design for Opioid Addiction Among Homeless Youth](http://amulyayadav.com/Papers/ijcai2020.pdf). In Proc. 29th International Joint Conference on Artificial Intelligence (IJCAI), pp. 4389--4395, 2020.

* Aida Rahmattalabi, Phebe Vayanos, Anthony Fulginiti, Eric Rice, Bryan Wilder, Amulya Yadav, Milind Tambe. [Exploring Algorithmic Fairness in Robust Graph Covering Problems](http://amulyayadav.com/Papers/nips19.pdf). In Proc. 33rd Intl. Conf. on Neural Information Processing Systems (NeurIPS), pp. 15750--15761, 2019.

* Eric Rice, Robin Petering, Amanda Yoshioka-Maxwell, Jaih Craddock, Darlene Woo, Nicole Wilson, Laura Onasch-Vera, Bryan Wilder, Amulya Yadav and Milind Tambe. [Piloting the Use of Artificial Intelligence to Enhance HIV Prevention Interventions for Youth Experiencing Homelessness](http://amulyayadav.com/Papers/JSSWR.pdf). In Proc. of the Journal of the Society for Social Work and Research, Volume 9, Issue 4, pp. 551-573, 2018.

* Amulya Yadav, Bryan Wilder, Eric Rice, Robin Petering, Jaih Craddock, Amanda Yoshioka-Maxwell, Mary Hemler, Laura Onasch-Vera, Milind Tambe and Darlene Woo. [Bridging the Gap Between Theory and Practice in Influence Maximization: Raising Awareness about HIV among Homeless Youth](http://amulyayadav.com/Papers/IJCAI18.pdf). In Proc. 27th International Joint Conference on Artificial Intelligence (IJCAI), pp. 5399-5403, 2018.

* Amulya Yadav, Ritesh Noothigattu, Eric Rice, Laura Onasch-Vera, Leandro Marcolino and Milind Tambe. [Please be an influencer? Contingency Aware Influence Maximization](http://amulyayadav.com/Papers/AAMAS18b.pdf). In Proc. 17th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 1423-1432, 2018.

* Lily Hu, Bryan Wilder, Amulya Yadav, Eric Rice and Milind Tambe. [Activating the Breakfast Club: Modeling Influence Spread in Natural World Social Networks](http://amulyayadav.com/Papers/AAMAS18a.pdf). In Proc. 17th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 1631-1640, 2018.

* Amulya Yadav, Aida Rahmattalabi, Ece Kamar, Phebe Vayanos, Milind Tambe and Venil Loyd Noronha. [Explanation Systems for Influence Maximization Algorithms](http://amulyayadav.com/Papers/SocInf17.pdf). In Proc. 3rd Intl. IJCAI Workshop on Social Influence Analysis, 2017.

* Bryan Wilder, Amulya Yadav, Nicole Immorlica, Eric Rice and Milind Tambe. [Uncharted but not Uninfluenced: Influence Maximization with an Uncertain Network](http://amulyayadav.com/Papers/AAMAS17B.pdf). In Proc. 16th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 1305-1313, 2017.

* Amulya Yadav, Bryan Wilder, Eric Rice, Robin Petering, Jaih Craddock, Amanda Yoshioka-Maxwell, Mary Hemler, Laura Onasch-Vera, Milind Tambe, Darlene Woo. [Influence Maximization in the Field: The Arduous Journey From Emerging to Deployed Application](http://amulyayadav.com/Papers/Yadav-AAMAS2017.pdf). In Proc. 16th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 150-158, 2017. **Best Paper Award Nomination at AAMAS-17**

* Amulya Yadav, Hau Chan, Albert Jiang, Haifeng Xu, Eric Rice, Milind Tambe. [Maximizing Awareness about HIV in Social Networks of Homeless Youth with Limited Information](http://amulyayadav.com/Papers/IJCAI17.pdf). In Proc. 26th International Joint Conference on Artificial Intelligence (IJCAI), pp. 4959-4963, 2017.

* Bryan Wilder, Amulya Yadav, Nicole Immorlica, Eric Rice, Milind Tambe. [Robust, Dynamic Influence Maximization](http://amulyayadav.com/Papers/OPTMAS17.pdf). In Proc. 8th Intl. AAMAS Workshop on Optimization in Multiagent Systems, 2017.

* Amulya Yadav, Hau Chan, Albert Jiang, Haifeng Xu, Eric Rice and Milind Tambe. [Using Social Networks to Raise HIV Awareness Among Homeless Youth](http://amulyayadav.com/Papers/IBM17.pdf). In IBM Journal of Research and Development: Volume 61, Issue 6(4), pp. 1-10, 2017.

* Amulya Yadav, Hau Chan, Albert Xin Jiang, Eric Rice, Ece Kamar, Barbara Grosz and Milind Tambe. [POMDPs for Assisting Homeless Shelters: Computational and Deployment Challenges](http://amulyayadav.com/Papers/IDEAS16.pdf). In Proc. 2nd Intl. AAMAS Workshop on Issues with Deployment of Emerging Agent-based Systems, 2016. **Most Visionary Paper Award at IDEAS-16**

* Amulya Yadav, Leandro Marcolino, Eric Rice, Robin Petering, Hailey Winetrobe, Harmony Rhoades, Milind Tambe and Heather Carmichael. [PSINET: Assisting HIV Prevention Amongst Homeless Youth by Planning Ahead](http://amulyayadav.com/Papers/AIMag.pdf). In AI Magazine: 37(2), pp. 47-62, July 2016.

* Leandro Marcolino, Aravind S. Lakshminarayanan, Amulya Yadav and Milind Tambe. [Simultaneous Influencing and Mapping Social Networks](http://amulyayadav.com/Papers/AAMAS16B.pdf). In Proc. 15th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 1439-1440, 2016.

* Amulya Yadav, Hau Chan, Albert Jiang, Haifeng Xu, Eric Rice and Milind Tambe. [Using Social Networks to Aid Homeless Shelters: Dynamic Influence Maximization under Uncertainty](http://amulyayadav.com/Papers/AAMAS16.pdf). In Proc. 15th Intl. Joint Conference on Autonomous Agents and Multiagent Systems (AAMAS), pp. 740-748, 2016.

* Amulya Yadav, Leandro Marcolino, Eric Rice, Robin Petering, Hailey Winetrobe, Harmony Rhoades, Milind Tambe and Heather Carmichael. [Preventing HIV Spread in Homeless Populations using PSINET](http://amulyayadav.com/Papers/IAAI2015.pdf). In Proc. 27th AAAI Conference on Innovative Applications of Artificial Intelligence, pp. 4006-4011, 2015.
