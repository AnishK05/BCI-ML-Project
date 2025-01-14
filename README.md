Check out our video demonstration [here](https://drive.google.com/file/d/1fQFq9-apAhN5-mCExt-DYWQ3ujR6EaNY/view?usp=sharing)!

This research paper presents a novel approach to assisting individuals with neuromuscular disorders and paralysis through an innovative Brain-Computer Interface (BCI) system. The study aims to develop a cost-effective, non-invasive solution that enables patients to control home appliances using brain signals associated with inner speech/internal thoughts (almost like mind control!).

The project involved creating a low-cost EEG device compatible with the BCI system. This device uses only two EEG nodes to capture brain signals, facilitating an affordable and accessible solution for users. EEG data was obtained from the IMAL Research Institute in Argentina and was preprocessed through re-referencing, filtering, resampling, and epoching to isolate signals corresponding to specific mental tasks.

Various machine learning models were evaluated, including Linear Discriminant Analysis (LDA), Convolutional Neural Networks (CNN), Random Forest, and Support Vector Machines (SVM). Among these, the LDA model exhibited the highest accuracy of 87% in detecting brain signals related to inner speech commands. The output from the machine learning model was used to control a Raspberry Pi, which managed home automation tasks such as switching lights on/off and adjusting temperature settings. The model's performance was validated through statistical significance testing, achieving a significance level of p=0.01, indicating the reliability of the system.

This research demonstrates significant advancements in BCI technology, offering an accessible and efficient solution for individuals with severe motor impairments.

Published 20-page award-winning research paper in the Social Science Research Network (SSRN): https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4836934

- This research paper was awarded as **"One of the Top 10 Most Impactful Research Papers on Disability Inclusion Research in 2024"**
- This research paper was awarded as **"One of the Top 10 Most Impactful Research Papers on Human Computer Interaction in 2024"**

Group Members: Anish Kalra, Trishay Naman

Note: Raspberry Pi scripts (which were used for deep learning model integration with Raspberry Pi imaging device) are not available in this repo
