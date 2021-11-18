---
permalink: /
author_profile: true
image: ../images/photo.jpeg
title: Privacy and Security in ML Seminars
---

<br>This is the homepage of the **Privacy & Security in Machine Learning (PriSec-ML) Interest Group**. It brings together researchers and practitioners around the world broadly interested in this topic. For the time being, it features recurring seminars, a couple of times a month, always on Wednesdays, around 1.30 PM (London Time).  

### Get Involved
- Subscribe to our **[mailing list](https://www.jiscmail.ac.uk/cgi-bin/webadmin?SUBED1=PRISEC-ML&A=1)** to receive to seminar and job announcements
- Join our **[Slack](https://prisec-ml.slack.com)** by using this [link](https://join.slack.com/t/prisec-ml/shared_invite/zt-y02o7shc-Ef~5IRsEyNwCzvZkfjy7lg) &ndash; this is particularly useful for students, who maintain an active working group with monthly (virtual) meet-ups
- Follow us on **[Twitter](https://twitter.com/prisec_ml)**
- Subscribe to our **[YouTube channel](http://youtube.com/c/PrivacyandMachineLearningInterestGroup)** where we live stream and keep recordings of the talks


### Upcoming Seminars



<img src="../images/eugene.jpg" style="float:right;width:100px;height:100px;margin-top:00px">
- 1 December 2021, 13:30 ([UK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20211201T1330&p1=136))  
**Eugene Bagdasaryan (Cornell Tech and Apple)**  
Blind Backdoors in Deep Learning  
[[Zoom Registration](https://ucl.zoom.us/meeting/register/tJUqce2hqTsuGdQKqxfBOFzzYxGWJnHKXThU)] [[Live Stream](https://youtu.be/TCBPX3CA5UQ)]<details><br>**Abstract:** We investigate a new method for injecting backdoors into machine learning models, based on compromising the loss-value computation in the model-training code. We use it to demonstrate new classes of backdoors strictly more powerful than those in the prior literature: single-pixel and physical backdoors in ImageNet models, backdoors that switch the model to a covert, privacy-violating task, and backdoors that do not require inference-time input modifications.<br><br>
Our attack is blind: the attacker cannot modify the training data, nor observe the execution of his code, nor access the resulting model. The attack code creates poisoned training inputs "on the fly," as the model is training, and uses multi-objective optimization to achieve high accuracy on both the main and backdoor tasks. We show how a blind attack can evade any known defense and propose new ones.
<br><br>**Bio:** Eugene is a PhD Candidate at Cornell Tech advised by Vitaly Shmatikov and Deborah Estrin. He is an Apple AI/ML Scholar. He focuses on privacy and security implications of applying machine learning in the real world, specifically backdoor attacks and defenses, differential privacy, and federated learning.<br>[https://www.cs.cornell.edu/~eugene/](https://www.cs.cornell.edu/~eugene/)<br></details>

<img src="../images/luca.jpeg" style="float:right;width:100px;height:100px;margin-top:00px">
- 8 December 2021, 13:30 ([UK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20211208T1330&p1=136))  
**Luca Melis** *(Large Social Network Provider That Recently Changed Its Name)*  
Differentially Private Query Release Through Adaptive Projection  
[[Zoom Registration](https://ucl.zoom.us/meeting/register/tJAucuurqzwiH9xXIeN07Esj0GvYdKf3DwVQ)] [[Live Stream](https://youtu.be/azF_CDX7zvg)]<details><br>**Abstract:** We propose, implement, and evaluate a new algorithm for releasing answers to very large numbers of statistical queries like k-way marginals, subject to differential privacy. Our algorithm makes adaptive use of a continuous relaxation of the Projection Mechanism, which answers queries on the private dataset using simple perturbation, and then attempts to find the synthetic dataset that most closely matches the noisy answers. We use a continuous relaxation of the synthetic dataset domain which makes the projection loss differentiable, and allows us to use efficient ML optimization techniques and tooling. Rather than answering all queries up front, we make judicious use of our privacy budget by iteratively and adaptively finding queries for which our (relaxed) synthetic data has high error, and then repeating the projection. We perform extensive experimental evaluations across a range of parameters and datasets, and find that our method outperforms existing algorithms in many cases, especially when the privacy budget is small or the query class is large. Published at [ICML 2021](https://arxiv.org/abs/2103.06641).
<br><br>**Bio:** [https://www.lucamel.is](https://www.lucamel.is)<br></details>


<img src="../images/xiong.jpg" style="float:right;width:100px;height:100px;margin-top:00px">
- 26 January 2022, 13:30 ([UK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20220126T1330&p1=136))  
**Li Xiong, Emory University**  
Trustworthy Machine Learning with Both Differential Privacy and Certified Robustness   
[[Zoom Registration](https://ucl.zoom.us/meeting/register/tJwpf-CtrTgvG9N19NBdQdCsxjqCce9-KvzX)] [[Live Stream](https://youtu.be/JCPK4wh-C88)]<details><br>**Abstract:** While deep learning models have achieved great success, they are also vulnerable to potential manipulations, ranging from model inversion attacks that attempt to infer sensitive training data from a model, to adversarial example attacks that create manipulated data instances to deceive a model.  In this talk, I will present our recent work on achieving 1) differential privacy (DP) to ensure privacy of the training data and 2) certified robustness against adversarial examples for deep learning models.  First, I will present a practical DP training framework for centralized setting with better empirical and theoretical utility (IJCAI’21).  Second, I will present a certified robustness approach via randomized smoothing for quantized neural networks (ICCV ’21). Finally, I will present a framework that kills two birds with one stone and achieves DP and certified robustness via randomized smoothing simultaneously.
<br><br>**Bio:** Li Xiong is a Professor of Computer Science and Biomedical Informatics at Emory University. She held a Winship Distinguished Research Professorship from 2015-2018. She has a Ph.D. from Georgia Institute of Technology, an MS from Johns Hopkins University, and a BS from the University of Science and Technology of China. She and her research lab, Assured Information Management and Sharing (AIMS), conduct research on the intersection of data management, machine learning, and data privacy and security. She has published over 160 papers and received six best paper (runner up) awards. She has served and serves as associate editor for IEEE TKDE, VLDBJ, IEEE TDSC, general or program co-chairs for ACM CIKM 2022, IEEE BigData 2020, and ACM SIGSPATIAL 2018, 2020. Her research has been supported by National Science Foundation (NSF), AFOSR (Air Force Office of Scientific Research), National Institute of Health (NIH), and Patient-Centered Outcomes Research Institute (PCORI). She is also a recipient of Google Research Award, IBM Smarter Healthcare Faculty Innovation Award, Cisco Research Awards, AT&T Research Gift, and Woodrow Wilson Career Enhancement Fellowship.  She is an ACM distinguished member.  More details at [http://www. cs.emory.edu/~lxiong](http://www. cs.emory.edu/~lxiong).<br></details>

**Google Calendar:** \[[html](https://calendar.google.com/calendar/embed?src=oormvn3d4hah013g6gd39pjpfk%40group.calendar.google.com&ctz=Europe%2FLondon)\] \[[ics](https://calendar.google.com/calendar/ical/oormvn3d4hah013g6gd39pjpfk%40group.calendar.google.com/public/basic.ics)\]


### Past Seminars

<img src="../images/reza.jpeg" style="float:right;width:100px;height:100px;margin-top:00px">
- 17 November 2021  
**Prof. Reza Shokri (National University of Singapore)**  
Advanced Membership Inference Attacks  
[[Recording](https://youtu.be/Ud7-sSJTG2k)]<details><br>**Abstract:** Data Protection regulations, such as GDPR, and AI governance frameworks require personal data to be protected when used in AI systems, and that the users have control over their data and awareness about how it is being used. For example, Article 35 of GDPR requires organizations to systematically analyze, identify and minimize the data protection risks of a project, especially when it involves innovative technologies such as deep learning. Thus, proper mechanisms need to be in place to quantitatively evaluate and verify the privacy of individuals in every step of the data processing pipeline in AI systems. In this talk, I will define what data privacy is in the context of machine learning, and how it can be quantified. I will also present ML Privacy Meter tool that enables quantifying the privacy risks of machine learning models. The tool produces privacy risk analysis reports, which help in identifying data records among the training data that are under high risk of being leaked through the model parameters or predictions.<br><br>
The privacy risk analysis in ML Privacy Meter is based on membership inference attacks. In this talk, I present a formal framework to reason about such attacks, and introduce new powerful attacks that outperform the existing attacks and are designed to precisely quantify the information leakage through models. This is a joint work with Jiayuan Ye, Aadyaa Maddi, and Sasi Murakonda<br><br>**Bio:** Reza Shokri is a NUS Presidential Young Professor of Computer Science. His research focuses on data privacy and trustworthy machine learning. He is a recipient of the IEEE Security and Privacy (S&P) Test-of-Time Award 2021, for his paper on quantifying location privacy. He received the Caspar Bowden Award for Outstanding Research in Privacy Enhancing Technologies in 2018, for his work on analyzing the privacy risks of machine learning models. He received the NUS Early Career Research Award 2019, VMWare Early Career Faculty Award 2021, Intel Faculty Research Award (Private AI Collaborative Research Institute) 2021-2022, and Google PDPO Faculty Award 2021. He obtained his PhD from EPFL.<br>
[https://www.comp.nus.edu.sg/~reza/](https://www.comp.nus.edu.sg/~reza/)<br></details>

<img src="../images/sara.png" style="float:right;width:100px;height:100px;margin-top:00px">
- 10 November 2021  
**Dr. Sara Hooker (Google Brain)**  
The myth of the interpretable, robust, compact and high performance DNN  
[[Recording](https://youtu.be/BZ3FDiXkP78)]<details><br>**Abstract:**<br>To-date, a discussion around the relative merits of different compression methods has centered on the trade-off between level of compression and top-line metrics. Along this dimension, compression techniques such as pruning and quantization are remarkably successful. It is possible to prune or heavily quantize with negligible decreases to test-set accuracy. However, top-line metrics obscure critical differences in generalization between compressed and non-compressed networks. In this talk, we will go beyond test-set accuracy and discuss some of my recent work measuring the trade-offs between compression, robustness and algorithmic bias. Characterizing these trade-offs provide insight into how capacity is used in deep neural networks -- the majority of parameters are used to represent a small fraction of the training set.<br><br>**Bio:**<br>[https://www.sarahooker.me](https://www.sarahooker.me)<br></details>

<img src="../images/konrad.jpeg" style="float:right;width:100px;height:100px;margin-top:0px">
- 13 October 2021  
**Prof. Konrad Rieck (Technische Universität Braunschweig)**  
Adversarial Preprocessing: Image-Scaling Attacks in Machine Learning  
[[Recording](https://youtu.be/kCKayHjZd3E)]<details><br>**Abstract:**<br>The remarkable advances of machine learning are overshadowed by attacks that thwart its proper operation. While previous work has mainly focused on attacking learning algorithms directly, another weak spot in intelligent systems has been overlooked: preprocessing. As an example of this threat, I present a recent class of attacks against image scaling. These attacks are agnostic to learning algorithms and affect the preprocessing of all vision systems that use vulnerable implementations, including versions of TensorFlow, OpenCV, and Pillow. Based on a root-cause analysis of the vulnerabilities, I introduce novel defenses that effectively block image-scaling attacks in practice and can be easily added to existing systems.<br><br>**Bio:**<br>[https://www.tu-braunschweig.de/en/sec/team/rieck](https://www.tu-braunschweig.de/en/sec/team/rieck)<br></details>


### Previous Iteration
This is a reboot of the [Turing Institute](https://www.turing.ac.uk)'s interest group in Privacy and Machine Learning ([old page](https://www.turing.ac.uk/research/interest-groups/privacy-preserving-data-analysis)). We have branched out and expanded to topics at the intersection of Security (not "just" Privacy) and Machine Learning.


<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn_NkH-IEVA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Organizers
- [Prof. Emiliano De Cristofaro](https://emilianodc.com/), UCL  
- [Dr. Giovanni Cherubin](https://giocher.com/), Alan Turing Institute  
- [Prof. Lorenzo Cavallaro](https://s2lab.cs.ucl.ac.uk/people/sullivan), UCL  
- [Dr. Vasilis Mavroudis](https://mavroud.is/), Alan Turing Institute  

