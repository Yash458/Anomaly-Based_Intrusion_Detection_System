# Anomaly-Based_Intrusion_Detection_System

### Abstract
With the increasing number of new attacks on ever-growing network traffic, it is becoming challenging to alert immediately any malicious activities to avoid loss of sensitive data and money. Thus, making intrusion detection as one of the major areas of concern in network security. Intrusion Detection System is used to Access unauthorized and malicious attacks over the network. Anomaly based Intrusion detection technique is one of the most commonly used technique. Machine learning techniques can be applied to IDS to detect normal and abnormal behaviour patterns. Although classification-based machine learning techniques are popular, they are not effective to detect unknown attacks. Unsupervised learning methods have been given a closer look for intrusion detection system, which are insignificant to detect dynamic intrusion activities. So here our vision will be to find best possible technique and make the most effective way for detection.


### Introduction
Nowadays, due to the utilities and services that the Internet provides such as social media, E-learning, online purchasing, VoIP, cloud services and so on, and the affordability of electronic devices and Internet access, the number of connected devices has increased exponentially. However, it is a nightmare for organizations and corporation security managers to prevent their networks from being attacked and compromised and preserve their secrets and the sensitive information of their customers from leaking out. Hence, cybersecurity has become more challenging than ever.

Anomaly-based IDS creates a profile that represents normal behaviour and any deviation from this profile is considered as attack. Given the promising capabilities of anomaly-based IDS, it became a principal focus of research and the most investigated topic among researchers in the literature. Hence, so many techniques have been used in order to build a profile or a model that can perform well in detecting anomalies such as evolutionary, information theory, statistical, and machine learning techniques.


**Aim:** To model and build Anomaly-Based Intrusion Detection System using Machine Learning algorithms.

### Objective:
Intrusion detection systems monitor network traffic in order to detect when an attack is being carried out by unauthorized entities.
* monitoring the operation of routers, firewalls, key management servers and files that are needed by other security controls aimed at detecting, preventing or recovering from cyberattacks
* providing administrators way to tune, organize and understand relevant OS audit trails and other logs that are otherwise difficult to track or parse
* providing a user-friendly interface so nonexpert staff members can assist with managing system security
* including an extensive attack signature database against which information from the system can be matched
* recognizing and reporting when the IDS detects that data files have been altered
* generating an alarm and notifying that security has been breached; and reacting to intruders by blocking them or blocking the server.


### Characteristics of Intrusion Detection System:
1) It must run continually without human supervision. The system must be reliable enough to allow it to run in the background of the system being observed.
2) It must be fault tolerant in the sense that it must survive a system crash and not have its knowledge-base rebuilt at restart.
3) It must impose minimal overhead on the system
4) It must observe deviations from normal behavior.
5) It must be easily tailored to the system in question. Every system has a different usage pattern, and the defense mechanism should adapt easily to these patterns.
6) It must cope with changing system behavior over time as new applications are being added. The system profile will change over time, and the IDS must be able to adapt.

![image](https://user-images.githubusercontent.com/63646378/147218692-eb24b6e7-6287-4e0a-9f3c-2f8ce41fce78.png)

### Dataset
The most problematic stage in assessing IDS is determining the proper dataset. There are various datasets available for evaluation purpose, Two of them are as follows:

**1) CICIDS2017:** It is a real-world network traffic IDS dataset which is publicly available for use. This dataset contains benign along with the most up-to-date seven common attacks, which resembles the true real-world data. The attacks included in this dataset are Brute Force attack, DoS, Web attack, Infiltration, Botnet attack, DDoS and PortScan attack. CICIDS2017 contains more than 2 million records and 78 attributes.
* Records: 2,827,876
* Features: 77 + label columns
* 9-attacks: BotNet, FTP Brute Force, DoS, DDoS, Heartbleed, Infilteration, SSH Brute Force, Web Attacks, and PortScan
* Problems: contains missing values, infinity values

**2) UNSW-NB15:** The UNSW-NB15 dataset has also been analyzed by The significant features from this dataset are selected by using various attributes of selection methods, including CfsSubsetEval of the greedy stepwise method and InfoGainAttibuteEval of the ranker method. The optimal selected attributes subset is then employed for the categorization by using several ML algorithms, including RF. The categorization that employs selective features shows improvements in its kappa statistics. Therefore, a weighted feature selection technique is recommended for identifying Wi-Fi impersonation through the AWID dataset. Appendix A lists the different datasets that have been used in the literature for evaluating AIDS.
* Records: 1,087,204
* Features: 44 + label column
* 9-attacks: Back Doors, DoS, Exploits, Worms, Fuzzers, Analysis Attacks, Shell Code Attacks, Reconnaissance Attacks, and Generic Attacks.
* Problem: contains missing values

