---
title: "Development of a Robotic Arm for precision Makeup Application on the Human Face"
collection: publications
permalink: /publication/2023-7-15-Développement du robot assistant pour le maquillage
excerpt: 'Passed the ENSAM ParisTech school defenses and was included in the laboratory.'
date: 2023-07-15
venue: 'Arts et Métiers ParisTech library'
paperurl: 'https://github.com/SichenPa221/SichenPa221.github.io/blob/master/files/SFE_Report.pdf'
citation: 'SU SICHEN, (2023). &quot;Développement du robot assistant pour le maquillage.&quot; <i>Journal 1</i>. 1(1).'
---
**Abstract**

<style>
    .justified-text {
        text-align: justify;
    }
</style>

<div class="justified-text">

<p>
The MURA (Make Up with Robotic Arm) project focuses on developing advanced models for makeup application, integrating robotic systems, computer vision, computer graphics, and machine learning. The primary objective is to enable a robotic arm to apply makeup, such as lipstick or eye liner, to a face. The robotic arm is equipped with a gripper enhanced with force sensing capabilities to hold the makeup product and measure the applied force, as well as a depth camera for accurate perception of the person's face. 
</p>

<p>
This research presents benefits associated with the successful implementation of the MURA project. Firstly, robotic makeup application allows for standardized procedures, ensuring consistent and reproducible results, which is essential for product evaluation and quality control. Secondly, this technology can cater to individuals who face difficulties in applying makeup themselves, such as those with disabilities. 
</p>

<p>
Before the MURA project, a proof-of-concept study was conducted by the Mechatronic Team, wherein makeup application was limited to a specific mannequin, guided by predefined planning rules. The MURA project aims to overcome these limitations by employing computer vision techniques to detect the region of the face where makeup is to be applied. The robot learns to apply makeup independently of face pose and morphology using machine learning, particularly reinforcement learning. Additionally, a digital twin of the makeup application setup was developed using ROS/Gazebo simulation, allowing for cost-effective and rapid model prototyping. 
</p>

<p>
In the simulation environment, the approach to train the makeup application models involves the following steps: estimating a 3D representation of the person's face using Google Mediapipe, identifying mesh keypoints to define the makeup region, employing inverse kinematics for the robot to apply makeup to all keypoints within the makeup region, generating a new 3D gazebo model with the applied makeup using computer graphics, and finally, providing the robot with a reward based on the application results. The reward system considers metrics such as makeup area coverage, application speed, and robot exerted force. Demonstrations of the model's performance in both simulation and real-life scenarios showcase its effectiveness on faces with various poses and morphologies.
</p>

<p>
Currently, the makeup application models are based on inverse kinematics, which may be computationally inefficient due to the costly optimization process. In the future, we plan to enhance our models by incorporating advanced reinforcement learning techniques, such as policy gradient or Q-learning, enabling the robot to leverage efficient deep learning-based forward kinematics. 
</p>

<p>
Overall, the MURA project represents a significant advancement in the field of robotic makeup application, promising standardized and accessible makeup solutions for various user groups. The combination of robotic systems, computer vision, computer graphics, and machine learning foster an interdisciplinary approach that paves the way for future developments in this domain. 
</p>

</div>

<div class="download-links_1">
  <a href="{{ page.paperurl }}" target="_blank" aria-label="Download the SFE Report PDF">Download paper</a>
  <a href="[https://github.com/SichenPa221/SichenPa221.github.io/raw/master/files/SFE_Report.pdf]" target="_blank" aria-label="Télécharger la version françai">télécharger la version françai</a>
</div>

<div class="download-links">
  <a href="{{ page.paperurl }}" target="_blank" aria-label="Download the SFE Report PDF">Download paper</a>
  <a href="https://github.com/SichenPa221/SichenPa221.github.io/raw/master/files/Master_thesis_English.pdf" target="_blank" aria-label="Download the Master Thesis in English PDF">Download English paper</a>
</div>

[Download English_paper here](https://github.com/SichenPa221/SichenPa221.github.io/blob/master/files/Master_thesis_English.pdf)
Recommended citation: SU SICHEN. (2023). "Développement du robot assistant pour le maquillage." <i>Journal 1</i>.

