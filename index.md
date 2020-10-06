---
layout: cv
title: Pramit-Resume
---
# Pramit Saha
Graduate student, University of British Columbia, Vancouver, Canada

<div id="webaddress">
<a href="https://pramitsaha.github.io/">Home Page</a>
| <a href="mailto:pramit@ece.ubc.ca">pramit@ece.ubc.ca</a>
| <a href="https://www.linkedin.com/in/pramit-saha-0a9338b5/">LinkedIn</a>
<!--| <a href="https://github.com/PramitSaha">Github</a>-->
</div>

<!--Add your research interest here and the domain that you have been working-->
## Research interests
Deep Learning, Bayesian Inference, Speech Motor Control, Speech Synthesis, Silent Speech Interface, Human Computer Interface, Computer Vision.

<!--Add the ongoing or completed projects as a part of portfolio-->
## Selected recent projects



`Jan2019 - Now`
__1. Investigating hand-to-speech motor control__

The goal of this project is to investigate and develop a plausible underlying mechanism of how our human motor control system leverages the biomechanical and physical constraints as well as the auditory perceptual abilities to reduce the difficulty of the speech task.

Human speech production is one of the most complex processes within the human motor repertoire, that needs a precise coordination of over 100 muscles per utterance of word. In continuous speech, the brain has to deal with the challenging task of rapid and accurate coordination of a set of redundant and interacting articulators, which requires the multi-dimensional control of multiple articulators at a dauntingly high rate. The neuro-computational bases behind such control is still not well understood. In this work, we endeavor to address this issue by investigating the effect of perceptual feedback-based regulations and spatio-temporal constraints for control of vowel sounds in a hand gesture-to-speech mapping system. As a starting point, we developed a synthesizer which can be controlled by hand movement to produce continuous vowel sounds easily and intuitively. We also investigated glove based 2D control, 1D+1D control and mouse control to understand how different control paradigms vary the effort of hand-to-speech motor control. Furthermore, we put forth an information theoretic view of the aforementioned control and demonstrated how deep learning based mapping can be utilized to reduce the difficulty level of the task.


<br>***Peer-reviewed Publications:***

[1] __Pramit Saha__ and Sidney Fels. "Your Hands Can Talk : Perceptually-Aware Mapping of Hand Gesture Trajectories to Vowel Sequences" [under review]

