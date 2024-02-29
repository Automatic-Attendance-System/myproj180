The primary objective of this endeavour is to develop a facial recognition-based attendance monitoring system tailored for both educational institutions and corporate environments, with the aim of refining and elevating the existing attendance management procedures to a higher echelon of efficiency and effectiveness. The incumbent conventional systems suffer from inherent ambiguities, resulting in inaccuracies and inefficiencies in attendance tracking. Leveraging technological advancements, this project endeavours to rectify the deficiencies inherent in the incumbent systems, thereby revolutionizing attendance management through process automation.

A distinguishing feature of this attendance tracking methodology, in contrast to conventional facial recognition techniques, is its inherent immunity to false attendance occurrences. Our hardware infrastructure interfaces with web servers via Internet of Things (IoT) technology, ensuring controlled accessibility. During the initial segment of a session, the hardware is oriented outward, capturing images of students as they enter the premises. Subsequently, after a predetermined interval, the hardware rotates 180 degrees, facing inward to capture departures. Attendance is then marked based on the temporal differential between entry and exit times, corresponding to respective subjects.

At the core of this system lies facial recognition technology, leveraging the inherent uniqueness of the human face for individual identification. The low probability of facial deviation or duplication renders it an ideal biometric trait for identity verification. The project entails the construction of facial databases to populate the recognizer algorithm, facilitating real-time comparison of captured facial images against the database for identity verification. Upon successful identification, attendance records are automatically generated and stored within a comprehensive database infrastructure. Accessible via a cloud-based server, this repository ensures seamless retrieval of attendance data for individual stakeholders.

**Results:**

**Project Scope and Objective:**  
Served as the lead developer for a "Hand Hygiene Compliance Monitoring System Using Gesture Recognition and Deep Learning" as part of a B.Tech project.  
The dataset comprised six classes of images, totalling 1418 images, with each class containing 150-300 images.  

**Machine Learning Model Development:**  
Utilized 90% of the dataset for training, with the remaining 10% allocated for testing.  
Adopted a batch size of 16.  

Employed Google's MobileNetV-2 architecture.  
Configured the learning rate to 0.0001.  
Leveraged transfer learning with pre-trained 'Imagenet' weights.  

**Model Performance:**  
An initial validation accuracy of 42% was recorded using NVIDIA Digits.  
Significant enhancement in accuracy to 63% post fine-tuning.  

**Deployment:**  
Successfully deployed the model to an FPGA DE10 nano.


![Alt Text](https://github.com/Automatic-Attendance-System/myproj180/blob/master/HandWash_Video.gif)

Original Video link: https://github.com/akshaywalkoli/Hand-Hygiene-Compliance-Monitoring-System-Using-Gesture-Recognition-and-Deep-Learning/blob/master/HandWash_Video.mp4
