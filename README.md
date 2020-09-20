Parkinson-Disease-Machine-Learning
This open source project is for using machine learning for detection and treatment of Parkinson disease and has been presented in Hack the Midlands (2019)


Back ground of the Research
==============================

 Parkinson disease(PD)is a kind of progressive disease in which an area of brain becomes damaged over the years. It causes various signs and symptoms. From one perspective, these signs and symptoms can be grouped into two major categories: motor symptoms and nonmotor symptoms. Motor symptoms are those that affect movement and muscles and nonmotor symptoms include neurobehavioral and cognitive problems, sleep problems, sensory problems, and autonomic neuropathy (dysautonomia).

Speech disturbance is one of the most common motor problems of PD. Research has shown that about 90% of PWP are affected with motor problems, especially speech impairment. In addition to the prevalence of vocal impairments in PD patients, gathering speech samples and doing signal processing of their voice has low cost and it is appropriate for telemonitoring and telediagnosis systems. Therefore, PD diagnosis from speech impairments is becoming more widespread.

In Parkinsonism patients, speech disorders result from neurologic impairments which are associated with weakness, slowness, or incoordination of the muscles used to produce speech. Speech disturbance usually occurs in the following forms: hypophonia, which is soft speech that results from weakness in the vocal musculature, monotonic speech, which deals with speech quality in the cases that are soft, hoarse, and monotonous, and festination speech, which is when the speech becomes excessively rapid, soft, breathy, and poorly intelligible .

Step1: Predict if a person is having Parkinson's or Not
===========================================================
The first part of the research is an attempt to prove that use different features(jitter, shimmer) of vocal data from a patient can help diagnose whether or not they suffer from Parkinson’s. As such, it is initially assumed that there is a relationship between the two. Our aim will be to run various machine learning classifiers (Ex. Naïve Bayes, SVM, etc.) on the data in hopes to reach a high predictability rate that is matched with a reasonable runtime. 

Step 2:  Use ensemble techiques to create a model give high accuracy 
===================================================================

This portion is under development.

Step 3: Create a Flask API  based REST service end point
===================================================================