[2] Yadong Liu\* , __Pramit Saha__\*, Arian Shamei, Bryan Gick and Sidney Fels. ["Deep learning based continuous vowel space mapping from hand gestures"](https://awc.caa-aca.ca/index.php/AWC/AWC19/paper/view/630), Acoustics Week in Canada 2019

[3] Yadong Liu\*, __Pramit Saha__\*, Arian Shamei, Bryan Gick and Sidney Fels. ["Mapping a Continuous Vowel Space to Hand Gestures."](https://jcaa.caa-aca.ca/index.php/jcaa/article/view/3373) Canadian Acoustics 48.1 (2020).

(\* indicates equal contribution)

`April2018 - Now`

__2. Mapping articulatory and acoustic domain__

The goal of this project is to find appropriate mappings between articulatory geometric configurations of the vocal tract and the acoustic properties of the resultant speech sound.

Thousands of individuals need surgical removal of their larynx due to critical diseases every year and therefore, require an alternative form of communication to articulate speech sounds after the loss of their voice box. This project addresses the articulatory-to-acoustic mapping problem based on synthetic images (Pink Trombone), ultrasound (US) tongue images and MRI vocal tract images for the development of a silent-speech interface (SSI) that can provide them with an assistance in their daily interactions. We employed deep learning based approaches to develop MRI based speech recognition and US based speech sythesis systems. Further, in order to find a joint latent representation between the articulatory and acoustic domain for vowel sounds, we utilized a convolutional autoencoder architecture and normalizing flow-based model to allow both forward and inverse mapping between mid-sagittal vocal tract geometry (of a two degrees-of-freedom articulatory synthesizer with 1D acoustic wave model) and Mel-spectrogram representation (of the synthesized speech sounds).


<br>***Peer-reviewed Publications:***

[1] __Pramit Saha__ and Sidney Fels. ["Learning Joint Articulatory-Acoustic Representations with Normalizing Flows."](https://arxiv.org/abs/2005.09463) arXiv preprint arXiv:2005.09463 (2020). [Accepted for publication in Interspeech 2020]

[2] __Pramit Saha__, Yadong Liu, Bryan Gick, and Sidney Fels. ["Ultra2Speech - A Deep Learning Framework for Formant Frequency Estimation and Tracking from Ultrasound Tongue Images"](https://arxiv.org/abs/2006.16367) [Early acceptance for publication in MICCAI 2020] [CODE](https://github.com/PramitSaha/Ultra2Speech/blob/main/Ultra2speech_shuffled_architecture_MICCAI.ipynb)

[3] __Pramit Saha__, Praneeth Srungarapu, and Sidney Fels. ["Towards Automatic Speech Identification from Vocal Tract Shape Dynamics in Real-time MRI."](https://www.isca-speech.org/archive/Interspeech_2018/abstracts/2537.html) Proc. Interspeech 2018 (2018): 1249-1253.


`Apr2018 - Apr2019`
__3. Recognizing imagined speech__

The goal of the project is to detect speech tokens from speech imagery brain signals (EEG). 

Speech imagery is about representing speech in terms of unspoken sounds inside the human brain that doesn’t involve overt vocalization or articulatory movements. Our project reveals the existence of some sort of brain footprint for articulatory movements underlying related speech token imagery. We build upon the idea that active thought process underlying covert speech does have some relevant features corresponding to the intended activity of different parts of the vocal tract, even though a person is not vocalizing. We further demonstrate that it is possible to detect the imagined words by understanding the intended involvement of vocal tract and vocal fold, which is internally encoded in the brain signals. Our hierarchical deep neural network architecture is able to capture some information about the signals that the brain implicitly sends to the speech articulators like tongue, vocal fold, etc even in the absence of a need for vocal communication.


<br>***Peer-reviewed Publications:***

[1] __Pramit Saha__, Muhammad Abdul-Mageed, and Sidney Fels. ["SPEAK YOUR MIND! Towards Imagined Speech Recognition with Hierarchical Deep Learning."](https://www.isca-speech.org/archive/Interspeech_2019/pdfs/3041.pdf) Proc. Interspeech 2019 (2019): 141-145.

[2] __Pramit Saha__, Sidney Fels, and Muhammad Abdul-Mageed. ["Deep learning the eeg manifold for phonological categorization from active thoughts."](https://ieeexplore.ieee.org/document/8682330) ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2019.

[3] __Pramit Saha__ and Sidney Fels. ["Hierarchical deep feature learning for decoding imagined speech from eeg."](https://www.aaai.org/ojs/index.php/AAAI/article/view/5146) Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 33. 2019.


`Jan2018 - Dec2018`

__4. Developing silent speech interfaces__

This project explores and evaluates the appropriate input and mapping methods to design a controllable silent speech synthesis engine using either our vocal tract or hands. It has two components: 

(i) *Ultrasound (US) based SSI:* We take a step towards developing a controllable interface via precise extraction of the upper oral cavity from ultrasound imaging modality, thereby, enabling speakers to drive an articulatory speech synthesizer directly by their tongue movements without the necessity of vocalization. At the core of this interface is the extraction of mid-sagittal cross-sectional area functions between tongue and palate using the US, which drives a computationally affordable FDTD-based 2D acoustic wave solver for precise simulation of acoustic wave propagation. The study motivates an investigation into the possible ways of augmenting US-based area functions to generate rich VT geometrical information that can potentially lead to the development of a real-time silent-speech interface.

(ii) *Hand control based SSI:* We introduce Sound stream: a low-cost, tangible and ambidextrous controller which drives a dynamic muscle-based model of the human vocal tract for articulatory speech synthesis. The controller facilitates the usage of multidimensional inputs from both hands which are mapped to the tongue muscles in a biomechanical modeling toolkit Artisynth using a microcontroller. The tongue kinematics is then mapped to a JASS based sound synthesis engine. As a demonstration, the user learns to interact and control a mid-sagittal view of the tongue structure in Artisynth through a set of sensors using both hands to synthesise continuous vocal sounds. 

<br>***Peer-reviewed Publications:***

[1] Yadong Liu, __Pramit Saha__, and Bryan Gick. "Visual Feedback and Self-monitoring in Speech Learning via Hand Movement" [Under review in The 179th Meeting of the Acoustical Society of America, 2020]

[2] __Pramit Saha__, Debasish Ray Mohapatra, S. V. Praneeth, and Sidney Fels. ["Sound-Stream II: Towards Real-Time Gesture-Controlled Articulatory Sound Synthesis."](https://jcaa.caa-aca.ca/index.php/jcaa/article/view/3248) Canadian Acoustics 46.4 (2018): 58-59.

[3] __Pramit Saha__, Debasish R. Mohapatra, Venkata Praneeth Srungarapu, and Sidney Fels. ["SOUND STREAM: Towards vocal sound synthesis via dual-handed simultaneous control of articulatory parameters."](https://asa.scitation.org/doi/10.1121/1.5068362) The Journal of the Acoustical Society of America 144, no. 3 (2018).


## Education

`Sep2017 - Now`
__M.A.Sc (Master of Applied Science), Electrical and Computer Engineering__, University of British Columbia

Supervised By: [Sidney Fels](https://www.ece.ubc.ca/faculty/sid-fels)

Project: Mapping articulatory-to-acoustic domain and investigating speech motor control

`Jul2012 - Jun2016`
__B.E.(Bachelor of Engineering) Honours (Rank: 5 out of 100 students) in Electrical Engineering__, Jadavpur University, Kolkata, India

Advisor: [Amitava Chatterjee](https://sites.google.com/site/amitavachatterjee1968/)

Project: Three-dimensional terrain image map generation for navigation of a quadruped robot in an uneven terrain.

## Professional Experience

`Sep2017 - Now`
__MITACS Globalink Graduate Fellow and Graduate Research Assistant, [HCT lab](https://hct.ece.ubc.ca/)__, Vancouver, Canada
- Department of Electrical and Computer Engineering (ECE), University of British Columbia (UBC), Vancouver, Canada
- Duties included: Research on developing controllable speech-related Human Computer Interface and Speech Motor Control
- Supervisor: Prof. Sidney Fels

`May2018 - Now`
__Treasurer and Executive Committee Member, UBC ECE Graduate Student Association (ECEGSA)__
- Duties included: In-charge of organizing and maintaining funds for ECE grad student events, Decision making on student welfare policies taken by ECEGSA.

`Jun2020 - Now`
__Graduate Academic Assistant, Electrical and Computer Engineering Department (ECE)__, University of British Columbia (UBC), Vancouver, Canada
- Duties included: Preparation of academic materials for online course.
- Instructor: Dr. Saloome Motavas

`Jun2016 - Sep2016`
__MITACS Globalink Research Intern, Faculty of Medicine and Dentistry__, Department of Radiology and Diagnostic Imaging, University of Alberta, Edmonton
- Duties included: Research on Medical image processing problems related to oral ultrasound image
- Supervisor: Prof. Lawrence Le

`May2015 - Jul2015`
__Summer Research Intern, Department of Electrical Engineering__, Indian Institute of Science (IISc Bangalore)
- Duties included: Research on MRI Image reconstruction and Compressed sensing
- Supervisor: Prof. Kasi Rajgopal

`Dec2014 - Jan2015`
__Winter Research Intern, Electronics and Electrical Communication Engineering Department__, Indian Institute of Technology (IIT Kgp)
- Duties included: Differential geomtery based shape feature extraction and classification of pulmonary lung nodules in CT images
- Supervisors: Prof. Sudipta Mukhopadhyay and Prof. Ashis Kumar Dhara


## Teaching Experience

`Jan2018 - Now`
__Teaching Assistant, University of British Columbia__, Vancouver, Canada

Responsibilities: Preparing course materials, conducting tutorial sessions, managing student projects, lab and exam grading

- APSC160 - Introduction to Computation in Engineering Design (Spring 2018, Fall 2018, Spring 2019, Fall 2019)
- ELEC 203 - Basic Circuit Analysis (Fall 2018, Fall 2019)
- ELEC 371 - Biomedical Engineering Instrumentation (Spring 2019, Spring 2020)
- ELEC 523 - Medical Imaging (Fall 2019)
- ELEC 341 - Systems and Control (Summer 2020)

## Reviewing Activities

- __MICCAI 2020__
- __Abstracts for UBC Language Sciences GSPFRD 2020__
- __MICCAI 2019__
- __IEEE TENCON 2016__


## Computing Skills

__Programming Language:__
Python (including deep learning frameworks: PyTorch, Keras, TensorFlow), MATLAB, C

__OS:__
Windows
## Awards and Recognitions

`2020`

__MICCAI 2020 Student Travel Award__ awarded by the MICCAI Society - Refunding MICCAI Registration

`2019`

__ISCA Travel Grant__ awarded by the International Speech and Communication Association (ISCA) - 650 Euro

`2019`

__AAAI Student Scholarship__ awarded by Association for Advancement of Artificial Intelligence (AAAI) - 400 Dollars

`2018-2019`

__Faculty of Applied Science Graduate Award__ awarded for academic and research achievements by the Department of Electrical and Computer Engineering (ECE) of University of British Columbia (UBC) - 8,000 Canadian dollars

`2017-Now`

__International Tuition Award__ awarded by the University of British Columbia - 9,600 Canadian Dollars

`2017-2018`

__MITACS Globalink Graduate Fellowship Award__ awarded by MITACS - 15,000 Canadian Dollars

`2016`

__MITACS Globalink Research Internship (GRI) Award__ awarded by MITACS - 6,800 Canadian Dollars

`2015`

__Best Paper Award__ awarded by IEEE INDICON 2015

`2014`

__Best Student Paper Award__ awarded by IEEE CALCON 2014

`2014`

__Best White Paper Award 2014__ awarded by Schneider Electric Pvt. Ltd.

`2012-2016`

__Ministry of Human Resource Development Scholarship__ awarded for securing 27th rank out of 7,00,000 candidates (approx.) in the 12th standard Board Examinations, by Government of India - 50,000 INR


## Publications

To see the complete list of my publications, please check [google scholar](https://scholar.google.com/citations?hl=en&user=Sb7d-rsAAAAJ) 

## Media / coverage / Talk

1. [What if you could hear new music by Satchmo? UBC researchers and speech from brain signals](https://www.youtube.com/watch?v=R5idxOkZiCk)

2. [UBC Award Recipient Interview](https://www.grad.ubc.ca/campus-community/meet-our-students/saha-pramit)

3. [UBC Language Sciences Talk: TEACHING, MAPPING, AND UNDERSTANDING THE SOUNDS OF LANGUAGE](https://languagesciences.ubc.ca/news-events/events/jun-12-2020-teaching-mapping-and-understanding-sounds-language-online-flash-talks)

4. [UBC ECE Graduate Student Achievement](https://www.ece.ubc.ca/news/202007/ece-student-pramit-saha-leads-imagine-speech-recognition-project)

## Community and Volunteer Activities

`2018-Now`

__Treasurer and Executive Committee Member__, ECE Graduate Student Association (ECEGSA), University of British Columbia

As the treasurer and executive committee member of ECEGSA, I am in charge of
organizing and maintaining funds for society of more than 300 graduate students in
the department. I participate in organizing the academic seminars and tutorials as
well as internal and external social events. I prepare budgets for each event, organize
meetings with the other members of the committee, communicate with the bank and the
departmental financial authorities, withdraw from and deposit money into the bank, audit
the expenditures monthly, etc. Besides, I participate in the decision making of different
departmental student welfare policies taking by ECEGSA (Electrical and Computer
Engineering Graduate Student Association).

`2017-2020`

__Lab Website Maintainer__, Human Computer Technologies (HCT) Lab, University of British Columbia

I am volunteering to maintain the lab website and keeping it up-to-date. I am running
tutorials to help the lab members understand how to create their profiles, include their
publications and other details in their profiles, etc.

`2012-2016`

__Class Representative and Member of Anti-Ragging Committee__, Electrical Engineering Department, Jadavpur University

I acted as the Class Representative of Department of Electrical Engineering, Jadavpur
University in my Undergraduate days, for four years. I was responsible for printing and
distributing study materials and notes handed over by the course instructors to me,
discussing with the students and deciding examination dates and communicating to the
department examination committee. Besides, I was in charge of maintaining general
discipline and academic environment in the class. Furthermore, I was the Student Member
of Anti-ragging Committee of Jadavpur University (2012-2016), where I used to meet
the other members and discuss about current ragging and disciplinary scenarios in the
campus, reporting about unwanted incidents in the department, propose solutions for
improving the anti-ragging policies, helping students with counselling, etc.

## Students mentored

[Himanshu Goyal](https://www.linkedin.com/in/himanshu-g/), Third-year Computer Science student, UBC

[Irene Wang](https://www.linkedin.com/in/irenewang05/), Third-year Computer Engineering student, UBC

[Bobby Smith](https://www.linkedin.com/in/robertdouglassmith/), Bachelor of Science (Biochemistry), UBC


## Links to other sites 

[Personal Home Page](https://pramitsaha.github.io/)

[HCT UBC Lab Profile](http://hct.ece.ubc.ca/person/pramit-saha/)

[UBC Language Science Profile](https://languagesciences.ubc.ca/people/student-member/pramit-saha)

[UBC Meet our students Profile](https://www.grad.ubc.ca/campus-community/meet-our-students/saha-pramit)

[UBC ECEGSA Treasurer Profile](http://gsa.ece.ubc.ca/contact/current-executives/)

