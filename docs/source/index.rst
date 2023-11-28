The Silent Emergency - Preterm Birth Prediction
===================================


   “The world is facing a silent emergency. . . of preterm births.” - UNICEF

Problem Statement
=================

Premature infants, those born before 37 weeks of gestation, are at risk for many negative, long-term health issues. If they survive, they may have difficulties with feeding, breathing, hearing, vision, and neurodevelopment. In The United States there were over 380,000 preterm infants born in 2022, approximately 10% of all births. The highest rates occured among Black women (14.6%), and lowest rates occurred among White women (9.4%) and Hispanic women (10.1%), which is a persistent trend. These rates have recently declined for White women yet remained unchanged for other groups. 

While there are known risk factors for preterm birth, an individual's likelihood of delivering before 37 weeks is not well-understood. 
The etiology of preterm birth is likely a complex interaction between biological, genetic, behavioral, and environmental factors. As of late, there has been increased understanding of social determinants of health and their effects on groups that are systemically disenfranchised. Such racial and ethnic health disparities can be further perpetuated or even exacerbated by underrepresentation of minority groups in healthcare research. It is likely that these environmental factors mediate preterm birth as they do a myriad of other health aspects.  

The current medical system focuses more on mitigation of the health consequences of a preterm birth than on its prediction and prevention. However, machine learning has the potential to support medical professionals with the early identification of a pregnancy likely to proceed to a preterm delivery. Data related to preterm birth can come from sources such as electronic health records, surveys, laboratory results, electrohysterographs, ultrasounds, genome sequences, and other diagnostic procedures. In short, it is noisy. While this is extremely challenging for a human to parse, machine learning models can be trained to identify patterns in large banks of data and to make predictions on new data. 

There have been several attempts to develop machine learning models to predict preterm birth. Promising results have been found with the use of cervical length images and electrohysterograph waveforms. However, these procedures are not routine for every pregnancy, and will not capture individuals who have limited access to health care. The most useful predictive model would be based on non-invasive, easily collectable, information. It should not require advanced medical access or a high amount of resources, and it should be available early on during a pregnancy so that there is enough time for intervention. 

We aim to address this problem by creating a classifier that uses demographic and lifestyle factors that are non-invasive and routinely collected. By using a representative dataset, we will ensure that we include all people in the development of advan and ensuring our model’s equitable performance across diverse racial and ethnic groups, we aim to contribute to a healthier start for all children.

Contents
--------

.. toctree::

   usage
   api
   executive_summary
   problem statement
   data description
   feature engineering
   model architecture
   training process
   evaluation metrics
   model
   results
   use case
   ethical scorecard
   acknowledgements
   references
   about


About
*****
This project was created for the 'Erdős Institute <https://www.erdosinstitute.org/>'_ 'Data Science Bootcamp <https://www.erdosinstitute.org/programs/fall-2023/data-science-boot-camp>'_, Fall 2023. Group members are 'Katherine Grillaert <https://www.linkedin.com/in/kgrillaert/>'_, 'Divya Joshi <https://www.linkedin.com/in/divya-joshi-phd-candidate/>'_, 'Noah Rahman <https://www.linkedin.com/in/noah-rahman-01504257/>'_, 'Alex Sutherland <https://www.linkedin.com/in/alexander-sutherland-math/>'_, and 'Kristina Zvolanek <https://www.linkedin.com/in/kristina-zvolanek/>'_. 

View our five minute presentation.

Github: 'www.github.com/kgrillaert/preterm_birth <https://www.github.com/kgrillaert/preterm_birth>'_

License: MIT License
